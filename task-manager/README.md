# Task Manager

Application web full-stack de gestion de tâches, développée avec React, Node.js, Express et MySQL.

🔗 **Demo live** : https://69f078000d9e9dd70f7c4daa--task-managerok.netlify.app/

---

## Fonctionnalités

- Ajouter, supprimer et cocher des tâches
- Barre de progression en temps réel
- Données persistées en base de données MySQL
- Interface responsive et moderne

---

## Stack technique

| Côté | Technologies |
|------|-------------|
| Front-end | React, Vite, Tailwind CSS |
| Back-end | Node.js, Express |
| Base de données | MySQL |
| Déploiement | Netlify (front), Render (back), Railway (BDD) |

---

## Architecture

React (Netlify) → API REST Express (Render) → MySQL (Railway)

---

## Lancer le projet en local

**Front-end**
```bash
cd task-manager
npm install
npm run dev
```

**Back-end**
```bash
cd task-manager-api
npm install
node index.js
```

Créer un fichier `.env` dans `task-manager-api` :

DB_HOST=localhost
DB_USER=root
DB_PASSWORD=tonmotdepasse
DB_NAME=taskmanager
PORT=3001

---

## API Endpoints

| Méthode | Route | Description |
|---------|-------|-------------|
| GET | /taches | Récupérer toutes les tâches |
| POST | /taches | Créer une tâche |
| PUT | /taches/:id | Modifier une tâche |
| DELETE | /taches/:id | Supprimer une tâche |
| DELETE | /taches | Supprimer toutes les tâches |

---

## Auteur

**Okan Gucuko** — [LinkedIn](https://linkedin.com/in/okan-gucuko) · [Portfolio](https://okan-guc-portfolio.netlify.app)
