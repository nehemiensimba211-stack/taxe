# Application web de collecte de taxes pour une commune

Ce projet open source permet la gestion et la collecte des taxes dans une commune avec une interface moderne et sécurisée.

## Technologies utilisées
- **Front-end** : React.js, HTML5, CSS3, JavaScript
- **Back-end** : Node.js, Express.js
- **Base de données** : MongoDB
- **Authentification** : JWT, rôles (admin, agent)

## Fonctionnalités principales
1. Authentification sécurisée (admin, agents)
2. Gestion des contribuables (CRUD)
3. Suivi des taxes par contribuable
4. Tableau de bord statistiques (montant collecté, impayés, rapport mensuel)
5. Export PDF et Excel des rapports
6. Notifications e-mail (optionnel)
7. Interface responsive mobile/desktop
8. UI claire et intuitive type dashboard

## Installation rapide

1. **Cloner le projet**
   ```bash
   git clone <url-du-repo>
   cd taxeapp
   ```
2. **Installer les dépendances**
   ```bash
   npm install
   cd client
   npm install
   ```
3. **Configurer la base de données**
   - Créer un fichier `.env` à la racine avec :
     ```env
     MONGO_URI=mongodb://localhost:27017/taxeapp
     JWT_SECRET=VotreSecret
     EMAIL_USER=VotreEmail (optionnel)
     EMAIL_PASS=MotDePasseEmail (optionnel)
     ```
4. **Lancer le serveur**
   ```bash
   npm run dev
   ```
5. **Lancer le front-end**
   ```bash
   cd client
   npm start
   ```

## Structure du projet
- `/client` : Front-end React
- `/server` : Back-end Node.js/Express
- `/models` : Schémas MongoDB
- `/routes` : API REST
- `/controllers` : Logique métier
- `/utils` : Fonctions utilitaires (PDF, Excel, email)

## Contribution
Code commenté, structuré et prêt pour l’open source. Les PR sont les bienvenues !

---

Pour toute question, consultez la documentation ou ouvrez une issue sur le dépôt GitHub.
