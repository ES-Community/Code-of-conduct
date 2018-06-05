<p align="center"><img src="https://i.imgur.com/6PwmrOg.png" width="250"></p>

```javascript
setImmediate( async function() {
    await ESCommunity.init();
    console.log("Bienvenue sur le code de conduite ES-Community");
});
```

ES-Community est une communauté ECMAScript francophone créée fin 2015. Notre désir est de rassembler les développeurs ECMAScript passionnés et ou professionnels en un seul point.

# Objectifs 

L'objectif de la communauté est avant tout de fournir un lieu d'échange, d'entraide et de veille technologique autour de l'écosystème ECMAScript (Javascript).

C'est aussi l'occasion de rencontrer et parler avec des développeurs qui possèdent des intérêts en commun avec vous. Nous nous entraidons dans les problématiques les plus fréquentes et dans la gestion de notre stack (Administration système, Docker, Base de données, Modules NPM, Frameworks, etc.). 

Mais finalement, c'est aussi plusieurs salons où l'on peut discuter librement entre nous de nos tracas quotidien. Et pourquoi pas un jour, se rassembler tous ensemble autour d'une bonne bière !
**EDIT** : C'est chose faite pour certains !

# Critères pour entrer sur le discord : 

```javascript
const user = process.connectedUser(); 

if(user instanceof ECMAScriptDeveloper) {
    user.join(ESCommunity);
    user.setChannel('Presentation');
    user.write(user.presentation);
}
```

- Être développeur ECMAScript (Javascript) par passion ou par métier. Cela comprend aussi les débutants qui ont la volonté d'apprendre sérieusement.

> **Attention:** Nous serons plus stricts sur le respect du code de conduite pour les plus jeunes.

# Code de conduite (À lire en entier)

```javascript
fs.createReadStream(path.join( __dirname , 'code_of_conduct.txt')).pipe(process.stdout);
```

En tant que membre de cette communauté, vous devez le respect à chaque développeur présent (humainement comme techniquement). Les insultes et les comportements désobligeants ne sont pas autorisés au sein de la communauté. Les moins expérimentés doivent redoubler d'efforts avant de requêter les autres sur des problématiques qui peuvent être résolues en faisant une simple recherche Google. 

Nous sommes essentiellement constitués de développeurs ECMAScript, vous êtes donc priés de ne pas venir nous faire la guerre sur nos orientations technologiques. Les critiques construites sont bien évidemment les bienvenues (dans la mesure où vous respectez les conditions pour entrer).

Vous vous devez de respecter les choix technologiques de chacun. Nous divergeons tous dans la vision que nous avons de l'écosystème ECMAScript (aussi bien front-end que back-end). Il est donc normal que chacun ait des préférences particulières pour un framework plutôt qu'un autre. Nous encourageons la diversité et l'expression de ses choix dans l'objectif de faire partager votre expérience à la communauté.

Si vous souhaitez discuter d'une problématique qui ne concerne pas ECMAScript, utilisez le salon "**Others**". Attention néanmoins à ne pas en abuser en demandant fréquemment de l'aide. Dans le cas contraire nous vous conseillons de chercher une communauté plus à même de répondre à vos attentes.

Les discussions à caractère **personnel** sont autorisées dans les salons **General**, **Others** et **Games**. 

```js
for await(const line of readLines( ESCommunity.prohibedBehaviors() ) ) {
    console.log(`- ${line}`);
}
```

Votre pseudonyme au sein de la communauté se doit d'être en relation avec l'esprit du code de conduite (respectueux, non offensant). Les changements de pseudonyme sont autorisés dès lors que les mentors (à minima) et la communauté sont mis au courant.

**Comportements et sujets de discussion prohibées** : 

- Attaque personnelle
- Contenu pornographique
- Harcèlement moral
- La politique
- Les religions

En adoptant ce code de conduite, **vous vous engagez à respecter à la lettre chacune des règles ci-dessus**. Nous serons intransigeants sur le respect et l'application du code de conduite quand il s'agit de jeunes développeurs. 

# Invitation Discord : 

```js
document.getElementById('discordInvitation').addEventListener('click',function(e) {
    e.preventDefault(); 
    ESCommunity.invite(user);
});
```

[![ES-Community](https://discordapp.com/api/guilds/157205145669599233/embed.png?style=banner2)](https://discord.gg/DTRKewP)

Les membres n'ayant pas effectué une présentation dans le salon `#presentation` auront un accès restreint à plusieurs salons.

Chaque présentation doit **être un minimum travaillé** et les mentors sont **en droit de vous demander de l'étoffer** si nécessaire. Voici des exemples d'informations **susceptibles d'intéresser les membres de la communauté** pour mieux vous connaître :

- Vôtre métier.
- Vos expériences et préférences (langages, technologies etc....).
- Profile Github/Gitlab/Bitbucket ou autres.
- Depuis combien de temps faites vous du JavaScript et/ou Node.JS (par passion ou non).
- Comment avez-vous découvert la communauté.

# Des salons pour chacun de vos besoins  

```javascript
const channels = ESCommunity.getChannels(); 
channels.forEach( channel => console.log(`- ${channel.name} (${channel.description})`) );
```

#### GENERAL
- `#annonces` - Salon des annonces officielles, seuls les modérateurs peuvent écrire
- `#presentation` - Présentations des membres de la communauté
- `#blabla` - Salon libre
- `#liens` - Ce salon vous permet d'envoyer des liens vers des projets/drafts intéressants (Obligatoirement en lien avec le groupe).
- `#tweets` - Salon privé où le Bot publie fréquemment les tweets les plus intéressants sur Node.JS et ECMAScript.

#### DEVELOPPEMENT
- `#ecmascript` - Tout ce qui est en liaison avec l'écosystème ECMAscript, par exemple : TypeScript, Babel, etc.
- `#nodejs` - Pour parler de tout ce qui concerne NodeJS
- `#front` - HTML & CSS, UI/UX Designer, WEBGL, Framework front, VanillaJS, JQuery, etc.
- `#node-native` - Tout ce qui concerne l'implémentation de packages natif sur Node.JS (N-API, NaN et Neon).
- `#autres` - Tout autres sujets qui concernent le développement.

#### BASE DE DONNEES
- `#systemes-sql` - Tout ce qui concerne les bases de type SQL (MySQL, MariaDB, SQL Server etc..).
- `#mongodb` - Salon dédié à la base MongoDB.
- `#rethinkdb` - Salon dédié à la base RethinkDB.
- `#redis` - Salon dédié à la base/broker Redis.
- `#autres` - Discussions et aides sur tout autres bases NoSQL.

#### ADMINISTRATION SYSTEME
- `#linux` - Tout les systèmes Linux (UNIX).
- `#docker` - Tout ce qui concerne Docker. (Déploiement, configuration etc..).
- `#windows` - Un problème avec Windows ?
- `#autres` - Tout autres problèmes en liaison avec le système.

#### AUTRES
- `#jeux` - Discussions autour de vos jeux préférés
- `#gif` - Salon d'échange de gifs funs autour du développement ou autres
- `#logs` - Salon de log des activités de l'ES-Community.
- `#projet` - Salon pour pésenter les projets réalisés par les membres de la communauté
- `#vocal` - Salon pour échanger lors d'un vocal
- `autres` - Salon pour parler de tout et n'importe quoi !

![Salon liens](https://i.imgur.com/Vs09TyU.png)

Merci de respecter le format suivant : `[**TITRE ET/OU EMOJI**] Description - Lien`. Les liens doivent obligatoirement être en relation avec le développement. 

# Mentors (Modération)  

Tout comportement abusif peut être rapporté aux Mentors de la communauté. Vous pouvez les mentionner sur Discord avec `@Mentor`.

Les mentors : 

- Fraxken
- Xavier
- Purexo
- Tiyo
- Antoine N.
- Nolan 🇨🇭
- Romain Lanz

