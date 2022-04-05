Dans le contexte d'un projet kaggle inter-université, il a fallu prédire le cumul de pluie en région bretonne à partir de modèle de Machine et Deep Learning.
Ce projet s'est fait en collaboration avec Météo France.

Dans la partie 'Documentation', on peut retrouver le rapport retracant les différentes intuitions et méthodes utilisées durant le projet ainsi que les résultats obtenus.

Chaque partie du rapport (présent dans la partie 'Documentation') vient en support des différents notebooks.
Pour trouver le notebook correspondant il faut savoir que la norme utilisée et la suivante : 
       
       DEEPCAMP_<PARTIE_RAPPORT>_<TITRE_NOTEBOOK>.ipynb
       
Par exemple : 

       DEEPCAMP_P1B_ANALYSE_STATISTIQUE.ipynb
       
est le notebook qui renvoie à la partie 1 section B et il s'agit du notebook d'analyse statistique.
DEEPCAMP est le nom du groupe sur Kaggle.

Dans le cadre du projet, deux jeux de données différents ont été utilisés : 

- L'un avec les prédictions Météo France et où nos modèles "ajustaientt" leurs résultats.
- L'un sans les prédictions Météo France et où nos modèles prédisaient le cumul de pluie directement.

Ainsi les notebooks sont regroupés par jeu de données utilisé :

PARTIE 1 : SANS PREDICTIONS DE METEO FRANCE
 DEEPCAMP_P1B_ANALYSE_STATISTIQUE.ipynb : Analyse descriptive globale
 DEEPCAMP_P1C&D&E_PREPROCESSING&MODELSML.ipynb : Preprocessing et modèles machine learning(hors LSTM) sans prédictions Météo France
 DEEPCAMP_P1E_LSTM.ipynb : Conception et entraînement des modèles LSTM sans prédictions Météo France


PARTIE 2 :AVEC PREDICTIONS DE METEO FRANCE
 DEEPCAMP_P2B_INTERPOLATION_CONCATENATION_ARPEGE.ipynb : Interpolation et concaténation des arpège 
 DEEPCAMP_P2C_PREDICTIONS.ipynb : Machine Learning avec prédictions Météo France
