# Classifying Speakers Using Speech Recognition

## 1. Introduction
Ce projet a pour objectif de classifier le type de locuteur (homme, femme ou enfant) à partir d'enregistrements sonores (.wav).  
L'approche repose sur la modélisation guidée par les données et l'utilisation de réseaux de neurones artificiels (ANN).  
Les performances des modèles ont été évaluées à l'aide de validation croisée et de métriques telles que la **matrice de confusion** et le **f1-score**.

Le projet comporte deux expériences principales :  
1. Classification Homme – Femme  
2. Classification Homme – Femme – Enfant  

Les fichiers audio sont traités pour extraire les **MFCC** (Mel Frequency Cepstral Coefficients) et des transformations supplémentaires sont appliquées pour préparer les données à l'entraînement.

---

## 2. Prérequis
- Python >= 3.8
- Librairies Python :
  - `numpy`
  - `pandas`
  - `scipy`
  - `librosa`
  - `scikit-learn`
  - `matplotlib`
  - `tensorflow`

Installation rapide des dépendances :  
```bash
pip install numpy pandas scipy librosa scikit-learn matplotlib tensorflow
