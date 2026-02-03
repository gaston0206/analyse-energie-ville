#  Analyse de la Consommation Énergétique

L'objectif de ce projet est d'analyser les données énergétiques afin de mieux comprendre les tendances de consommation et les facteurs environnementaux (météo) qui les influencent.

##  Présentation du Projet
Ce projet suit une méthodologie rigoureuse pour explorer, nettoyer, analyser et visualiser les données de consommation. Nous cherchons à établir des corrélations entre les conditions climatiques et la demande énergétique sur trois zones distinctes.

##  À propos du Jeu de Données
Le dataset **powerconsumption** comporte **52 416 observations** avec **09 variables** clés :

| Variable | Description |
| :--- | :--- |
| **Datetime** | Date et heure de l'observation |
| **Temperature** | Température météorologique |
| **Humidity** | Humidité de l'air |
| **WindSpeed** | Vitesse du vent |
| **GeneralDiffuseFlows** | Flux diffus généraux |
| **DiffuseFlows** | Flux diffus |
| **Power_Consumption_Zone 1** | Consommation électrique - Zone 1 |
| **Power_Consumption_Zone 2** | Consommation électrique - Zone 2 |
| **Power_Consumption_Zone 3** | Consommation électrique - Zone 3 |

##  Méthodologie
1. **Exploration :** Analyse descriptive des variables.
2. **Nettoyage :** Traitement des valeurs manquantes et formatage des dates.
3. **Analyse (EDA) :** Étude des corrélations entre météo et consommation.
4. **Visualisation :** Création de graphiques pour identifier les pics de consommation.

## Structure du dépôt
* `data/` : Contient le fichier source `powerconsumption.csv`.
* `images/` : Contient les graphiques d'analyse (ex: courbes de charge, corrélations).
* `analyse.py` (ou notebook) : Code source de l'étude.

##  Technologies utilisées
* **Python 3**
* **Pandas** & **NumPy**
* **Matplotlib** & **Seaborn**
* **Os**
