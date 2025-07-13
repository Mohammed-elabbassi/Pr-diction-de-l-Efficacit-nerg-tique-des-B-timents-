# Prédiction de l'Efficacité Énergétique des Bâtiments 
## Description du Projet 
Le projet consiste à utiliser la base de données sur l'efficacité énergétique des 
bâtiments pour développer un modèle de machine learning capable de prédire la 
charge de chauffage et la charge de refroidissement des bâtiments en fonction de 
divers paramètres de construction. 
## Objectifs 
• Analyser les caractéristiques des bâtiments qui influencent leur efficacité 
énergétique. 
• Développer des modèles de régression (ELM , BP)  pour prédire les charges de 
chauffage et de refroidissement. 
• Évaluer la performance des modèles en utilisant des métriques appropriées. 
Étapes du Projet 
1. Collecte de Données : 
o Utiliser le dataset ENB2012_data.xlsx qui comprend 768 échantillons et 8 
caractéristiques, visant à prédire deux réponses à valeurs réelles. 
2. Exploration des Données : 
o Analyser les 8 caractéristiques (X1 à X8) et les 2 cibles (Y1 et Y2) :  
▪ X1 : Relative Compactness  
▪ X2 : Surface Area 
▪ X3 : Wall Area 
▪ X4 : Roof Area 
▪ X5 : Overall Height 
▪ X6 : Orientation 
▪ X7 : Glazing Area 
▪ X8 : Glazing Area Distribution 
▪ Y1 : Heating Load 
▪ Y2 : Cooling Load 
Les attributs ont tous une valeur réelle sauf X6 et X8 qui sont des entiers. 

3. Ressources 
Python, avec des bibliothèques Pandas, Scikit-learn, et Matplotlib pour 
l'analyse et la visualisation. 
