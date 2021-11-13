Ce repo constitue la **frontend et backend** du dashboard interactif construit dans le cadre d'un projet de scoring bancaire. <br>
La partie entrainement et interprétation est disponible sur mon github [ici](https://github.com/MavielS/modele-de-scoring-bancaire). <br>

<p align='center';">
  <b>Retrouvez le résultat final
    <a href="https://bank-scoring-api.herokuapp.com/">ici</a> ! </br>
  </b>
  <i>(Le chargement de la page peut prendre jusqu'à 30s si le serveur n'a pas été utilisé depuis un moment.)</i>
</p> 


# Présentation du projet 

Ce projet constitue le [projet n°7](https://openclassrooms.com/fr/paths/164/projects/632/assignment) de ma formation Data Scientist. <br>
L'objectif était de développer pour la société « Prêt à Dépenser », une société de crédit de consommation, un modèle de scoring de la probabilité de défaut de paiement d’un client avec pas ou peu d’historique de prêt.<br> <br>

Par la suite, j'ai pu déployer ce modèle sous forme d'une API exploitée par une interface web interactive.

# Fichiers disponibles

Vous pouvez trouver ici:
1. Le dossier frontend: il contient le code pour le dashboard streamlit ainsi que le dockerfile associé.
2. Le dossier backend: il contient le code pour l'API FastAPI ainsi que le dockerfile associé.
3. Un fichier docker-compose permettant un déploiement rapide.

![alt text](https://github.com/MavielS/dashboard-bank-scoring/blob/main/archi.PNG)

# Execution en local

Si vous souhaitez exécuter ce projet en local dans un conteneur docker, exécutez:

    docker-compose build
    docker-compose up

Pour visiter la documentation du service résultant est disponible à l'adresse http://localhost:8000.  
L'interface streamlit est disponible à l'adresse  http://localhost:8501.

Pour voir les logs:

    docker-compose logs



