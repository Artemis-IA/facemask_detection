Détection du port du masque avec Keras
Ce projet vise à développer un modèle de détection du port du masque à l'aide de Keras. Les étapes du projet sont les suivantes :

Préparation des données
Télécharger le jeu de données de visages avec masque et sans masque
Charger les images et les redimensionner
Appliquer la préparation des données nécessaire pour le modèle VGG16
Splitter les données en données d'apprentissage, validation et test
Visualiser les images de la classe Avec_Masque et Sans_Masque
Architecture CNN sur Keras
Charger et configurer le modèle VGG16 pour l'application souhaitée
Appeler le ModelCheckpoint pour sauvgarder le meilleurs modèle durant l'apprentissage
Lancer un apprentissage en utilisant les données d'apprentissage et les données de validation avec un historique
Tracer les courbes d'accuracy et d'erreur de train et validation
Calculer l'accuracy et la matrice de confusion sur les données de test
Application
Tester le modèle développé sur des nouvelles images
Développer un code python qui va activer la Webcam et identifier si la personne qui est devant la Webcam porte un masque ou non
Déploiement
Le projet est déployé sur GitHub. Le dépôt contient :

Un Notebook Jupyter qui réalise les différentes étapes du projet
Un mini rapport sur le projet réalisé
Le modèle VGG16.h5 (facultatif)
Ce Readme.md
Utilisation
Pour utiliser le projet, suivez les étapes suivantes :

Clonez le dépôt sur votre ordinateur
Ouvrez le Notebook Jupyter dans un IDE Python
Exécutez les cellules du Notebook en suivant l'ordre
Performances
Le modèle a obtenu une accuracy de 99,9% sur les données de test. Il est donc capable de détecter le port du masque avec une grande précision.

Conclusion
Ce projet a permis de développer un modèle de détection du port du masque efficace. Le modèle peut être utilisé pour diverses applications, telles que le contrôle des entrées dans des lieux publics ou la surveillance vidéo.

Améliorations possibles
Le modèle pourrait être amélioré de plusieurs manières, par exemple :

Utiliser un jeu de données plus volumineux
Appliquer des techniques de Data Augmentation pour améliorer la robustesse du modèle
Utiliser un modèle plus complexe, tel qu'un modèle ResNet ou un modèle DenseNet
Nous espérons que ce projet vous a plu.
