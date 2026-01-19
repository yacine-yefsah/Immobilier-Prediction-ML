# 🏠 Analyse Statistique et Prédiction Immobilière - Boston Housing

## 📌 Présentation du Projet
Ce projet a été réalisé dans le cadre de mon **Master 1 Statistique Appliquée et Analyse Décisionnelle (SAAD)** à l'Université de Caen Normandie. L'objectif est double :
1. Explorer les variables socio-économiques et structurelles qui influencent le prix de l'immobilier.
2. Développer un modèle de Machine Learning (Régression Linéaire) capable de prédire la valeur médiane des logements.

## 🛠️ Stack Technique & Outils
* **Environnement :** Google Colab / Jupyter Notebook
* **Langage :** Python 3.x
* **Librairies clés :**
    * `Pandas` & `Numpy` : Manipulation et nettoyage des données.
    * `Matplotlib` & `Seaborn` : Visualisations avancées (Heatmaps, Scatter plots, Boxplots).
    * `Scikit-Learn` : Prétraitement, split Train/Test et modélisation.

## 📈 Méthodologie Statistique
Le projet suit une rigueur analytique complète :
* **Exploration (EDA) :** Analyse de la distribution du prix et étude des corrélations. 
* **Gestion des Outliers :** Utilisation de la méthode de l'Écart Interquartile (IQR) pour identifier et traiter les valeurs aberrantes.
* **Modélisation :** Mise en œuvre d'une Régression Linéaire multiple.
* **Évaluation :** Comparaison des performances avant et après nettoyage via les métriques $R^2$ et $RMSE$.

## 🎯 Résultats et Impact
Le nettoyage des données a permis une amélioration significative de la précision du modèle :
* **Avant nettoyage :** $R^2$ = 0.6688 | $RMSE$ = 4.92
* **Après suppression des outliers :** **$R^2$ = 0.7525** | **$RMSE$ = 3.15**
* **Conclusion :** Le nombre de pièces (`rm`) est le prédicteur le plus fort du prix, tandis que le taux de pauvreté (`lstat`) et l'éloignement des centres d'emploi (`dis`) ont un impact négatif.

---
*Projet réalisé par Yacine YEFSAH - Étudiant en M1 SAAD, Université de Caen Normandie.*
