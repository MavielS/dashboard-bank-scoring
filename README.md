Ce repo constitue la **frontend et backend** du dashboard interactif construit dans le cadre d'un projet de scoring bancaire. <br>
La partie entrainement et interprétation est disponible sur mon github [ici](https://github.com/MavielS/modele-de-scoring-bancaire). <br>

<p align='center';">
  <b>Retrouvez le résultat final
    <a href="https://bank-scoring-ui.herokuapp.com/">ici</a> ! </br>
  </b>
  <i>(Le chargement de la page peut prendre jusqu'à 30s si le serveur n'a pas été utilisé depuis un moment.)</i>
</p> 
<p align='center';">
  <b>Retrouvez
    <a href="https://youtu.be/flV-HBf5Hdw">ici une présentation vidéo du dashboard</a> ! </br>
  </b>
</p> 
                                                    


# Présentation du projet 

Ce projet constitue le [projet n°7](https://openclassrooms.com/fr/paths/164/projects/632/assignment) de ma formation Data Scientist. <br> <br>
![](https://github.com/MavielS/modele-de-scoring-bancaire/blob/main/in_a_nutshell.jpg)


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

Pour visiter la documentation du service résultant est disponible à l'adresse http://localhost:8080.  
L'interface streamlit est disponible à l'adresse  http://localhost:8501.

Pour voir les logs:

    docker-compose logs



