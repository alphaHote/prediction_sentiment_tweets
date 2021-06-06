# description du projet : prediction_sentiment_tweets
    objectif : créer un modèle capable de classer un tweet (négatif ou positif)
    dataset  : 
              source     : https://www.kaggle.com/kazanova/sentiment140
              description: 1.6 million tweets texts extraits en utilisant
                           "twitter API" accompagnés d'une annotation 
                           (0 pour neg et 1 pour pos).  
# pronostic des étapes de prétraitement :
    enlèvement des abreviations, stop words et ponctuation
    lemmatization avec nltk
    entrainnement du modèle Word2Vec avec comme fenêtre 5 et taille maxi 300
# pronostic des étapes de modélisation :
    1. Représenter chaque tweet par la somme des vecteurs de chaque mot dans le 
       tweet et les stocker dans une matrice représentant les caractéristiques.
    2. Diviser le dataset aléatoirement en 70% d'apprentissage et 30% de test.
    3. entrainnement de la regression logistique.
# éxecution du programme :
    il est souhaitable d'utiliser un environnement virtuel.
