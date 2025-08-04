# Freewings Bot - Documentation Française

## Table des Matières
1. [Premiers Pas](#premiers-pas)
2. [Catégories de Commandes](#catégories-de-commandes)
3. [Commandes Publiques](#commandes-publiques)
4. [Systèmes de Sécurité](#systèmes-de-sécurité)
5. [Commandes de Configuration](#commandes-de-configuration)
6. [Support](#support)

---

## Premiers Pas

Freewings est un bot Discord complet développé par [Citymoon Dynamics](https://discord.gg/Sp9GTrmcQG) et **@diamondclass**. Le bot fournit des fonctionnalités de sécurité, modération, communauté, divertissement et utilitaires pour les serveurs Discord.

### Démarrage Rapide
1. Utilisez `/empezar` pour explorer toutes les fonctionnalités disponibles
2. Visitez le [Dashboard](https://www.freewingsbot.com) pour une configuration avancée
3. Utilisez les commandes `/setup` pour configurer les fonctionnalités du serveur (nécessite des permissions Administrateur)

---

## Catégories de Commandes

### 🏠 Accueil
- **`/empezar`** - Guide interactif pour explorer toutes les fonctionnalités du bot

### 🫂 Communauté
- **`/user`** - Informations et gestion des utilisateurs
- **`/server`** - Informations et statistiques du serveur
- **`/channel`** - Informations et gestion des canaux
- **`/bot`** - Informations et statistiques du bot
- **`/traducir`** - Intégration Google Translate
- **`/seguir`** - Suivre les comptes de réseaux sociaux pour les notifications
- **`/sugerir`** - Soumettre des suggestions au canal configuré

### 🎮 Mini-jeux
- **`/ahorcado`** - Jeu du pendu avec plusieurs niveaux de difficulté
- **`/chess`** - Jeu d'échecs
- **`/osint`** - Jeu OSINT (Open Source Intelligence)

### 🙈 Amusement
- **`/8ball`** - Réponses de la boule magique 8
- **`/abrazo`** - Faire un câlin à quelqu'un
- **`/golpe`** - Action de frappe ludique
- **`/amor`** - Compatibilité amoureuse
- **`/beso`** - Embrasser quelqu'un
- **`/howgay`** - Calculateur amusant de pourcentage gay
- **`/giveaway`** - Créer et gérer des concours

### 🎵 Musique
- **`/play`** - Jouer de la musique depuis diverses sources
- **`/pause`** - Mettre en pause la lecture actuelle
- **`/resume`** - Reprendre la lecture en pause
- **`/stop`** - Arrêter la lecture et vider la file d'attente
- **`/skip`** - Passer la chanson actuelle
- **`/queue`** - Afficher la file d'attente actuelle
- **`/nowplaying`** - Afficher la chanson en cours de lecture
- **`/volume`** - Ajuster le volume de lecture
- **`/shuffle`** - Mélanger la file d'attente
- **`/loop`** - Basculer le mode boucle
- **`/clear`** - Vider la file d'attente de lecture
- **`/remove`** - Supprimer une chanson spécifique de la file d'attente

### 🛡️ Sécurité
- **`/antilinks`** - Système de protection anti-liens
- **`/antibot`** - Protection contre les bots non autorisés
- **`/antiban`** - Protection contre les bannissements massifs
- **`/antikick`** - Protection contre les expulsions massives
- **`/antichannels`** - Protection contre la création massive de canaux
- **`/antirole`** - Protection contre la création massive de rôles
- **`/antiwebhookcreate`** - Protection contre la création de webhooks
- **`/antiwebhookspam`** - Protection contre le spam de webhooks
- **`/antinsfw`** - Filtre de contenu NSFW
- **`/anticlientapp`** - Protection contre les applications client modifiées
- **`/ghostping`** - Détection de ghost ping
- **`/massrole`** - Protection contre l'attribution massive de rôles
- **`/estado`** - État de tous les systèmes de sécurité
- **`/owneralerts`** - Système d'alertes du propriétaire

### 🔨 Modération
- **`/ban`** - Bannir des utilisateurs
- **`/kick`** - Expulser des utilisateurs
- **`/timeout`** - Mettre en timeout des utilisateurs
- **`/purge`** - Effacer des messages
- **`/historial`** - Voir l'historique des sanctions
- **`/notas`** - Système de notes de modération

### 🎫 Tickets
- **`/ticket create`** - Créer un nouveau ticket
- **`/ticket claim`** - Réclamer un ticket existant
- **`/ticket rename [nom]`** - Renommer le ticket actuel
- **`/ticket adduser [utilisateur]`** - Ajouter un utilisateur au ticket
- **`/ticket removeuser [utilisateur]`** - Retirer un utilisateur du ticket
- **`/ticket done`** - Fermer le ticket
- **`/ticket setup`** - Configuration interactive du système de tickets
- **`/ticket updatepanel`** - Mettre à jour le panneau de tickets
- **`/ticket setlimit [limite]`** - Définir la limite de tickets par utilisateur

### ⚙️ Configuration
- **`/setup`** - Commande principale de configuration avec diverses sous-commandes pour la configuration du serveur

---

## Commandes Publiques

### Commandes de Communauté

#### `/user [utilisateur]`
Afficher des informations détaillées sur l'utilisateur
- **Sous-commandes:**
  - `info` - Informations complètes de l'utilisateur
  - `avatar` - Avatar de l'utilisateur
  - `banner` - Bannière de l'utilisateur
  - `roles` - Rôles de l'utilisateur
  - `permissions` - Permissions de l'utilisateur
- Inclut badges, statut d'activité et navigation interactive

#### `/server`
Informations et statistiques du serveur
- **Sous-commandes:**
  - `info` - Informations générales du serveur
  - `stats` - Statistiques détaillées
  - `icon` - Icône du serveur
  - `banner` - Bannière du serveur
  - `boosts` - Informations de boost
- Inclut statistiques en temps réel et fonctionnalités spéciales

#### `/channel [canal]`
Informations et gestion des canaux
- **Sous-commandes:**
  - `info` - Informations complètes du canal
  - `permissions` - Voir les permissions du canal
  - `roles` - Rôles avec accès au canal
  - `nuke` - Nettoyer complètement le canal
- ⚠️ **Nuke** nécessite des permissions d'administrateur et supprime TOUS les messages

#### `/bot`
Informations et statistiques du bot
- **Sous-commandes:**
  - `info` - Informations générales du bot
  - `icon` - Icône du bot
- Inclut statistiques de serveurs, utilisateurs, latence et utilisation mémoire

#### `/traducir [texte] [langue_cible]`
Traduire du texte avec Google Translate
- Modal interactif pour traduire n'importe quel texte
- Support de plusieurs langues (en, fr, de, it, etc.)
- Auto-détection de la langue source
- Traduction instantanée et précise

#### `/seguir`
Activer les notifications pour les nouvelles publications
- Suivre les chaînes YouTube, Twitter, Twitch et Kick
- Notifications automatiques dans votre canal choisi
- Garder votre communauté à jour

#### `/sugerir`
Soumettre des suggestions au canal configuré
- Système de suggestions avec boutons de validation
- Création automatique de fils pour discussion
- Modération par les administrateurs

### Commandes de Divertissement

#### `/8ball [question]`
Obtenir des réponses mystiques à vos questions
- Réponses aléatoires
- Amusant et divertissant
- Expérience classique de boule magique 8

#### `/ahorcado [difficulté]`
Jouer au jeu du pendu
- Plusieurs niveaux de difficulté
- Catégories de mots
- Gameplay interactif

#### `/chess [adversaire]`
Jouer aux échecs avec d'autres utilisateurs
- Implémentation complète des échecs
- Gameplay au tour par tour
- Validation des mouvements

#### `/osint [difficulté]`
Jeu OSINT (Open Source Intelligence)
- Éducatif et amusant
- Plusieurs niveaux de difficulté
- Apprendre les techniques d'investigation

#### `/amor [utilisateur1] [utilisateur2]`
Calculer la compatibilité amoureuse entre utilisateurs
- Algorithme de compatibilité
- Résultats amusants et détaillés

#### `/abrazo [utilisateur]`
Faire un câlin à quelqu'un
- Animations et messages personnalisés
- Interaction sociale amusante

#### `/beso [utilisateur]`
Embrasser quelqu'un
- Animations et messages personnalisés
- Interaction sociale amusante

#### `/golpe [utilisateur]`
Frapper ludiquement quelqu'un
- Animations et messages personnalisés
- Interaction sociale amusante

#### `/howgay [utilisateur]`
Calculateur amusant de pourcentage gay
- Résultats aléatoires et amusants
- Aucune intention offensante

#### `/giveaway`
Créer et gérer des concours
- Système complet de concours
- Configuration de prix et durée
- Sélection automatique des gagnants

### Commandes de Musique

#### `/play [chanson/url]`
Jouer de la musique depuis diverses sources
- Support YouTube, Spotify, SoundCloud
- Gestion de file d'attente
- Audio de haute qualité

#### `/search [terme]`
Rechercher des chansons sur YouTube
- Résultats interactifs
- Sélection multiple de chansons

#### `/pause`
Mettre en pause la lecture actuelle

#### `/resume`
Reprendre la lecture en pause

#### `/stop`
Arrêter la lecture et vider la file d'attente

#### `/skip`
Passer la chanson actuelle

#### `/queue`
Afficher la file d'attente musicale actuelle
- Liste des chansons avec durées
- Indicateurs de position dans la file
- Temps total de la file d'attente

#### `/nowplaying`
Afficher la chanson en cours de lecture
- Informations et progression de la chanson
- Miniature et durée
- Informations du demandeur

#### `/volume [niveau]`
Ajuster le volume de lecture (0-100)

#### `/shuffle`
Mélanger la file d'attente

#### `/loop`
Basculer le mode boucle

#### `/clear`
Vider la file d'attente de lecture

#### `/remove [position]`
Supprimer une chanson spécifique de la file d'attente

---

## Systèmes de Sécurité

### Protection Anti-Liens (`/antilinks`)
- Seul le propriétaire du serveur peut configurer
- Sanctionne automatiquement les utilisateurs qui envoient des liens non autorisés
- Système de confirmation pour activer/désactiver

### Protection Anti-Bot (`/antibot`)
- Détecte et prévient l'entrée de bots non autorisés
- Configuration automatique de vérification

### Protection Anti-Ban (`/antiban`)
- Prévient les bannissements massifs de membres
- Alertes automatiques au propriétaire

### Protection Anti-Kick (`/antikick`)
- Prévient les expulsions massives de membres
- Système de détection automatique

### Protection Anti-Canaux (`/antichannels`)
- Prévient la création massive de canaux
- Protection contre les raids

### Protection Anti-Rôles (`/antirole`)
- Prévient la création massive de rôles
- Protection contre les modifications non autorisées

### Protection Anti-Webhook (`/antiwebhookcreate`, `/antiwebhookspam`)
- Prévient la création non autorisée de webhooks
- Protection contre le spam de webhooks

### Filtre NSFW (`/antinsfw`)
- Détecte et filtre le contenu inapproprié
- Configuration automatique

### Protection Anti-Client (`/anticlientapp`)
- Détecte les applications client modifiées
- Prévention d'exploits

### Détection de Ghost Ping (`/ghostping`)
- Détecte les messages rapidement supprimés
- Prévention du harcèlement subtil

### Protection Anti-Mass Role (`/massrole`)
- Prévient l'attribution massive de rôles
- Protection contre les modifications non autorisées

### État de Sécurité (`/estado`)
- Affiche l'état de tous les systèmes de sécurité
- Informations détaillées pour chaque protection

### Alertes du Propriétaire (`/owneralerts`)
- Système d'alertes spécial pour le propriétaire
- Notifications d'événements importants

---

## Commandes de Configuration

### `/setup autoroles`
Gérer les rôles automatiques
- **`agregar`** - Ajouter un rôle automatique
- **`eliminar`** - Supprimer un rôle automatique
- **`listar`** - Lister les rôles automatiques

### `/setup logs`
Activer ou désactiver les logs du serveur
- **`activar`** - Activer le système de logs
- **`desactivar`** - Désactiver le système de logs
- **`[canal]`** - Canal pour les logs (optionnel)

### `/setup sugerencias`
Configurer le canal de suggestions
- **`[canal]`** - Canal où les suggestions seront envoyées

### `/setup reactionroles`
Configurer un système de reaction roles
- Système de configuration interactif
- Création de messages avec réactions automatiques

### `/setup whitelist`
Configurer les utilisateurs ou rôles autorisés
- **`add`** - Ajouter utilisateur/rôle à la whitelist
- **`remove`** - Retirer utilisateur/rôle de la whitelist
- **`list`** - Lister utilisateurs/rôles dans la whitelist

### `/setup badwords`
Configurer le système de filtrage des gros mots
- **`add`** - Ajouter un mot à la blacklist
- **`remove`** - Retirer un mot de la blacklist
- **`list`** - Lister les mots dans la blacklist

### `/setup welcome`
Configurer le système de bienvenue
- Redirige vers le tableau de bord web pour configuration avancée
- Messages et embeds personnalisés
- Options d'attribution de rôles

---

## Commandes de Modération

### `/ban [utilisateur]`
Bannir des utilisateurs du serveur
- Modal interactif pour raison, durée et preuve
- Confirmation avant exécution
- Journalisation automatique des sanctions

### `/kick [utilisateur]`
Expulser des utilisateurs du serveur
- Modal interactif pour raison et preuve
- Confirmation avant exécution
- Journalisation automatique des sanctions

### `/timeout [utilisateur]`
Mettre temporairement en sourdine des utilisateurs
- Configuration de durée
- Modal pour raison et preuve
- Confirmation avant exécution

### `/purge [quantité]`
Effacer des messages du canal
- Suppression massive de messages
- Filtres par utilisateur ou type
- Confirmation avant exécution

### `/historial [utilisateur]`
Voir l'historique des sanctions
- Liste complète des sanctions
- Informations détaillées pour chaque cas
- Navigation interactive

### `/notas`
Système de notes de modération
- Ajouter des notes sur les utilisateurs
- Consulter les notes existantes
- Gestion des informations de modération

---

## Système de Tickets

### `/ticket create`
Créer un nouveau ticket
- Système automatique de création de canaux
- Configuration automatique des permissions
- Message de bienvenue personnalisé

### `/ticket claim`
Réclamer un ticket existant
- Pour modérateurs et administrateurs
- Attribution de responsabilité

### `/ticket rename [nom]`
Renommer le ticket actuel
- Changement de nom du canal
- Journalisation des changements

### `/ticket adduser [utilisateur]`
Ajouter un utilisateur au ticket
- Donner accès à des utilisateurs spécifiques
- Gestion des permissions

### `/ticket removeuser [utilisateur]`
Retirer un utilisateur du ticket
- Révoquer l'accès des utilisateurs
- Gestion des permissions

### `/ticket done`
Fermer le ticket
- Fermeture automatique du canal
- Génération de transcription
- Archivage de conversation

### `/ticket setup`
Configuration interactive du système de tickets
- Flux de configuration guidé
- Configuration des rôles et permissions
- Personnalisation des messages

### `/ticket updatepanel`
Mettre à jour le panneau de tickets
- Mise à jour automatique du panneau principal
- Synchronisation de configuration

### `/ticket setlimit [limite]`
Définir la limite de tickets par utilisateur
- Contrôle du spam de tickets
- Configuration par administrateurs

---

## Support

- **Dashboard :** [https://www.freewingsbot.com](https://www.freewingsbot.com)
- **Serveur de Support :** [https://discord.gg/Sp9GTrmcQG](https://discord.gg/Sp9GTrmcQG)
- **Développeur :** @diamondclass
- **Organisation :** Citymoon Dynamics

### Obtenir de l'Aide
1. Utilisez `/empezar` pour une aide interactive
2. Visitez notre serveur de support pour l'assistance communautaire
3. Consultez le tableau de bord pour des guides de configuration détaillés
4. Contactez l'équipe de développement pour les problèmes techniques

---

*Freewings Bot - Gestion Complète de Serveurs Discord*
*Développé avec ❤️ par Citymoon Dynamics et @diamondclass*
