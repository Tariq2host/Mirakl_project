## Multi Class image classification of e-commerce products


# Guide

Touts mes élèments de réponse sont détaillés dans les quatres notebooks:


- `eda.ipynb` : Notebook pour l'analyse exploratoire des données (Exploratory Data Analysis - EDA).
- `pre-processing.ipynb` : Notebook pour les étapes de prétraitement des données.
- `training.ipynb` : Notebook pour l'entraînement des modèles.
- `test_evaluation.ipynb` : Notebook pour l'évaluation des modèles sur les jeux de données de test.


# Méthodologie et synthèse de travail

Le schéma ci-dessous présente une synthèse des résultats obtenus. Nous avons réussi à entraîner un modèle de classification avec une précision (accuracy) de 43 % et un F1-score de 37 %, ce qui représente des valeurs faibles, mais qui peuvent être améliorées en entraînant le meme modèle avec les meme paramètres sur 50 époques, par exemple. Ma contrainte était les ressources de calcul pour l'entraîner sur 50 époques, ce qui est chronophage avec mon CPU.
<img src="img\Synthèse.png" />

# Activer l'environnement

```bash
python -m venv .venv
\.venv\Scripts\activate # sur windows
```

```bash
source .venv/bin/activate  # Sur Linux/MacOS
```

# Installation des librairies

```bash
pip install -r requirements.txt
```

# Structure du projet

## Détails des dossiers et fichiers

- `all_images/` : Dossier contenant toutes les images utilisées ou générées par le projet.
- `data/` : Dossier où les jeux de données bruts ou transformés sont stockés.
- `models/` : Dossier pour enregistrer les modèles entraînés.
- `eda.ipynb` : Notebook pour l'analyse exploratoire des données (Exploratory Data Analysis - EDA).
- `pre-processing.ipynb` : Notebook pour les étapes de prétraitement des données.
- `README.md` : Fichier de documentation du projet, comprenant sa structure, son utilisation, etc.
- `requirements.txt` : Liste des dépendances Python nécessaires à l'exécution du projet.
- `test_evaluation.ipynb` : Notebook pour l'évaluation des modèles sur les jeux de données de test.
- `training.ipynb` : Notebook pour l'entraînement des modèles.


# Author

Tariq CHELLALI

# Licence 

MIT
