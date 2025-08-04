# Freewings Bot - English Documentation

## Table of Contents
1. [Getting Started](#getting-started)
2. [Command Categories](#command-categories)
3. [Public Commands](#public-commands)
4. [Security Systems](#security-systems)
5. [Setup Commands](#setup-commands)
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
- **`/sugerir`** - Submit suggestions to the configured channel

### 🎮 Mini-games
- **`/ahorcado`** - Hangman game with multiple difficulty levels
- **`/chess`** - Chess game
- **`/osint`** - OSINT (Open Source Intelligence) game

### 🙈 Fun
- **`/8ball`** - Magic 8-ball responses
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
- **`/queue`** - Display current queue
- **`/nowplaying`** - Show currently playing song
- **`/volume`** - Adjust playback volume
- **`/shuffle`** - Shuffle the queue
- **`/loop`** - Toggle loop mode
- **`/clear`** - Clear playback queue
- **`/remove`** - Remove specific song from queue

### 🛡️ Security
- **`/antilinks`** - Anti-links protection system
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
- **`/owneralerts`** - Owner alerts system

### 🔨 Moderation
- **`/ban`** - Ban users
- **`/kick`** - Kick users
- **`/timeout`** - Timeout users
- **`/purge`** - Clear messages
- **`/historial`** - View sanction history
- **`/notas`** - Moderation notes system

### 🎫 Tickets
- **`/ticket create`** - Create a new ticket
- **`/ticket claim`** - Claim an existing ticket
- **`/ticket rename [name]`** - Rename the current ticket
- **`/ticket adduser [user]`** - Add user to ticket
- **`/ticket removeuser [user]`** - Remove user from ticket
- **`/ticket done`** - Close the ticket
- **`/ticket setup`** - Interactive ticket system configuration
- **`/ticket updatepanel`** - Update ticket panel
- **`/ticket setlimit [limit]`** - Set ticket limit per user

### ⚙️ Setup
- **`/setup`** - Main setup command with various subcommands for server configuration

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
- Includes server and user statistics, latency, and memory usage

#### `/traducir [text] [target_language]`
Translate text using Google Translate
- Interactive modal for translating any text
- Support for multiple languages (en, fr, de, it, etc.)
- Auto-detection of source language
- Instant and accurate translation

#### `/seguir`
Activate notifications for new posts
- Follow YouTube, Twitter, Twitch, and Kick channels
- Automatic notifications in your chosen channel
- Keep your community updated

#### `/sugerir`
Submit suggestions to the configured channel
- Suggestion system with validation buttons
- Automatic thread creation for discussion
- Moderation by administrators

### Entertainment Commands

#### `/8ball [question]`
Get mystical answers to your questions
- Random responses
- Fun and entertaining
- Classic magic 8-ball experience

#### `/ahorcado [difficulty]`
Play hangman game
- Multiple difficulty levels
- Word categories
- Interactive gameplay

#### `/chess [opponent]`
Play chess with other users
- Full chess implementation
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
- YouTube, Spotify, SoundCloud support
- Queue management
- High-quality audio

#### `/search [term]`
Search for songs on YouTube
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
Display current music queue
- Song list with durations
- Queue position indicators
- Total queue time

#### `/nowplaying`
Display currently playing song
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

### Anti-Links Protection (`/antilinks`)
- Only the server owner can configure
- Automatically sanctions users who send unauthorized links
- Confirmation system to activate/deactivate

### Anti-Bot Protection (`/antibot`)
- Detects and prevents unauthorized bot entry
- Automatic verification configuration

### Anti-Ban Protection (`/antiban`)
- Prevents mass banning of members
- Automatic alerts to owner

### Anti-Kick Protection (`/antikick`)
- Prevents mass kicking of members
- Automatic detection system

### Anti-Channels Protection (`/antichannels`)
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
- Detects messages that are quickly deleted
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

## Setup Commands

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
- Creation of messages with automatic reactions

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
- Interactive modal for reason, duration, and proof
- Confirmation before execution
- Automatic sanction logging

### `/kick [user]`
Kick users from server
- Interactive modal for reason and proof
- Confirmation before execution
- Automatic sanction logging

### `/timeout [user]`
Temporarily mute users
- Duration configuration
- Modal for reason and proof
- Confirmation before execution

### `/purge [amount]`
Clear messages from channel
- Mass message deletion
- Filters by user or type
- Confirmation before execution

### `/historial [user]`
View sanction history
- Complete list of sanctions
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
Close ticket
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
