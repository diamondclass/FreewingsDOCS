# Documentation du Bot Freewings

## Table des Matières
1. [Commencer](#commencer)
2. [Catégories de Commandes](#catégories-de-commandes)
3. [Commandes Publiques](#commandes-publiques)
4. [Systèmes de Sécurité](#systèmes-de-sécurité)
5. [Commandes de Configuration](#commandes-de-configuration)
6. [Support](#support)

---

## Commencer

Freewings est un bot Discord complet développé par [NearDevs](https://discord.gg/Sp9GTrmcQG) et **@diamondclass**. Le bot fournit des fonctionnalités de sécurité, modération, communauté, divertissement et utilitaires pour les serveurs Discord.

### Démarrage Rapide
1. Utilisez `/empezar` pour explorer toutes les fonctionnalités disponibles
2. Visitez le [Dashboard](https://www.freewingsbot.com) pour une configuration avancée
3. Utilisez les commandes `/setup` pour configurer les fonctionnalités du serveur (nécessite les permissions Administrateur)

---

## Catégories de Commandes

### 🏠 Accueil (Hogar)
- **`/empezar`** - Guide interactif pour explorer toutes les fonctionnalités du bot

### 🫂 Communauté (Comunidad)
- **`/user`** - Informations et gestion des utilisateurs
- **`/server`** - Informations et statistiques du serveur
- **`/channel`** - Informations et gestion des canaux
- **`/bot`** - Informations et statistiques du bot
- **`/traducir`** - Intégration Google Translate
- **`/seguir`** - Suivre les comptes de réseaux sociaux pour les notifications
- **`/sugerir`** - Soumettre des suggestions au canal configuré

### 🎮 Mini-jeux (Minijuegos)
- **`/ahorcado`** - Jeu du pendu avec plusieurs niveaux de difficulté
- **`/chess`** - Jeu d'échecs
- **`/osint`** - Jeu OSINT (Renseignement Open Source)

### 🙈 Amusement (Diversión)
- **`/8ball`** - Réponses de la boule magique 8
- **`/abrazo`** - Serrer quelqu'un dans ses bras
- **`/golpe`** - Action de frappe ludique
- **`/amor`** - Compatibilité amoureuse
- **`/beso`** - Embrasser quelqu'un
- **`/giveaway`** - Créer des tirages au sort
- **`/howgay`** - Calculatrice amusante de pourcentage gay

### 🔩 Configuration
- **`/setup`** - Configurer les fonctionnalités du serveur (Administrateur uniquement)

---

## Commandes Publiques

### `/empezar` - Commencer
**Description :** Guide interactif pour explorer toutes les fonctionnalités de Freewings
**Usage :** `/empezar`
**Fonctionnalités :**
- Système de menu interactif
- Exploration des commandes par catégories
- Statistiques du bot en temps réel
- Liens directs vers le dashboard

### `/user` - Informations Utilisateur
**Description :** Informations et gestion complètes des utilisateurs
**Sous-commandes :**
- **`info`** - Informations complètes de l'utilisateur incluant badges, date d'adhésion, rôles
- **`avatar`** - Afficher l'avatar de l'utilisateur en haute résolution
- **`banner`** - Afficher la bannière de l'utilisateur (si disponible)
- **`roles`** - Lister tous les rôles de l'utilisateur sur le serveur
- **`permissions`** - Afficher les permissions clés de l'utilisateur

**Exemples d'Usage :**
```
/user info @utilisateur
/user avatar
/user banner @utilisateur
/user roles @utilisateur
/user permissions @utilisateur
```

### `/server` - Informations du Serveur
**Description :** Statistiques et informations du serveur
**Sous-commandes :**
- **`info`** - Informations générales du serveur
- **`stats`** - Statistiques détaillées du serveur
- **`icon`** - Icône du serveur
- **`banner`** - Bannière du serveur
- **`boosts`** - Informations des boosts

### `/channel` - Gestion des Canaux
**Description :** Informations des canaux et outils de gestion
**Sous-commandes :**
- **`info`** - Informations complètes du canal
- **`permissions`** - Aperçu des permissions du canal
- **`roles`** - Rôles ayant accès au canal
- **`nuke`** - Effacer tous les messages (Administrateur uniquement)

### `/bot` - Informations du Bot
**Description :** Informations techniques sur Freewings
**Sous-commandes :**
- **`info`** - Informations générales du bot incluant uptime, latence, nombre de serveurs
- **`icon`** - Avatar du bot

### `/traducir` - Traduction
**Description :** Traduire du texte en utilisant Google Translate
**Usage :** `/traducir`
**Fonctionnalités :**
- Interface modale interactive
- Support pour plusieurs langues (en, fr, de, it, etc.)
- Résultats de traduction instantanés
- Gestion d'erreurs pour les langues invalides

### `/seguir` - Notifications des Réseaux Sociaux
**Description :** Suivre les comptes de réseaux sociaux pour des notifications automatiques
**Plateformes Supportées :**
- Chaînes YouTube
- Comptes Twitter
- Streams Twitch
- Streams Kick
**Fonctionnalités :**
- Notifications automatiques dans le canal choisi
- Mises à jour en temps réel
- Support pour plusieurs plateformes

### `/sugerir` - Suggestions
**Description :** Soumettre des suggestions au canal de suggestions configuré
**Fonctionnalités :**
- Création automatique de fils pour la discussion
- Boutons de validation pour les administrateurs
- Gestion organisée des suggestions

### `/ahorcado` - Jeu du Pendu
**Description :** Jeu classique du pendu avec une vaste base de données de mots
**Niveaux de Difficulté :**
- 🟢 **Facile** - Jusqu'à 6 lettres
- 🟡 **Moyen** - 7-10 lettres
- 🔴 **Difficile** - Plus de 10 lettres
- 🎲 **Aléatoire** - N'importe quelle difficulté

**Fonctionnalités :**
- 8 catégories : Technologie, Programmation, Science, Nature, Animaux, Sports, Culture, Géographie, Alimentation
- Affichage interactif de l'alphabet
- Suivi des statistiques (précision, efficacité, temps)
- Devinette de mots et de lettres
- Progression visuelle du pendu

**Usage :** `/ahorcado [difficulté]`

### `/chess` - Jeu d'Échecs
**Description :** Jouer aux échecs avec d'autres utilisateurs
**Fonctionnalités :**
- Implémentation complète des échecs
- Jeu au tour par tour
- Validation des mouvements

### `/osint` - Jeu OSINT
**Description :** Jeu d'enquête de Renseignement Open Source
**Fonctionnalités :**
- Défis d'investigation
- Contenu éducatif sur les techniques OSINT

### `/8ball` - Boule Magique 8
**Description :** Posez une question à la boule magique 8
**Usage :** `/8ball [question]`
**Fonctionnalités :**
- 20 réponses différentes en espagnol
- Génération de réponses aléatoires
- Interaction amusante pour prendre des décisions

### Commandes d'Amusement
- **`/abrazo [utilisateur]`** - Envoyer un câlin à quelqu'un
- **`/golpe [utilisateur]`** - Action de frappe ludique
- **`/amor [utilisateur1] [utilisateur2]`** - Calculer la compatibilité amoureuse
- **`/beso [utilisateur]`** - Envoyer un baiser à quelqu'un
- **`/howgay [utilisateur]`** - Calculatrice amusante de pourcentage gay
- **`/giveaway`** - Créer et gérer des tirages au sort

---

## Systèmes de Sécurité

Freewings inclut des fonctionnalités de sécurité complètes (configurées via `/setup` ou dashboard) :

### Systèmes Anti-Spam
- **Protection anti-ban** - Prévient les bannissements massifs
- **Protection anti-bot** - Bloque les ajouts suspects de bots
- **Anti-spam de canaux** - Prévient le spam de création/suppression de canaux
- **Anti-spam de rôles** - Protège contre la manipulation de rôles
- **Anti-spam de webhooks** - Prévient l'abus de webhooks
- **Protection anti-kick** - Bloque les expulsions massives
- **Anti-NSFW** - Filtrage de contenu
- **Anti-liens** - Filtrage et protection des liens
- **Détection de ghost ping** - Détecte et enregistre les ghost pings

### Systèmes de Surveillance
- **Permissions d'audit log** - Suivre les changements de permissions
- **Alertes du propriétaire** - Notifier les propriétaires du serveur d'activités suspectes
- **Détection de rôles massifs** - Surveiller les changements massifs de rôles
- **Surveillance d'applications client** - Suivre l'utilisation des applications

---

## Commandes de Configuration

### `/setup` - Configuration du Serveur
**Permission Requise :** Administrateur

**Sous-commandes :**

#### `/setup autoroles`
Configurer l'attribution automatique de rôles pour les nouveaux membres
- **`agregar [rôle]`** - Ajouter un rôle à la liste d'auto-attribution
- **`eliminar [rôle]`** - Retirer un rôle de la liste d'auto-attribution
- **`listar`** - Lister tous les auto-rôles configurés

#### `/setup logs`
Configurer le système de journalisation du serveur
- **`activar [canal]`** - Activer les logs dans le canal spécifié
- **`desactivar`** - Désactiver le système de journalisation
- Sélection interactive d'événements (événements de canal, événements de rôle, événements de membre, événements de message, événements de webhook)

#### `/setup sugerencias`
Configurer le système de suggestions
- **`[canal]`** - Définir le canal pour les suggestions

#### `/setup reactionroles`
Créer des systèmes de reaction roles
- Création interactive d'embeds
- Titre, description et couleur personnalisés
- Attribution de rôles via réactions

#### `/setup whitelist`
Gérer les utilisateurs et rôles autorisés
- **`add user/role [cible]`** - Ajouter à la whitelist (Propriétaire uniquement)
- **`remove user/role [cible]`** - Retirer de la whitelist (Propriétaire uniquement)
- **`list user/role [page]`** - Lister les éléments en whitelist

#### `/setup badwords`
Gérer le filtre de gros mots
- **`activar`** - Activer le filtre de gros mots
- **`desactivar`** - Désactiver le filtre de gros mots
- **`agregar [mot]`** - Ajouter un mot à la liste noire
- **`quitar [mot]`** - Retirer un mot de la liste noire
- **`listar`** - Lister tous les mots en liste noire

#### `/setup welcome`
Configurer le système de bienvenue (Dashboard uniquement)
- Redirige vers le dashboard web pour la configuration

---

## Support

- **Dashboard :** [https://www.freewingsbot.com](https://www.freewingsbot.com)
- **Communauté des Développeurs :** [Discord NearDevs](https://discord.gg/Sp9GTrmcQG)
- **Développeur Principal :** @diamondclass
- **Copyright :** Freewings © 2025
