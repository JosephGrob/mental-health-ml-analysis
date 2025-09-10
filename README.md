# Mental Health & Machine Learning – Predictive Analysis

> **Cours** : Machine Learning (Lettres / UNIL)  
> **Auteur** : Joseph Grob  
> **Rendu 1** – Automne 2024

---

## Contexte du Projet

Ce projet explore l'utilisation de **modèles de machine learning** pour analyser des données liées à la **santé mentale**, telles que :
- les symptômes déclarés,
- les comportements numériques,
- ou les facteurs sociaux, démographiques et psychologiques.

L'objectif est d'entraîner des modèles prédictifs capables d’estimer un **état mental ou émotionnel** (par exemple : stress, anxiété, bien-être...) à partir d’un questionnaire ou de variables observées.

---

## Objectifs du Projet

- Appliquer un pipeline ML sur un jeu de données lié à la santé mentale
- Nettoyer, encoder et normaliser les données
- Comparer plusieurs modèles (SVM, Random Forest, KNN…)
- Évaluer les performances à l’aide de métriques classiques (accuracy, F1, recall…)
- Interpréter les résultats et visualiser les biais ou erreurs

---

## 📁 Contenu du projet

- `ml_mental_health_project.ipynb`  
  > Notebook principal contenant tout le code, les visualisations et les résultats

- Données (non incluses ici pour confidentialité ou poids)

---

## Modèles testés

- **Random Forest** – robuste et interprétable
- **K-Nearest Neighbors** – simple et visuel
- **Support Vector Machine (SVM)** – efficace sur petits datasets
- **Logistic Regression** – baseline rapide

📊 Les résultats ont été comparés avec une **validation croisée** et optimisés avec `GridSearchCV`.

---

## Librairies utilisées

- `pandas`, `numpy` – manipulation de données
- `matplotlib`, `seaborn` – visualisation
- `scikit-learn` – modèles ML, préprocessing, metrics
- `xgboost` *(si utilisé)*
- `tqdm` – barres de progression

---

## Reproductibilité

Pour exécuter le projet :


pip install -r requirements.txt

Lancer le notebook :

jupyter notebook ml_mental_health_project.ipynb

## Données

Les données utilisées ne sont pas incluses dans ce dépôt par souci de confidentialité ou poids.

Merci de consulter Moodle ou contacter l’auteur pour y accéder.

## Contact

📧 grob.j1890@gmail.com
