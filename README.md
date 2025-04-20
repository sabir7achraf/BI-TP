# TP Business Intelligence & Data Mining

**Institution :** Université Abdelmalek Essaadi - Faculté des Sciences et Techniques (FST) Tanger
**Département :** Génie Informatique
**Réalisé par :** SABIR ACHRAF
**Supervisé par :** P. Abdelhadi FENNAN

## Description

Ce document résume les travaux pratiques (TP) réalisés dans le cadre du module de Business Intelligence & Data Mining. Il couvre diverses techniques et outils allant de la création de bases de données décisionnelles à l'application d'algorithmes de Machine Learning pour la classification, le clustering, et la découverte de règles d'association, en utilisant SQL Server, WEKA, Java et Python.

## Structure des Expériences

Le TP est divisé en plusieurs expériences :

1.  **Expérience 1 : Création de Base de Données (SQL Server)**
    * Utilisation de SQL Server pour créer les bases de données `HireBase` et `TopHireDW`. [source: 2]
    * Création et peuplement des tables de dimensions (`DimCustomer`, `DimDate`, `DimVan`) et de faits (`FactHire`). [source: 4, 5, 6, 7]

2.  **Expérience 2 : Exploration de l'outil WEKA**
    * Installation et présentation de l'environnement WEKA (Waikato Environment for Knowledge Analysis). [source: 8, 9, 10, 11]
    * Exploration des différentes interfaces : Explorer, Experimenter, KnowledgeFlow, Workbench, Simple CLI. [source: 12, 13, 14, 15, 16]
    * Chargement de datasets au format ARFF (ex: `iris.arff`, `weather.nominal.arff`). [source: 21]
    * Visualisation des données et des attributs. [source: 22, 23, 25, 26, 27, 28]
    * Génération de données synthétiques. [source: 24]

3.  **Expérience 3 : Tâches de Prétraitement (Preprocessing) avec WEKA**
    * Application de filtres sur les datasets (ex: `labor`, `weather`, `iris`), notamment des filtres de discrétisation non supervisée. [source: 29]
    * Utilisation de `FilteredAssociator` pour la recherche de règles d'association (Apriori mentionné mais non directement utilisé). [source: 30, 31]

4.  **Expérience 4 : Classification avec WEKA**
    * Application d'algorithmes de classification sur le dataset `iris`.
    * Test des algorithmes : J48 (arbre de décision) [source: 31], Naive Bayes [source: 33], et MultiClassClassifier (en remplacement de K-Nearest Neighbors). [source: 33]
    * Visualisation des résultats de classification. [source: 32, 34, 35]

5.  **Expérience 5 : Clustering avec WEKA**
    * Application de l'algorithme K-Means sur le dataset `iris`. [source: 35]
    * Visualisation des clusters formés. [source: 35]

6.  **Expérience 6 : Programme Java**
    * Implémentation d'une classe Java `SimulatedInstance` pour représenter des données avec des attributs numériques et catégoriels. [source: 36, 37, 38, 39, 40, 41, 42]
    * (Le code complet et l'objectif précis nécessiteraient une analyse plus approfondie du code source).

7.  **Expérience 7 : Algorithme Apriori avec Python**
    * Utilisation d'un dataset Kaggle.
    * Installation et utilisation de la librairie `apyori` en Python. [source: 44]
    * Chargement de données CSV, transformation en liste de transactions. [source: 44, 45]
    * Exécution de l'algorithme Apriori. [source: 45]
    * Visualisation des règles d'association trouvées (parsing dans un DataFrame Pandas). [source: 46]

8.  **Expérience 8 : Test du Chi-Carré (Chi-Square) avec Python**
    * Implémentation et exécution d'un test statistique du Chi-Carré. [source: 47] (Détails de l'implémentation non visibles dans l'extrait).

9.  **Expérience 9 : Classification avec Python (Scikit-learn)**
    * Utilisation des librairies Python : `numpy`, `pandas`, `scikit-learn` (et potentiellement `matplotlib`). [source: 48, 50]
    * Chargement et manipulation du dataset `Social_Network_Ads.csv`. [source: 50]
    * Implémentation d'un modèle de classification (détails spécifiques du modèle non visibles dans l'extrait). [source: 50]
    * Affichage des résultats/output. [source: 51]

10. **Expérience 10 : (Contenu spécifique non détaillé)**
    * Probablement une autre application de technique de Data Mining avec Python/Scikit-learn. [source: 52]

11. **Expérience 11 : Clustering avec Python (Scikit-learn)**
    * Implémentation d'un algorithme de clustering (probablement K-Means). [source: 53]
    * Choix du nombre de clusters (k=3 mentionné). [source: 54]

12. **Expérience 12 : Mesures de Similarité/Distance avec Python**
    * Implémentation et calcul de la Similarité et Distance de Jaccard. [source: 56]
    * Implémentation et calcul de la Distance Euclidienne. [source: 57]

13. **Expérience 13 : Visualisation de Données avec Python**
    * Création de graphiques avec Python (probablement Matplotlib/Seaborn).
    * Implémentation d'un graphique linéaire (Line Plot). [source: 58]
    * Implémentation d'un histogramme. [source: 59]

## Outils et Technologies Utilisés

* **SGBD :** Microsoft SQL Server [source: 2]
* **Outil BI/DM :** WEKA (Version 3.8.6) [source: 8, 12]
* **Langages de Programmation :** Java [source: 36], Python [source: 44, 48, 50]
* **Librairies Python :**
    * `apyori` [source: 44]
    * `pandas` [source: 50]
    * `numpy` [source: 48]
    * `scikit-learn` [source: 50]
    * `matplotlib` [source: 49, 58, 59] (ou équivalent pour la visualisation)
