# Prédiction du risque de maladie cardiaque

Ce projet fait partie de mon mémoire de Master en Big Data Analytics (UVCI).
Il utilise des données de santé américaines (BRFSS) pour prédire si une personne
a une maladie cardiaque, à partir de son âge, de son sexe, de son état de santé
et de ses habitudes de vie (tabac, alcool, alimentation, activité physique).

## Ce que fait le code
- Nettoie les données et les sépare en deux parties : 80 % pour apprendre, 20 % pour tester.
- Analyse les données et supprime les variables redondantes (poids et taille).
- Compare quatre modèles : régression logistique, arbre de décision,
  HistGradientBoosting et EBM (Explainable Boosting Machine).
- Mesure leurs performances sur le jeu de test, puis par sexe et par tranche d'âge.
- Explique quelles variables pèsent le plus dans la prédiction.
- Enregistre les graphiques (PNG) et les tableaux (Excel) dans le dossier `outputs/`.

## Utilisation
1. Mettre le fichier `CVD_cleaned.csv` dans le dossier du projet.
2. Installer les bibliothèques : `pip install -r requirements.txt`
3. Ouvrir le notebook et exécuter toutes les cellules.

## Auteur
Nana Pacôme Bienvenu – UVCI, 2026
