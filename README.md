# BonheurNationalBrut
Comment prédire le niveau de bonheur d'un pays ?
![Démonstration streamlit](https://bonheur-national-brut.streamlit.app/)


## Introduction: 

Le bonheur est une aspiration universelle partagée par tous les individus, suscitant un vif intérêt. Cette étude se focalise sur le bonheur dans le monde et cherche à comprendre les facteurs qui l'influencent et à évaluer leur poids. L'objectif est de déterminer les raisons pour lesquelles certains pays sont mieux classés que d'autres en termes de bonheur, et de répondre à la problématique : 
QUELS FACTEURS ONT LE PLUS D'INFLUENCE SUR LE BONHEUR DES INDIVIDUS ?


## Extraction et mutualisation des données: 

Deux jeux de données ont été utilisés : le World Happiness Report 2021 et le World Happiness Report. Ils ont été obtenus à partir de Kaggle et contiennent des informations sur différents facteurs liés au bonheur dans les pays. Des données supplémentaires ont également été ajoutées, telles que des indicateurs sur la guerre, le chômage et d'autres facteurs sociaux et politiques.


## Modélisation : quantitatif et classification: 

La modélisation quantitative vise à prédire le bonheur à partir du dataset 2021 en utilisant des modèles de régression. Différents modèles ont été testés, tels que la régression linéaire, Ridge, Lasso et Elastic Net. La régression linéaire multiple s'est avérée être la méthode la plus performante pour prédire le bonheur dans un pays. Les modèles de classification ont également été utilisés pour identifier les variables prédictives du bonheur. Le modèle de Random Forest Classifier a obtenu les meilleurs résultats.


## Conclusion:

En conclusion, cette étude a permis de comprendre les facteurs qui influencent le bonheur dans le monde. La régression linéaire multiple s'est avérée être la méthode la plus performante pour prédire le bonheur dans un pays. Le modèle de Random Forest Classifier a été identifié comme le plus adapté pour la classification des variables prédictives du bonheur. Ces résultats montrent l'importance des facteurs économiques, sociaux et politiques dans le bonheur des individus.




Les variables ayant le plus de poids sont le PIB, la liberté de la presse et l'espérance de vie en bonne santé. Nos analyses nous ont permis de mettre en place un quiz permettant de prédire son score de bonheur personnel.
![Démonstration streamlit](https://bonheur-national-brut.streamlit.app/)
