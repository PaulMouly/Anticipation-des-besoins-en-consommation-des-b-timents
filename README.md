# Anticipation-des-besoins-en-consommation-de-bâtiments

L’objectif de ce projet est de prédire la consommation énergétique et les émissions de CO2 des bâtiments commerciaux qui n'avaient pas encore fait l'objet de relevés, en se basant sur des données structurelles. Ce travail s'inscrit dans un objectif plus large visant à devenir neutre en émissions de carbone d'ici 2050.

Étapes du projet :

    Analyse exploratoire des données :
        Exploration des caractéristiques des bâtiments (taille, usage, localisation, etc.) et identification des corrélations entre ces variables et les émissions de CO2 et la consommation d’énergie.

    Traitement des données :
        Nettoyage et prétraitement des données pour gérer les valeurs manquantes, appliquer des transformations (normalisation, log-transformations) et créer des variables supplémentaires à partir des informations existantes, comme la nature des sources d’énergie utilisées.

    Évaluation de l'ENERGY STAR Score :
        Test de l’intégration du score ENERGY STAR dans la modélisation pour voir s’il améliore la prédiction des émissions et de la consommation d’énergie.

    Modélisation et prédiction :
        Utilisation de plusieurs algorithmes de machine learning (ElasticNet, SVM, GradientBoosting, RandomForest) pour prédire les émissions de CO2 et la consommation énergétique des bâtiments.
        Optimisation des hyperparamètres et évaluation des modèles à l’aide de validation croisée pour choisir le meilleur modèle.

Ce projet permet de démontrer l’importance de l’analyse structurelle des bâtiments dans la prédiction de leur consommation énergétique et de leurs émissions de CO2, ainsi que l’utilité de l’ENERGY STAR Score pour améliorer les modèles de prédiction.
