# Google Play Store Ratings Analysis

> EDA on the Google Play Store dataset examining what drives app ratings, installs, and category performance — with a focus on business-relevant insights for product and marketing teams.

---

## Overview

This project analyses the Google Play Store dataset to surface actionable insights about app performance across categories, pricing models, and content ratings. The analysis is structured around questions a product or growth team would actually ask — not just descriptive statistics.

## Key questions explored

- Which app categories have the highest average ratings?
- Does a paid vs free model affect user ratings?
- Is there a relationship between app size and install count?
- Which content ratings dominate installs?

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

## Project structure

```
google-play-eda-python/
├── data/
│   └── googleplaystore.csv        # Raw dataset
├── notebooks/
│   └── google_play_eda.ipynb      # Full analysis notebook
└── README.md
```

## Selected findings

- **Health & Fitness** and **Books & Reference** categories average the highest ratings, despite lower install volumes
- **Free apps** have marginally lower average ratings than paid equivalents — likely due to a higher volume of low-engagement users
- App size has a **non-linear relationship** with installs — mid-size apps (10–50MB) perform best
- **Everyone-rated** apps account for over 80% of total installs across the store

## How to run

```bash
git clone https://github.com/Sunil12Subu/google-play-eda-python
cd google-play-eda-python
pip install pandas matplotlib seaborn jupyter
jupyter notebook notebooks/google_play_eda.ipynb
```

---

*Part of a data analysis portfolio by [Sunil Subramaniam Sreedhar](https://linkedin.com/in/sunil-subramaniam-sreedhar) — Senior Data Analyst based in Dortmund, Germany.*
