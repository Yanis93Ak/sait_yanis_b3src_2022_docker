# sait_yanis_b3src_2022_docker
Projet: Docker Bachelor 3ème année System, Réseau et Cloud. Edit 06/02/2022 by Yanis SAIT

# Description du projet :
L’objectifs de ce projet est d’intégrer le déploiement d’une API Rest avec Docker afin de pouvoir
l’intégrer dans un système d’intégration continue.  


## Résumé :
Nous allons utiliser "DOCKER COMPOSE" pour exécuter l'application multi-conteneurs. Puis grâce à docker-compose nous pourrons créer, démarrer tous les services de notre configuration et supprimer nos containers en une ligne de commande, que nous verrons ci-dessous

  
  
## Exigences :
Installer Docker Desktop en vous rendant ici : [Docker Desktop](https://www.docker.com/products/docker-desktop)  
Disposer d'une connexion Internet au moment de la création de l'image.  
Créer un compte si vous n'en avez pas : [Hub Docker](https://hub.docker.com/)  
  
  

### Mise en place et lancement de l'application :

- Ouvrir un terminal (CMD, Powershell, ou autre)
- Vérifier que vous possédez Docker Compose en effectuant la commande suivante: docker-compose -v
- Vous rendre dans le dossier contenant le fichier Docker-compose.yml
ex " cd .\Desktop\Projet Docker\"TEXTE*_docker",
- Exécuter la commande suivante afin de monter et de lancer le container : docker-compose up,
- Pour arréter un container vous pouvez exécuter simultanément CTRL-C,
- Vous avez pliusieurs container à Build ? Pas de problème Vous devez faire un "docker-compose up -d" en mode détaché, cela veut dire qu'il sera exécuté en baackground (arrière plan) et cela vous permez de pouvoir build un second conteneur une fois le premier installé.
- Une fois le conteneur lancé sans erreur il faut aller sur: http://localhost:7000 si bien évidemment vous n'avez pas changé les configurations sur le fichier docker-compose.yml
- Pour lancer le container il faut faire un "docker-compose start"
- Pour arréter le container "docker-compose stop"
- Et enfin pour le supprimer un "docker-compose down"


Enjoy :-)
Create by Yanis SAIT
