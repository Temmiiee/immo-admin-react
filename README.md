# Immo Admin React

Immo Admin React est une application React + Vite conçue pour gérer les différents biens immobiliers mis en vente.

## Fonctionnalités

- Gestion des biens immobiliers.
- Récupération des informations depuis l'API à l'adresse [localhost:8081/api](http://localhost:8081/api).
- Interface utilisateur développée avec React et Vite.

## Prérequis

Assurez-vous d'avoir installé [Docker](https://www.docker.com/) sur votre machine avant de lancer l'application.

## Installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/Temmiiee/immo-admin-react
   
2. Accédez au répertoire du projet :
   ```bash
   cd immo-admin-react

3. Lancez le docker-compose pour démarrer l'application :
   ```bash
   docker-compose up

L'application sera accessible à l'adresse localhost:3000.

## Configuration

L'application est configurée pour récupérer les données depuis l'API à l'adresse localhost:8081/api. 
Veuillez vous assurer que l'API est correctement configurée et accessible.
Sinon, il est possible de modifier l'adresse de l'API depuis le fichier .env.

## Plugins utilisés

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
