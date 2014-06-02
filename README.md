A l'heure actuelle, voici l'état d'avancement du projet : 

- Fonctionnalités complètes : Génération du labyrinthe, gestion des déplacements et collisions, gestion du héros et de ses attaques,et du gameplay (fin de partie, timers, vie, ...) et fichier de configuration.
- Fonctionnalités partielles : Mode multiplayer (en BETA), armes et objets (impossibilité de ramasser des objets dans le labyrinthe mais utilisation des armes par défaut).

Afin de pouvoir jouer à notre jeu, il faut impérativement avoir nodeJS sur son ordinateur. Afin que vous puissiez jouer, nous avons tout de même pensé à vous en installant notre jeu directement sur notre serveur afin que vous puissiez le tester dans de très bonnes conditions. L’url de notre serveur est http://141.138.157.237. Pour installer nodeJS, il faut télécharger le fichier sur le site http://nodejs.org/. Donc après l’installation de nodeJS il faut également installer git sur la machine. Pour installer git sur la machine, vous devez vous  rendre sur le site de git et le télécharger à l’adresse http://git-scm.com/. Il faut laisser faire l’installation par défaut. Git est un système de versioning. Il permettra de récupérer la dernière version sur notre github. Nous travaillons avec un système de versioning afin de collaborer ensemble de façon efficiente. Après l’installation de ces deux composants il faudra taper différentes commandes dans un terminal que nous allons expliquer:

- git clone http://github.com/baloran/labyrinthe (Cette commande permet de récupérer les dernière sources sur le github)
- cd labyrinthe (on se déplace dans le dossier que l’on vient de récupérer)
- npm install (on installe les dépendances dont on a besoin afin de fonctionner)
- sails lift (on lance l’application grâce au lanceur d’applications de notre framework, c’est-à-dire sails).


Il suffira ensuite de se rendre sur son navigateur préféré et de se rendre à l’url suivante afin de pouvoir profiter de notre jeu : http://localhost:1337

Afin d’améliorer notre note, nous avons décidé de rajouter des fonctionnalités permettant de jouer avec ses amis en mode pvp (Player Vs Player). En plus de cela, nous avons mis en place une API REST pour pouvoir utiliser une base de données d’item et d’ennemis. Cela permettra à des personnes de rajouter, grâce à une interface simple, des items et des ennemis simplement. Tout cela permet de pouvoir projeter le jeu dans le temps car beaucoup de choses sont en place afin de faciliter le développement.


Pour la liste des sources/inpirations:

- http://fr.wikipedia.org/wiki/Mod%C3%A9lisation_math%C3%A9matique_d%27un_labyrinthe
- http://fr.wikipedia.org/wiki/Algorithme_de_Dijkstra
- http://fr.wikipedia.org/wiki/Algorithme_A*
- http://socket.io/#how-to-use
- http://nodejs.org/api/
- http://beta.sailsjs.org/#!documentation