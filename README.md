TP MLOps — Pipeline ML avec MLflow
🔗 Autre projet : TP CI/CD Docker + GitHub Actions

Description
Pipeline Machine Learning (dataset Iris) avec :

Tracking d'expériences avec MLflow (paramètres, métriques, modèles)
Comparaison d'expériences (n_estimators = 50 / 100 / 200)
Prédictions avec modèle sauvegardé (joblib)
Analyse Data Drift
Versionnement Git
Résultats
n_estimators	Accuracy
50	0.90
100	0.90
200	0.90
Sur ce dataset, augmenter n_estimators n'améliore pas l'accuracy : plus d'arbres = plus de calcul sans gain ici.
