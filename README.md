# Toxic_Comment_classification

Projet dans le cadre du cours de NLP (M1 ISEN), Toxic_Comment_classification a pour but de créer un model capable de classifier des commentaires au travers de tags comme :

- toxic
- severe_toxic
- obscene
- threat
- insult
- identity_hate

Le but étant à terme de pouvoir sensibiliser et/ou prévenir des internautes sur les propriétés néfastes de certains commentaires.

## Auteurs

- [Pierre Giraud](https://github.com/Giraud-Pierre)
- [Jean Schneider](https://github.com/skuuuuuuu)
- [Louis Manouvriez](https://www.github.com/Spac3Drunk)

## Tech Utilisées

- [jupyter notebook](https://jupyter.org/)
- [tensorflow](https://www.tensorflow.org/)
- [sklearn](https://scikit-learn.org/stable/)

## Dataset

- [Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data#)

## Comment utiliser notre projet:

- Copier le notebook ‘Classification_commentaires_toxiques_2.ipynb’ de la branche main dans votre drive et l’ouvrir avec google colab
- Créer un raccourci du dossier ci-dessous dans un dossier ‘NLP_4A’ dans votre drive:

    * https://drive.google.com/drive/folders/1W5GG4tJkbGfFiyt8-k9VFJXM99Zaoeuc?usp=sharing
    * Ce dossier est aussi présent sur le repository github. Il correspond au dossier ‘Projet’

- Exécuter la partie ‘importation des packages’ qui va importer les bibliothèques nécessaires au projet
- Si vous voulez réaliser la partie ‘études des jeux de données’ pour observer la répartition des commentaires dans les données, effectuez au préalable la partie ‘importation des données’, sinon passez directement à la partie ‘préparation des données’
- Dans la ‘préparation des données’, 
    * Les 2 premières étapes ‘Définition de la fonction prepare_string()’ et ‘nettoyages des commentaires’ peuvent être passées. Ces étapes prenant un certain temps, les données nettoyées ont été fournies dans le dossier fourni précédemment.
    * Il faut lancer la partie ‘chargement des données une fois traitées’ et les parties suivantes pour rendre ces données utilisable pour les modèles suivants
- Dans la partie ‘étude de différents modèles’, chaque modèle est exécutable indépendamment si vous souhaitez voir comment il fonctionne. Lors du lancement, le programme sauvegarde le meilleur modèle pour chaque type de modèle dans un dossier ‘Model’ sur votre drive.
    * Note 1: Certains modèles prenant un certain temps à s'entraîner, des modèles préalablement entraînés sont fournis dans le dossier ’Model’ du dossier ’Projet’ fourni précédemment. Si vous souhaitez réutiliser un ou plusieurs de ces modèles, copiez le/les fichier(s) correspondant(s) dans un dossier ‘Model’ sur votre drive.
    * Note 2: Les sauvegardes de modèle pèsent relativement lourd (plusieurs centaines de MO) et peuvent prendre une place conséquente sur votre google drive. Pensez à les supprimer quand vous avez fini d’utiliser le projet.
