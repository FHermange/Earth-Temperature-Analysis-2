# Earth Temperature Analysis

## Table of Contents

- [Project Overview](project-overview)
- [Data Sources](data-sources)
- [Tools](tools)
- [Data Cleaning & Preparation](data-cleaning-&-preparation)
- [Exploratory Data Analysis](exploratory-data-analysis)
- [Data Analysis](data-analysis)
- [Results/Findings](results/findings)
- [Limitations](limitations)
- [Machine Learning](machine-learning)

### Project Overview:
This data analysis aims to observe the global warming (and disruption) of climate on a planetary scale over the last centuries and decades and to provide insights into the relationship between global warming and CO2 emissions (annual, per capita, cumulative and consumption-based), other greenhouse gases, energy mix and other relevant measures. By analyzing various aspects of warming intensity data throughout the globe (and specific areas if needed), we seek to identify correlations, trends and gain a deeper understanding of its evolution in time. Finally, through a machine learning trained model, we'll attempt to forecast the global warming evolution past 2024. This file will include a French/English translation for the convenience of our audience.

###### *Cette analyse a pour objectif d'observer le réchauffement climatique (et ses perturbations) à l'échelle planétaire au cours des derniers siècles et décennies ainsi qu'à fournir des informations pertinentes quant à la relation entre le réchauffement climatique et les émissions de CO2 (annuelles, par habitant, cumulées et basées sur la consommation), gaz à effet de serre, mix énergétique et autres mesures pertinentes. En analysant divers aspects des données ayant attrait à l’intensité du réchauffement climatique à travers le monde (et dans des zones spécifiques si nécessaire), nous chercherons à identifier les corrélations, les tendances et à mieux comprendre son évolution dans le temps. Enfin, grâce à un modèle entraîné de Machine Learning, nous tenterons de prévoir l'évolution du réchauffement climatique au-delà de 2024. Ce fichier comprendra une traduction Français/Anglais pour le confort de notre public*

- This project will then provide:
  - A global analysis
  - An analysis by geographic area
  - A Comparison with phases of temperature evolution prior to our time.
  - A Machine Learning trained model


<h6>- Ce projet présentera ainsi:
  - Une analyse globale
  - Une analyse par zones géographiques
  - Une comparaison avec les phases d'évolution des températures antérieures à notre époque
  - Un modèle de Machine Learning entraîné </h6>

### Data Sources: 

The data source used is NASA's and can be downloaded here:
###### Les sources de données peuvent être téléchargées ici :
- https://data.giss.nasa.gov/gistemp/
- https://github.com/owid/co2-data

Global Data: The first dataset used for this analysis is the "GLB.Ts+dSST.csv" file, which stands for "GLOBAL Land-Ocean Temperature Index in 0.01 degrees Celsius". It contains the average monthly temperatures in °C on the planet's surface from 1880 - 2024, across the globe.

###### Global Data : Le premier jeu de données utilisé pour cette analyse est le fichier « GLB.Ts+dSST.csv », pour « GLOBAL Land-Ocean Temperature Index in 0,01 degrés Celsius ». Il contient les températures mensuelles moyennes en °C à la surface de la planète de 1880 à 2024, à travers le monde.

North Hemisphere Data: The second dataset is the "NH.Ts+dSST" which presents the monthly average temperatures in °C on the surface of the planet over the years 1880 - 2024, located in the Northern hemisphere only.
###### North Hemisphere Data : Le second jeu de données est le fichier "NH.Ts+dSST", qui présente quant à lui les températures moyennes mensuelles en °C à la surface de la planète sur les années 1880 - 2024, situées dans l'hémisphère Nord uniquement.

South Hemisphere Data: The third dataset is the "SH.Ts+dSST" which presents the monthly average temperatures in °C on the surface of the planet over the years 1880 - 2024, located in the Southern hemisphere only.
###### South Hemisphere Data : Le troisième jeu de données est le fichier "NH.Ts+dSST", qui présente quant à lui les températures moyennes mensuelles en °C à la surface de la planète sur les années 1880 - 2024, situées dans l'hémisphère Sud uniquement.

Zonal Annual Means: The fourth dataset is the "ZonAnn.Ts+dSST" which displays the average annual temperatures in °C of the globe according to zones defined by their latitude.
###### Zonal Annual Means : Le quatrième jeu de données est le fichier "ZonAnn.Ts+dSST" qui présente les températures moyennes annuelles en °C du globe en fonction de zones définies par leur latitude.

Data on CO2 and Greenhouse Gas Emissions by Our World in Data: Finally, the last dataset "owid_co2.data.xlsx" includes full data on CO2 emissions (annual, per capita, cumulative and consumption-based), other greenhouse gases, energy mix and other relevant measures.
###### Data on CO2 and Greenhouse Gas Emissions by Our World in Data : Enfin, le dernier ensemble de données nommé « owid_co2.data.xlsx » comprend des données complètes sur les émissions de CO2 (annuelles, par habitant, cumulées et basées sur la consommation), d'autres gaz à effet de serre, le mix énergétique et d'autres mesures pertinentes.

### Tools

- Python - *Data Cleaning, Data Exploration, Data Analysis and Machine Learning Training Model*
- PowerBI - *Creating reports*

<h6>- Python - *Nettoyage, Exploration et Analyse de données, ainsi qu'Entraînement d'un Modèle de Machine Learning*
- PowerBI - *Création de rapports*</h6>

### Data Cleaning & Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data loading and Inspection.
2. Handling missing values.
3. Data Cleaning and formatting.

<h6>Lors de la phase initiale de préparation des données, nous avons effectué les tâches suivantes :
1. Chargement et inspection des données.
2. Gestion des valeurs manquantes.
3. Nettoyage et formatage des données.</h6>

### Exploratory Data Analysis

EDA involved exploring the global temperatures data to answer key questions, such as:
- Is there a global temperature increase over the years and decades ?
- If so, does this increase impact the whole globe evenly ? Or are there Specific areas impacted most ?
- Is there a relationship between CO2 / Greenhouse Gas Emissions and this increase ?
- Did that relationship evolve throughout the years and how ?

<h6> L'exploration des données a notamment consistée à balayer l'ensemble de nos jeux de données sur les températures mondiales pour répondre à des questions clés, telles que :
- Y a-t-il une hausse de la température globale au fil des années et des décennies ?
- Si oui, cette hausse impacte-t-elle uniformément l'ensemble du globe ? Ou y a-t-il des zones géographiques davantage impéctées ?
- Existe-t-il une relation entre les émissions de CO2 / Gaz à effet de serre et cette hausse ?
- Cette relation a-t-elle évolué au fil des années et comment ?</h6>

### Data Analysis

* Note : Inclure du code Python de données pertinentes *

### Results/Findings

Tha analysis results are summarized as follow :

### Limitations
* Inclure toutes les modifications faites au data et qui pouvaient gêner leur exploitation/lecture/analyse *
* Exemple : nous avons dû supprimer les années allant de 1750 à 1879 de owid_co2.data.xlsx car les autres jeux de données ne débutent qu'à partie de 1880 *
  
### Machine Learning

