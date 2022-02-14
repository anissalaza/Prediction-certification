###### _Ce projet est réalisé dans le cadre de la formation Data Analyst (Bac +3/4, certifié RNCP) proposée par OpenClassrooms. Il fait partie des 9 projets à valider afin d'en être diplômé_.

# Prediction-certification

## Introduction

Étant libre de la thématique de ce dernier projet, j'ai tout naturellement décidé de l'articuler autour d'un sujet qui m'anime ; la musique. Mon objectif est alors de comprendre la structure d'un hit afin de créer un modèle de prédiction de certification des singles et/ou albums en France. Ainsi, le projet se construit autour d'une problématique clé :   

  **Comment expliquer l'obtention d'une certification d'or, de platine ou de diamant ? Quelles sont les variables déterminantes ?**        

L'impact de l'avénement du streaming sera alors déterminant dans la compréhension du sujet.

Ce projet sera réalisé grâce au langage informatique : _Python_.

* Outils utilisés :
  * Jupyter et JupyterLab
  * Librairies Python
  * Tableau
  * Keynote

Les étapes ont été les suivantes :  

∙ [Constitution d'un jeu de données](https://github.com/anissalaza/Prediction-certification/blob/9cb6facffef0e67f72659c7ee461291fa5660141/Preprocessing.ipynb) _(plus de 3000 données et 34 variables)_ : web scraping grâce aux librairies Python (BeautifulSoup et Requests), récupération des données (audio features) des chansons grâce à la librairie Spotipy et téléchargements de fichiers au format csv (SNEP et Spotify)  

∙ [Data cleaning et Exploratory data analysis](https://github.com/anissalaza/Prediction-certification/blob/cb9772cd8309f12f8a22929b02f6a701cf39564b/EDA.ipynb) : nettoyage de la base de données, analyse des données sous Python (statistiques descriptives, régressions linéaires et logistiques) + tests statistiques (Pearson, Khi-2, V-Cramer, Coefficient de Phi, Kolmogorov-Smirnov, Breusch-Pagan, ANOVA, Kruskal-Wallis et Eta-Squared)

∙ Visualisation : visualisation graphique grâce l'outil de visualisation Tableau + librairies Python (_Matplotlib, Seaborn et Plotly_) 

∙ [Modélisation](https://github.com/anissalaza/Prediction-certification/blob/cb9772cd8309f12f8a22929b02f6a701cf39564b/Modelisation.ipynb) : création du modèle de prédiction des certifications (_Régression logistique, Random Forest, Linear SVC, Catboost, kNN, Decision Tree, Naive Bayes, LightGBM, XGBoost, k-means, ACP, tSNE_)

∙ Rédaction d'un [rapport](https://github.com/anissalaza/Prediction-certification/blob/cb9772cd8309f12f8a22929b02f6a701cf39564b/Rapport.pdf) et d'une [présentation](https://github.com/anissalaza/Prediction-certification/blob/main/Soutenance.pdf) évalués lors d'une soutenance devant un jury

-----------------------------------------------

## Organisation du repository

#### *Preprocessing*
Ce fichier contient le **notebook Jupyter** qui permet de récupérer les données.

#### *EDA*
Ce **notebook Jupyter** contient le nettoyage et l'exportation des données.

#### *Modelisation*
Ce **notebook Jupyter** contient les différents modèles testés.

#### *Rapport*
Ce fichier correspond au rapport rédigé et répondant à notre problématique.

#### *Soutenance*
Ce fichier a été présenté lors de la **soutenance** validant le projet
