# ML su Open Data del Comune di Bari – Incidenti stradali 2023

Repository a supporto della tesi: sperimentazione esplorativa sull’uso di tecniche di Machine Learning applicate a un dataset open data comunale (incidenti stradali – Comune di Bari, 2023).

## Obiettivi
- Classificazione: predire la presenza di lesioni (binary classification) a partire da variabili descrittive.
- Analisi spaziale: identificare hotspot tramite clustering geografico (DBSCAN) e descrivere i cluster per gravità.

## Dataset
Il dataset è pubblicato come Open Data dal Comune di Bari:
- Fonte: (https://opendata.comune.bari.it/dataset/6738d454-744f-456a-a1d8-858d0adeb177/resource/eeca93bd-96b4-4da6-bdf7-0531f6c8cfa8/download/elenco-incidenti-periodo-2023.csv)
- Anno: 2023
- Note: il dataset non viene versionato nel repo (si scarica via URL per riproducibilità).

## Metodo (in sintesi)
1. Preprocessing: pulizia, selezione variabili, gestione missing, encoding.
2. Classificazione: Logistic Regression e MLPClassifier (train/test split).
3. Valutazione: accuracy, precision, recall, F1-score.
4. Analisi spaziale: DBSCAN + profilazione cluster (lesioni/no-lesioni).
