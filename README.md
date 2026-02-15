# Projet COVID-19 - MLOps & Machine Learning

## Description
Ce projet vise à prédire l'infection au SARS-CoV-2 à partir de données cliniques (analyses sanguines et tests viraux) en utilisant plusieurs modèles de Machine Learning (**Random Forest, AdaBoost, SVM, KNN**) et en intégrant des pratiques MLOps avec **MLflow** pour le suivi des expériences.

**Dépôt GitHub** : [https://github.com/melyoussoufi279-source/corona-project](https://github.com/melyoussoufi279-source/corona-project)

## Structure du Projet

## Structure du Projet
```
corona-project/
├── data/
│   └── daataset.xlsx.xlsx
├── src/
│   ├── preprocessing.py
│   └── train.py
├── notebooks/
│   └── Corona_virus (5).ipynb
├── reports/
├
├── requirements.txt
└── README.md
```


## Installation
1.  Cloner ce dépôt.
2.  Installer les dépendances :
    ```bash
    pip install -r requirements.txt
    ```

## Usage
Pour exécuter le pipeline complet (chargement des données, préprocessing, entraînement, évaluation) :
bash
python main.py

## Suivi MLflow 
# Pour visualiser les expériences et comparer les modèles :
mlflow ui
## Auteur
Projet réalisé par Mohamed Elyoussoufi.

