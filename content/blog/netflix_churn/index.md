---
title: 📊 Analyse du churn Netflix avec Jupyter Notebook
summary: Présentation d’une analyse de churn Netflix réalisée dans un notebook Jupyter, intégrée directement dans un article de blog.
date: 2026-03-17
authors:
  - Mahomet limenia KEITA
tags:
  - Jupyter
  - Data Science
  - Churn Analysis
  - Netflix
cover:
  icon:
    name: "📔"
image:
  caption: "Analyse réalisée à partir d’un notebook Jupyter intégré dans le site"
  focal_point: Center
  placement: 1
content_meta:
  trending: true
---

Dans ce projet, j’ai réalisé une analyse du churn sur un jeu de données Netflix directement dans un notebook Jupyter.  
Au lieu de faire des captures d’écran ou de copier-coller le code et les graphiques, ce billet permet d’intégrer directement le notebook dans la page, tout en conservant une présentation claire et professionnelle.

Cette approche permet de partager dans un même espace :
- le contexte analytique,
- le code Python,
- les visualisations,
- et les résultats de modélisation.

{{< toc mobile_only=true is_open=true >}}

## Pourquoi publier ce notebook ?

> [!TIP]
> **Analyse reproductible** : En publiant le notebook original, il devient plus simple de relire l’analyse, de reproduire les résultats et d’améliorer le travail par la suite.

Cette analyse sur le churn Netflix permet notamment de montrer :

- **L’exploration du jeu de données** – aperçu des premières lignes, types des colonnes, statistiques descriptives et dimensions du dataset.
- **L’analyse descriptive** – étude des variables numériques et catégorielles liées au churn.
- **La visualisation des comportements utilisateurs** – répartition par abonnement, appareil principal, genre favori, mode de paiement et autres variables importantes.
- **La modélisation prédictive** – utilisation d’un modèle de régression logistique pour prédire le churn.
- **L’évaluation du modèle** – génération d’un rapport de classification pour mesurer la performance.

## Aperçu de l’analyse réalisée

Le notebook contient plusieurs étapes clés :

1. **Importation des bibliothèques Python**  
   Utilisation de `pandas`, `numpy`, `matplotlib`, `seaborn` et des outils de `scikit-learn`.

2. **Chargement du jeu de données Netflix**  
   Lecture du fichier contenant les comportements utilisateurs.

3. **Analyse descriptive du dataset**  
   Vérification des types de variables, statistiques descriptives et taille de la base.

4. **Préparation des variables**  
   Conversion des colonnes catégorielles et numériques dans le bon format.

5. **Visualisations exploratoires**  
   Histogrammes des variables quantitatives et diagrammes des variables qualitatives selon le churn.

6. **Modélisation du churn**  
   Entraînement d’un modèle de régression logistique avec standardisation.

7. **Évaluation**  
   Analyse du `classification_report` pour interpréter les résultats.

## Notebook intégré

Ci-dessous, le notebook complet est intégré directement dans cette page :

{{< notebook
    src="Netflix_churn_analytics.ipynb"
    title="Analyse du churn Netflix"
    show_metadata=true
    line_numbers=true
    dense=false
    download_label="Télécharger le notebook"
    show_outputs=true
>}}

## Ce que montre ce projet

Cette analyse met en évidence une démarche classique de data science appliquée à un problème métier concret : la prédiction du churn client.

Elle permet de :
- comprendre les variables qui décrivent le comportement des utilisateurs,
- observer les différences entre clients churners et non churners,
- construire un premier modèle prédictif,
- et poser les bases d’une analyse plus avancée.
