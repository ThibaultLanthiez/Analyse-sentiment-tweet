[:arrow_left: Retour vers le portfolio](https://github.com/ThibaultLanthiez/Portfolio)

<img src="https://github.com/ThibaultLanthiez/Analyse-sentiment-tweet/blob/main/image-dataset.PNG" width="100%" and height="80%"/>

# Analyse du sentiment exprimé par un tweet

L'objectif est de déterminer si un tweet est haineux ou non en fonction du texte qui le compose.

Pour cela, j'ai téléchargé sur la plateforme Kaggle, un jeu de données composé d'un ensemble de tweets de tailles variables.

Puis, avec le langage python j'ai mis en forme ces tweets pour les transformer en séquences de tokens.

Enfin, avec la bibliothèque Keras de python, j'ai créé un réseau de neurones récurrents (RNN). 

Après entraînement et optimisation, mon modèle est capable de déterminer correctement la nature de 90% des tweets que l'on lui donne.

# Code

Voici le code du projet : [notebook](https://github.com/ThibaultLanthiez/Analyse-sentiment-tweet/blob/main/Projet_9_Analyse_de_sentiment_Message_haineux.ipynb)
