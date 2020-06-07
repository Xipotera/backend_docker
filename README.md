Backend docker
-

Ce projet est créé pour aider à apprendre les configurations de docker pour les projets backend.

## Pré-requis

Installez [node](https://nodejs.org/en/download/). 

Exemple d'instructions d'installation de `node LTS 14.x`:

```
curl -sL https://deb.nodesource.com/setup_14.x | bash
sudo apt install -y nodejs
```

Installez tous les packages avec `npm install`


## Démarrage en mode production

Les éléments suivants sont nécessaires à partir de l'exercice 5. Notez que toutes les informations ne sont pas nécessaires dans tous les exercices.

## Exo 6 -> pour exécuter le projet

Pour démarrer le serveur en mode production: `npm start`

Testez que le projet est en cours d'exécution en allant sur <http://localhost:8000>

## Exo 7 -> accepter les connexions

Si votre interface ne s'exécute pas dans la même origine, exécutez le serveur avec `FRONT_URL=<front-url> npm start` (sans <>) pour autoriser les demandes cross-origin.
