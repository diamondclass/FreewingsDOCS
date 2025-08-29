# Freewings Bot - Documentation en Français

## Table des Matières
1. [Premiers Pas](#premiers-pas)
2. [Catégories de Commandes](#catégories-de-commandes)
3. [Commandes Publiques](#commandes-publiques)
4. [Systèmes de Sécurité](#systèmes-de-sécurité)
5. [Commandes de Configuration](#commandes-de-configuration)
6. [Support](#support)

---

## Premiers Pas

Freewings est un bot Discord complet développé par [Citymoon Dynamics](https://discord.gg/Sp9GTrmcQG) et **@diamondclass**. Le bot fournit des fonctionnalités de sécurité, modération, communauté, divertissement et utilité pour les serveurs Discord.

### Démarrage Rapide
1. Utilisez `/empezar` pour explorer toutes les fonctionnalités disponibles
2. Visitez le [Dashboard](https://www.freewingsbot.com) pour la configuration avancée
3. Utilisez les commandes `/setup` pour configurer les fonctionnalités du serveur (nécessite les permissions d'Administrateur)

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
- **`/sugerir`** - Envoyer des suggestions au canal configuré
- **`/recordatorio`** - Système de rappels personnels par MP
- **`/nivel`** - Système de niveaux et XP avec classements

### 🎮 Mini-jeux
- **`/ahorcado`** - Jeu du pendu avec plusieurs niveaux de difficulté
- **`/chess`** - Jeu d'échecs
- **`/osint`** - Jeu OSINT (Intelligence des Sources Ouvertes)

### 🙈 Divertissement
- **`/8ball`** - Réponses de la boule magique 8
- **`/abrazo`** - Faire un câlin à quelqu'un
- **`/golpe`** - Action de coup joueur
- **`/amor`** - Compatibilité amoureuse
- **`/beso`** - Embrasser quelqu'un
- **`/howgay`** - Calculateur amusant de pourcentage gay
- **`/giveaway`** - Créer et gérer des concours

### 🎵 Musique
- **`/play`** - Jouer de la musique de diverses sources
- **`/pause`** - Mettre en pause la lecture actuelle
- **`/resume`** - Reprendre la lecture en pause
- **`/stop`** - Arrêter la lecture et vider la file d'attente
- **`/skip`** - Passer la chanson actuelle
- **`/queue`** - Afficher la file d'attente actuelle
- **`/nowplaying`** - Afficher la chanson en cours de lecture
- **`/volume`** - Ajuster le volume de lecture
- **`/shuffle`** - Mélanger la file d'attente
- **`/loop`** - Basculer le mode de boucle
- **`/clear`** - Vider la file d'attente de lecture
- **`/remove`** - Supprimer une chanson spécifique de la file d'attente

### 🛡️ Sécurité
- **`/antilinks`** - Système avancé de protection anti-liens
- **`/filescan`** - Analyse de fichiers avec VirusTotal
- **`/securitylogs`** - Historique des violations de sécurité
- **`/antibot`** - Protection contre les bots non autorisés
- **`/antiban`** - Protection contre les bannissements massifs
- **`/antikick`** - Protection contre les expulsions massives
- **`/antichannels`** - Protection contre la création massive de canaux
- **`/antirole`** - Protection contre la création massive de rôles
- **`/antiwebhookcreate`** - Protection contre la création de webhooks
- **`/antiwebhookspam`** - Protection contre le spam de webhooks
- **`/antinsfw`** - Filtre de contenu NSFW
- **`/anticlientapp`** - Protection contre les applications client modifiées
- **`/ghostping`** - Détection des ghost pings
- **`/massrole`** - Protection contre l'attribution massive de rôles
- **`/estado`** - État de tous les systèmes de sécurité
- **`/owneralerts`** - Alertes pour le propriétaire du serveur

### 🔨 Modération
- **`/ban`** - Bannir des utilisateurs
- **`/kick`** - Expulser des utilisateurs
- **`/timeout`** - Rendre muet temporairement les utilisateurs
- **`/purge`** - Nettoyer les messages
- **`/historial`** - Voir l'historique des sanctions
- **`/notas`** - Système de notes de modération

### 🎫 Tickets
- **`/ticket create`** - Créer un nouveau ticket
- **`/ticket claim`** - Réclamer un ticket existant
- **`/ticket rename [nom]`** - Renommer le ticket actuel
- **`/ticket adduser [utilisateur]`** - Ajouter un utilisateur au ticket
- **`/ticket removeuser [utilisateur]`** - Supprimer un utilisateur du ticket
- **`/ticket done`** - Fermer le ticket
- **`/ticket setup`** - Configuration interactive du système de tickets
- **`/ticket updatepanel`** - Mettre à jour le panneau de tickets
- **`/ticket setlimit [limite]`** - Définir la limite de tickets par utilisateur

### ⚙️ Configuration
- **`/setup`** - Commande principale de configuration avec divers sous-commandes pour la configuration du serveur

---

## Commandes Publiques

### Commandes de Communauté

#### `/user [utilisateur]`
Afficher les informations détaillées de l'utilisateur
- **Sous-commandes:**
  - `info` - Informations complètes de l'utilisateur
  - `avatar` - Avatar de l'utilisateur
  - `banner` - Bannière de l'utilisateur
  - `roles` - Rôles de l'utilisateur
  - `permissions` - Permissions de l'utilisateur
- Inclut les badges, le statut d'activité et la navigation interactive

#### `/server`
Informations et statistiques du serveur
- **Sous-commandes:**
  - `info` - Informations générales du serveur
  - `stats` - Statistiques détaillées
  - `icon` - Icône du serveur
  - `banner` - Bannière du serveur
  - `boosts` - Informations sur les boosts
- Inclut les statistiques en temps réel et les fonctionnalités spéciales

#### `/channel [canal]`
Informations et gestion des canaux
- **Sous-commandes:**
  - `info` - Informations complètes du canal
  - `permissions` - Voir les permissions du canal
  - `roles` - Rôles avec accès au canal
  - `nuke` - Nettoie complètement le canal
- ⚠️ **Nuke** nécessite les permissions d'administrateur et supprime TOUS les messages

#### `/bot`
Informations et statistiques du bot
- **Sous-commandes:**
  - `info` - Informations générales du bot
  - `icon` - Icône du bot
- Inclut les statistiques des serveurs, utilisateurs, latence et utilisation de la mémoire

#### `/traducir [texte] [langue_destination]`
Traduire du texte en utilisant Google Translate
- Modal interactif pour traduire n'importe quel texte
- Support pour plusieurs langues (en, fr, de, it, etc.)
- Auto-détection de la langue source
- Traduction instantanée et précise

#### `/seguir`
Activer les notifications pour les nouvelles publications
- Suivre les chaînes YouTube, Twitter, Twitch et Kick
- Notifications automatiques dans votre canal choisi
- Gardez votre communauté à jour

#### `/sugerir`
Envoyer des suggestions au canal configuré
- Système de suggestions avec boutons de validation
- Création automatique de fils pour la discussion
- Modération par les administrateurs

#### `/recordatorio`
Système de rappels personnels
- **Utilisation de base:** `/recordatorio mensaje:"Rappeler réunion" fecha:"2024-12-25 15:30"`
- **Sous-commandes:**
  - `listar` - Afficher les rappels actifs
  - `eliminar` - Supprimer un rappel spécifique
- **Fonctionnalités:**
  - Notifications automatiques par MP
  - Plusieurs formats de date supportés
  - Gestion personnelle des rappels
  - Vérification automatique toutes les minutes

#### `/nivel`
Système complet de niveaux et XP
- **Sous-commandes:**
  - `perfil [utilisateur]` - Voir le profil de niveau personnel ou d'un autre utilisateur
  - `leaderboard [page]` - Classement du serveur avec pagination
  - `global [page]` - Classement global entre tous les serveurs
  - `config` - Configuration du système (administrateurs uniquement)
- **Fonctionnalités:**
  - XP automatique par messages et temps en vocal
  - Système d'achievements débloquables
  - Messages de montée de niveau personnalisables
  - Cooldown configurable entre messages
  - Statistiques d'activité détaillées

### Commandes de Divertissement

#### `/8ball [question]`
Obtenir des réponses mystiques à vos questions
- Réponses aléatoires
- Amusant et divertissant
- Expérience classique de la boule magique 8

#### `/ahorcado [difficulté]`
Jouer au pendu
- Plusieurs niveaux de difficulté
- Catégories de mots
- Gameplay interactif

#### `/chess [adversaire]`
Jouer aux échecs avec d'autres utilisateurs
- Implémentation complète des échecs
- Gameplay par tours
- Validation des mouvements

#### `/osint [difficulté]`
Jeu OSINT (Intelligence des Sources Ouvertes)
- Éducatif et amusant
- Plusieurs niveaux de difficulté
- Apprendre les techniques d'investigation

#### `/amor [utilisateur1] [utilisateur2]`
Calculer la compatibilité amoureuse entre utilisateurs
- Algorithme de compatibilité
- Résultats amusants et détaillés

#### `/abrazo [utilisateur]`
Faire un câlin à un autre utilisateur
- Animations et messages personnalisés
- Interaction sociale amusante

#### `/beso [utilisateur]`
Embrasser un autre utilisateur
- Animations et messages personnalisés
- Interaction sociale amusante

#### `/golpe [utilisateur]`
Frapper joueusement un autre utilisateur
- Animations et messages personnalisés
- Interaction sociale amusante

#### `/howgay [utilisateur]`
Calculateur amusant de pourcentage gay
- Résultats aléatoires et amusants
- Sans intention offensante

#### `/giveaway`
Créer et gérer des concours
- Système complet de concours
- Configuration des prix et durée
- Sélection automatique des gagnants

### Commandes de Musique

#### `/play [chanson/url]`
Jouer de la musique de diverses sources
- Support pour YouTube, Spotify, SoundCloud
- Gestion de file d'attente
- Audio haute qualité

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
Afficher la file d'attente de musique actuelle
- Liste de chansons avec durées
- Indicateurs de position dans la file d'attente
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
Basculer le mode de boucle

#### `/clear`
Vider la file d'attente de lecture

#### `/remove [position]`
Supprimer une chanson spécifique de la file d'attente

---

## Systèmes de Sécurité

### Système Anti-Liens Avancé (`/antilinks`)
**Nouvelles fonctionnalités:**
- **Configuration flexible:** Permet les liens Discord, images et vidéos
- **Liste blanche personnalisable:** Domaines autorisés par serveur
- **Mode strict:** Blocage total des liens non autorisés
- **Analyse de sécurité:** Vérification automatique des URLs suspectes
- **Limite configurable:** Maximum de liens par message
- **Sous-commandes:**
  - `toggle` - Activer/désactiver le système
  - `whitelist` - Gérer les domaines autorisés
  - `config` - Configuration avancée

### Analyse de Fichiers (`/filescan`)
**Nouveau système de sécurité:**
- **Intégration VirusTotal:** Analyse complète des fichiers
- **Configuration API:** Sous-commande pour configurer la clé API
- **Formats multiples:** Support pour pièces jointes et URLs
- **Analyse détaillée:** Statistiques de détection et recommandations
- **Limite de taille:** Jusqu'à 32MB par fichier
- **Vérification par hash:** Pour fichiers déjà analysés
- **Sous-commandes:**
  - `config` - Configurer la clé API VirusTotal
  - Utilisation directe avec pièce jointe ou URL

### Historique de Sécurité (`/securitylogs`)
**Nouveau système de surveillance:**
- **Suivi complet:** Toutes les violations de sécurité
- **Statistiques détaillées:** Par utilisateur et type de violation
- **Escalade automatique:** 4 niveaux de sévérité
- **Sous-commandes:**
  - `usuario` - Voir l'historique d'un utilisateur spécifique
  - `servidor` - Statistiques générales du serveur
  - `limpiar` - Supprimer les anciens enregistrements

### Système de Niveaux et XP (`/nivel`)
**Nouveau système de gamification:**
- **XP automatique:** Par messages et temps en vocal
- **Système de niveaux:** Progression exponentielle
- **Classements:** Par serveur et global
- **Achievements débloquables:** Par activité et niveaux
- **Configuration flexible:** XP, cooldowns, messages
- **Sous-commandes:**
  - `perfil` - Voir les statistiques personnelles
  - `leaderboard` - Classement du serveur
  - `global` - Classement global
  - `config` - Configuration du système

### Système Anti-Spam Amélioré
**Fonctionnalités avancées:**
- **Rate limiting:** 5 messages en 10 secondes
- **Détection de motifs:** Spam, caractères répétés, majuscules
- **Analyse de contenu:** NSFW, toxicité, liens suspects
- **Escalade automatique:** 4 niveaux de sévérité (MINOR, MODERATE, SEVERE, EXTREME)
- **Timeouts automatiques:** De 5 minutes à 7 jours
- **Logs détaillés:** Enregistrement complet dans le canal mod-logs

### Protection Anti-Bot (`/antibot`)
- Détecte et empêche l'entrée de bots non autorisés
- Configuration automatique de vérification

### Protection Anti-Ban (`/antiban`)
- Empêche les bannissements massifs de membres
- Alertes automatiques au propriétaire

### Protection Anti-Kick (`/antikick`)
- Empêche les expulsions massives de membres
- Système de détection automatique

### Protection Anti-Canaux (`/antichannels`)
- Empêche la création massive de canaux
- Protection contre les raids

### Protection Anti-Rôles (`/antirole`)
- Empêche la création massive de rôles
- Protection contre les modifications non autorisées

### Protection Anti-Webhook (`/antiwebhookcreate`, `/antiwebhookspam`)
- Empêche la création non autorisée de webhooks
- Protection contre le spam de webhooks

### Filtre NSFW (`/antinsfw`)
- Détecte et filtre le contenu inapproprié
- Configuration automatique

### Protection Anti-Client (`/anticlientapp`)
- Détecte les applications client modifiées
- Prévention des exploits

### Détection de Ghost Ping (`/ghostping`)
- Détecte les messages rapidement supprimés
- Prévention du harcèlement subtil

### Protection Anti-Mass Role (`/massrole`)
- Empêche l'attribution massive de rôles
- Protection contre les modifications non autorisées

### État de Sécurité (`/estado`)
- Affiche l'état de tous les systèmes de sécurité
- Informations détaillées de chaque protection

### Alertes du Propriétaire (`/owneralerts`)
- Système d'alertes spéciales pour le propriétaire
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
- **`add`** - Ajouter un utilisateur/rôle à la whitelist
- **`remove`** - Supprimer un utilisateur/rôle de la whitelist
- **`list`** - Lister les utilisateurs/rôles dans la whitelist

### `/setup badwords`
Configurer le système de filtrage des mauvais mots
- **`add`** - Ajouter un mot à la liste noire
- **`remove`** - Supprimer un mot de la liste noire
- **`list`** - Lister les mots dans la liste noire

### `/setup welcome`
Configurer le système de bienvenue
- Redirige vers le dashboard web pour la configuration avancée
- Messages et embeds personnalisés
- Options d'attribution de rôles

---

## Commandes de Modération

### `/ban [utilisateur]`
Bannir des utilisateurs du serveur
- Modal interactif pour raison, durée et preuves
- Confirmation avant exécution
- Enregistrement automatique des sanctions

### `/kick [utilisateur]`
Expulser des utilisateurs du serveur
- Modal interactif pour raison et preuves
- Confirmation avant exécution
- Enregistrement automatique des sanctions

### `/timeout [utilisateur]`
Rendre muet temporairement les utilisateurs
- Configuration de durée
- Modal pour raison et preuves
- Confirmation avant exécution

### `/purge [quantité]`
Nettoyer les messages du canal
- Suppression massive de messages
- Filtres par utilisateur ou type
- Confirmation avant exécution

### `/historial [utilisateur]`
Voir l'historique des sanctions
- Liste complète des sanctions
- Informations détaillées de chaque cas
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
- Enregistrement des changements

### `/ticket adduser [utilisateur]`
Ajouter un utilisateur au ticket
- Donner accès à des utilisateurs spécifiques
- Gestion des permissions

### `/ticket removeuser [utilisateur]`
Supprimer un utilisateur du ticket
- Révoquer l'accès des utilisateurs
- Gestion des permissions

### `/ticket done`
Fermer le ticket
- Fermeture automatique du canal
- Génération de transcription
- Archivage de conversation

### `/ticket setup`
Configuration interactive du système de tickets
- Flux guidé de configuration
- Configuration des rôles et permissions
- Personnalisation des messages

### `/ticket updatepanel`
Mettre à jour le panneau de tickets
- Mise à jour automatique du panneau principal
- Synchronisation avec la configuration

### `/ticket setlimit [limite]`
Définir la limite de tickets par utilisateur
- Contrôle du spam de tickets
- Configuration par administrateurs

---

## Support

- **Dashboard:** [https://www.freewingsbot.com](https://www.freewingsbot.com)
- **Serveur de Support:** [https://discord.gg/Sp9GTrmcQG](https://discord.gg/Sp9GTrmcQG)
- **Développeur:** @diamondclass
- **Organisation:** Citymoon Dynamics

### Obtenir de l'Aide
1. Utilisez `/empezar` pour l'aide interactive
2. Visitez notre serveur de support pour l'assistance de la communauté
3. Consultez le dashboard pour les guides détaillés de configuration
4. Contactez l'équipe de développement pour les problèmes techniques

---

*Freewings Bot - Gestion Intégrale de Serveurs Discord*
*Développé avec ❤️ par Citymoon Dynamics et @diamondclass*
