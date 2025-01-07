# Segmentation des Clients d'un Site E-commerce

## Contexte du Projet

Olist est une entreprise brésilienne proposant une solution de vente sur les marketplaces en ligne. Dans le cadre de la mise en place de son écosystème Data et afin d’optimiser les efforts de communication de son équipe Marketing, Olist sollicite la création d'une segmentation clients détaillée. Cette segmentation permettra de mieux comprendre les comportements des utilisateurs et d'adapter les campagnes marketing en fonction de ces profils.

Le projet consiste à réaliser une segmentation non supervisée des clients d’Olist afin de regrouper ceux ayant des comportements ou des caractéristiques similaires. L’objectif est d’identifier des segments distincts permettant à l’équipe Marketing de personnaliser ses campagnes et de mieux cibler ses efforts de communication.
Objectifs du Projet

Les objectifs principaux du projet sont :
- Analyse exploratoire des données : Comprendre les données disponibles sur les clients et leurs comportements afin de définir des segments pertinents.
- Segmentation des clients : Utiliser des techniques de clustering pour regrouper les clients en différents segments, en fonction de leurs caractéristiques (historique des commandes, produits achetés, satisfaction, etc.).
- Description actionable de la segmentation : Fournir une description détaillée de chaque segment, de sa logique sous-jacente et des recommandations pratiques pour l’équipe Marketing.
- Analyse de la stabilité des segments : Proposer une fréquence de mise à jour des segments afin de maintenir leur pertinence au fil du temps, en fonction des évolutions du comportement des clients.
- Respect des standards de code : Assurer que le code respecte la convention PEP8 pour faciliter son intégration et sa maintenance par l’équipe d’Olist.

## Données

Les données mises à disposition par Olist sont anonymisées et comprennent les informations suivantes sur les clients depuis janvier 2017 :
- Historique des commandes : Données sur les achats passés, les quantités, et les fréquences des achats.
- Produits achetés : Information sur les produits sélectionnés par les clients.
- Satisfaction : Données sur les commentaires de satisfaction des clients.
- Localisation : L'emplacement géographique des clients.

Ces données serviront à comprendre les comportements des clients et à construire les segments.

## Méthodologie

Le projet se divise en plusieurs étapes clés :

Analyse exploratoire des données (EDA) :
- Exploration des données disponibles, identification des variables pertinentes et compréhension des distributions.
- Identification des comportements récurrents et des relations entre les différentes variables (historique des commandes, satisfaction, localisation, etc.).

Segmentation des clients :
- Application de méthodes non supervisées pour effectuer des regroupements de clients ayant des comportements ou des caractéristiques similaires.
- Utilisation de techniques de clustering (par exemple, K-means, DBSCAN, ou hierarchique) pour déterminer les segments les plus pertinents.

Création de la segmentation actionable :
- Fourniture d’une description détaillée de chaque segment, de ses caractéristiques et de la logique derrière chaque regroupement.
- Proposition de stratégies spécifiques pour chaque segment que l’équipe Marketing pourra utiliser pour ses campagnes.

Analyse de la stabilité des segments et mise à jour :
- Simulation de la fréquence nécessaire pour la mise à jour des segments afin de maintenir leur pertinence au fil du temps.
- Proposition d'une méthode de mise à jour basée sur l’évolution des comportements des clients.

Présentation des résultats :
- Rédaction d'un rapport de synthèse sur la segmentation, incluant les résultats du clustering et des recommandations pour la fréquence de mise à jour.
- Préparation d’une présentation interne pour obtenir les retours de l’équipe.

## Outils et Technologies

L’analyse et la segmentation sont réalisées avec les outils et bibliothèques suivants :
- Pandas pour la manipulation des données.
- Scikit-learn pour les méthodes de clustering et l’évaluation des performances.
- Matplotlib et Seaborn pour la visualisation des résultats.
- NumPy pour les opérations numériques.
- Jupyter Notebook pour la création de notebooks interactifs.

## Résultats et Application

Les résultats du projet permettront à l’équipe Marketing d’Olist de mieux cibler ses campagnes et de personnaliser ses messages en fonction des comportements et des profils des clients. La segmentation permettra également de différencier les bons et moins bons clients en termes de commandes et de satisfaction.

Une fois la segmentation réalisée, des recommandations seront fournies concernant la fréquence de mise à jour des segments, afin de garantir que ces derniers restent pertinents et actualisés au fil du temps. Cela permettra à Olist de maintenir une approche flexible et réactive face aux évolutions des comportements d'achat de ses clients.
