# Projet de Reconnaissance des Émotions à partir de la Parole

Ce projet se concentre sur le traitement de la parole et la reconnaissance des émotions. Il comprend plusieurs composants clés:

1. **Articles de recherche**: Deux articles récents traitant le dataset fourni (BAVED dataset) avec les réseaux de neurones pour la reconnaissance des émotions à partir de la parole.

2. **Chargement des données**: Un programme Python qui charge les fichiers audio du dataset (wavs+noise), en ajoutant à chaque signal le label de l'émotion qui lui correspond.

3. **Prétraitement et extraction des caractéristiques MFCC**: Application sur chaque fichier audio si nécessaire des étapes de prétraitement et d'extraction des caractéristiques MFCC, qui sont essentielles pour la reconnaissance des émotions à partir de la parole.

4. **Division du dataset**: Le dataset "arabic_dataset.zip" a été divisé en 3 subsets: 50% pour l'apprentissage, 20% pour la validation, et 30% pour le test. Chaque subset joue un rôle crucial dans la formation et l'évaluation du modèle.

5. **Construction du modèle neuronal**: Utilisation de la librairie PyTorch pour construire un modèle neuronal capable de s'intégrer aux 3 applications demandées. Le choix de ne pas utiliser un modèle pré-entrainé est expliqué.

6. **Apprentissage du modèle neuronal**: L'apprentissage du modèle neuronal sur le dataset fourni en faisant varier ses hyperparamètres. Cela permet d'optimiser le modèle pour la reconnaissance des émotions à partir de la parole.

7. **Métriques de performance/test**: Affichage des métriques de performance/test (accuracy, precision, fscore, confusion matrix, vitesse de reconnaissance ...) du modèle pour chaque variation des hyperparamètres.

8. **Discussion des résultats**: Une discussion autour des résultats obtenus, y compris les implications pour la reconnaissance des émotions à partir de la parole.

Pour plus de détails sur chaque composant, veuillez consulter les sections correspondantes ci-dessous.