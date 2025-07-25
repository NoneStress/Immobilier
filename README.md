# 🏘️ Prédiction des prix d'appartements au Maroc

## 📌 Objectif
Développer un modèle de machine learning capable de prédire le prix d’un appartement à partir de ses caractéristiques (surface, nombre de chambres, ville, etc.).

## 📊 Méthodologie

1. Analyse exploratoire des données (EDA)
2. Nettoyage et traitement des valeurs manquantes
3. Encodage des variables catégorielles
4. Séparation en jeu d'entraînement et test
5. Mise à l'échelle des données
6. Entraînement de plusieurs modèles de régression :
   - Régression Linéaire
   - Random Forest
   - SVR
   - Gradient Boosting
7. Validation croisée
8. Optimisation d’hyperparamètres avec GridSearchCV
9. Évaluation via MSE, RMSE, MAE, R²
10. Sauvegarde du meilleur modèle (`model.pkl`)

## 📁 Structure du projet

```
.
├── data/
│   └── appartements-data-db.csv
├── notebooks/
│   └── jeuDonnee_commente.ipynb
├── models/
│   └── model.pkl
├── README.md
└── requirements.txt
```

## ⚙️ Exécution du projet

```bash
pip install -r requirements.txt
jupyter notebook notebooks/jeuDonnee_commente.ipynb
```

## 🧪 Auteurs
Nasser Yerbanga
