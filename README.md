# PaluCare – Système d'analyse des soins de paludisme chez les enfants malnutris

## Description

**PaluCare** est un système d'analyse de données médicales conçu pour analyser et évaluer les soins apportés aux enfants souffrant de paludisme et de malnutrition. Ce projet combine des techniques de data engineering, de science des données et de visualisation pour fournir des informations exploitables aux professionnels de la santé. L'objectif est d'améliorer la qualité des soins et d'optimiser les processus de traitement en tirant parti des données médicales.

## Fonctionnalités

- **Exploration et nettoyage des données** : Traitement des données brutes pour identifier les valeurs manquantes, corriger les anomalies et standardiser les formats de données.
- **Pipeline ETL** : Automatisation du processus d'extraction, de transformation et de chargement des données à l'aide d'Apache Airflow.
- **Analyse statistique** : Réalisation d'analyses descriptives et inférentielles pour mieux comprendre l'impact des traitements sur la santé des enfants.
- **Modélisation prédictive** : Utilisation de modèles de machine learning pour prédire les résultats des traitements en fonction de divers paramètres médicaux (comme le taux d'hémoglobine, le poids, etc.).
- **Visualisation interactive** : Création de tableaux de bord pour visualiser les statistiques importantes, telles que la répartition des âges des patients et l'évolution des taux d'hémoglobine par traitement.
- **Système d'alertes** : Mise en place d'alertes en temps réel pour notifier les professionnels de la santé des cas critiques, comme les enfants présentant des taux d'hémoglobine dangereusement bas.

## Technologies utilisées

- **Python** : Pour la manipulation des données et le développement de l'application.
- **Pandas** : Pour l'exploration, la transformation et l'analyse des données.
- **Apache Airflow** : Pour la création de pipelines ETL (Extraction, Transformation, Chargement).
- **Scikit-learn** : Pour la modélisation et la prédiction des résultats.
- **Dash** : Pour la création de tableaux de bord interactifs et la visualisation des données.
- **Kafka** : Pour l'intégration d'un système d'alertes en temps réel basé sur des événements critiques.
- **Docker** : Pour le déploiement et la conteneurisation de l'application.

## Installation et Exécution

### Prérequis

Assurez-vous d'avoir les éléments suivants installés :

- [Python 3.11](https://www.python.org/downloads/)
- [Pipenv](https://pipenv.pypa.io/en/latest/) ou `pip`
- [Docker](https://www.docker.com/)

### Étapes d'installation

1. Clonez ce dépôt GitHub :

   ```bash
   git clone https://github.com/votre-utilisateur/palu-care.git
   cd palu-care

### Auteurs
 **Georges KAPUTU  - Développeur principal et data engineer.
