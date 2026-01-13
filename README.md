# Projet Microservices - Docker

## Exercice 3 : Commandes Docker

1. Construire les images Docker :
`docker-compose build`

2. Lancer tous les services :
`docker-compose up -d`

3. Vérifier que les conteneurs sont en cours d'exécution :
`docker ps`

4. Arrêter tous les services :
`docker-compose down`

## Bonus

L'avantage principal de docker-compose dans une architecture microservices est la gestion centralisée. Il permet de définir et de déployer l'ensemble de l'infrastructure (réseaux, volumes, et dépendances entre services) via un seul fichier de configuration, ce qui garantit un environnement de développement reproductible et simplifie la communication interne entre les différents microservices.
