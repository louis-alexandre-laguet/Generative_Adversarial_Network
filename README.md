# Implémentation de GANs et Variants sur Différents Datasets

Ce repository contient plusieurs implémentations de Generative Adversarial Networks (GANs) et de leurs variantes. L'objectif de ces exercices est d'explorer les GANs pour la génération d'images, en partant d'un DCGAN simple jusqu'à une version conditionnelle avec WGAN-GP.

## Contenu du repository

### 1. DCGAN sur des images de briques Lego
**Objectif :**
- Entraîner un DCGAN (Deep Convolutional GAN) pour générer des images en niveaux de gris de 64×64 pixels représentant des briques Lego.
- Utilisation d'un discriminateur et d'un générateur convolutionnels.
- Visualisation de l'évolution des images générées au fil de l'entraîment.

### 2. WGAN-GP (Wasserstein GAN avec Gradient Penalty)
**Objectif :**
- Comprendre les limitations des GANs standards (instabilité, mode collapse) et voir comment le WGAN les corrige.
- Implémenter un WGAN utilisant la distance de Wasserstein au lieu de la divergence Jensen-Shannon.
- Appliquer le Gradient Penalty (GP) pour stabiliser l'entraîment en forçant le critique à respecter la condition de Lipschitz.
- Comparer les performances avec un GAN classique.

### 3. WGAN-GP Conditionnel sur CelebA
**Objectif :**
- Implémenter un GAN conditionnel (Conditional GAN) permettant de générer des images en fonction d'un label.
- Intégration des labels dans le générateur et le critique pour orienter la génération d'images.
- Expérimentation avec des attributs de CelebA (ex: cheveux blonds ou non).
- Analyse de la qualité des images générées en fonction des labels conditionnels.

Les modèles entraînés sont enregistrés dans le fichier `models.zip`.
