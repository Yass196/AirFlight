# AirFlight
REST API, Angular 8, .NET,  Flight company reservation system.

![](https://cdn.clipart.email/3e71cb82aa8ee84ffa95d23bdfb8995d_best-spider-web-illustrations-royalty-free-vector-graphics-clip-_612-387.jpeg)
#  Projet Web Crawler

## Description 
Le but de ce projet est de faire un logiciel qui permet de parcourir un site web ainsi que tous les liens de ce dernier. Une fois le parcours de toutes les URL effectuée :
- Afficher la liste des urls trouvés  ainsi que la liste des fichiers HTML, images et autre fichier trouvé en précisant cette fois leurs type et taille .
- Effectuer la recherche d’un mot clé et afficher les urls contenant ce mot clé.

## Structure du projet 
Nous avons réalisés deux versions différentes :
- **version 1** : avec GUI
- **version 2** : avec Interface Web et Serveur Web

## Exécution 
- Telecharger le dernier commit de gitlab
 - Nom du package : webCrawlerProject
 - Installer Java 11 ou supérieur
-  Télécharger les jars :
1. Jsoup 1.13.1 : https://jsoup.org/download  
1. Json-simple-1.1.1:http://www.java2s.com/Code/Jar/j/Downloadjsonsimple11jar.htm  
- Ajouter les Jars au projet sur Eclipse :
Project ⇒  Build Path ⇒  Configure Build Path ⇒  Libraries ⇒  Add external jars

## Etapes pour tester 
1. Télecharger le projet 
1. Utiliser un éditeur adéquat ( Eclipse/VisualStudio..)
1. Executer le main du projet :
    1. **versionGUI** : dans la classe Server()
    1. **versionWEB **: dans la classe ServerWeb() 
   ⇒ Pour cette version lancer un navigateur et saisir localhost:9000
1. Saisir l'url a explorer sur le input 
1.Une fois le resultat affiché , on peut chercher un mot 
    1. **versionGUI** : il suffit de saisir le mot a chercher sur l'input spécifique a cela .
    1. **versionWEB **:  un bouton s'affiche "Click here to search a word", il nous redirige vers une nouvelle fenêtre  ou on a un input pr cela .

## FichierJson et Index 
