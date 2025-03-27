# Supervision_MINDS_
Algorithme de Détection  menace MINDS utilisant LOF

Algorithme MINDS - Détection d'Anomalies Réseau

Description

Ce projet implémente un algorithme de détection d'anomalies basé sur MINDS, utilisant une approche statistique du trafic réseau normal (CAMNEP) complétée par Local Outlier Factor (LOF).

Dépendances

Installez les bibliothèques suivantes avec pip :

pip install numpy pandas matplotlib seaborn scikit-learn

Alternativement, vous pouvez utiliser Google Colab ou Anaconda Jupyter Notebook qui contiennent ces dépendances préinstallées.

Fichiers de données nécessaires

Placez dans le dossier du projet :

Le dataset de test nommé obligatoirement dataset.csv

Le dataset d'entraînement nommé obligatoirement train_10.txt

Adaptez ces noms en fonction des datasets d'entraînement que vous utilisez.

Fonctions implémentées

run_camnep_train_detection : Entraîne le modèle sur les données normales.

run_camnep_test_detection : Détecte les anomalies en calculant un score statistique.

run_camnep_test_detection_lof : Variante utilisant LOF pour l'analyse locale des anomalies.

plot_conf_matrices_camnep_with_metrics_and_counts : Évalue et visualise les résultats avec des matrices de confusion.

Ce README fournit une vue d'ensemble rapide et pratique pour exécuter l'algorithme sur vos données.


