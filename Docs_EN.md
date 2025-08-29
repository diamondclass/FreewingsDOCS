# Freewings Bot - English Documentation

## Table of Contents
1. [Getting Started](#getting-started)
2. [Command Categories](#command-categories)
3. [Public Commands](#public-commands)
4. [Security Systems](#security-systems)
5. [Configuration Commands](#configuration-commands)
6. [Support](#support)

---

## Getting Started

Freewings is a comprehensive Discord bot developed by [Citymoon Dynamics](https://discord.gg/Sp9GTrmcQG) and **@diamondclass**. The bot provides security, moderation, community, entertainment, and utility features for Discord servers.

### Quick Start
1. Use `/empezar` to explore all available features
2. Visit the [Dashboard](https://www.freewingsbot.com) for advanced configuration
3. Use `/setup` commands to configure server features (requires Administrator permissions)

---

## Command Categories

### 🏠 Home
- **`/empezar`** - Interactive guide to explore all bot features

### 🫂 Community
- **`/user`** - User information and management
- **`/server`** - Server information and statistics
- **`/channel`** - Channel information and management
- **`/bot`** - Bot information and statistics
- **`/traducir`** - Google Translate integration
- **`/seguir`** - Follow social media accounts for notifications
- **`/sugerir`** - Send suggestions to configured channel
- **`/recordatorio`** - Personal reminder system via DM
- **`/nivel`** - Level and XP system with leaderboards

### 🎮 Minigames
- **`/ahorcado`** - Hangman game with multiple difficulty levels
- **`/chess`** - Chess game
- **`/osint`** - OSINT (Open Source Intelligence) game

### 🙈 Fun
- **`/8ball`** - Magic 8 ball responses
- **`/abrazo`** - Hug someone
- **`/golpe`** - Playful hit action
- **`/amor`** - Love compatibility
- **`/beso`** - Kiss someone
- **`/howgay`** - Fun gay percentage calculator
- **`/giveaway`** - Create and manage giveaways

### 🎵 Music
- **`/play`** - Play music from various sources
- **`/pause`** - Pause current playback
- **`/resume`** - Resume paused playback
- **`/stop`** - Stop playback and clear queue
- **`/skip`** - Skip current song
- **`/queue`** - Show current queue
- **`/nowplaying`** - Show currently playing song
- **`/volume`** - Adjust playback volume
- **`/shuffle`** - Shuffle the queue
- **`/loop`** - Toggle loop mode
- **`/clear`** - Clear playback queue
- **`/remove`** - Remove specific song from queue

### 🛡️ Security
- **`/antilinks`** - Advanced anti-links protection system
- **`/filescan`** - File scanning with VirusTotal
- **`/securitylogs`** - Security violation history
- **`/antibot`** - Protection against unauthorized bots
- **`/antiban`** - Protection against mass bans
- **`/antikick`** - Protection against mass kicks
- **`/antichannels`** - Protection against mass channel creation
- **`/antirole`** - Protection against mass role creation
- **`/antiwebhookcreate`** - Protection against webhook creation
- **`/antiwebhookspam`** - Protection against webhook spam
- **`/antinsfw`** - NSFW content filter
- **`/anticlientapp`** - Protection against modified client applications
- **`/ghostping`** - Ghost ping detection
- **`/massrole`** - Protection against mass role assignment
- **`/estado`** - Status of all security systems
- **`/owneralerts`** - Alerts for server owner

### 🔨 Moderation
- **`/ban`** - Ban users
- **`/kick`** - Kick users
- **`/timeout`** - Temporarily mute users
- **`/purge`** - Clean messages
- **`/historial`** - View sanction history
- **`/notas`** - Moderation notes system

### 🎫 Tickets
- **`/ticket create`** - Create a new ticket
- **`/ticket claim`** - Claim an existing ticket
- **`/ticket rename [name]`** - Rename current ticket
- **`/ticket adduser [user]`** - Add user to ticket
- **`/ticket removeuser [user]`** - Remove user from ticket
- **`/ticket done`** - Close the ticket
- **`/ticket setup`** - Interactive ticket system configuration
- **`/ticket updatepanel`** - Update ticket panel
- **`/ticket setlimit [limit]`** - Set ticket limit per user

### ⚙️ Configuration
- **`/setup`** - Main configuration command with various subcommands for server configuration

---

## Public Commands

### Community Commands

#### `/user [user]`
Display detailed user information
- **Subcommands:**
  - `info` - Complete user information
  - `avatar` - User avatar
  - `banner` - User banner
  - `roles` - User roles
  - `permissions` - User permissions
- Includes badges, activity status, and interactive navigation

#### `/server`
Server information and statistics
- **Subcommands:**
  - `info` - General server information
  - `stats` - Detailed statistics
  - `icon` - Server icon
  - `banner` - Server banner
  - `boosts` - Boost information
- Includes real-time statistics and special features

#### `/channel [channel]`
Channel information and management
- **Subcommands:**
  - `info` - Complete channel information
  - `permissions` - View channel permissions
  - `roles` - Roles with channel access
  - `nuke` - Completely clean the channel
- ⚠️ **Nuke** requires administrator permissions and deletes ALL messages

#### `/bot`
Bot information and statistics
- **Subcommands:**
  - `info` - General bot information
  - `icon` - Bot icon
- Includes server statistics, users, latency, and memory usage

#### `/traducir [text] [target_language]`
Translate text using Google Translate
- Interactive modal to translate any text
- Support for multiple languages (en, fr, de, it, etc.)
- Auto-detection of source language
- Instant and accurate translation

#### `/seguir`
Activate notifications for new posts
- Follow YouTube, Twitter, Twitch, and Kick channels
- Automatic notifications in your chosen channel
- Keep your community updated

#### `/sugerir`
Send suggestions to configured channel
- Suggestion system with validation buttons
- Automatic thread creation for discussion
- Moderation by administrators

#### `/recordatorio`
Personal reminder system
- **Basic usage:** `/recordatorio mensaje:"Remember meeting" fecha:"2024-12-25 15:30"`
- **Subcommands:**
  - `listar` - Show active reminders
  - `eliminar` - Delete specific reminder
- **Features:**
  - Automatic DM notifications
  - Multiple supported date formats
  - Personal reminder management
  - Automatic verification every minute

#### `/nivel`
Complete level and XP system
- **Subcommands:**
  - `perfil [user]` - View personal level profile or another user's
  - `leaderboard [page]` - Server ranking with pagination
  - `global [page]` - Global ranking across all servers
  - `config` - System configuration (administrators only)
- **Features:**
  - Automatic XP from messages and voice time
  - Unlockable achievement system
  - Customizable level-up messages
  - Configurable cooldown between messages
  - Detailed activity statistics

### Entertainment Commands

#### `/8ball [question]`
Get mystical answers to your questions
- Random responses
- Fun and entertaining
- Classic magic 8 ball experience

#### `/ahorcado [difficulty]`
Play hangman
- Multiple difficulty levels
- Word categories
- Interactive gameplay

#### `/chess [opponent]`
Play chess with other users
- Complete chess implementation
- Turn-based gameplay
- Move validation

#### `/osint [difficulty]`
OSINT (Open Source Intelligence) game
- Educational and fun
- Multiple difficulty levels
- Learn investigation techniques

#### `/amor [user1] [user2]`
Calculate love compatibility between users
- Compatibility algorithm
- Fun and detailed results

#### `/abrazo [user]`
Hug another user
- Custom animations and messages
- Fun social interaction

#### `/beso [user]`
Kiss another user
- Custom animations and messages
- Fun social interaction

#### `/golpe [user]`
Playfully hit another user
- Custom animations and messages
- Fun social interaction

#### `/howgay [user]`
Fun gay percentage calculator
- Random and fun results
- No offensive intent

#### `/giveaway`
Create and manage giveaways
- Complete giveaway system
- Prize and duration configuration
- Automatic winner selection

### Music Commands

#### `/play [song/url]`
Play music from various sources
- Support for YouTube, Spotify, SoundCloud
- Queue management
- High-quality audio

#### `/search [term]`
Search songs on YouTube
- Interactive results
- Multiple song selection

#### `/pause`
Pause current playback

#### `/resume`
Resume paused playback

#### `/stop`
Stop playback and clear queue

#### `/skip`
Skip current song

#### `/queue`
Show current music queue
- Song list with durations
- Queue position indicators
- Total queue time

#### `/nowplaying`
Show currently playing song
- Song information and progress
- Thumbnail and duration
- Requester information

#### `/volume [level]`
Adjust playback volume (0-100)

#### `/shuffle`
Shuffle the queue

#### `/loop`
Toggle loop mode

#### `/clear`
Clear playback queue

#### `/remove [position]`
Remove specific song from queue

---

## Security Systems

### Advanced Anti-Links System (`/antilinks`)
**New features:**
- **Flexible configuration:** Allows Discord links, images, and videos
- **Customizable whitelist:** Allowed domains per server
- **Strict mode:** Total blocking of unauthorized links
- **Security analysis:** Automatic verification of suspicious URLs
- **Configurable limit:** Maximum links per message
- **Subcommands:**
  - `toggle` - Enable/disable system
  - `whitelist` - Manage allowed domains
  - `config` - Advanced configuration

### File Scanning (`/filescan`)
**New security system:**
- **VirusTotal integration:** Complete file analysis
- **API configuration:** Subcommand to configure API key
- **Multiple formats:** Support for attachments and URLs
- **Detailed analysis:** Detection statistics and recommendations
- **Size limit:** Up to 32MB per file
- **Hash verification:** For already analyzed files
- **Subcommands:**
  - `config` - Configure VirusTotal API key
  - Direct use with file attachment or URL

### Security History (`/securitylogs`)
**New monitoring system:**
- **Complete tracking:** All security violations
- **Detailed statistics:** By user and violation type
- **Automatic escalation:** 4 severity levels
- **Subcommands:**
  - `usuario` - View specific user history
  - `servidor` - General server statistics
  - `limpiar` - Delete old records

### Level and XP System (`/nivel`)
**New gamification system:**
- **Automatic XP:** From messages and voice time
- **Level system:** Exponential progression
- **Leaderboards:** Server and global
- **Unlockable achievements:** By activity and levels
- **Flexible configuration:** XP, cooldowns, messages
- **Subcommands:**
  - `perfil` - View personal statistics
  - `leaderboard` - Server ranking
  - `global` - Global ranking
  - `config` - System configuration

### Enhanced Anti-Spam System
**Advanced features:**
- **Rate limiting:** 5 messages in 10 seconds
- **Pattern detection:** Spam, repeated characters, caps
- **Content analysis:** NSFW, toxicity, suspicious links
- **Automatic escalation:** 4 severity levels (MINOR, MODERATE, SEVERE, EXTREME)
- **Automatic timeouts:** From 5 minutes to 7 days
- **Detailed logs:** Complete recording in mod-logs channel

### Anti-Bot Protection (`/antibot`)
- Detects and prevents unauthorized bot entry
- Automatic verification configuration

### Anti-Ban Protection (`/antiban`)
- Prevents mass member bans
- Automatic owner alerts

### Anti-Kick Protection (`/antikick`)
- Prevents mass member kicks
- Automatic detection system

### Anti-Channel Protection (`/antichannels`)
- Prevents mass channel creation
- Protection against raids

### Anti-Role Protection (`/antirole`)
- Prevents mass role creation
- Protection against unauthorized modifications

### Anti-Webhook Protection (`/antiwebhookcreate`, `/antiwebhookspam`)
- Prevents unauthorized webhook creation
- Protection against webhook spam

### NSFW Filter (`/antinsfw`)
- Detects and filters inappropriate content
- Automatic configuration

### Anti-Client Protection (`/anticlientapp`)
- Detects modified client applications
- Exploit prevention

### Ghost Ping Detection (`/ghostping`)
- Detects quickly deleted messages
- Prevention of subtle harassment

### Anti-Mass Role Protection (`/massrole`)
- Prevents mass role assignment
- Protection against unauthorized modifications

### Security Status (`/estado`)
- Shows status of all security systems
- Detailed information for each protection

### Owner Alerts (`/owneralerts`)
- Special alert system for owner
- Important event notifications

---

## Configuration Commands

### `/setup autoroles`
Manage automatic roles
- **`agregar`** - Add automatic role
- **`eliminar`** - Remove automatic role
- **`listar`** - List automatic roles

### `/setup logs`
Activate or deactivate server logs
- **`activar`** - Enable logging system
- **`desactivar`** - Disable logging system
- **`[channel]`** - Channel for logs (optional)

### `/setup sugerencias`
Configure suggestions channel
- **`[channel]`** - Channel where suggestions will be sent

### `/setup reactionroles`
Configure a reaction roles system
- Interactive configuration system
- Automatic reaction message creation

### `/setup whitelist`
Configure authorized users or roles
- **`add`** - Add user/role to whitelist
- **`remove`** - Remove user/role from whitelist
- **`list`** - List users/roles in whitelist

### `/setup badwords`
Configure bad words filtering system
- **`add`** - Add word to blacklist
- **`remove`** - Remove word from blacklist
- **`list`** - List words in blacklist

### `/setup welcome`
Configure welcome system
- Redirects to web dashboard for advanced configuration
- Custom messages and embeds
- Role assignment options

---

## Moderation Commands

### `/ban [user]`
Ban users from server
- Interactive modal for reason, duration, and evidence
- Confirmation before execution
- Automatic sanction logging

### `/kick [user]`
Kick users from server
- Interactive modal for reason and evidence
- Confirmation before execution
- Automatic sanction logging

### `/timeout [user]`
Temporarily mute users
- Duration configuration
- Modal for reason and evidence
- Confirmation before execution

### `/purge [amount]`
Clean channel messages
- Mass message deletion
- User or type filters
- Confirmation before execution

### `/historial [user]`
View sanction history
- Complete sanction list
- Detailed information for each case
- Interactive navigation

### `/notas`
Moderation notes system
- Add notes about users
- Consult existing notes
- Moderation information management

---

## Ticket System

### `/ticket create`
Create a new ticket
- Automatic channel creation system
- Automatic permission configuration
- Customized welcome message

### `/ticket claim`
Claim an existing ticket
- For moderators and administrators
- Responsibility assignment

### `/ticket rename [name]`
Rename current ticket
- Channel name change
- Change logging

### `/ticket adduser [user]`
Add user to ticket
- Give access to specific users
- Permission management

### `/ticket removeuser [user]`
Remove user from ticket
- Revoke user access
- Permission management

### `/ticket done`
Close the ticket
- Automatic channel closure
- Transcript generation
- Conversation archiving

### `/ticket setup`
Interactive ticket system configuration
- Guided configuration flow
- Role and permission configuration
- Message customization

### `/ticket updatepanel`
Update ticket panel
- Automatic main panel update
- Configuration synchronization

### `/ticket setlimit [limit]`
Set ticket limit per user
- Ticket spam control
- Administrator configuration

---

## Support

- **Dashboard:** [https://www.freewingsbot.com](https://www.freewingsbot.com)
- **Support Server:** [https://discord.gg/Sp9GTrmcQG](https://discord.gg/Sp9GTrmcQG)
- **Developer:** @diamondclass
- **Organization:** Citymoon Dynamics

### Getting Help
1. Use `/empezar` for interactive help
2. Visit our support server for community assistance
3. Check the dashboard for detailed configuration guides
4. Contact the development team for technical issues

---

*Freewings Bot - Comprehensive Discord Server Management*
*Developed with ❤️ by Citymoon Dynamics and @diamondclass*
