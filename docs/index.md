# Home of my documentation site
![alt text](img/welcome.jpg)

## General Theme
! [ign docs](https://www.ign.fr/institut)

## Here we talk about everything about geomatic

To begin with, do you know what “geomatics” is?
The term “geomatics” was proposed in the late 1960s by the French scientist Bernard Dubuisson.
And sources are very important in this field.
So, as you know, we are going to talk about data sources.

## 1. Définition
Une source de données est l’origine d’une information exploitable dans un système d’information.
Elle peut être interne ou externe, structurée ou non structurée, statique ou temps réel.

Objectif : garantir fiabilité, traçabilité, fraîcheur et exploitabilité.

## 2.Typologie des sources de données
A. Par origine
1. Sources internes
Produites par l’organisation :
    - ERP, CRM
    - Bases métiers
    - Logs applicatifs
    - Capteurs IoT internes
    - Données RH / financières

➡ Avantage : maîtrise et gouvernance plus simples   
➡ Risque : silos, qualité hétérogène

2. Sources externes
Produites par des tiers :
    - Données open data (ex. INSEE)
    - Données géographiques (ex. OpenStreetMap)
    - APIs privées (ex. Google)
    - Fournisseurs spécialisés (météo, marchés, télédétection)   

➡ Enjeu : contractualisation, licence, mise à jour

B. Par structure
1. Données structurées
    - Tables relationnelles (SQL)
    - CSV
    - Data Warehouse

Exploitation simple, requêtes optimisées.

2. Données semi-structurées
    - JSON
    - XML
    - Logs formatés

Flexible, nécessite transformation.

3. Données non structurées
    - Images
    - Vidéos
    - PDF
    - Texte libre

Traitement via NLP, vision par ordinateur, etc.

C. Par mode d’acquisition
1. Saisie humaine
    - Formulaires
    - Enquêtes
    - Applications métiers

Risque d’erreurs → besoin de validation.

2. Capteurs et instruments
    - GPS
    - Stations météo
    - Satellites (ex. NASA)
    - Drones

Production massive, nécessite stockage adapté.

3. Web scraping / APIs
    - Extraction automatisée :
    - APIs REST
    - Connecteurs SaaS

Attention aux conditions d’usage.