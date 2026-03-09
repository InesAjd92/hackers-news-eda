# 🔍 Hacker News — Exploratory Data Analysis

<div align="center">

![Python](https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=00f5ff)
![Pandas](https://img.shields.io/badge/Pandas-0d1117?style=for-the-badge&logo=pandas&logoColor=00f5ff)
![Seaborn](https://img.shields.io/badge/Seaborn-0d1117?style=for-the-badge&logo=python&logoColor=00f5ff)
![Matplotlib](https://img.shields.io/badge/Matplotlib-0d1117?style=for-the-badge&logo=python&logoColor=00f5ff)
![Jupyter](https://img.shields.io/badge/Jupyter-0d1117?style=for-the-badge&logo=jupyter&logoColor=F37626)

![Status](https://img.shields.io/badge/Status-Completed-00ff88?style=for-the-badge)
![Language](https://img.shields.io/badge/Language-EN-00f5ff?style=for-the-badge)

</div>

---

## 📋 Table of Contents · Sommaire

- [🇬🇧 English](#-english)
- [🇫🇷 Français](#-français)

---

## 🇬🇧 English

### Context

[Hacker News](https://news.ycombinator.com/) is a social news platform run by Y Combinator, focused on technology and entrepreneurship. This dataset covers stories posted between 2015 and 2016 (~20,000 posts), including author, timestamp, points, and number of comments.

📦 **Dataset source:** [Hacker News on Kaggle](https://www.kaggle.com/datasets/hacker-news/hacker-news)

---

### ❓ Research Questions

This EDA investigates what drives engagement on Hacker News:

1. How are **points and comments** distributed across posts?
2. Is there a **correlation** between points and comments?
3. Are there **influential authors** who consistently produce viral content?
4. Which **keywords and topics** appear most in viral post titles?
5. How has **post volume evolved** over time, and what drives activity peaks?

---

### 💡 Key Findings

```
┌─────────────────────────────────────────────────────────────────┐
│  📊 INSIGHTS SUMMARY                                            │
├─────────────────────────────────────────────────────────────────┤
│  • Power law distribution — most posts get < 10 points         │
│  • Strong correlation (r ≈ 0.78) between points & comments     │
│  • Only 6.9% of posts qualify as "viral" (95th percentile)     │
│  • Top authors (e.g. ingve, 24 viral posts) drive engagement   │
│  • Viral titles feature: Google, Apple, open, code, learning   │
│  • Activity peaks align with major security & tech events      │
└─────────────────────────────────────────────────────────────────┘
```

---

### 🗂️ Project Structure

```
hacker-news-eda/
│
├── hackers_news_exploration_v2.ipynb   # Main analysis notebook
├── hacker_news.csv                     # Dataset (download from Kaggle)
└── README.md                           # This file
```

---

### 🚀 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/InesAjd92/hacker-news-eda.git
cd hacker-news-eda
```

**2. Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

**3. Download the dataset**

Download `hacker_news.csv` from [Kaggle](https://www.kaggle.com/datasets/hacker-news/hacker-news) and place it in the project folder.

**4. Launch the notebook**
```bash
jupyter notebook hackers_news_exploration_v2.ipynb
```

---

### 🛠️ Tech Stack

| Tool | Usage |
|------|-------|
| `pandas` | Data loading, cleaning, manipulation |
| `numpy` | Numerical operations |
| `matplotlib` | Base visualisations |
| `seaborn` | Statistical plots & styling |
| `collections.Counter` | Efficient word frequency counting |
| `re` | Regex-based text extraction |

---

## 🇫🇷 Français

### Contexte

[Hacker News](https://news.ycombinator.com/) est une plateforme de news sociale gérée par Y Combinator, axée sur la tech et l'entrepreneuriat. Ce dataset couvre les posts publiés entre 2015 et 2016 (~20 000 posts), avec auteur, horodatage, points et nombre de commentaires.

📦 **Source du dataset :** [Hacker News sur Kaggle](https://www.kaggle.com/datasets/hacker-news/hacker-news)

---

### ❓ Questions de recherche

Cette EDA explore les facteurs d'engagement sur Hacker News :

1. Comment se distribuent **points et commentaires** sur les posts ?
2. Existe-t-il une **corrélation** entre points et commentaires ?
3. Y a-t-il des **auteurs influents** qui produisent régulièrement du contenu viral ?
4. Quels **mots-clés et thèmes** reviennent dans les titres des posts viraux ?
5. Comment le **volume de posts a-t-il évolué** dans le temps, et qu'est-ce qui déclenche les pics ?

---

### 💡 Résultats clés

```
┌─────────────────────────────────────────────────────────────────┐
│  📊 SYNTHÈSE DES INSIGHTS                                       │
├─────────────────────────────────────────────────────────────────┤
│  • Distribution en loi de puissance — la plupart des posts     │
│    reçoivent moins de 10 points                                 │
│  • Forte corrélation (r ≈ 0.78) entre points et commentaires   │
│  • Seulement 6.9% des posts sont "viraux" (95e percentile)     │
│  • Quelques auteurs concentrent l'essentiel du contenu viral   │
│  • Titres viraux dominés par : Google, Apple, open, code...    │
│  • Les pics d'activité coïncident avec des événements tech     │
└─────────────────────────────────────────────────────────────────┘
```

---

### 🗂️ Structure du projet

```
hacker-news-eda/
│
├── hackers_news_exploration_v2.ipynb   # Notebook d'analyse principal
├── hacker_news.csv                     # Dataset (à télécharger sur Kaggle)
└── README.md                           # Ce fichier
```

---

### 🚀 Comment lancer le projet

**1. Cloner le repo**
```bash
git clone https://github.com/InesAjd92/hacker-news-eda.git
cd hacker-news-eda
```

**2. Installer les dépendances**
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

**3. Télécharger le dataset**

Télécharger `hacker_news.csv` depuis [Kaggle](https://www.kaggle.com/datasets/hacker-news/hacker-news) et le placer dans le dossier du projet.

**4. Lancer le notebook**
```bash
jupyter notebook hackers_news_exploration_v2.ipynb
```

---

### 🛠️ Stack technique

| Outil | Usage |
|-------|-------|
| `pandas` | Chargement, nettoyage, manipulation des données |
| `numpy` | Opérations numériques |
| `matplotlib` | Visualisations de base |
| `seaborn` | Graphiques statistiques & style |
| `collections.Counter` | Comptage de fréquences de mots |
| `re` | Extraction de texte par regex |

---

<div align="center">

---

*Projet réalisé par [Ines Amdjahed](https://github.com/InesAjd92) · Data Analyst Junior · Paris 🇫🇷*

[![Portfolio](https://img.shields.io/badge/Portfolio-0d1117?style=for-the-badge&logo=firefox&logoColor=00f5ff)](https://inesamdjahed.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=00f5ff)](https://linkedin.com/in/ines-amdjahed)

</div>
