# Projet COVID-19 - MLOps & Machine Learning

## Description
Ce projet vise à prédire l'infection au SARS-CoV-2 à partir de données cliniques (analyses sanguines et tests viraux) en utilisant plusieurs modèles de Machine Learning (Random Forest, AdaBoost, SVM, KNN) et en intégrant des pratiques MLOps avec MLflow pour le suivi des expériences.

## Dépôt GitHub
https://github.com/melyoussoufi279-source/corona-project

## Structure du Projet
```bash
corona-project/
│
├── data/                      # Contient le fichier de dataset daataset.xlsx.xlsx
│
├── notebooks/                  # Notebooks d'analyse exploratoire
│   └── Corona_virus (5).ipynb
│
├── src/                        # Code source
│   ├── preprocessing.py        # Prétraitement et préparation des données
│   └── train.py                # Entraînement et tracking MLflow
│
├── reports/                    # Rapport LaTeX et images générées
│
├── README.md                   # Documentation (ce fichier)
│
└── requirements.txt            # Dépendances Python

## Installation des dépendances Python
Pour installer toutes les dépendances nécessaires, exécutez :

bash
pip install -r requirements.txt


## Usage

# Pour exécuter le pipeline complet (chargement des données, préprocessing, entraînement, évaluation) :

python main.py


## Suivi MLflow

Pour visualiser les expériences et comparer les modèles :

mlflow ui


## Auteur


Projet réalisé par Mohamed Elyoussoufi

