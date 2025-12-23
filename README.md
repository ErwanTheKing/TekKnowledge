# 🎓 TekKnowledge

**Plateforme d'apprentissage gamifiée pour les étudiants Epitech**

TekKnowledge est une plateforme interactive conçue pour accompagner les étudiants Epitech du niveau zéro à l'autonomie complète, en s'alignant sur la pédagogie Epitech basée sur les challenges, l'autonomie et les projets.

---

## 🎯 Objectifs

- **Accompagner l'étudiant** du zéro à l'autonomie
- **Coller à la pédagogie Epitech** : challenge, autonomie, projets
- **Créer une communauté Tek** authentique et engagée
- **Rendre l'entraînement flexible** et adapté à chaque profil
- **Motiver et gamifier** l'apprentissage pour créer de l'émulation
- **Valoriser les progrès** : CV, LinkedIn, portfolios
- **Rester utile** tout au long de la scolarité
- **Permettre l'apprentissage partout** : bus, campus, café...

---

## ✨ Fonctionnalités

### 1. 📊 Système de Progression
- **Barres de niveau** avec progression visuelle
- **Points d'expérience (XP)** gagnés après chaque recode et quiz
- **Système de badges** pour récompenser les accomplissements
- **Défis journaliers** pour maintenir la motivation

### 2. 👤 Espace Utilisateur Avancé
- **Historique complet** des recodes réalisés
- **Scores détaillés** des quiz effectués
- **Graphiques d'évolution** par compétence
- **Tableau de bord** : notions maîtrisées vs notions à revoir

### 3. 🎨 Création de Contenu par les Utilisateurs
- **Créer des quiz** personnalisés
- **Proposer des exercices** à la communauté
- **Challenger d'autres étudiants** sur des sujets spécifiques

### 4. ⏱️ Mode Examen
- Questions aléatoires en nombre configurable
- Chronomètre intégré
- Score final avec analyse détaillée des performances

### 5. 🏆 Classements Multiples
- Meilleurs scores globaux
- Plus de recodes réussis
- Utilisateurs les plus actifs
- Classements par domaine : **Réseau**, **Web**, **Algo**, **Cybersécurité**...

### 6. 🎁 Système de Récompenses & Boutique Virtuelle
- **TekPoints** : monnaie virtuelle de la plateforme
- **Customisation d'avatar** avec items cosmétiques
- **Badges spéciaux** pour accomplissements remarquables
- Boutique avec items purement esthétiques

---

## 🛠️ Stack Technique

### Frontend
- **React** avec **Next.js** (App Router)
- **TypeScript** pour la robustesse du code
- **HTML5** & **CSS3** pour l'interface
- **React Hook Form** pour la gestion des formulaires
- **Zod** pour la validation des données

### Backend
- **Next.js API Routes** pour les endpoints
- **PostgreSQL** comme base de données
- **Prisma** comme ORM

### Authentification & Sécurité
- **Auth.js** (NextAuth.js) pour l'authentification
- **OAuth** (GitHub, Google, etc.)
- **Credentials Provider** pour login/password
- **bcrypt** pour le hashage des mots de passe

### DevOps
- **Docker** pour la containerisation
- **Docker Compose** pour l'orchestration locale

---

## 🚀 Installation & Lancement

### Prérequis
- **Node.js** 18.x ou supérieur
- **Docker** & **Docker Compose**
- **npm** ou **yarn** ou **pnpm**

### Installation

```bash
# Cloner le repository
git clone https://github.com/votre-username/TekKnowledge.git
cd TekKnowledge

# Installer les dépendances
npm install

# Configurer les variables d'environnement
cp .env.example .env.local
# Éditer .env.local avec vos configurations

# Lancer la base de données avec Docker
docker-compose up -d

# Appliquer les migrations Prisma
npx prisma migrate dev

# Seed la base de données (optionnel)
npx prisma db seed

# Lancer le serveur de développement
npm run dev
```

L'application sera accessible sur [http://localhost:3000](http://localhost:3000)

