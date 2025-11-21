# Identification des utilisateurs de Copilote

**Projet MOD 7.2 -- Introduction à la Data Science**\
*École Centrale Lyon*

```{=html}
<p align="center">
```
`<img src="https://img.shields.io/badge/ML-Classification-blue?style=for-the-badge"/>`{=html}
`<img src="https://img.shields.io/badge/Python-3.10+-yellow?style=for-the-badge"/>`{=html}
`<img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge"/>`{=html}
`<img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge"/>`{=html}
```{=html}
</p>
```
## Table des matières

-   Contexte & Objectifs
-   Structure du repository
-   Méthodologie
-   Résultats
-   Installation & Exécution
-   Limites & Perspectives
-   Auteurs

## Contexte & Objectifs

Ce projet vise à développer un classifieur capable d'identifier les
utilisateurs du logiciel Copilote (Infologic) à partir de leurs séquences d'actions.

Rapport complet :
[Rapport_ECL\_\_\_Intro_Datascience.pdf](./Rapport_ECL_Datascience.pdf)

## Structure du repository

    📦 identification-utilisateurs-copilote
    ├── README.md
    ├── Rapport_ECL_Datascience.pdf
    ├── notebook.ipynb
    ├── requirements.txt
    ├── data/
    └── src/

## Méthodologie

-   Exploration des données
-   Prétraitement
-   Feature Engineering
-   Modélisation & optimisation (RandomForest, XGBoost, SVM, Logistic
    Regression)

## Résultats

  Modèle          Accuracy   F1 Micro   F1 Macro
  --------------- ---------- ---------- ----------
  Random Forest   0.7393     0.7393     0.6645
  XGBoost         0.6845     0.6845     0.6209

## Installation & Exécution

``` bash
pip install -r requirements.txt
jupyter notebook
```

## Limites & Perspectives

-   Sessions courtes
-   Déséquilibre des classes

## Auteurs

-   Anthonio Zavatara\
-   Elmehdi Marhfour\
-   Youssef Ismaini\
    Enseignant : Julien Velcin
