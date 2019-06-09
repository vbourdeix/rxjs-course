
## Cours RxJS en pratique

Ce dépôt contient le code du cours [RxJs en pratique](https://angular-university.io/course/rxjs-course).

Ce dépôt est à jour avec Angular 8, et un fichier package-lock.json est disponible, pour éviter des problèmes d'installation liés au versionning sémantique.

![RxJs en pratique](https://s3-us-west-1.amazonaws.com/angular-university/course-images/rxjs-in-practice-course.png)


# Prérequis d'installation

IMPORTANT: Veuillez utiliser la dernière version de Node et en particulier NPM, pour vous assurer que le package-lock.json soit utilisé.

Pour exécuter ce projet, npm doit être installé sur votre machine. Voici quelques tutoriels pour installer node sur différents environnements :

*Il est important d'installer une version récente de node*

- [Installer Node et NPM sur Windows](https://www.youtube.com/watch?v=8ODS6RM6x7g)
- [Installer Node et NPM sur Linux](https://www.youtube.com/watch?v=yUdHk-Dk_BY)
- [Installer Node et NPM sur Mac](https://www.youtube.com/watch?v=Imj8PgG3bZU)


# Installation d'Angular CLI

Vous pouvez installer angular-cli de manière globale sur votre machine avec la commande suivante:

    npm install -g @angular/cli 


# Comment utiliser ce dépôt

Vous pouvez installer la branche master avec les commandes suivantes:

    git clone https://github.com/vbourdeix/rxjs-course.git
    
Lancez la commande suivante pour installer les dépendances (node_modules) :

    npm install 

En utilisant une version de NPM supérieure à 5 vous vous assurerez d'installer exactement les bonnes versions des dépendances, de manière à ne pas rencontrer de problème lié aux mises à jour suivant le versionning sémantique.

Cela peut prendre quelques minutes.

# Lancer le backend

Afin de pouvoir fournir des exemples réalistes, nous allons avoir besoin de faire tourner une petite API REST d'exemple comme backend. Vous pouvez lancer le backend d'exemple fourni avec la commande suivante :

    npm run server

Il s'agit d'une API REST servie par Express (serveur Node).

# Lancer le frontend

Pour faire tourner le frontend, vous pouvez lancer la commande suivante :

    npm start 

L'application est alors accessible sur le port 4200 4200: [http://localhost:4200](http://localhost:4200)



# Important 

Ce dépôt contient plusieurs branches correspondant à différentes étapes des exemples fournis en cours.

Vous pouvez consulter la liste des branches disponibles avec la commande suivante :

    git branch -a

Pour récupérer une branche distante dans votre dépôt git local du même nom, vous devez lancer la commande suivante (exemple avec la branche 1-navigation-and-containers) :

      git checkout -b section-1 origin/1-navigation-and-containers

Vous pouvez également télécharger une archive zip d'une branche donnée en la sélectionnant parmi la liste des branches en haut à gauche de l'interface sur github, puis en cliquant sur le bouton "Clone or Download" puis "Download as ZIP".
