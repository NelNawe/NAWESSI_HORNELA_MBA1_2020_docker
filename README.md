PROJET-DOCKER


* Description du projet

Le but du projet est de récupérer un projet APIREST et le deployer sur Docker pour qu'il soit opensource.Le cas de notre projet est une APIREST comportant 2 conteneurs (backend(Apirest) et frontend(react)).

*Préréquis 

Avoir un compte github ou le creer

installer Docker pour ubuntu, Docker Desktop pour windows et pour mac 

installer  powershell sur windows ou utiliser un terminal sur ubuntu

intaller postman pour tester l'API,

creer un compte en ligne sur mongodb pour la sauvegarde à distance des données

creer un compte sur Docker Hub  pour enregistrer nos images (frontend et Backend) sur le cloud publique de Docker

Générer une clé SSh 


*déploiement

 récupéré le code source de l'APIrest 
 
 creer un fichier  Dockerfile depuis notre editeur de code qui nous permettra de creeer une image pour lancer notre projet (Frontend et backend)
 
 creer un compte sur Mongodb pour sauvegarder à distance les données de nos utilisateurs(nom,adresse mail ...).Par cela , nous pourrions manager les différents comptes utilisateurs.
 
 creer un fichier Docker-compose.yml depuis notre éditeur de code ,celui çi nous permettra de lancer nos deux conteneurs(Backend et frontend) au meme moment
 
 lancer l'application sur postman pour se rassurer que notre api fonctionne normalement
 
 Creer ensuite notre compte sur docker hub qui est comme un cloud qui nous permettra de sauvegarder les images( image de frontend et backend) que nous avons buildé 
 
 



