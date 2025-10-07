# Earthquake_DataEngineer_MSFabric
# 🌍 Projet Data Engineering sur les Séismes avec Microsoft Fabric

## 🔎 Aperçu du projet
Ce projet illustre la mise en place d’une **pipeline complète de data engineering et d’analyse** avec **Microsoft Fabric**, combinant les environnements **Data Factory**, **Data Engineering** et **Power BI**.

L’objectif est d’**ingérer, transformer et analyser les données d’événements sismiques mondiaux** issues de l’API **USGS (United States Geological Survey)**.

---

## 🧰 Technologies utilisées
- **Python**  
- **PySpark**  
- **Microsoft Fabric**  
  - Data Factory  
  - Data Engineering  
  - Power BI  

---

## 📁 Contenu du projet

### 🥉 Bronze Layer — Ingestion des données brutes
Ingestion des données sismiques brutes depuis l’API USGS et stockage dans leur **format original**, servant de base pour les étapes de transformation suivantes.

### 🥈 Silver Layer — Nettoyage et transformation
Nettoyage, transformation et consolidation des données du niveau Bronze pour obtenir un **jeu de données structuré**, prêt pour l’analyse.

### 🥇 Gold Layer — Jeu de données analytique
Raffinement et optimisation des données pour créer des **datasets prêts à l’analyse** et adaptés à la **visualisation dans Power BI**, permettant de générer des **insights à forte valeur ajoutée**.

---

## 📊 Description des attributs des données

| Attribut | Type | Description |
|-----------|------|-------------|
| **id** | string | Identifiant unique de l’événement |
| **latitude** | double | Latitude de l’événement |
| **longitude** | double | Longitude de l’événement |
| **elevation** | double | Altitude du lieu de l’événement (en mètres) |
| **title** | string | Titre ou nom de l’événement |
| **place_description** | string | Description de la localisation |
| **sig** | bigint | Score de signification de l’événement |
| **mag** | double | Magnitude du séisme |
| **magType** | string | Type d’échelle de magnitude utilisée |
| **time** | timestamp | Date et heure exactes de l’événement |
| **updated** | timestamp | Dernière mise à jour des données de l’événement |

---

## 📈 Objectif final
Mettre en place un **pipeline complet de traitement et d’analyse de données sismiques** dans **Microsoft Fabric**, de l’ingestion des données brutes à la **visualisation dans Power BI**, afin d’**explorer les tendances et insights mondiaux sur les séismes**.
