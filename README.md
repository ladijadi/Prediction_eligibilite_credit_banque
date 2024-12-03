
# Prédiction d'Éligibilité pour un Crédit chez une Banque

## Description

Ce projet vise à prédire l'éligibilité des clients pour un crédit bancaire en utilisant des modèles de machine learning. Le modèle prédit si un client est éligible ou non pour un crédit en fonction de divers facteurs financiers et personnels.

### Objectifs

- Analyser des données financières et personnelles des clients.
- Développer un modèle de prédiction de l'éligibilité au crédit.
- Tester et évaluer plusieurs algorithmes de machine learning tels que KNN, Random Forest, SVM, etc.

## Technologies Utilisées

- Python
- Jupyter Notebook
- Scikit-learn
- Pandas
- Matplotlib
- Joblib (pour la sauvegarde des modèles)

## Installation

1. Clonez ce dépôt :
   ```
   git clone https://github.com/ladijadi/Prediction_eligibilite_credit_banque.git
   ```
   
2. Installez les dépendances :
   ```
   pip install -r requirements.txt
   ```

3. Chargez les données et exécutez le notebook `notebook.ipynb` pour analyser et entraîner le modèle.

## Modèles

- **KNN** : Utilisé pour la classification de l'éligibilité au crédit.
- **Random Forest** : Un autre modèle pour la prédiction basé sur des arbres de décision.
- **SVM** : Utilisé pour la séparation des classes en fonction des caractéristiques.

## Sauvegarde des Modèles

Les modèles entraînés sont sauvegardés sous le format `.joblib` pour une utilisation ultérieure, comme suit :
- `knn_model.joblib` : Modèle KNN
- `random_forest_model.joblib` : Modèle Random Forest

## Usage

1. Entraînez un modèle en utilisant les données disponibles.
2. Sauvegardez et chargez les modèles avec `joblib` pour une utilisation future.
3. Appliquez le modèle sur de nouvelles données pour prédire l'éligibilité au crédit.
