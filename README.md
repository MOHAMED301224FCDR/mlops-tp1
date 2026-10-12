# TP MLOps — Pipeline ML avec MLflow

Autre projet : [TP CI/CD Docker + GitHub Actions](https://github.com/MOHAMED301224FCDR/tp1)
Autre projet : [TP MLOps — MLflow](https://github.com/MOHAMED301224FCDR/mlops-tp1)
## Description

- Tracking d'experiences avec **MLflow** (parametres, metriques, modeles)
- Comparaison d'experiences (n_estimators = 50 / 100 / 200)
- Predictions avec modele sauvegarde (joblib)
- Analyse **Data Drift**
- Versionnement **Git**

## Resultats

| n_estimators | Accuracy |
|--------------|----------|
| 50           | 0.90     |
| 100          | 0.90     |
| 200          | 0.90     |

Sur ce dataset, augmenter n_estimators n'ameliore pas l'accuracy : plus d'arbres = plus de calcul sans gain ici.
