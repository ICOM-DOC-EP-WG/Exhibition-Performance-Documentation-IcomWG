# Mapping

## How to add a project to Wikidata a step-by-step guide

### Why we use Wikidata

You are probably familiar with Wikipedia, the collaborative online encyclopedia. Wikidata is the database behind Wikipedia, open to everyone. Instead of storing texts, it stores **structured facts**: projects, people, institutions, all connected to one another.

For our working group, it is the ideal tool for mapping exhibition and performance documentation projects around the world. Every project you add automatically becomes visible on our website, and can be discovered and reused by other researchers. It is far more powerful than a shared spreadsheet, and requires no technical expertise.

Do not worry: you cannot "break" anything. Every edit is recorded and reversible.

------

### Before you start: create an account

Go to [wikidata.org](https://www.wikidata.org) and click **"Create account"** in the top right corner. It is free and takes only a minute. If you already have a Wikipedia account, it works on Wikidata too.

------

### Step 1. Check whether the project already exists

Type the name of the project in the search bar at the top of the page.

Look carefully at the results. If the project appears, click on it to open its entry. If not, move on to Step 2.

------

### Step 2a. The project does not exist yet: create an entry

In the left-hand menu, click **"Create a new item"**.

You will see two fields to fill in:

- **Label**: the name of the project as it is commonly known. If possible, enter it in both English and French by clicking "+ Add" below the field.
- **Description**: a short sentence summarising the project, for example: *"Research project on the documentation of performance art in European museums"*. Again, versions in both English and French are ideal.

Click **"Create"**. Your entry now exists in Wikidata, with a unique identifier starting with the letter Q.

------

### Step 2b. The project already exists: skip to Step 3

No need to create a new entry. Simply open it and continue.

------

### Step 3. Add the main subjects (this is the most important part)

This is what allows our query to find your project. Without this step, the project will not appear on our website.

On the project's entry, scroll down to the **"Statements"** section and click **"+ Add statement"**.

In the field that appears, type **"main subject"** and select the corresponding property (its code is P921).

You must add **at least two values** for this field:

**1. Mandatory:** type `Q788790` or "documentation" and select the corresponding entry.

**2. At least one of the following three options**, depending on what the project focuses on:

| If the project deals with...       | Type in the field |
| ---------------------------------- | ----------------- |
| **Exhibitions**                    | `Q464980`         |
| **Performance art**                | `Q35140`          |
| **Documentation** in a broad sense | `Q213156`         |

To add a second value to the same field, click **"+ Add value"** just below.

Click **"Publish"** (or the save icon) after each addition.

------

### Step 4. Complete the entry with additional information

This is not mandatory, but the more complete an entry is, the more useful it becomes. The following information is especially valuable, always added via **"+ Add statement"**:

| Information      | What to search for in the field                   |
| ---------------- | ------------------------------------------------- |
| Type of project  | "instance of" (P31), then type "research project" |
| Host institution | "affiliation" (P1416)                             |
| Website          | "official website" (P856), then paste the URL     |
| Start year       | "inception" (P571)                                |
| Country          | "country" (P17)                                   |
| Team members     | "author" (P50), then add names                    |

------

### Step 5. Why and how to source your statements

In Wikidata, anyone can add information. **References** are what distinguish a verifiable piece of data from an unsourced claim. They give credibility to the entry and allow others to check information at its source. For our collective mapping effort, this matters: an unsourced project risks being challenged or removed by other Wikidata contributors.

The good habit is simple: **every statement you add should have at least one reference.**

#### How to add a reference

Once a statement is published, it appears on the entry with a small **"+ Add reference"** link beneath it. Click it.

Two situations:

- **The project has a website or an online presence**

Choose the property **"reference URL" (P854)**, then paste the address of the page that mentions or describes the project. An article, an institutional page, a research directory entry: all of these work.

- **You are directly responsible for the project**

If you are entering first-hand information, use the property **"stated in" (P248)** and point to the project's official website or publication. You can also use **"quote" (P1683)** to include a short verbatim excerpt.

Click **"Publish"** to save the reference.

#### What to avoid

Avoid leaving important statements (affiliation, dates, team members) without any reference. An entirely unsourced entry is fragile and less useful to the community.

------

### If in doubt

Feel free to look at an already well-documented project entry for inspiration. You can also leave an entry incomplete and come back to it later, or ask another group member to fill it in.

And once more: you cannot break anything. If something goes wrong, an administrator can always correct or undo an edit.



## Comment référencer un projet dans Wikidata : guide pas à pas

### Pourquoi on utilise Wikidata ?

Vous connaissez probablement Wikipedia, l'encyclopédie collaborative en ligne. Wikidata, c'est la base de données qui se cache derrière Wikipedia, et qui est ouverte à tous. Au lieu de stocker des textes, elle stocke des **faits structurés** : des projets, des personnes, des institutions, reliés entre eux.

Pour notre groupe de travail, c'est l'outil idéal pour cartographier les projets de documentation d'expositions et de performances dans le monde. Chaque projet que vous y ajoutez devient automatiquement visible sur notre site web, et peut être retrouvé et utilisé par d'autres chercheur·euses. C'est bien plus puissant qu'un tableau Excel partagé, et ça ne demande pas de compétences techniques particulières.

Pas d'inquiétude : vous ne pouvez rien "casser". Toute modification est enregistrée et réversible.

------

### Avant de commencer : créer un compte

Rendez-vous sur [wikidata.org](https://www.wikidata.org) et cliquez sur **"Créer un compte"** en haut à droite. C'est gratuit et rapide. Un compte Wikipedia existant fonctionne directement sur Wikidata.

------

### Étape 1. Vérifier si le projet existe déjà

Dans la barre de recherche en haut de la page, tapez le nom du projet que vous souhaitez ajouter.

Regardez attentivement les résultats. Si le projet apparaît, cliquez dessus pour ouvrir sa fiche. Sinon, passez à l'étape 2.

------

### Étape 2a. Le projet n'existe pas encore : créer une fiche

Dans le menu de gauche, cliquez sur **"Créer un nouvel élément"**.

Vous verrez deux champs à remplir :

- **Nom (label)** : le nom du projet, tel qu'il est connu. Si possible, entrez-le en français ET en anglais en cliquant sur "+ Ajouter" sous le champ.
- **Description** : une phrase courte qui résume le projet, par exemple : *"Projet de recherche sur la documentation des arts de la performance en Europe"*. Là aussi, une version en français et en anglais est idéale.

Cliquez sur **"Créer"**. Votre fiche existe maintenant dans Wikidata, avec un identifiant unique qui commence par la lettre Q.

------

### Étape 2b. Le projet existe déjà : passer directement à l'étape 3

Pas besoin de recréer une fiche. Ouvrez-la et continuez.

------

### Étape 3. Ajouter les sujets principaux (c'est la partie la plus importante)

C'est ce qui permet à notre requête de retrouver votre projet. Sans cette étape, le projet ne s'affichera pas sur notre site.

Sur la fiche du projet, descendez jusqu'à la section **"Déclarations"** et cliquez sur **"+ Ajouter une déclaration"**.

Dans le champ qui apparaît, tapez **"sujet principal"** ou **"main subject"**, puis sélectionnez la propriété correspondante (son code est P921).

Vous devez ajouter **au minimum deux valeurs** pour ce champ :

**1. Obligatoire :** tapez `Q788790` ou "documentation" et sélectionnez l'entrée correspondante.

**2. Au moins une de ces trois options**, selon ce que fait le projet :

| Si le projet porte sur...             | Tapez dans le champ |
| ------------------------------------- | ------------------- |
| Des **expositions**                   | `Q464980`           |
| De l'**art de la performance**        | `Q35140`            |
| De la **documentation** au sens large | `Q213156`           |

Pour ajouter une deuxième valeur au même champ, cliquez sur **"+ Ajouter une valeur"** juste en dessous.

Cliquez sur **"Publier"** (ou l'icône de sauvegarde) après chaque ajout.

------

### Étape 4. Compléter la fiche avec d'autres informations

Ce n'est pas obligatoire, mais plus une fiche est complète, plus elle est utile. Voici les informations les plus utiles à ajouter, toujours via **"+ Ajouter une déclaration"** :

| Information          | Ce qu'il faut chercher dans le champ                         |
| -------------------- | ------------------------------------------------------------ |
| Type de projet       | "nature de l'élément" (P31), puis tapez "projet de recherche" |
| Institution porteuse | "affiliation" (P1416)                                        |
| Site web             | "site officiel" (P856), puis collez l'URL                    |
| Année de début       | "date de fondation ou création" (P571)                       |
| Pays                 | "pays" (P17)                                                 |
| Membres de l'équipe  | "auteur" (P50), puis ajoutez les noms                        |

---

### Étape 5. Pourquoi et comment sourcer vos déclarations

Dans Wikidata, n'importe qui peut ajouter une information. Les **références** permettent de distinguer une donnée vérifiable d'une simple affirmation. C'est ce qui donne de la crédibilité à la fiche et permet à d'autres de vérifier l'information à la source. Pour notre cartographie collective, c'est particulièrement important : un projet mal sourcé risque d'être contesté ou supprimé par d'autres contributeur·rices Wikidata.

La bonne habitude est simple : **chaque déclaration que vous ajoutez devrait avoir au moins une référence.**

#### Comment ajouter une référence

Une fois qu'une déclaration est publiée, elle apparaît sur la fiche avec un petit lien **"+ Ajouter une référence"** en dessous. Cliquez dessus.

Deux cas de figure :

- **Le projet a un site web ou une page en ligne**

Choisissez la propriété **"URL de référence" (P854)**, puis collez l'adresse de la page qui mentionne ou décrit le projet. Un article, une page institutionnelle, une entrée dans un annuaire de recherche, tout cela convient.

- **Vous êtes vous-même responsable du projet**

Si vous entrez des informations de première main, utilisez la propriété **"indiqué par" (P248)** et pointez vers le site ou la publication officielle du projet. Vous pouvez aussi utiliser **"selon" (P1683)** pour indiquer une citation textuelle courte.

Cliquez sur **"Publier"** pour enregistrer la référence.

#### Ce qu'on évite

Évitez de laisser des déclarations importantes (affiliation, dates, membres) sans aucune référence. Une fiche entièrement non sourcée est fragile et moins utile pour la communauté.

------

### En cas de doute

N'hésitez pas à regarder la fiche d'un projet déjà bien documenté pour vous en inspirer. Vous pouvez aussi laisser une fiche incomplète et y revenir plus tard, ou demander à un autre membre du groupe de la compléter.

Et encore une fois : vous ne pouvez rien casser. Si quelque chose ne va pas, un administrateur peut toujours corriger ou annuler une modification.

Je lance les deux en parallèle.

------

## Cómo referenciar un proyecto en Wikidata: guía paso a paso

### ¿Por qué usamos Wikidata?

Probablemente conoces Wikipedia, la enciclopedia colaborativa en línea. Wikidata es la base de datos que se encuentra detrás de Wikipedia, abierta a todas las personas. En lugar de almacenar textos, almacena **hechos estructurados**: proyectos, personas, instituciones, todos conectados entre sí.

Para nuestro grupo de trabajo, es la herramienta ideal para cartografiar los proyectos de documentación de exposiciones y performances en el mundo. Cada proyecto que añadas se vuelve automáticamente visible en nuestro sitio web, y puede ser encontrado y utilizado por otras personas investigadoras. Es mucho más potente que una hoja de cálculo compartida, y no requiere ningún conocimiento técnico especial.

No te preocupes: no puedes "romper" nada. Cada modificación queda registrada y es reversible.

------

### Antes de empezar: crear una cuenta

Ve a [wikidata.org](https://www.wikidata.org) y haz clic en **"Crear una cuenta"** en la esquina superior derecha. Es gratuito y rápido. Si ya tienes una cuenta de Wikipedia, funciona directamente en Wikidata.

------

### Paso 1. Verificar si el proyecto ya existe

Escribe el nombre del proyecto en la barra de búsqueda en la parte superior de la página.

Observa atentamente los resultados. Si el proyecto aparece, haz clic para abrir su ficha. Si no, pasa al paso 2.

------

### Paso 2a. El proyecto no existe todavía: crear una ficha

En el menú de la izquierda, haz clic en **"Crear un nuevo elemento"**.

Verás dos campos para rellenar:

- **Etiqueta (label)**: el nombre del proyecto tal como se conoce habitualmente. Si es posible, introdúcelo en español Y en inglés haciendo clic en "+ Añadir" bajo el campo.
- **Descripción**: una frase corta que resume el proyecto, por ejemplo: *"Proyecto de investigación sobre la documentación de las artes escénicas en museos europeos"*. Igualmente, una versión en español e inglés es ideal.

Haz clic en **"Crear"**. Tu ficha existe ahora en Wikidata, con un identificador único que empieza por la letra Q.

------

### Paso 2b. El proyecto ya existe: pasar directamente al paso 3

No es necesario volver a crear una ficha. Ábrela y continúa.

------

### Paso 3. Añadir los temas principales (es la parte más importante)

Esto es lo que permite a nuestra consulta encontrar tu proyecto. Sin este paso, el proyecto no aparecerá en nuestro sitio web.

En la ficha del proyecto, desplázate hacia abajo hasta la sección **"Declaraciones"** y haz clic en **"+ Añadir una declaración"**.

En el campo que aparece, escribe **"tema principal"** o **"main subject"** y selecciona la propiedad correspondiente (su código es P921).

Debes añadir **al menos dos valores** para este campo:

**1. Obligatorio:** escribe `Q788790` o "documentation" y selecciona la entrada correspondiente.

**2. Al menos una de estas tres opciones**, según lo que hace el proyecto:

| Si el proyecto trata sobre...       | Escribe en el campo |
| ----------------------------------- | ------------------- |
| **Exposiciones**                    | `Q464980`           |
| **Arte de la performance**          | `Q35140`            |
| **Documentación** en sentido amplio | `Q213156`           |

Para añadir un segundo valor al mismo campo, haz clic en **"+ Añadir un valor"** justo debajo.

Haz clic en **"Publicar"** (o el icono de guardar) después de cada adición.

------

### Paso 4. Completar la ficha con otras informaciones

No es obligatorio, pero cuanto más completa esté una ficha, más útil resulta. Las siguientes informaciones son especialmente valiosas, siempre añadidas mediante **"+ Añadir una declaración"**:

| Información             | Qué buscar en el campo                                       |
| ----------------------- | ------------------------------------------------------------ |
| Tipo de proyecto        | "naturaleza del elemento" (P31), luego escribe "proyecto de investigación" |
| Institución responsable | "afiliación" (P1416)                                         |
| Sitio web               | "sitio web oficial" (P856), luego pega la URL                |
| Año de inicio           | "fecha de fundación o creación" (P571)                       |
| País                    | "país" (P17)                                                 |
| Miembros del equipo     | "autor" (P50), luego añade los nombres                       |

------

### Paso 5. Por qué y cómo referenciar tus declaraciones

En Wikidata, cualquier persona puede añadir información. Las **referencias** permiten distinguir un dato verificable de una simple afirmación. Dan credibilidad a la ficha y permiten que otras personas verifiquen la información en su fuente. Para nuestra cartografía colectiva, esto es especialmente importante: un proyecto mal referenciado puede ser cuestionado o eliminado por otras personas contribuidoras de Wikidata.

El buen hábito es sencillo: **cada declaración que añadas debería tener al menos una referencia.**

#### Cómo añadir una referencia

Una vez publicada una declaración, aparece en la ficha con un pequeño enlace **"+ Añadir una referencia"** debajo. Haz clic en él.

Dos situaciones posibles:

- **El proyecto tiene un sitio web o una página en línea**

Elige la propiedad **"URL de referencia" (P854)**, luego pega la dirección de la página que menciona o describe el proyecto. Un artículo, una página institucional, una entrada en un directorio de investigación: todo esto es válido.

- **Eres directamente responsable del proyecto**

Si introduces información de primera mano, utiliza la propiedad **"declarado en" (P248)** y apunta al sitio web o la publicación oficial del proyecto. También puedes usar **"cita" (P1683)** para incluir un extracto textual breve.

Haz clic en **"Publicar"** para guardar la referencia.

#### Qué evitar

Evita dejar declaraciones importantes (afiliación, fechas, miembros) sin ninguna referencia. Una ficha completamente sin referencias es frágil y menos útil para la comunidad.

------

### En caso de duda

No dudes en consultar la ficha de un proyecto ya bien documentado para inspirarte. También puedes dejar una ficha incompleta y volver a ella más tarde, o pedir a otro miembro del grupo que la complete.

Y una vez más: no puedes romper nada. Si algo sale mal, una persona administradora siempre puede corregir o deshacer una modificación.

------

## Como referenciar um projeto no Wikidata: guia passo a passo

### Por que usamos o Wikidata?

Você provavelmente conhece a Wikipedia, a enciclopédia colaborativa online. O Wikidata é a base de dados por trás da Wikipedia, aberta a todas as pessoas. Em vez de armazenar textos, ele armazena **fatos estruturados**: projetos, pessoas, instituições, todos conectados entre si.

Para o nosso grupo de trabalho, é a ferramenta ideal para mapear os projetos de documentação de exposições e performances no mundo. Cada projeto que você adicionar torna-se automaticamente visível no nosso site, e pode ser encontrado e reutilizado por outras pesquisadoras e pesquisadores. É muito mais poderoso do que uma planilha compartilhada, e não exige nenhum conhecimento técnico especial.

Não se preocupe: você não pode "quebrar" nada. Cada modificação é registrada e reversível.

------

### Antes de começar: criar uma conta

Acesse [wikidata.org](https://www.wikidata.org) e clique em **"Criar uma conta"** no canto superior direito. É gratuito e rápido. Se você já tem uma conta na Wikipedia, ela funciona diretamente no Wikidata.

------

### Passo 1. Verificar se o projeto já existe

Digite o nome do projeto na barra de pesquisa no topo da página.

Observe atentamente os resultados. Se o projeto aparecer, clique nele para abrir sua ficha. Caso contrário, passe ao passo 2.

------

### Passo 2a. O projeto ainda não existe: criar uma ficha

No menu à esquerda, clique em **"Criar um novo item"**.

Você verá dois campos para preencher:

- **Rótulo (label)**: o nome do projeto tal como é habitualmente conhecido. Se possível, insira-o em português E em inglês clicando em "+ Adicionar" abaixo do campo.
- **Descrição**: uma frase curta que resume o projeto, por exemplo: *"Projeto de pesquisa sobre a documentação das artes cênicas em museus europeus"*. Da mesma forma, uma versão em português e inglês é ideal.

Clique em **"Criar"**. Sua ficha agora existe no Wikidata, com um identificador único que começa pela letra Q.

------

### Passo 2b. O projeto já existe: ir diretamente ao passo 3

Não é necessário recriar uma ficha. Abra-a e continue.

------

### Passo 3. Adicionar os temas principais (esta é a parte mais importante)

É isso que permite à nossa consulta encontrar o seu projeto. Sem este passo, o projeto não aparecerá no nosso site.

Na ficha do projeto, desça até a seção **"Declarações"** e clique em **"+ Adicionar uma declaração"**.

No campo que aparecer, digite **"tema principal"** ou **"main subject"** e selecione a propriedade correspondente (seu código é P921).

Você deve adicionar **pelo menos dois valores** para este campo:

**1. Obrigatório:** digite `Q788790` ou "documentation" e selecione a entrada correspondente.

**2. Pelo menos uma destas três opções**, de acordo com o que o projeto aborda:

| Se o projeto trata de...          | Digite no campo |
| --------------------------------- | --------------- |
| **Exposições**                    | `Q464980`       |
| **Arte da performance**           | `Q35140`        |
| **Documentação** em sentido amplo | `Q213156`       |

Para adicionar um segundo valor ao mesmo campo, clique em **"+ Adicionar um valor"** logo abaixo.

Clique em **"Publicar"** (ou o ícone de salvar) após cada adição.

------

### Passo 4. Completar a ficha com outras informações

Não é obrigatório, mas quanto mais completa for uma ficha, mais útil ela se torna. As informações a seguir são especialmente valiosas, sempre adicionadas via **"+ Adicionar uma declaração"**:

| Informação              | O que procurar no campo                                      |
| ----------------------- | ------------------------------------------------------------ |
| Tipo de projeto         | "natureza do elemento" (P31), depois digite "projeto de pesquisa" |
| Instituição responsável | "afiliação" (P1416)                                          |
| Site                    | "site oficial" (P856), depois cole a URL                     |
| Ano de início           | "data de fundação ou criação" (P571)                         |
| País                    | "país" (P17)                                                 |
| Membros da equipe       | "autor" (P50), depois adicione os nomes                      |

------

### Passo 5. Por que e como referenciar suas declarações

No Wikidata, qualquer pessoa pode adicionar informações. As **referências** permitem distinguir um dado verificável de uma simples afirmação. Elas dão credibilidade à ficha e permitem que outras pessoas verifiquem a informação na sua fonte. Para o nosso mapeamento coletivo, isso é especialmente importante: um projeto mal referenciado pode ser contestado ou removido por outras pessoas contribuidoras do Wikidata.

O bom hábito é simples: **cada declaração que você adicionar deve ter pelo menos uma referência.**

#### Como adicionar uma referência

Assim que uma declaração é publicada, ela aparece na ficha com um pequeno link **"+ Adicionar uma referência"** abaixo. Clique nele.

Duas situações possíveis:

- **O projeto tem um site ou uma página online**

Escolha a propriedade **"URL de referência" (P854)**, depois cole o endereço da página que menciona ou descreve o projeto. Um artigo, uma página institucional, uma entrada em um diretório de pesquisa: tudo isso é válido.

- **Você é diretamente responsável pelo projeto**

Se você está inserindo informações de primeira mão, use a propriedade **"declarado em" (P248)** e aponte para o site ou a publicação oficial do projeto. Você também pode usar **"citação" (P1683)** para incluir um trecho textual breve.

Clique em **"Publicar"** para salvar a referência.

#### O que evitar

Evite deixar declarações importantes (afiliação, datas, membros) sem nenhuma referência. Uma ficha completamente sem referências é frágil e menos útil para a comunidade.

------

### Em caso de dúvida

Não hesite em consultar a ficha de um projeto já bem documentado para se inspirar. Você também pode deixar uma ficha incompleta e voltar a ela mais tarde, ou pedir a outro membro do grupo que a complete.

E mais uma vez: você não pode quebrar nada. Se algo der errado, uma pessoa administradora sempre pode corrigir ou desfazer uma modificação.

## Niveau avancé : Requête SPARQL 

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

Cette requete plus complète ne fonctionne pas : 

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