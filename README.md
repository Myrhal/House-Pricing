# 🏠 Prédiction des prix immobiliers – Kaggle Challenge

Projet de machine learning basé sur le jeu de données **House Prices: Advanced Regression Techniques** (Kaggle).  
Objectif : prédire le **prix de vente des maisons** à partir de leurs caractéristiques.

---

## 📊 Objectifs du projet

- Explorer et comprendre les variables influençant le prix de vente (`SalePrice`)
- Nettoyer et préparer les données (valeurs manquantes, encodage, normalisation)
- Construire une **baseline** avec une régression linéaire
- Entraîner un modèle **Random Forest** pour capturer les relations non linéaires
- Optimiser le modèle via **Pipeline + GridSearchCV + Cross-validation**
- Évaluer les performances avec le **RMSE**

---

## 🧠 Approche méthodologique

1. **Exploration des données (EDA)**
   - Analyse des distributions, outliers, et corrélations principales.
   - Visualisation des variables explicatives les plus importantes.

2. **Nettoyage et préparation**
   - Gestion des valeurs manquantes (médiane, mode, valeurs fictives).
   - Encodage des variables catégorielles.
   - Mise à l’échelle des variables numériques si nécessaire.

3. **Modélisation**
   - Régression linéaire comme modèle de référence (baseline).
   - Random Forest pour améliorer la performance.

4. **Optimisation**
   - Utilisation d’un **pipeline Scikit-learn complet**.
   - Recherche d’hyperparamètres par **GridSearchCV** avec validation croisée.

---

## 📈 Résultats

| Modèle               | RMSE (validation) |
|----------------------|------------------:|
| Régression linéaire  | 29 674.95         |
| Random Forest        | 29 305.19         |

➡️ Le Random Forest offre un **léger gain de performance**.

---

## 🛠️ Outils et librairies

- **Langage :** Python  
- **Librairies principales :** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- **Environnement :** Jupyter Notebook

