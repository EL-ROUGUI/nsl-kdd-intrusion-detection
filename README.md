# 🔍 Détection d'intrusions réseau avec Machine Learning (NSL-KDD)

Projet d'analyse de données réseau à l'aide de 4 modèles de classification supervisée pour détecter des attaques potentielles sur le dataset NSL-KDD.

## 🎯 Objectif

Classer les connexions réseau comme normales ou malveillantes (attaque) en utilisant différents modèles de Machine Learning.  
Ce projet simule une approche d’un IDS (Intrusion Detection System) basé sur l'IA.

## 📂 Dataset utilisé

- **NSL-KDD** : version nettoyée et équilibrée du KDD Cup 1999
- Variables pré-traitées, encodées et normalisées
- Target : `normal` vs `attack`

## 🔧 Modèles testés

| Modèle              | Bibliothèque     |
|---------------------|------------------|
| Régression Logistique | Scikit-learn     |
| Support Vector Machine (SVM) | Scikit-learn     |
| Random Forest       | Scikit-learn     |
| XGBoost             | XGBoost          |

## 📊 Métriques d’évaluation

- Accuracy  
- Precision, Recall, F1-score  
- Courbe ROC & AUC  
- Matrice de confusion

## 📈 Résultats (extrait)

| Modèle        | Précision | Rappel | F1-score | AUC     |
|---------------|-----------|--------|----------|---------|
| XGBoost       | 0.91      | 0.87   | 0.89     | 0.94    |
| Random Forest | 0.89      | 0.86   | 0.87     | 0.92    |
| SVM           | 0.85      | 0.80   | 0.82     | 0.89    |
| Log. Reg.     | 0.76      | 0.73   | 0.74     | 0.83    |

> 📌 XGBoost a offert la meilleure performance globale sur ce dataset.

## 📌 Tech stack

- Python
- Scikit-learn
- Pandas / NumPy / Matplotlib / Seaborn
- XGBoost
- Jupyter Notebook

## 📁 Contenu du projet

- `notebook_ids.ipynb` : code complet du projet, de l'import au benchmark
- `data/` : jeux de données (non inclus, à télécharger)
- `README.md` : documentation du projet

## 🧠 Compétences développées

- Prétraitement de données réseau
- Benchmark de modèles supervisés
- Évaluation multi-métrique
- Visualisation d’indicateurs
- Présentation de résultats

---

