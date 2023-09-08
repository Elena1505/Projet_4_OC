# Projet 4: Anticipez les besoin en consommation des bâtiments 
## Présentation:
Je travaille pour la ville de Seattle. Pour atteindre son objectif de ville neutre en émissions de carbone en 2050, 
mon équipe s’intéresse de près à la consommation et aux émissions des bâtiments non destinés à l’habitation.

## Mission:
Des relevés minutieux ont été effectués par les agents de la ville en 2016. 
Cependant, ces relevés sont coûteux à obtenir, et à partir de ceux déjà réalisés, je veux tenter de prédire 
les émissions de CO2 et la consommation totale d’énergie de bâtiments non destinés à l’habitation pour lesquels elles 
n’ont pas encore été mesurées.
Je cherche également à évaluer l’intérêt de l’"ENERGY STAR Score" pour la prédiction d’émissions, qui est fastidieux 
à calculer avec l’approche utilisée actuellement par mon équipe. Je l'intègrerais dans la modélisation et jugerais de 
son intérêt.

Je sors tout juste d’une réunion de brief avec mon équipe. Voici un récapitulatif de ma mission :

- Réaliser une courte analyse exploratoire.
- Tester différents modèles de prédiction afin de répondre au mieux à la problématique.

## Données:
Voici les données : https://s3.eu-west-1.amazonaws.com/course.oc-static.com/projects/Data_Scientist_P4/2016_Building_Energy_Benchmarking.csv

Et leur source : https://data.seattle.gov/dataset/2016-Building-Energy-Benchmarking/2bpz-gwpy
## Construction:
Dans ce dépôt, vous trouverez plusieurs fichiers:

- "exploration.ipynb" : notebook  comportant les analyses pré-exploratoires réalisées.
- "prediction_emission_CO2.ipynb" : notebook comportant la prediction des emissions de CO2.
- "prediction_consommation_d'energie.ipynb" : notebook comportant la prediction de consommation totale d'energie. 

## Packages:
Différents packages Python ont été utilisés:

- pandas 1.4.4
- numpy 1.23.5
- seaborn 0.11.2
- matplotlib 3.5.2
- shap 0.41.0
- scikit-learn 1.0.2
- scipy 1.9.1


## Compétences:
- Mettre en place le modèle d'apprentissage supervisé adapté au problème métier
- Adapter les hyperparamètres d'un algorithme d'apprentissage supervisé afin de l'améliorer
- Transformer les variables pertinentes d'un modèle d'apprentissage supervisé
- Évaluer les performances d’un modèle d'apprentissage supervisé
