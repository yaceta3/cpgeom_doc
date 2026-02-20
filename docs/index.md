# Site de documentation
![Bienvenue](img/welcome.jpg)

---

## Sommaire
- [Définition](#definition)
- [Sources internes](#sources-internes)
  - [Référentiel parcellaire interne](#referentiel-parcellaire-interne)
  - [Référentiel BD TOPO](#referentiel-bd-topo)
  - [Géoplateforme](#geoplateforme)
- [Sources externes](#sources-externes)
  - [INSEE](#insee)
  - [Urbansimul](#urbansimul)
  - [OpenStreetMap (OSM)](#osm)
---

## Définition
Une **source de données** est l’origine d’une information exploitable dans un système d’information.  
Elle peut être **interne ou externe**, **structurée ou non structurée**, **statique ou temps réel**.  

**Objectif** : garantir **fiabilité**, **traçabilité**, **fraîcheur** et **exploitabilité**.

---

## Sources internes
Dans la DDT, les sources internes sont principalement des **référentiels** utilisés dans les missions quotidiennes.  

### Référentiel parcellaire interne
- **Type** : vectoriel (polygones parcelles)  
- **Format** : Shapefile, GeoJSON  
- **Mise à jour** : mensuelle  
- **Licence / Usage** : interne DDT uniquement  
- **Exemple d’usage** : analyse foncière et attribution de parcelles à des projets.

### Référentiel BD TOPO
- **Type** : vectoriel (routes, bâtiments, hydrographie…)  
- **Format** : Shapefile, GPKG  
- **Mise à jour** : trimestrielle  
- **Licence / Usage** : usage officiel pour SIG  
- **Exemple d’usage** : cartographie et planification territoriale.

### Géoplateforme
![Géoplateforme](img/geoplateforme.jpg)  
- **Type** : multi-données SIG  
- **Format** : WMS, WFS, GeoJSON  
- **Accès** : [Lien Géoplateforme](https://www.ign.fr/geoplateforme)  
- **Usage** : intégration centralisée des données internes et externes  
- **Exemple d’usage** : extraction rapide de données par zone d’intérêt.

---

## Sources externes
Les sources externes viennent d’institutions ou plateformes publiques/privées.  

### INSEE
![INSEE](img/insee.png)  
- **Type** : tabulaire/statistique  
- **Format** : CSV, XLS  
- **Mise à jour** : annuelle ou trimestrielle selon l’indicateur  
- **Licence / Usage** : ouverte (Open Data)  
- **Exemple d’usage** : indicateurs démographiques et socio-économiques.

### Urbansimul
![Urbansimul](img/urbansimul.png)  
- **Type** : foncier, simulation urbaine  
- **Format** : CSV, API interne  
- **Licence / Usage** : usage interne pour simulation de projets urbains  
- **Exemple d’usage** : analyse d’impact foncier et urbanistique.

### OpenStreetMap (OSM)
![OSM](img/osm.png)  
- **Type** : vectoriel (points, lignes, polygones)  
- **Format** : .osm, GeoJSON  
- **Mise à jour** : continue, contribution collaborative  
- **Licence / Usage** : ODbL  
- **Exemple d’usage** : cartographie libre, réseau routier, points d’intérêt.
