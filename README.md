# tp2-madhous-youssef

# Info

- Mail: youssef.madhous@ynov.com
- Github_username: Madhous

## Principe du Projet

- Création d'une infrastructure postgres en utilisant docker-compose.yml, nginx, nodejs

## Prérequis

- nginx
- nodjs

# Installation

- Cloner le repo

- Aller dans le dossier "tp2-madhous-youssef/docker" avec le terminal.

- Puis lancer:

```bash
npm install
cd docker/
docker-compose up
````

# Simple NodeJS API
- GET/API
```bash
{ "message": "Hello World" }
````
- GET/API/status
```bash
{
"status": "OK" ,
"postgresUptime": String ,
"redisConnectedClients": Number
}
````
En tapant sur http://localhost:10080 ca va se diriger vers le serveur node à l'écoute au port 10080.

## Vérification
- Pour vérifier, il faut lancer la commande:
```bash
docker ps
````
## Stopper
```bash
cd Docker
docker-compose down
````