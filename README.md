# Groupe de Projet n°2 :

### Membres du groupe
ACHAHOUR Hamza
DUPUIS Jean
GUIGHIL Benjamin (chef de projet)
GUIGNARD Thomas
MOUHOUBI Khawla
RIBOUT Horace
VALEZE Valentin

## Installation
### Installation de Jetty et Jersey sur Eclipse :

Maven est requis pour faire fonctionner le code (gestion des dépendances)

* 1) Sur Eclipse aller dans Help -> Install New Software
* 2) Cliquer sur Add dans le coin en haut à droite
* 3) Dans la fenêtre qui s'affiche dans le champ Name mettre "M2Eclipse"
Et dans Location mettre "http://download.eclipse.org/technology/m2e/releases"
* 4) Cliquer sur OK après avoir tout coché dans l'écran au milieu (là où vous
    sera affiché Maven...)
    
### Installation de REST (Jersey inclus) :

Ici le plugin REST contient tout ce dont on a besoin, il manque juste "Jetty" (qu'on
installera plus tard...)

* 1) Sur Eclipse aller dans Help -> Eclipse Marketplace...
* 2) Dans la barre de recherche, tapper "Jersey" puis Entrer
* 3) Le plugin RESTful Plugin for Eclipse s'affichera, cliquer sur Install

### Installation de Jetty :

* 1) Sur Eclipse aller dans Help -> Install New Software
* 2) Cliquer sur Add
* 3) Dans Name mettre Eclipse Jetty et dans Location mettre
http://eclipse-jetty.github.io/update/

* 4) Cliquer sur OK après avoir tout coché dans l'écran au milieu (là où vous
    sera affiché Eclipse Jetty Integration...)

# Import du projet d'exemple des enseignants
Pour importer le projet d'exemple des professeurs et le compiler :

* 1) File -> Import -> Existing Maven Project
* 2) Clique droit sur le dossier du projet Run as -> Java Application
* 3) Une fois fais, aller dans le navigateur dans localhost:8080
