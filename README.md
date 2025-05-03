# Analyse prédictive des valeurs foncières en France (2017–2023)

Ce projet explore l’évolution du prix immobilier en France à partir des données publiques DVF sur les transactions de 2017 à 2023. Il comprend des étapes de nettoyage, d’analyse visuelle et de modélisation avancée (régression linéaire, Random Forest, XGBoost...).

## Objectif
Estimer le prix au m² à partir des caractéristiques des biens vendus, en analysant les facteurs géographiques, temporels et structurels.

## Contenu du dépôt

- `real_estate_modeling_france_2017_2023.ipynb` : Notebook complet du projet.
- `carte_france_interactive.html` : Carte choroplèthe interactive des prix au m² par département.
- `README.md` : Présentation synthétique du projet.

## Données
Les données utilisées proviennent du jeu suivant sur Kaggle :  
➡️ [French Real Estate Dataset (2017–2023)](https://www.kaggle.com/datasets/nechbamohammed/real-estate-dataset)

## Résultats
- Hausse du prix au m² entre 2017 et 2023.
- Hétérogénéité spatiale importante entre départements.
- XGBoost est le modèle le plus performant sur notre jeu de test.

## Auteurs
Projet personnel réalisé en parallèle d’un stage dans le domaine du logement social.

---

