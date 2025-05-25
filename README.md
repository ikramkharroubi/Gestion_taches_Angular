# Gestionnaire de Tâches (Task Manager)



## 💻 Technologies Utilisées

### Frontend
- Angular 17
- TypeScript
- HTML5/CSS3
- Reactive Forms
- RxJS

### Backend
- Node.js
- Express.js


Une application web moderne de gestion de tâches développée avec Angular (frontend) et Node.js (backend).

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Angular](https://img.shields.io/badge/Angular-17.0.0-red.svg)
![Node.js](https://img.shields.io/badge/Node.js-18.0.0-green.svg)

## 🌟 Fonctionnalités

- ✅ Création, modification et suppression de tâches
- ✅ Filtrage des tâches (Toutes, Terminées, Non terminées)
- ✅ Interface utilisateur intuitive et responsive
- ✅ Double-clic pour éditer les tâches
- ✅ Validation des formulaires
- ✅ Gestion des erreurs
- ✅ API RESTful

## 🚀 Démarrage Rapide

### Prérequis

- Node.js (v18 ou supérieur)
- npm (v9 ou supérieur)
- Angular CLI (v17 ou supérieur)

### Installation

1. **Cloner le repository**
```bash
git clone https://github.com/votre-username/gestion-taches-angular.git
cd gestion-taches-angular
```

2. **Installer les dépendances du Frontend**
```bash
cd task-manager-frontend
npm install
```

3. **Installer les dépendances du Backend**
```bash
cd ../task-manager-backend
npm install
```

### Configuration

1. **Backend**
   - Créer un fichier `.env` dans le dossier `task-manager-backend`
   - Ajouter les variables d'environnement nécessaires :
   ```env
   PORT=3000
   MONGODB_URI=votre_uri_mongodb
   ```

2. **Frontend**
   - Créer un fichier `.env` dans le dossier `task-manager-frontend`
   - Configurer l'URL de l'API :
   ```env
   API_URL=http://localhost:3000
   ```

### Lancement

1. **Démarrer le Backend**
```bash
cd task-manager-backend
npm run start
```

2. **Démarrer le Frontend**
```bash
cd task-manager-frontend
ng serve
```

L'application sera accessible à l'adresse : `http://localhost:4200`

## 🛠️ Structure du Projet