# Age_Prediction

Ce projet vise à explorer et comparer différentes méthodes d'estimation de l'âge facial en utilisant des modèles d'apprentissage en profondeur.

## Contexte du Projet

L'estimation de l'âge facial a des applications diverses, de la sécurité au marketing. Cependant, la précision de cette estimation reste un défi. Ce projet se penche sur l'utilisation de modèles d'apprentissage en profondeur pour améliorer la précision de l'estimation.

## Méthodologie du Travail

### Données
- Utilisation du dataset UTKFace pour l'entraînement, comprenant des images faciales avec des annotations d'âge, de sexe, et d'origine ethnique.
- Prétraitement des données incluant l'exploration de la structure du jeu de données, le défloutage des images, et le redimensionnement.

### Modèles d'Apprentissage en Profondeur
- Choix de modèles diversifiés, y compris VGG16, ResNet50, InceptionV3, et un modèle CNN personnalisé.
- Paramètres d'entraînement avec optimiseur Adam, fonction de perte MSE, et métrique MAE.

### Résultats et Interprétation
- Visualisation des courbes d'apprentissage et interprétation des performances de chaque modèle.

### Benchmarking
- Évaluation des performances avec des métriques telles que MAE, MSE, RMSE, R^2, et Accuracy.
