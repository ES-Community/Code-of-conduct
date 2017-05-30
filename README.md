```javascript
ESCommunity.init();
console.log("Bienvenue sur le code de conduite ES-Community");
```

ES-Community est une communauté ECMAscript francophone créée fin 2015. Notre désir est de rassembler les développeurs ECMAscript passionnés et ou professionnelle en un seul point.

# Objectifs 

L'objectif de la communauté est avant tout de fournir un lieu d'échange, d'entraide et de veille technologique autour de l'écosystème ECMAScript (Javascript).

C'est aussi l'occasion de rencontrer et parler avec des développeurs qui possèdent des intêrets en commun avec vous. Nous nous entraidons dans les problématiques les plus fréquentes et dans la gestion de notre stack (Administration système, Docker, Base de donnée, Modules NPM, Frameworks, etc.). 

Mais finalement, c'est aussi plusieurs salons où l'on peut discuter librement entre nous de nos tracas quotidien. Et pourquoi pas un jour, se rassembler tous ensemble autour d'une bonne bière !
**EDIT** : C'est chose faite pour certains !

# Critères pour entrer sur le discord : 

```javascript
const user = ESCommunity.connectedUser(); 

if(user instanceof ECMAScriptDeveloper) {
    user.join(ESCommunity);
    user.commit(user.presentation);
}
```

- Etre développeur ECMAscript (Javascript) par passion ou par métier. Cela comprend aussi les débutants qui ont la volonté d'apprendre sérieusement.

> **Attention:** Nous serons plus strict sur le respect du code de conduite pour les plus jeunes.

# Code de conduite (A lire en entier)

```javascript
fs.createReadStream( path.join( __dirname , 'code_of_conduct.txt').pipe(process.stdout);
```

En tant que membre de cette communauté, vous devez le respect à chaque développeur présent (Humainement comme techniquement). Les insultes et les comportements désobligeants ne sont pas autorisés au sein de la communauté. Les moins expérimentés doivent redoubler d'efforts avant de requêter les autres sur des problématiques qui peuvent être résolues en faisant une simple recherche google. 

Nous sommes essentiellement constituées de développeurs ECMAscript, vous êtes donc priés de ne pas venir nous faire la guerre sur nos orientations technologiques. Les critiques construites sont bien évidemment les bienvenues (dans la mesure où vous respectez les conditions pour entrer).

Vous vous devez de respecter les choix technologiques de chacun. Nous divergeons tous dans la vision que nous avons de l'écosystème ECMAscript (aussi bien front-end que back-end). Il est donc normal que chacun est des préférences particulières pour un framework plutôt qu'un autre. Nous encourageons la diversité et l'expression de ses choix à travers la communauté dans l'objectif de faire partager votre expérience à tous les utilisateurs. Cela donnera peut-être lieu à des débats constructifs qui serviront les intérêts de chacun (dans le plus grand des calmes et respect).

Si vous souhaitez discuter d'une problématique autour de PHP, Ruby, Go ou autres, utilisez le salon "**Others**". Attention ce n'est pas non plus un salon qui est fait pour parler de vos problèmes quotidiens en PHP. Si vous avez besoin d'aide sur un autre langage nous vous conseillons de chercher de l'aide sur une autre communauté.

Les discussions à caractère **personnel** sont autorisées dans les salons **General**, **Others** et **Games**. 

**Comportements et sujets de discussion prohibées** : 

- Attaque personnelle. 
- Contenu pornographique. 
- Harcèlement moral.
- La politique
- Les religions

En adoptant ce code de conduite, **vous vous engagez à respecter à la lettre chacune des règles ci-dessus**. 

# Invitation Discord : 

[![ES-Community](https://discordapp.com/api/guilds/157205145669599233/embed.png?style=banner2)](https://discord.gg/DTRKewP)

> **Attention :** Les membres n'ayant pas effectué une présentation auront un accès restreint à plusieurs salons (ecmascript, nodejs, front, system, cpp-rust, database, gif, links et games) et n'auront pas accès au rôle `@Community`

# Des salons pour chacun de vos besoins  

```javascript
const channels = ESCommunity.getChannels(); 
channels.forEach( channel => console.log(`- ${channel.name} (${channel.description})`) );
```

- **annonces** (salon des annonces officielles, seuls les modérateurs peuvent écrire).
- general & autres (salons libre).
- ecmascript (et tous qui est en liaison avec ECMAscript, par exemple : TypeScript, Babel, CoffeeScript etc..) 
- **nodejs**
- front (HTML & CSS, UI/UX Designer, WEBGL, Framework front, VanillaJS, JQuery etc.) 
- system (Scripts bash, mise en production, etc..).
- cpp-rust (C++, notamment pour des packages C++ NodeJS avec le V8 Engine et Rust lang pour des bindings avec neon).
- database (SQL, MySQL, MariaDB, MongoDB, Redis, RethinkDB, etc.) 
- others (Un peu tout et rien).
- gif (Salon d'échange de gif fun autour du développement ou autres).
- games (Discussion autour de vos jeux préférés).
- vocal (Salon pour échanger lors d'un vocal)
- links

> Le salon **#links** vous permet d'envoyer des liens vers des projets/drafts intéressants. Cela doit avoir un lien avec le groupe, bien évidemment. 

![Salon liens](https://i.imgur.com/Vs09TyU.png)

# Modération  

Tous comportements abusifs peuvent être rapportés aux modérateurs de la communauté Vous pouvez les mentionners sur Discord avec `@Moderateur`.

Les modérateurs : 

- Fraxken
- Xavier
- Purexo
- Tiyo
- Antoine N.

