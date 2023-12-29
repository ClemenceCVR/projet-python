# Projet Python pour la data science - ENSAE Paris - 2A

## Clémence Chevrier et Soline Mignot

### Introduction
Voici le Github réalisé dans le cadre de notre projet Python. Nous nous sommes intéressées au prix de l'immobilier en France, et plus particulièrement à Paris. Ce projet Python vise à explorer et analyser les prix de l'immobilier en France, en mettant particulièrement l'accent sur la ville de Paris. L'objectif est de comprendre les tendances du marché immobilier et d'identifier les facteurs qui influent sur la valeur foncière. Nous avons choisi de nous intéresser aux prix de l'immobilier en raison de leur impact significatif sur l'économie, les individus et la société dans son ensemble. Comprendre les tendances immobilières, en particulier dans une ville dynamique comme Paris, peut fournir des informations cruciales pour les décisions d'investissement, les politiques publiques et la planification urbaine.

### Sources des données

La base de données principale provient de data.gouv.fr et comprend les demandes de valeurs foncières géolocalisées. Cette base de données contient plus de 4,6 millions d'enregistrements qui ont été nettoyés et préparés pour l'analyse. En plus des données foncières, nous avons utilisé des bases de données complémentaires sur les gares parisiennes et les espaces verts à Paris, également disponibles sur data.gouv.fr.

### Structure du projet

Dans un premier temps, nous avons commencé par nettoyer la base de données et réaliser des statistiques descriptives couvrant la France et l'Île-de-France. Par la suite, nous nous sommes intéressées à une analyse approfondie de la corrélation entre les variables, qu'elles soient qualitatives ou quantitatives, et la valeur foncière. Ensuite, nous avons réduit notre analyse à Paris, où nous avons introduit de nouvelles variables absentes dans la base de données initiale. Finalement, nous avons procédé à la modélisation des données parisiennes, effectué le traitement du modèle, appliqué la méthode des moindres carrés, puis réalisé une autre régression afin d'affiner encore plus notre compréhension des dynamiques du marché immobilier dans la capitale.

### Fichiers

Les fichiers sont :
- projet_python_final.ipynb, qui contient tout notre code
- departements-version-simplifiee.geojson, permettant de tracer les départements sur une carte de France
- emplacement-des-gares-idf.csv, qui contient toutes les gares d'Ile de France
- stations_les_plus_proches.txt, qui permet d'avoir accès au résultat d'un code qui met 1h20 à tourner
- df_paris_espaces_verts_les_plus_proches.txt, qui permet d'avoir accès au résultat d'un code qui met 16 min à tourner
