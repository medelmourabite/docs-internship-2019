# Technologies et outils utilisés
1. ## Front end
    1. ### React:

        #### Description:
        React (aussi appelé React.js ou ReactJS) est une bibliothèque JavaScript libre développée par Facebook depuis 2013. Le but principal de cette bibliothèque est de faciliter la création d'application web monopage, via la création de composants dépendant d'un état et générant une page (ou portion) HTML à chaque changement d'état.
        React est une bibliothèque qui ne gère que l'interface de l'application, considéré comme la vue dans le modèle MVC. Elle peut ainsi être utilisée avec une autre bibliothèque ou un framework MVC comme AngularJS.

        #### Utilisation:
        Dans le projet, React est utilisé pour concevoir les interfaces de l'application **emailing**.
        Il facilite la creation de composants réutilisabales
        le chois de cette bibliotheque est basé sur le fais qu'elle se démarque de ses concurrents par sa flexibilité et ses performances, en travaillant avec un DOM virtuel et en ne mettant à jour le rendu dans le navigateur qu'en cas de nécessité.

        #### Autres composants:
        * ##### Babel:
        Babel ou Babel.js est un compilateur JavaScript gratuit et à code source ouvert, ainsi qu'un transpileur configurable utilisé dans le développement Web. Babel permet aux développeurs de logiciels d'écrire du code source dans un langage de programmation ou un langage de balisage préféré et de le faire traduire par Babel en JavaScript, un langage compris par les navigateurs Web modernes.

        Babel est un outil populaire pour utiliser les dernières fonctionnalités du langage de programmation JavaScript. En tant que transpiler ou compilateur source à source, les développeurs peuvent programmer en utilisant les nouvelles fonctionnalités du langage ECMAScript 6 (ES6) en utilisant Babel pour convertir leur code source en versions de JavaScript que les navigateurs en évolution peuvent traiter. La version principale de Babel est téléchargée 5 millions de fois par mois.

        Les plugins Babel sont disponibles pour fournir des conversions spécifiques utilisées dans le développement Web. Par exemple, les développeurs travaillant avec React.js peuvent utiliser Babel pour convertir le balisage JSX (JavaScript eXtension) en JavaScript à l’aide du paramètre prédéfini de Babel "react".

        * ##### SASS
        Sass (Syntactically Awesome Stylesheets) est un langage dynamique de génération de feuilles de style en cascade initialement développé par Hampton Catlin et Nathalie Weizenbaum.

        Sass est un préprocesseur CSS. C'est un langage de description compilé en CSS. SassScript est un langage de script pouvant être utilisé à l’intérieur du code Sass. Deux syntaxes existent. La syntaxe originale, nommée « syntaxe indentée », est proche de Haml. La nouvelle syntaxe se nomme SCSS. Elle a un formalisme proche de CSS.

    2. ### Express:
        #### Description:
        Express.js est un framework pour construire des applications web basées sur Node.js. C'est de fait le framework standard pour le développement de serveur en Node.js. L'auteur original, TJ Holowaychuck, le décrit comme un serveur inspiré de Sinatra 4 dans le sens qu'il est relativement minimaliste tout en permettant d'étendre ses fonctionnalités via des plugins.
        


### Laravel :
Laravel est un framework web open-source écrit en PHP respectant le principe modèle-vue-contrôleur et entièrement développé en programmation orientée objet. Laravel est distribué sous licence MIT, avec ses sources hébergées sur GitHub.
Laravel a été créé par Taylor Otwell en juin 2011.
Le référentiel Laravel/laravel présent sur le site GitHub contient le code source des premières versions de Laravel. À partir de la cinquième version, le framework est développé au sein du référentiel Laravel/framework.
En peu de temps, une communauté d'utilisateurs du framework s'est constituée, et il est devenu en 2016 le projet PHP le mieux noté de GitHub.
Laravel reste pourtant basé sur son grand frère Symfony, pour au moins 30 % de ses lignes (utilisation de "Symfony component").

## API:
### Symfony 3:
Symfony est un ensemble de composants PHP ainsi qu'un framework MVC libre écrit en PHP. Il fournit des fonctionnalités modulables et adaptables qui permettent de faciliter et d’accélérer le développement d'un site web.
L'agence web française SensioLabs est à l'origine du framework Sensio Framework. À force de toujours recréer les mêmes fonctionnalités de gestion d'utilisateurs, gestion ORM, etc., elle a développé ce framework pour ses propres besoins. Comme ces problématiques étaient souvent les mêmes pour d'autres développeurs, le code a été par la suite partagé avec la communauté des développeurs PHP.


1. ## Docker:
    Docker est un logiciel libre permettant facilement de lancer des applications dans des conteneurs logiciels.

    Docker est un outil qui peut empaqueter une application et ses dépendances dans un conteneur isolé, qui pourra être exécuté sur n'importe quel serveur. Il ne s'agit pas de virtualisation, mais de conteneurisation, une forme plus légère qui s'appuie sur certaines parties de la machine hôte pour son fonctionnement. Cette approche permet d'accroître la flexibilité et la portabilité d’exécution d'une application, laquelle va pouvoir tourner de façon fiable et prédictible sur une grande variété de machines hôtes, que ce soit sur la machine locale, un cloud privé ou public, une machine nue, etc
1. ## NGINX
    NGINX est un logiciel libre de serveur Web (ou HTTP) ainsi qu'un proxy inverse écrit par Igor Sysoev, dont le développement a débuté en 2002 pour les besoins d'un site russe à très fort trafic (Rambler). Une partie de la documentation a été traduite du russe vers l'anglais.
1. ## Php-fpm
    PHP-FPM (FastCGI Process Manager) est une interface SAPI permettant la communication entre un serveur Web et PHP, basée sur le protocole FastCGI et écrite par Andrei Nigmatulin. Il constitue ainsi une alternative au serveur PHP avec des options pour les sites subissant de fortes charges.
1. ## Webpack
    Webpack est un ensemble de modules JavaScript opensource. Son objectif principal est de regrouper des fichiers JavaScript pour les utiliser dans un navigateur, mais il est également capable de transformer, regrouper ou empaqueter à peu près n'importe quelle ressource. Webpack prend des modules avec des dépendances et génère des actifs statiques représentant ces modules. Il s'agit d'un ensemble de modules principalement destiné à JavaScript, mais il peut transformer des actifs frontaux tels que HTML, CSS et même des images si les plug-ins correspondants sont inclus.
1. ## Nodejs
    Node.js est une plateforme logicielle libre et événementielle en JavaScript orientée vers les applications réseau qui doivent pouvoir monter en charge.
    Parmi les modules natifs de Node.js, on retrouve http qui permet le développement de serveur HTTP. Il est donc possible de se passer de serveurs web tels que Nginx ou Apache lors du déploiement de sites et d'applications web développés avec Node.js.
    Concrètement, Node.js est un environnement bas niveau permettant l’exécution de JavaScript côté serveur.

1. ## MySQL
    MySQL est un système de gestion de bases de données relationnelles (SGBDR). Il fait partie des logiciels de gestion de base de données les plus utilisés au monde, autant par le grand public (applications web principalement) que par des professionnels, en concurrence avec Oracle, PostgreSQL et Microsoft SQL Server. 
