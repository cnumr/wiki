
# ecoCode

## Informations utiles

-  __Catégorie__ : Système d'évaluation

-  __URL__ : [https://github.com/cnumr/ecoCode](https://github.com/cnumr/ecoCode)

-  __Auteurs__ : Geoffrey Lalloué / Jules Delecour

-  __Mainteneurs__ : [Geoffrey Lalloué](https://github.com/glalloue) / [Jules Delecour](https://github.com/jules-delecour-dav) / [Olivier Le Goaër](https://github.com/olegoaer) / [Julien Hertout](https://github.com/jhertout)

-  __Nombre d'utilisateurs__ : non connu / 12 forks / 15 stars (en date du 25.03.2022)

-  __Statut__ : Validé

## Description

### Objectifs de l'outil

ecoCode est un projet collectif visant à réduire l'empreinte environnementale des services du numériques en se focalisant sur la partie logicielle. Le but du projet est de fournir une liste d'analyseurs de code statiques pour identifier les défauts de qualité d'un code source pouvant avoir un impact écologique : consommation d'énergie et de ressources, obésiciel, durée de vie des terminaux, etc.

### Mode opératoire

ecoCode s'appuie sur des référentiels de bonnes pratiques évolutifs, adaptés à différentes technologies. 
Un plugin SonarQube implémente ensuite ces référentiels en se basant sur les règles identifiées pour scanner le code source d'un projet.

### Description détaillée

ecoCode supporte actuellement 4 technologies :

-   [Java](https://github.com/cnumr/ecoCode/blob/main/sonarqube-plugin-greenit/native-analyzer/java-plugin)
-   [PHP](https://github.com/cnumr/ecoCode/blob/main/sonarqube-plugin-greenit/native-analyzer/php-plugin)
-   [Python](https://github.com/cnumr/ecoCode/blob/main/sonarqube-plugin-greenit/native-analyzer/python-plugin)
-   [Android](https://github.com/cnumr/ecoCode/blob/main/sonarqube-plugin-greenit/native-analyzer/android-plugin)

## Outils associés

### Dépendances

Cet outil est dépendant du référentiel de règles (les 115 règles de l’écoconception) proposées par le CNumR.
Il n'est pas dépendant d'autres outils du CNumR

### Déclinaisons

Aucun autre outils utilise cet outil comme dépendance.

### Autres outils liés

Aucun autre outils CNumrR n'est associé à cet outil.

## Limitations / contraintes

ecoCode se base sur un référentiel de règles (les 115 règles de l'écoconception) qui sont protégées par une licence interdisant la commercialisation de celles-ci.

Les règles sont remontées dans l'outil. Celui-ci n'est donc pas commercialisable en tant qu'outil. 

Les résultats fournis par l’algorithme sont proposés sous [licence Creative Commons CC-By-NC-ND](https://creativecommons.org/licenses/by-nc-nd/2.0/fr/), il peut être possible de les intégrer dans une offre commerciale à condition de mentionner la source.

## Pour aller plus loin

https://github.com/cnumr/ecoCode