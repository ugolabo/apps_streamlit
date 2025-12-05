# Apps interactives Streamlit

Une recension d'outils pour construire des applications interactives pour :

- exécuter des modèles d'IA avec une interface de saisie de données,
- construire des tableaux de bord interactif avec une interface de saisie de donnée
- et bien plus.

## Cas

IMG

Liens :

https://ugolabo-ml-random-forests-st-01-modele-widb6v.streamlit.app/

https://toucan-fortune-streamlit-projet-integrateur-01-accueil-0fsbkp.streamlit.app/M%C3%A9triques

Machine Learning avec Random Forests sur Streamlit

Chaine: noeuds Raspberry Pi Pico (microcontrôleur et capteur) à Streamlit (tableau de bord) via MQTT et MongoDB Atlas (relié aux projets précédents))

## Équivalences

Il existe d'autres outils que Streamlit :

https://streamlit.io/ Streamlit
https://fastapi.tiangolo.com/ FastAPI

Le supra-module PyCaret de Machine Learning (il pilote entre autres Scikit-Learn, XGBoost, LightGBM, ???). PyCaret couvre les principales étapes du MLOps : pré-traitement des données, entrainement des modèles, analyse et affinage des modèles, prévisions, sauvagarde et déploiement du modèle. À la dernière étape, PyCaret automatise la construction d'une app avec FastAPI

https://pycaret.gitbook.io/docs/get-started/functions/deploy#create_api
FastAPI

PyCaret automatise aussi la construction d'une app Gradio

https://pycaret.gitbook.io/docs/get-started/functions/deploy#create_app
Gradio

ou d'un conteneur Docker

https://pycaret.gitbook.io/docs/get-started/functions/deploy#create_docker
Docker

PyCaret automatise même la publication du modèle et de l'app sur certains services cloud. Avec Streamlit, rien n'est automatisé.
