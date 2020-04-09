# Real-time-ASL-recognition
Real Time ASL sign language recognition with Deep Learning

Projet réalisé par Loic Baum dans le cadre du cours de SYS866 à l'ETS, Montréal

### Fichiers du projet

Il y a deux notebooks pour l'entrainement des modèles : le premier pour le dataset ASL-Alphabet Kaggle et le deuxième pour celui de l'université de Surrey. 

Comme dit dans le rapport, les datasets ont été modifiés, mais impossible de les inclure sur GitHub car le poids total est d'environ 4 Go.

En théorie,les notebooks devraient avoir gardé en mémoire les derniers résultats obtenus sur le modèle VGG16.

Il y également un notebook qui pour réaliser le pré-processing des images et un notebook pour la classification en temps réel.

Pour la classification en temps réel, le script est configuré pour une webcam de 480x720 pixels.

### Codes utilisés :
Pour le projet, je me suis inspiré de ce code : https://www.kaggle.com/gargimaheshwari/asl-recognition-with-deep-learning
J'y ai apporté plusieurs modifications notamment avec l'ajout de fonctions pour charger et sauvegarder un modèle entrainé, pour importer le modèle VGG16 avec transfer learning et d'autres petites modifications.

### Codes implémentés moi-même
J'ai implémenté moi même tous les scripts de preprocessing d'images, ainsi que le script permettant la classification en temps réel.
