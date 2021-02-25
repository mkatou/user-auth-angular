# user-auth-angular

## Pour exécuter l'application

> npm start

        l'application se lance automatiquement sur le port 8080

## Existant

Comme il a été dit dans l'énocé du projet, nous sommes partis d'un projet déjà existant. Cette application a été développée avec la version 8 d'Angular. Elle permet à un utilisateur de s'enregistrer et ensuite de s'authentifier. C'est une application configurée avec Webpack 4.

## Le travail demandé

L'idée est d'ajouter un component à une application déjà existante.
Dans notre cas, nous avons ajouter un component alert pour gérer les arlets, c'est à dire afficher un message en 'danger' lorsqu'il a une erreur et en 'sucess' lorsque tout s'est bien passé.

## Déroulement

=> D'abord nous avons créé le service 'alert.service' dans lequel on définit un observable puis des méthodes success(), error() et clear()

=> Ensuite, nous avons créé un component '_components'.
Et dans ce component, nous avons un fichier 'alert.component.ts' dans lequel on définit la logique en souscrivant à l'observable créé au niveau du service 'alert.service'.

=> Enfin, le fichier 'alert.component.html' dans lequel nous faisons un biding afin d'afficher le message alert correspondant.
