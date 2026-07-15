# Projet MTI820

Projet de session MTI820.

## Structure

```
projet-mti820/
├── data/           Données brutes et traitées
├── notebooks/       Notebooks Jupyter d'analyse
│   ├── 01_EDA.ipynb
│   ├── 02_preprocessing.ipynb
│   ├── 03_regex.ipynb
│   └── 04_naive_bayes.ipynb
├── src/            Code source réutilisable
└── README.md
```

## Installation

```bash
pip install pandas numpy scikit-learn spacy spacy-lookups-data matplotlib seaborn wordcloud jupyter
python -m spacy download en_core_web_sm
```

## Données

Dataset : [Drug Review Dataset (Drugs.com)](https://archive.ics.uci.edu/dataset/461/drug+review+dataset+drugs+com)

Les fichiers `drugsComTrain_raw.csv` et `drugsComTest_raw.csv` (~107 Mo) ne sont pas versionnés dans le dépôt
(trop volumineux pour git). Télécharger le dataset depuis le lien ci-dessus et placer les deux fichiers CSV
dans `data/` avant d'exécuter les notebooks.
