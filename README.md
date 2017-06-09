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

- Etre développeur ECMAScript (Javascript) par passion ou par métier. Cela comprend aussi les débutants qui ont la volonté d'apprendre sérieusement.

> **Attention:** Nous serons plus stricts sur le respect du code de conduite pour les plus jeunes.

# Code de conduite (A lire en entier)

```javascript
fs.createReadStream( path.join( __dirname , 'code_of_conduct.txt').pipe(process.stdout);
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

> **Attention :** Les membres n'ayant pas effectué une présentation dans le salon `#presentation` auront un accès restreint à plusieurs salons (ecmascript, nodejs, front, system, cpp-rust, database, gif, links et games).

# Des salons pour chacun de vos besoins  

```javascript
const channels = ESCommunity.getChannels(); 
channels.forEach( channel => console.log(`- ${channel.name} (${channel.description})`) );
```

- `#annonces` - Salon des annonces officielles, seuls les modérateurs peuvent écrire
- `#general` & `#others` - Salons libres
- `#presentation` - Présentations des membres de la communauté
- `#ecmascript` - Tout ce qui est en liaison avec l'écosystème ECMAscript, par exemple : TypeScript, Babel, etc.
- `#nodejs` - Pour parler de tout ce qui concerne NodeJS
- `#front` - HTML & CSS, UI/UX Designer, WEBGL, Framework front, VanillaJS, JQuery, etc.
- `#system` - Scripts bash, mise en production, etc.
- `#cpp-rust` - C++, notamment pour des packages C++ NodeJS avec le V8 Engine et Rust-lang pour des bindings avec neon
- `#Database` - SQL, MySQL, MariaDB, MongoDB, Redis, RethinkDB, etc.
- `#gif` - Salon d'échange de gifs funs autour du développement ou autres
- `#games` - Discussions autour de vos jeux préférés
- `#vocal` - Salon pour échanger lors d'un vocal
- `#links` - Ce salon vous permet d'envoyer des liens vers des projets/drafts intéressants. Cela doit avoir un lien avec le groupe, bien évidemment

![Salon liens](https://i.imgur.com/Vs09TyU.png)

Merci de respecter le format suivant : `[**TITRE ET/OU EMOJI**] Description - Lien`. Les liens doivent obligatoirement être en relation avec le développement. 

# Modération  

Tout comportement abusif peut être rapporté aux modérateurs de la communauté. Vous pouvez les mentionner sur Discord avec `@Moderateur`.

Les modérateurs : 

- Fraxken
- Xavier
- Purexo
- Tiyo
- Antoine N.

