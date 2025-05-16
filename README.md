# 🌦️ Analyse Climatique des Données Météo Françaises

Ce projet a pour but d'explorer, visualiser et analyser l'évolution de plusieurs indicateurs climatiques en France à travers les décennies. Il s'appuie sur des données météorologiques historiques classées par **domaine climatique** (température, précipitations, vent, etc.) et permet une visualisation interactive des tendances par département.

## 📊 Objectifs

- Visualiser l'évolution de variables climatiques par département.
- Étudier les tendances à long terme (1950–2023).
- Détecter les extrêmes climatiques (records historiques).
- Adapter les analyses par grandes catégories (température, précipitations, vent, etc.).
- Identifier les limites d’analyse pour les variables comportant trop de valeurs manquantes (ex: neige, brouillard, gelées).

## 🧪 Données

Les données utilisées incluent les variables suivantes :

### 🌡️ Température
- `TM` : Température moyenne
- `TX`, `TN` : Températures max / min
- `TXAB`, `TNAB` : Anomalies de température
- `NBJTX30`, `NBJTX35` : Nombre de jours ≥30°C, ≥35°C
- `NBJTX0`, `NBJTN5` : Nombre de jours avec gel

### 🌧️ Précipitations
- `RR` : Précipitations totales
- `RRAB` : Anomalie précipitations
- `NBJRR10`, `NBJRR30`, `NBJRR50`, `NBJRR100` : Nombre de jours avec pluie ≥ seuils (10 à 100 mm)

### 💨 Vent
- `FFM` : Force moyenne du vent
- `FXIAB` : Rafales extrêmes
- `NBJFF10`, `NBJFF16`, `NBJFF28` : Jours avec vent fort

### ☀️ Ensoleillement
- `INST`, `GLOT`, `DIFT`, `DIRT` : Différents indicateurs d’ensoleillement

### 🧊 Phénomènes (non analysés à cause de données manquantes)
- `HNEIGEFTOT`, `NBJNEIG`, `NBJGREL`, `NBJBROU`, `NBJORAG`

### 📈 Pression et Humidité
- `PMERM` : Pression au niveau de la mer
- `UMM` : Humidité moyenne

## 🛠️ Fonctionnalités

- Interface interactive avec `ipywidgets`
- Visualisation avec `Plotly`
- Filtres par département, période, variable
- Option pour afficher les extrêmes historiques

## 📷 Exemple de visualisation

![Exemple](images/746adb49-51e3-4198-8fa5-acd7c51a426d.png)

## 🚀 Lancer le notebook

1. Ouvrir le fichier `new_last_script.ipynb` dans Jupyter Notebook ou JupyterLab.
2. Exécuter les cellules pour afficher les visualisations interactives.

## 📝 Remarques

- Certaines variables n’ont pas été exploitées à cause de leur **taux élevé de valeurs manquantes**.
- Le projet est structuré par **domaine climatique**, ce qui facilite les analyses ciblées.

## 📚 À venir

- Déploiement sur GitHub Pages ou Binder
- Nettoyage automatique des valeurs manquantes
- Export des graphes pour rapports PDF

---

## 👤 Auteur

Projet réalisé par [Cheikh SARR - Oumar Kaba - Gilles Agbo - Ben Iman]  
Contact : cheikh.sarr@etu.univ-poitiers.fr



