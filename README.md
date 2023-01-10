# Projet-Python-LA-ICP MS

## Contexte

La LA-ICP MS est une méthode d'analyse permettant de visualiser la présence d'isotopes sur l'échantillon. La machine balaye l'échantillon ligne par ligne, ce qui permet de reconstruire une carte de présence d'un isotope dans l'échantillon. 

## Problématique 
Les données obtenues consistent en une intensité du signal pour différents isotopes, qui n'est que qualitative. Le but est de réaliser un code permettant d'obtenir des données qualitatives, en l'occurrence la concentration des différents isotopes.

## Programme

Le programme fourni récupère les données du dossier *data* et réalise une calibration à partir de données.

![Exemple de courbe de calibration](https://github.com/ABeague/Projet-Python-LA-ICPMS/blob/main/Curve_Calibration.png)

Il réalise ensuite une image qualitative et une image quantitative de l'échantillon représentant la présence d'un isotope à partir des données du dossier *data/image*.

![Image quantitative](https://github.com/ABeague/Projet-Python-LA-ICPMS/blob/main/Imshow_Concentration.png)

# Fichiers

Ce dépôt contient les fichiers suivants :
- *Procede_Theorique.ipynb* est une description plus détaillée du projet,
- *Code Source.ipynb* contient la totalité du programme,
- Le dossier data contient toutes les données nécessaires au fonctionnement du programme,
- Les autres fichiers sont les images de ce *README*.
