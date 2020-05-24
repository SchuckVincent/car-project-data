# Compte rendu du projet data MD5P2020
### Hugo Gomez - Vincent Schuck
## Car Data Price Prediction

#### ***Présentation du projet***
Le projet proposé par M. Guezguez consiste à réaliser les étapes d’un projet de data science en se basant sur la prédiction du prix de revente de voiture.
L’objectif final est donc de mettre en place un modèle de Machine Learning qui va prédire le prix auquel va être revendu le véhicule que l’on souhaite le plus précis possible.
Nous ne partons pas de zéro car nous avons eu comme base de départ un dataset de véhicule d’occasion récupéré sur un site de revente de voiture.
Les principales étapes vont être de s’approprier la donnée, la nettoyer, extraire et ajouter des features importantes pour la précision du modèle et enfin mettre en place le modèle le plus précis possible.

#### ***Fonctionnement du projet***
Dans le dossier, vous trouverez 3 notebooks. Pour une meilleure lisibilité nous avons séparé le notebook final en 3 fichiers.

**Notebooks :**
- 1_explo_cleaning.ipynb : contient la partie exploration de la donnée, nettoyage de la donnée et la partie features engineering.
- 2_scraping_prix.ipynb : contient la partie scraping d’un site avec les données sur le prix neuf des voitures.
- 3_ml_prediction.ipynb : contient une petite partie de features engineering, la partie sur la sélection des features, la création du modèle et son amélioration
- 4_final.ipynb : contient les trois parties précédentes concaténées en un seul fichier
