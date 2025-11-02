# Haar Cascade Classifier - Face Detection Project

Ce projet présente la détection de visages sur images et vidéos en utilisant la méthode classique Haar Cascade d'OpenCV.

## Description

Le projet est divisé en plusieurs étapes :

### 1. Détection de visages sur images

- Chargement d'une image dans le programme.
- Utilisation d'un classifieur pré-entraîné Haar Cascade pour détecter les visages.
- Encadrement des visages détectés par des rectangles rouges.
- Affichage du résultat final avec toutes les détections.
- Images utilisées : Image 4 & Image 5.

Cette étape permet une localisation rapide des visages et sert de base pour la détection dans des séquences vidéos.

### 2. Détection de visages dans une vidéo

- Découpage de la vidéo en images (frames).
- Détection des visages sur chaque frame.
- Affichage de la vidéo avec encadrement des visages détectés.
- Vidéo utilisée : "Squeezie sort avec Lena Situation".

Cette étape montre la capacité à suivre les visages dans un contexte dynamique et réel.

### 3. Sauvegarde des frames avec visages détectés

- Extraction des frames contenant des visages.
- Sauvegarde de ces frames sous forme d'images distinctes.
- Vidéo utilisée : "Denzel Washington Partage Son Meilleur Conseil Pour Réussir".

Cette méthode est utile pour l'analyse plus approfondie des expressions faciales et moments importants dans la vidéo.

## Installation

Installer les dépendances nécessaires avec Python :

pip install opencv-python matplotlib


## Usage

Ouvrir le notebook Jupyter `Haar Cascade Classifier.ipynb` et exécuter les cellules étape par étape pour reproduire les résultats.

## Auteur

DialRoss  
[GitHub](https://github.com/DialRoss)



