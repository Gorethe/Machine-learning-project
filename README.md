Ce notebook Jupyter implémente un modèle d'apprentissage profond pour la classification d'images en utilisant le dataset CIFAR-10.
Il est structuré en plusieurs sections qui couvrent l'importation des bibliothèques, le chargement et le prétraitement des données, 
la visualisation des images, la création et l'entraînement du modèle, et enfin l'évaluation des performances.

1. Importation des Modules
Les bibliothèques nécessaires sont importées, notamment :

torch et torch.nn pour le deep learning avec PyTorch.

torchvision pour charger le dataset CIFAR-10.

matplotlib et seaborn pour la visualisation.

sklearn.metrics pour l'évaluation des performances.

2. Chargement et Prétraitement des Données
Le dataset CIFAR-10 est chargé et divisé en ensembles d'entraînement, de validation et de test.

Des transformations sont appliquées pour enrichir les données (retournement horizontal, recadrage aléatoire, etc.) et normaliser les images.

3. Visualisation des Images
Quelques images du dataset sont affichées pour vérification, avec leurs étiquettes correspondantes.

4. Création du Modèle
Un modèle de réseau neuronal est défini (l'architecture n'est pas détaillée dans le snippet fourni).

La fonction de perte et l'optimiseur sont configurés.

5. Entraînement et Évaluation
Le modèle est entraîné sur les données d'entraînement.

Les performances sont évaluées sur les ensembles de validation et de test.

Des métriques comme l'accuracy et la matrice de confusion sont utilisées pour évaluer le modèle.

# Utilisation
Exécution : Lancez les cellules du notebook dans l'ordre pour charger les données, entraîner le modèle et évaluer les résultats.

Personnalisation : Modifiez l'architecture du modèle ou les hyperparamètres pour améliorer les performances.

Visualisation : Utilisez les sections de visualisation pour inspecter les données et les résultats.

Remarques
Le notebook est conçu pour être exécuté dans un environnement compatible avec PyTorch (comme Google Colab).

Les transformations appliquées aux images aident à améliorer la généralisation du modèle.

N'hésitez pas à explorer et à expérimenter avec le code pour mieux comprendre le processus d'apprentissage profond sur CIFAR-10 !
