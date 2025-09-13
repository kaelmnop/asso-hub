# Dashboard Asso

Projet découverte onRails: tableau de bord pour associations culturelles.  
Permet la gestion des membres, de l'agenda, des fichiers, des projets, de la trésorerie, etc.

## Stack
- **Backend** : Ruby on Rails 8 (API) + PostgreSQL  
- **Frontend** : React (Vite, TypeScript)  
- **UI** : MUI (et Tailwind plus tard)

## Installation et lancement

### Backend (API Rails)
```bash
cd api
bin/rails db:create db:migrate
bin/rails s
```

Accessible sur http://localhost:3000

### Frontend (React)
```bash
cd web
npm install
npm run dev
```

Accessible sur http://localhost:5173
