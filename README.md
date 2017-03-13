```javascript
ESCommunity.init();
console.log("Bienvenue sur le code de conduite ES-Community");
```

# Objectifs 

L'objectif de la communauté est avant tout de fournir un lieu d'échange, d'entraide et de veille technologique autour de l'écosystème ECMAScript (Javascript).

C'est aussi l'occasion de rencontrer et parler avec des développeurs qui possèdent des intêrets en commun. Nous nous entraidons dans les problématiques les plus fréquentes et dans la gestion de notre stack (Administration système, Docker, Database, Modules etc..). 

Mais finalement, c'est aussi plusieurs salons où l'on peut discuter librement entre nous de nos tracas quotidien. Et pourquoi pas un jour, se rassembler tous ensemble autour d'une bière ! 

# Critères pour entrer : 

```javascript
const user = ESCommunity.connectedUser(); 

if(user instanceof ECMAScript_developer && user.age >= 16) {
    user.join(ESCommunity);
    user.send('présentation');
}
```

- Avoir **plus de 16 ans obligatoirement**.
- Etre développeur ECMAscript (Javascript) par passion ou par métier.
- Faire une pull-request sur membre.md avec votre présentation en respectant le format déjà présent dans le fichier (Vous pouvez venir et faire la pull-request après). 

> Nous n'acceptons pas les moins de 16 ans pour des questions de maturité et d'expérience de vie. Tous nos essais ont été des échecs...

# Code de conduite

```javascript
const code_of_conduct = await ESCommunity.code_of_conduct();
console.log(code_of_conduct);
```

En tant que membre de cette communauté, vous devez le respect à chaque développeur présent. Les insultes et les comportements désobligeants ne sont pas autorisés dans le groupe. Les moins expérimentés doivent redoubler d'efforts avant de requêter les autres sur des problématiques (le spam est interdit). 

N'oubliez jamais que tout projet est une tâche humaine lourde et difficile à gérer (surtout à long terme). Ne jugez donc pas trop vite les membres de la communauté. Respectez les projets de chacun et si cela ne vous plaît pas, gardez-vous de tout commentaire négatif ou ironique.

Les discussions à caractère **personnel** sont autorisées dans les salons **Général** & **Autres**. Dans les autres salons, les membres de la communauté peuvent vous demander en tout respect d'arrêter votre discussion ou de la déplacer dans le salon approprié.

La communauté est essentiellement constituée de développeurs ECMAscript, vous êtes donc priés de ne pas venir pour faire la guerre du meilleur langage de développement. Ce n'est point l'objectif de notre communauté. 
Les critiques sont bien évidemment les bienvenues (uniquement dans les salons **Général** et **Autres**). 

Tout recrutement abusif sera sanctionné. Ne venez donc pas dans l'unique but de recruter pour votre projet.

Les comportements de trolling sont prohibés si votre interlocuteur ne vous connaît pas ou peu. Il en va de même pour l'ironie ou toutes autres phrases à la limite de l'insulte gratuite. 

Les discussions autour de sujets politiques ou faisant référence aux religions sont prohibées.

Les débats doivent être explicitement fondés sur des bases techniques solides. Tout débat "guéguerre" du genre : "**C# VS JAVA**" sont prohibés de la communauté. Nous n'acceptons ce genre de débat que quand il y a des arguments de fond intéressants (comme par exemple : portabilité, gestion HA, etc.). Avoir une vision 360 degrés sur l'ensemble des éléments, c'est ce qui fait l'expertise (et pas seulement cracher sur la "**syntaxe**" qui ne nous convient pas).

Une trop longue période d'inactivité peut être la raison d'une expulsion du groupe. (Surtout si l'on ne vous connaît pas du tout).

**Autres comportements inadmissibles** : 

- Attaque personnelle. 
- Publication de contenu pornographique. 
- Harcèlement moral.

En adoptant ce code de conduite, **vous vous engagez à respecter à la lettre chacune des règles ci-dessus**. 

# Lien Discord : 

Lien d'invitation : [ES-Community](https://discord.gg/DTRKewP)

> **Attention :** Merci de vous présenter et de respecter le code de conduite ainsi que les règles pour nous rejoindre présente ci-dessus.

# Des salons pour chacun de vos besoins  

```javascript
const salons = ESCommunity.getSalons(); 
salons.forEach( salon => console.log(`- ${salon.name} (${salon.description})`) );
```

- **annonces** (salon des annonces officielles, seuls les modérateurs peuvent écrire).
- general & autres (salons libre).
- ecmascript (et tous qui est en liaison avec ECMAscript, par exemple : TypeScript, Babel, CoffeeScript etc..) 
- **nodejs**
- webgl (Tous qui concerne canvas,webgl ou des moteurs de jeu web comme phaser.io, superpowers, etc.) 
- html-css
- front (AngularJS, ReactJS, VueJS, RiotJS, JQuery, VanillaJS, etc.) 
- unix (Scripts bash, mise en production, etc..).
- ui-design
- cpp-rust (C++, notamment pour des packages C++ NodeJS avec le V8 Engine et Rust lang pour des bindings avec neon).
- database (SQL, MySQL, MariaDB, MongoDB, Redis, RethinkDB, etc.) 
- gif (Salon d'échange de gif fun autour du développement ou autres).
- games (Discussion autour de vos jeux préférés).
- exercices (Salon temporaire pour les exercices NodeJS).
- links

> Le salon **#liens** vous permet d'envoyer des liens vers des projets/drafts intéressants. Cela doit avoir un lien avec le groupe, bien évidemment. 

![Salon liens](https://i.imgur.com/Vs09TyU.png)

# Autres langages 

```javascript
const darkside = ['php','go','ruby','java','python','scala',...];
ESCommunity.getSalon('others').allow(darkside);
```

Si vous souhaitez discuter d'une problématique autour de PHP, Ruby, Go ou autres, utilisez le salon "**Autres**". Attention ce n'est pas non plus un salon qui est fait pour parler de vos problèmes quotidiens en PHP.

# Modérateurs  

Tous comportements abusifs peuvent être rapportés aux modérateurs de la communauté ! 

- Fraxken (@fraxken), Skype : fraxkens 
- Purexo (@Purexo_) 
- Xstoudi (@Xstoudi)
- Tiyo
- Antoine Neff
