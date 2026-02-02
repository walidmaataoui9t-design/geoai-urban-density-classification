# Mini-projet 3 - Attribution des Modules IA

**Groupe 1 | 31 janvier 2026**

## Classification de zones urbaines selon leur densité

---

## Attributions Individuelles

### 1. **Er-rakho Khadija** → Régression Logistique
- Modèle baseline simple et rapide
- Implémenter, entraîner, évaluer
- Matrice de confusion + rapport de classification
- `sklearn.linear_model.LogisticRegression`

### 2. **Ibn Aissa Ferdaous** → Random Forest **MEILLEUR MODÈLE**

- Modèle principal recommandé
- Hyperparamètre tuning (n_estimators, max_depth)
- Visualiser importance des features
- `sklearn.ensemble.RandomForestClassifier`

### 3. **Walid El Maataoui** → SVM (Support Vector Machine)

- Tester différents kernels (linear, RBF, polynomial)
- Optimiser C et gamma
- Documenter temps de calcul
- `sklearn.svm.SVC`

### 4. **Issa Zouak** → KNN (K-Nearest Neighbors)

- Trouver k optimal (tester 3-15)
- Comparer métriques de distance
- Graphique accuracy vs k
- `sklearn.neighbors.KNeighborsClassifier`

### 5. **Mohammed Belfellah** → XGBoost (Gradient Boosting)

- Modèle avancé haute performance
- Tuning learning_rate, max_depth, n_estimators
- Comparer avec Random Forest
- `xgboost.XGBClassifier` (installer: `pip install xgboost`)

---

## Informations Essentielles

### Dataset

- **Variables :** `X_train`, `X_test`, `y_train`, `y_test` (déjà dans notebook, Cellule 25)
- **Features :** 7 caractéristiques standardisées
- **Classes :** 4 types (0=faible, 1=moyenne, 2=élevée, 3=zone_industrielle)
- **Taille :** ~70 train / ~18 test

### Livrables (pour chaque membre)

**Dans `projet1_geo_info.ipynb` :**

1. Nouvelle section avec votre nom
2. Code d'implémentation du modèle
3. Accuracy + Classification report + Matrice de confusion
4. Visualisation (heatmap confusion matrix obligatoire)
5. Interprétation brève (3-4 phrases)

**Standards :**

- `random_state=42` partout
- Sauvegarder figures dans `figures/`
- Commenter le code

---

## Calendrier

| Phase                       | Date Limite |
| --------------------------- | ----------- |
| Implémentation Individuelle | 3 février   |
| Tests & Débogage            | 4 février   |
| Intégration Groupe          | 5 février   |
| Rapport Final               | 6 février   |

> **Note :** Ce calendrier est pour notre organisation interne. On peut accélérer et ajuster les dates selon notre progression. Discutons ensemble si besoin de modifier.

