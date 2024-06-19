<p align="center"><img src="https://i.imgur.com/6PwmrOg.png" width="250"></p>

ES-Community est une communauté ECMAScript francophone créée fin 2015. Notre désir est de rassembler les développeurs ECMAScript passionnés et ou professionnels en un seul point.
- [Objectifs](#objectifs)
- [Critères d'entrée](#critères-dentrée)
- [Code de conduite](#code-de-conduite)
  - [Comportements et sujets de discussion prohibés](#comportements-et-sujets-de-discussion-prohibés)
  - [Règles spécifiques à certain salons](#règles-spécifiques-à-certain-salons)
- [Modération](#modération)
- [Contribution](#contribution)
- [Invitation Discord](#invitation-discord)
- [Salons](#salons)
  - [Liste](#liste)
    - [Général](#général)
    - [Développement](#développement)
    - [Systèmes et databases](#systèmes-et-databases)
    - [Autres](#autres)
    - [Evenements](#evenements)
    - [Archives](#archives)
  - [Formats](#formats)
    - [#liens](#liens)
    - [#lives](#lives)
    - [#jobs](#jobs)
    - [#projets](#projets)
  - [#news](#news)
  - [Threads](#threads)
- [Bot](#bot)
- [Politique d'archivage](#politique-d-archivage)
- [Administrateurs](#administrateurs)
- [Mentors](#mentors)

# Objectifs
L'objectif de la communauté est avant tout de fournir un lieu d'échange, d'entraide et de veille technologique autour de l'écosystème ECMAScript (JavaScript).

C'est aussi l'occasion de rencontrer et parler avec des développeurs qui possèdent des intérêts en commun avec vous. Nous nous entraidons dans les problématiques les plus fréquentes et dans la gestion de notre stack (Administration système, Docker, Base de données, Modules NPM, Frameworks, etc.).

Mais finalement, c'est aussi plusieurs salons où l'on peut discuter librement entre nous de nos tracas quotidien. Et pourquoi pas un jour, se rassembler tous ensemble autour d'une bonne bière ! **EDIT** : C'est chose faite pour certains !

# Critères d'entrée
```js
const you = ESCommunity.currentUser();

if (!you.hasReadCodeOfConduct) {
    throw new Error("Merci de lire le code de conduite !");
}
you.setChannel('Presentation');
you.write("... Hello world !");
```
* Être développeur ECMAScript (JavaScript) par passion ou par métier. Cela comprend aussi les débutants qui ont la volonté d'apprendre sérieusement.
* Avoir lu et accepter entièrement le code de conduite ci-dessous.

# Code de conduite
```js
fs.createReadStream(path.join( __dirname , 'code_of_conduct.txt')).pipe(process.stdout);
```
En tant que membre de cette communauté, vous devez le respect à chaque développeur présent (humainement comme techniquement). Les insultes et les comportements désobligeants ne sont pas autorisés au sein de la communauté. Les moins expérimentés doivent redoubler d'efforts avant de requêter les autres sur des problématiques qui peuvent être résolues en faisant une simple recherche Google.

Nous sommes essentiellement constitués de développeurs ECMAScript, vous êtes donc priés de ne pas venir nous faire la guerre sur nos orientations technologiques. Les critiques construites sont bien évidemment les bienvenues (dans la mesure où vous respectez les conditions pour entrer).

Vous vous devez de respecter les choix technologiques de chacun. Nous divergeons tous dans la vision que nous avons de l'écosystème ECMAScript (aussi bien front-end que back-end). Il est donc normal que chacun ait des préférences particulières pour un framework plutôt qu'un autre. Nous encourageons la diversité et l'expression de ses choix dans l'objectif de partager votre expérience à la communauté.

Si vous souhaitez discuter d'une problématique qui ne concerne pas ECMAScript, utilisez le salon `#autres` de la section `Développement`. Attention néanmoins à ne pas en abuser en y demandant fréquemment de l'aide. Si c'est le cas, nous vous conseillons de chercher une communauté plus à même de répondre à vos attentes.

Les discussions à caractère personnel sont autorisées dans les salons  `#autres` et `#jeux` de la section `#autres` ainsi que dans le channel `#blabla` de la section `Général`.

Votre pseudonyme au sein de la communauté se doit d'être en relation avec l'esprit du code de conduite (respectueux, non offensant, etc.). Les changements de pseudonyme sont autorisés dès lors que les mentors (à minima) et la communauté sont informés. Les caractères spéciaux et/ou emoji ne sont pas autorisés au début du pseudonyme (cela nous rendant la tâche compliquée pour vous notifier).

```js
for await (const line of ESCommunity.prohibedBehaviors()) {
    console.log(`- ${line}`);
}
```
## Comportements et sujets de discussion prohibés
* attaque personnelle ;
* contenu pornographique ;
* harcèlement moral ;
* politique ;
* religions.

## Règles spécifiques à certain salons
* Il est interdit de réagir textuellement dans les salons `#liens`, `#jobs` et `#projets`.
* Les contenus présentés dans le salon `#projets` doivent être dans la thématique de la communauté, à savoir le développement.

En adoptant ce code de conduite, **vous vous engagez à respecter à la lettre chacune des règles ci-dessus**. Nous serons intransigeants sur le respect et l'application du code de conduite.

# Modération
Les sanctions et modalités d'application concernant les manquements au code de conduite sont définies dans le document [code de modération](./MODS.md).

# Contribution
Tout membre de la communauté a un droit de participation et de vote sur les différentes contributions et évolutions proposées au sein de l'organisation GitHub ou du serveur Discord lui-même. A cet égard, les mentors et les administrateurs sont en tout point égaux aux membres. Pour plus d'informations, merci de lire le [guide de contribution](./CONTRIBUTING.md).

# Invitation Discord
```js
document.getElementById('discordInvitation').addEventListener('click',function(e) {
    e.preventDefault();
    ESCommunity.invite(user);
});
```
[![ES-Community](https://discordapp.com/api/guilds/157205145669599233/embed.png?style=banner2)](https://discord.gg/zJsuc6vvhn)

Les membres n'ayant pas effectué une présentation dans le salon `#presentation` peuvent accéder aux salons `#annonces` et `#blabla` en lecture et au salon `#presentation` en écriture. Tous les autres salons leur sont inaccessibles.

Chaque présentation doit **être un minimum travaillé** et les mentors sont **en droit de vous demander de l'étoffer** si nécessaire. Voici des exemples d'informations **susceptibles d'intéresser les membres de la communauté** pour mieux vous connaître :

- Votre métier.
- Vos expériences et préférences (langages, technologies etc....).
- Profil GitHub / Gitlab / Bitbucket ou autres.
- Depuis combien de temps faites vous du JavaScript et/ou Node.js (par passion ou non).
- Comment avez-vous découvert la communauté.

# Salons
```js
const channels = ESCommunity.getChannels();
for (const [name, description] of channels) {
    console.log(`- \`#${name}\` - ${description}`)
}
```
## Liste
### Général
- `#annonces` - Salon des annonces officielles, seuls les modérateurs peuvent écrire
- `#presentation` - Présentations des membres de la communauté
- `#blabla` - Salon libre
- `#liens` - Ce salon vous permet d'envoyer des liens vers des projets/drafts intéressants (Obligatoirement en lien avec le groupe).
- `#lives` - Salon d'annonce de stream de nos membres.
- `#news` - Salon de suivi des nouvelles tech.
- `#jobs` - Salon permettant de partager des offres d'emploi au reste de la communauté

### Développement
- `#debutant` - Salon dédié à toutes questions de débutant
- `#ecmascript` - Tout ce qui est en liaison avec l'écosystème ECMAScript, par exemple : Babel, etc.
- `#front` - HTML & CSS, UI/UX Designer, WEBGL, Framework front, VanillaJS, JQuery, etc.
- `#nodejs` - Pour parler de tout ce qui concerne Node.js
- `#typescript` - Pour parler du langage TypeScript.
- `#native` - Tout ce qui concerne l'implémentation de packages natif sur Node.js (N-API, NaN et Neon).
- `#security` - Tout ce qui est lien avec la sécurité d'applications web, les bonnes pratiques d'authentification, etc.
- `#autres-dev` - Tout autres sujets qui concernent le développement.

### Systèmes et databases
- `#database` - Tout ce qui concerne des problèmes liés à une SGBD.
- `#linux` - Tout les systèmes Linux (UNIX).
- `#docker` - Tout ce qui concerne Docker. (Déploiement, configuration etc..).
- `#autres-sys` - Tout autres problèmes en liaison avec le système.

### Autres
- `#jeux` - Discussions autour de vos jeux préférés
- `#gif` - Salon d'échange de gifs funs autour du développement ou autres
- `#logs` - Salon de log des activités de l'ES-Community.
- `#projets` - Salon pour présenter les projets réalisés par les membres de la communauté
- `#autres` - Salon pour parler de tout et n'importe quoi !

### Evenements
- `#meetup` - Discussions autour des différents meetup.
- `#weektalk` - Infos sur les prochains [weektalks](https://github.com/ES-Community/weektalk).
- `#insomni-hack` - Discussions au sujet de [l'insomni-hack](https://insomnihack.ch).
- `#ludum-dare` - Discussions au sujet de [Ludum Dare](https://ldjam.com/events/ludum-dare/rules).
- `#advent-of-code` - Discussions au sujet de [l'advent of code](https://adventofcode.com/)

### Archives
- `#giveaway`
- `#covid`
- `#tweets` - Salon privé où le Bot publie fréquemment les tweets les plus intéressants sur Node.js et ECMAScript.
- `#design` - Salon permettant de partager des créations graphiques.
- `#battledev` - Discussion au sujet de la [BattleDev](https://battledev.blogdumoderateur.com).

## Formats
Pour certains salons, merci de bien vouloir respecter les formats suivants.

### #liens
Les liens doivent obligatoirement être en relation avec le développement.

`[**TITRE et/ou ÉMOJI**] Description - Lien`

![Salon liens](https://user-images.githubusercontent.com/2799010/45076365-4322f380-b0ea-11e8-9d98-3fb9913b0f20.png)

### #lives
Les lives doivent obligatoirement être en relation avec le développement.

```md
Description courte (ce que vous allez faire, stack utilisée, etc.)

Date (et heure) du live

Lien vers votre chaine
```

### #jobs
```md
**[ Orientation du poste ] - [ Langage(s) et/ou technologie(s) (si possible avec des émojis) ] - Intitulé du poste**

Description courte (missions proposés, lieu, nom de la boite, rémunération, etc.)

Lien de l'annonce et/ou contact
```

![Salon jobs](https://user-images.githubusercontent.com/2799010/45076330-25ee2500-b0ea-11e8-8a0f-ff97d2fd7dd8.png)

L'indication d'une fourchette de rémunération est obligatoire. La modération s'engage à retirer les annonces ne correspondant pas aux attentes et à en notifier l'auteurice (accompagné de l'annonce originale).

### #projets

```md
**Nom du projet**

Description du projet

<Lien du projet> (ex: site web, repo git)
```

![Salon projets](https://user-images.githubusercontent.com/2799010/45077282-05739a00-b0ed-11e8-9574-43152eb60e22.png)

## #news

Ce canal est en lecture seule, y seront retransmises les nouvelles de

- Typescript, TypeScript Community #updates (Discord), annonces des MaJs de Typescript
- Node.js, via feed atom (bot), annonces des releases de Node.js
- AdonisJS, AdonisJS Framework #📢-announces (Discord), annonces des MaJs de Adonis
- Tailwind CSS, Tailwind CSS #announcements (Discord), annonces des MaJs de Tailwind CSS

La communauté peut proposer la mise à jour de cette liste via une PR. Peuvent être envisagées comme source de communication simple :

- un canal d'annonce d'un serveur Discord
- un webhook

En l'absence de ces moyens, Feed RSS et scrapping peuvent être ajoutés via le [Bot](#Bot)

## Threads
Maintenant que Discord autorise la création de fils de discussion (threads), vous êtes libre de les utiliser.

- Si vous souhaitez commenter un message dans un des [salons ci-dessus](#formats), il est requis de passer par un fil de discussion dorénavant.
- Si vous sentez qu'une discussion prend le pas sur le canal, basculez sur un thread pour libérer le canal à d'autres sujets.

# Bot
La communauté développe et utilise son propre bot Discord, il est actuellement utilisé pour les fonctionnalités suivantes :
- Valider les messages postés dans les channels `#liens`, `#jobs` et `#projets`
- Poster des messages de manière automatique comme :
  - Des jeux en promotion provenant de [Epic Games](https://store.epicgames.com) et [GOG](https://www.gog.com) dans le channel `#jeux`
  - Les publications du site [XKCD](https://xkcd.com) dans le channel `#gif`

Si vous souhaitez l'améliorer ou proposer d'autres fonctionnalités, vous pouvez y contribuer sur [son dépôt GitHub](https://github.com/ES-Community/bot).

# Politique d'archivage
Plutôt que de supprimer un canal car il n'est pas utilisé par la communauté, il est possible de le déplacer dans la catégorie Archives et il passera en lecture seule.
Ce type de décision se prend via les PR : proposition d'une PR avec le canal à archiver déplacé dans la section Archives. Une fois la PR validée les administrateurs appliqueront la décision.

# Administrateurs
Les administrateurs mettent en application les décisions prises par la communauté et avertissent ou sanctionnent en cas de manquement au code de conduite de la part d'un membre.
Ils sont nommés à la discrétion des fondateurs, triés parmi les mentors.

Les administrateurs :
- Fraxken
- Purexo
- Xavier
- Romain Lanz
- Targos

Tout comportement abusif peut être rapporté aux Administrateurs de la communauté. Vous pouvez les mentionner sur Discord avec `@Administrateurs`.

# Mentors
Les mentors sont des membres brillant par leur investissement dans la communauté en étant particulièrement actifs avec une communication adéquate, pédagogique et bienveillante.
Ils participent à faire vivre le Discord en animant les discussions sur les évolutions du code de conduite, encouragent les membres à proposer des changements en les guidant au besoin et mettent en place les weektalks.
Ils sont nommés selon les modalités du [Code de contribution](CONTRIBUTING.md).

Les mentors :
- Fraxken
- Xavier
- Purexo
- Romain Lanz
- Targos
- Koko
- TnTakara
