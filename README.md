<p align="center">
  <img src="docs/images/logo.png" alt="Logo Djahiri" width="120" style="border-radius: 20px;" />
</p>

<p align="center">
  Plateforme mobile et web de signalement d’incivilités urbaines.
</p>

## Table des matières

- [Présentation](##présentation)
- [Fonctionnalités principales](##fonctionnalités_principaless)
- [Interfaces de l’application](##️interfaces-de-lapplication)
- [Technologies utilisées](##technologies-utilisées)
- [Architecture](##architecture)
- [Installation et utilisation](#installation-et-utilisation)
- [Auteurs](##auteurs)

## 🌍 Présentation

<img src="docs\img\captures\LandingPage.png" alt="Logo Djahiri" width="620" style="border-radius: 2px;" />

Djahiri est une plateforme mobile et web de signalement d’incivilités urbaines, pensée pour encourager la participation citoyenne et améliorer le cadre de vie.

L’application permet aux citoyens de signaler facilement des problèmes observés dans leur environnement, comme les dépôts sauvages, les problèmes de propreté, les dégradations ou les anomalies de voirie, à l’aide d’une photo, d’une description et d’une géolocalisation.

Au-delà du simple signalement, Djahiri valorise l’engagement citoyen grâce à un système de points, de badges et de suivi des signalements. Chaque contribution devient ainsi visible, mesurable et reconnue.

Le projet propose également un espace d’administration permettant de consulter, modérer, valider ou rejeter les signalements envoyés par les citoyens.

Des livrables sont disponibles dans le dossier "Livrables" afin d'approfondir la compréhension du projet :

- Livrable 1 : <a href="Livrables/Livrable 1_projet master_Yves Roland DEBO_Zakariae BOUAMAMA.pdf" target="_blank">[Description du projet, planing et cahier des charges]</a>

- Livrable 2 : <a href="Livrables/livrable 2___Rapport_d_avancement___projet_master.pdf" target="_blank">[Conception et réalisation du projet]</a>

- Rapport final : <a href="Livrables/livrable final___projet_master___Yves Roland_Zakariae.pdf" target="_blank">[Rapport final du projet faisant la somme de toutes les analyses et réalisations]</a>


## 🧩 Fonctionnalités principales

Djahiri propose un ensemble de fonctionnalités permettant aux citoyens de signaler, suivre et valoriser leurs actions en faveur de l’amélioration du cadre de vie urbain.

### 📸 Signalement d’incivilités
<p align="center">
<img src="docs\img\captures\signaler.png" alt="Logo Djahiri" width="520" style="border-radius: 2px;" /></p>

- Création d’un signalement avec photo
- Ajout d’une description
- Géolocalisation automatique du lieu
- Sélection du type de problème : propreté, voirie, dégradation, sécurité, etc.
- Envoi du signalement avec un statut initial **En attente**

### 📰 Fil d’actualité

- Consultation des signalements publiés
- Affichage des photos, descriptions, lieux, dates et statuts
- Réactions de soutien aux signalements
- Consultation et ajout de commentaires

### 👤 Espace utilisateur

- Inscription et connexion sécurisée
- Consultation du profil utilisateur
- Suivi des signalements envoyés
- Filtrage des signalements par statut : **Validé**, **Rejeté**, **En attente**, **Résolu**
- Consultation des points et badges obtenus

### 🎯 Gamification

- Attribution de points après validation d’un signalement
- Déblocage de badges selon l’activité de l’utilisateur
- Valorisation de l’engagement citoyen
- Suivi du niveau de participation

### 🔔 Notifications

- Notification lors du changement de statut d’un signalement
- Notification en cas de validation ou de rejet
- Notification lors de l’obtention d’un badge

### 🛠️ Administration et modération

- Consultation des signalements envoyés par les citoyens
- Vérification des signalements
- Validation ou rejet avec motif
- Suivi des incidents urbains depuis un panel d’administration








## 🖥️ Interfaces de l’application

### Landing page
<p align="center">
<img src="docs\img\captures\LandingPage.png" alt="Logo Djahiri" width="620" style="border-radius: 2px;" /></p>

### Dashboard Admin
<p align="center">
<img src="docs\img\captures\admin_dashboard.png" alt="Logo Djahiri" width="620" style="border-radius: 2px;" /></p>

### Page de modération
<p align="center">
<img src="docs\img\captures\admin_moderation.png" alt="Logo Djahiri" width="620" style="border-radius: 2px;" /></p>

<p align="center">
<img src="docs\img\captures\admin_validation.png" alt="Logo Djahiri" width="620" style="border-radius: 2px;" /></p>

### Dashboard utilisateur
<p align="center">
<img src="docs\img\captures\user_dashboard.png" alt="Logo Djahiri" width="620" style="border-radius: 2px;" /></p>

### Profil utilisateur
<p align="center">
<img src="docs\img\captures\profil.png" alt="Logo Djahiri" width="620" style="border-radius: 2px;" /></p>


## Technologies utilisées


## Architecture

### Architecture Logicielle
<p align="center">
<img src="docs\img\Architecture Logicielle.png" alt="Logo Djahiri" width="620" style="border-radius: 2px;" /></p>

### Structure de la base de données
<p align="center">
<img src="docs\img\DB_modelisation.png" alt="Logo Djahiri" width="620" style="border-radius: 2px;" /></p>

### Architecture Techniques du Backend
<p align="center">
<img src="docs\img\archi hexago.png" alt="Logo Djahiri" width="620" style="border-radius: 2px;" /></p>

### Stratégie de déploiement
<p align="center">
<img src="docs\img\devops.png" alt="Logo Djahiri" width="620" style="border-radius: 2px;" /></p>


## installation et utilisation

Le projet est déployé sur un serveur accessible à l'adresse suivante :

- Interface web : https://stg.djahiri.ci/
- Api : https://stg-api.djahiri.ci/swagger-ui/index.html#/

Vous pouvez donc tester l'application via l'interface web ou via l'application mobile.

Pour vous connecter, utilisez les identifiants suivants :

Pour l'admin :
- Email : admin2@admin.com
- Mot de passe : password

Pour l'utilisateur :
- Email : yvesrolanddebo@gmail.com
- Mot de passe : password

Ou en créant un nouveau compte.

### 1. Télécharger l'apk
Dézipper le fichier .zip puis installer l'apk depuis un téléphone android ou un emulateur android :
<a href="executables\djahiri.apk">Accéder à l'apk ici</a>

### 2. Utilisation

Une fois connecté, vous pouvez:
 - En tant qu'utilisateur, effectuer un signalement en cliquant sur le bouton "Signaler" en bas.
 - En tant qu'admin, modérer les signalements en cliquant sur le lien "Signalements" dans le menu en haut à gauche.

## Auteurs

Ce projet a été réalisé par : 

- Yves Roland Dago DEBO
- Zakariae BOUAMAMA

Année académique : 2025-2026
Master 2 Cyber
Université Catholique de Lille