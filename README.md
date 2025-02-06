# Databricks-Accidents-Project

## Présentation du projet

Le projet présenté ici porte sur la prédiction de la gravité des accidents de la route en utilisant des algorithmes de machine learning, notamment la méthode des K plus proches voisins (KNN) et l'arbre de décision ainsi que le Random Forest. 
L'objectif est de créer un modèle performant capable de prédire, pour chaque victime d'accident, la gravité de ses blessures, en fonction de diverses caractéristiques relatives à l'accident.


## Les sources des données
Nous avons suivi un tutoriel réalisé par Ilyes Talbi (https://larevueia.fr/xgboost-vs-random-forest-predire-la-gravite-dun-accident-de-la-route/)
Les données ont été tirées du site data.gouv.fr.

Pour ce projet nous avons 4 fichiers différents. 

    carac.csv nous donne des caractéristiques sur les accidents.
    lieux.csv recense des données sur les lieux des accidents.
    veh.csv donne des informations sur les véhicules impliqués.
    vict.csv donne des informations sur les victimes.

## Le modèle retenu et ses performances

Le modèle retenu est l'abre de décision, c'est avec lui que nous avons le meuilleur f1-score (macro_avg)
Résultat : 
    - Decision tree : f1_score = 0.62
    - Random Forest : 0.61
    - KNN : 0.60

## Contenu du repository

Ce repository contient : 
  - Un ficher README.md qui présente le projet, les sources de données, le modèle retenu et ses performances.
  - Le notebook utilisé pour réaliser ce travail sur Azure DataBricks (.dbc)
