# Mapping projects

## Wikidata

### Guidelines to enter a project

On wikidata, register and log in

Research the name of the project. 

If it exist, add part of …

If it doesn’t exist, add an element 

https://www.wikidata.org/wiki/Q138794877

### Requête SPARQL 

 **requête SPARQL** pour les projets dont le **main subject (`P921`)** est **`Q464980`**et/ou  **`Q35140`**et/ou **`Q213156`**, **ET `Q788790`**

```
SELECT DISTINCT ?projet ?projetLabel ?projetDescription ?site WHERE {
  # Q788790 (Documentation) est obligatoire
  ?projet wdt:P921 wd:Q788790 .

  # ET au moins un autre main subject parmi Q464980, Q35140, Q788790
  ?projet wdt:P921 ?otherSubject .
  VALUES ?otherSubject { wd:Q464980 wd:Q35140 wd:Q213156 }

  # Récupérer les labels, descriptions et sites
  SERVICE wikibase:label { bd:serviceParam wikibase:language "[AUTO_LANGUAGE],fr,en". }
  OPTIONAL { ?projet wdt:P856 ?site . }
  OPTIONAL { ?projet schema:description ?projetDescription .
             FILTER(LANG(?projetDescription) = "fr" || LANG(?projetDescription) = "en") }
  
}
LIMIT 100
```

```
SELECT DISTINCT
  ?project
  (SAMPLE(?projectLabel) AS ?title)
  (GROUP_CONCAT(DISTINCT ?typeLabel; SEPARATOR=", ") AS ?type)
  (GROUP_CONCAT(DISTINCT ?affiliationLabel; SEPARATOR=", ") AS ?affiliation)
  (GROUP_CONCAT(DISTINCT ?memberInfo; SEPARATOR="; ") AS ?teamMembers)
  (SAMPLE(?description) AS ?description)
  (SAMPLE(?dates) AS ?dates)
  (GROUP_CONCAT(DISTINCT ?languageLabel; SEPARATOR=", ") AS ?languages)
  (GROUP_CONCAT(DISTINCT ?countryLabel; SEPARATOR=", ") AS ?country)
  (GROUP_CONCAT(DISTINCT ?link; SEPARATOR=", ") AS ?links)
  (GROUP_CONCAT(DISTINCT ?tagLabel; SEPARATOR=", ") AS ?tags)
WHERE {
  # Filtre : Q788790 obligatoire + au moins un autre
  ?project wdt:P921 wd:Q788790 .
  ?project wdt:P921 ?otherSubject .
  VALUES ?otherSubject { wd:Q464980 wd:Q35140 wd:Q213156}

  # Labels pour le projet et ses propriétés
  SERVICE wikibase:label { bd:serviceParam wikibase:language "[AUTO_LANGUAGE],fr,en". }

  # Type de projet (P31)
  OPTIONAL { ?project wdt:P31 ?type . }

  # Affiliation (P1416)
  OPTIONAL { ?project wdt:P1416 ?affiliation . }

  # Description
  OPTIONAL { ?project schema:description ?description .
             FILTER(LANG(?description) = "fr" || LANG(?description) = "en") }

  # Dates (début/fin) → Calculées ici avec BIND
  OPTIONAL { ?project wdt:P571 ?startDate . }
  OPTIONAL { ?project wdt:P576 ?endDate . }
  BIND(COALESCE(
    CONCAT(?startDate, IF(BOUND(?endDate), CONCAT(" – ", ?endDate), "")),
    "Inconnu"
  ) AS ?dates)

  # Langues (P407)
  OPTIONAL { ?project wdt:P407 ?language . }

  # Pays (P17)
  OPTIONAL { ?project wdt:P17 ?country . }

  # Lien officiel (P856)
  OPTIONAL { ?project wdt:P856 ?link . }

  # Tags (main subjects P921 + instance of P31)
  OPTIONAL { ?project wdt:P921 ?tag . }
  OPTIONAL { ?project wdt:P31 ?tag2 . }

  # Membres de l'équipe avec rôles (P50 + qualifier P3831)
  OPTIONAL {
    ?project p:P50 ?authorStatement .
    ?authorStatement ps:P50 ?member .
    OPTIONAL { ?authorStatement pq:P3831 ?role . }
    BIND(CONCAT(
      COALESCE(STR(?memberLabel), STRAFTER(STR(?member), "entity/")),
      IF(BOUND(?role), CONCAT(" (", COALESCE(STR(?roleLabel), STRAFTER(STR(?role), "entity/")), ")"), "")
    ) AS ?memberInfo)
  }

  FILTER(LANG(?projectLabel) = "fr" || LANG(?projectLabel) = "en")
}
GROUP BY ?project
LIMIT 100
```

Main subjects

| QID         | Signification (EN)                                      | Signification (FR)          | Lien                                          |
| ----------- | ------------------------------------------------------- | --------------------------- | --------------------------------------------- |
| **Q464980** | [Exhibition](https://www.wikidata.org/wiki/Q464980)     | **Exposition**              | [Voir](https://www.wikidata.org/wiki/Q464980) |
| **Q35140**  | [Performance art](https://www.wikidata.org/wiki/Q35140) | **Art de la performance**   | [Voir](https://www.wikidata.org/wiki/Q35140)  |
| **Q213156** | [Documentation](https://www.wikidata.org/wiki/Q213156)  | **Documentation**           | [Voir](https://www.wikidata.org/wiki/Q213156) |
| **Q788790** | [Performance](https://www.wikidata.org/wiki/Q788790)    | **Performance (spectacle)** | [Voir](https://www.wikidata.org/wiki/Q788790) |