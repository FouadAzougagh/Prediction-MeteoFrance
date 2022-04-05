Projet DEFIIA2022_Equipe DEEPCAMP: description des notebooks python

Chaque notebook renvoie à une partie spécifique du rapport (présent dans la partie 'Documentation').
La norme de nommage d'un notebook est la suivante :
       
       DEEPCAMP_<PARTIE_RAPPORT>_<TITRE_NOTEBOOK>.ipynb
       
Par exemple : 

       DEEPCAMP_P1B_ANALYSE_STATISTIQUE.ipynb
       
est le notebook qui renvoie à la partie 1 section B et il s'agit du notebook d'analyse statistique.

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
