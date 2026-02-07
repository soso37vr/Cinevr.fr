# 🎬 CINEVR.FR — Wiki officielle

Bienvenue sur la **wiki GitHub de CINEVR.FR**, une plateforme communautaire de **cinéma en réalité virtuelle** dédiée aux diffusions gratuites sur **Bigscreen VR**.

---

## 🚀 Présentation du projet

**CINEVR.FR** est un site web interactif permettant :

* d’annoncer et gérer des **diffusions de films en VR**,
* de **proposer des films** via la communauté,
* d’offrir une **interface immersive**, animée et personnalisable,
* de gérer l’ensemble via un **panel administrateur intégré**.

Le projet fonctionne **entièrement côté client** (aucun backend requis).

---

## 🧩 Technologies utilisées

* **HTML5**
* **CSS3 avancé** (variables CSS, animations, responsive design)
* **JavaScript (ES6)**
* **React 18 (via CDN)**
* **Babel Standalone**
* **Web Audio API** (sons et ambiance)
* **LocalStorage** (sauvegarde des données)

👉 Aucun framework serveur, aucune base de données externe.

---

## 🖥️ Fonctionnalités principales

### 🎥 Diffusions VR

* Affichage des films programmés
* Carte avec affiche + lecture vidéo au survol
* Date, heure et code Bigscreen affichés
* Stockage local des diffusions

### 👥 Propositions communautaires

* Formulaire public pour proposer un film
* Envoi stocké en attente de validation
* Gestion complète depuis l’admin

### 🔐 Espace administrateur

* Connexion par code secret
* Publication de films
* Suppression de diffusions
* Validation / rejet des propositions

⚠️ Le mot de passe admin est **en dur dans le code** (à modifier avant mise en production).

### 🎨 Personnalisation

* Plus de **30 thèmes** (sombres & clairs)
* Couleurs dynamiques via CSS variables
* Thème sauvegardé automatiquement

### 🔊 Ambiance sonore

* Son de clic interactif
* Fond sonore d’ambiance
* Contrôle du volume dans les paramètres

---

## 📁 Structure du projet

```
/
 └── cinevr.html   # Application complète (single file)
```

➡️ Tout est contenu dans un **seul fichier HTML**.

---

## ▶️ Installation & utilisation

1. Cloner le dépôt :

```bash
git clone https://github.com/votre-compte/cinevr.git
```

2. Ouvrir le fichier :

```bash
cinevr.html
```

3. Lancer simplement dans un navigateur moderne (Chrome, Edge, Firefox).

Aucun serveur requis 🎉

---

## 🛠️ Configuration admin

Dans le code JavaScript :

* Modifier le mot de passe admin
* Adapter les textes, services ou styles
* Ajouter vos propres règles de modération

---

## ⚠️ Limitations connues

* Pas de backend (données locales uniquement)
* Mot de passe visible dans le code
* Pas de gestion multi-utilisateur
* Vidéos uniquement via URL MP4 directe

➡️ Pour une version pro : backend recommandé (Firebase, Supabase, etc.)

---

## 📌 Objectif du projet

Créer une **plateforme VR communautaire**, simple à déployer, visuelle, immersive et accessible à tous les utilisateurs de Bigscreen VR.

---

## ❤️ Crédits

Projet développé par **CINEVR.FR**

Contributions et idées bienvenues 🚀

---

## 📄 Licence

© CINEVR.FR — Tous droits réservés.

Ce projet est **propriétaire**.

* Le code source est visible à des fins de consultation uniquement
* **Toute modification, réutilisation, redistribution ou exploitation** du code est **strictement interdite** sans autorisation explicite
* **Seul l’administrateur du projet** est autorisé à gérer, modifier et publier du contenu

Aucune contribution externe n’est acceptée.
