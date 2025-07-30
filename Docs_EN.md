# Freewings Bot Documentation

## English Documentation

### Table of Contents
1. [Getting Started](#getting-started)
2. [Command Categories](#command-categories)
3. [Public Commands](#public-commands)
4. [Security Systems](#security-systems)
5. [Setup Commands](#setup-commands)
6. [Support](#support)

---

## Getting Started

Freewings is a comprehensive Discord bot developed by [NearDevs](https://discord.gg/Sp9GTrmcQG) and **@diamondclass**. The bot provides security, moderation, community, entertainment, and utility features for Discord servers.

### Quick Start
1. Use `/empezar` to explore all available features
2. Visit the [Dashboard](https://www.freewingsbot.com) for advanced configuration
3. Use `/setup` commands to configure server features (requires Administrator permissions)

---

## Command Categories

### 🏠 Home (Hogar)
- **`/empezar`** - Interactive guide to explore all bot features

### 🫂 Community (Comunidad)
- **`/user`** - User information and management
- **`/server`** - Server information and statistics
- **`/channel`** - Channel information and management
- **`/bot`** - Bot information and statistics
- **`/traducir`** - Google Translate integration
- **`/seguir`** - Follow social media accounts for notifications
- **`/sugerir`** - Submit suggestions to the configured channel

### 🎮 Mini-games (Minijuegos)
- **`/ahorcado`** - Hangman game with multiple difficulty levels
- **`/chess`** - Chess game
- **`/osint`** - OSINT (Open Source Intelligence) game

### 🙈 Fun (Diversión)
- **`/8ball`** - Magic 8-ball responses
- **`/abrazo`** - Hug someone
- **`/golpe`** - Playful hit action
- **`/amor`** - Love compatibility
- **`/beso`** - Kiss someone
- **`/giveaway`** - Create giveaways
- **`/howgay`** - Fun gay percentage calculator

### 🔩 Setup
- **`/setup`** - Configure server features (Administrator only)

---

## Public Commands

### `/empezar` - Getting Started
**Description:** Interactive guide to explore all Freewings features
**Usage:** `/empezar`
**Features:**
- Interactive menu system
- Category-based command exploration
- Real-time bot statistics
- Direct links to dashboard

### `/user` - User Information
**Description:** Comprehensive user information and management
**Subcommands:**
- **`info`** - Complete user information including badges, join date, roles
- **`avatar`** - Display user's avatar in high resolution
- **`banner`** - Show user's banner (if available)
- **`roles`** - List all user roles in the server
- **`permissions`** - Display user's key permissions

**Usage Examples:**
```
/user info @username
/user avatar
/user banner @username
/user roles @username
/user permissions @username
```

### `/server` - Server Information
**Description:** Server statistics and information
**Subcommands:**
- **`info`** - General server information
- **`stats`** - Detailed server statistics
- **`icon`** - Server icon
- **`banner`** - Server banner
- **`boosts`** - Boost information

### `/channel` - Channel Management
**Description:** Channel information and management tools
**Subcommands:**
- **`info`** - Complete channel information
- **`permissions`** - Channel permissions overview
- **`roles`** - Roles with access to the channel
- **`nuke`** - Clear all messages (Administrator only)

### `/bot` - Bot Information
**Description:** Technical information about Freewings
**Subcommands:**
- **`info`** - General bot information including uptime, latency, server count
- **`icon`** - Bot's avatar

### `/traducir` - Translation
**Description:** Translate text using Google Translate
**Usage:** `/traducir`
**Features:**
- Interactive modal interface
- Support for multiple languages (en, fr, de, it, etc.)
- Instant translation results
- Error handling for invalid languages

### `/seguir` - Social Media Notifications
**Description:** Follow social media accounts for automatic notifications
**Supported Platforms:**
- YouTube channels
- Twitter accounts
- Twitch streams
- Kick streams
**Features:**
- Automatic notifications in chosen channel
- Real-time updates
- Multiple platform support

### `/sugerir` - Suggestions
**Description:** Submit suggestions to the configured suggestions channel
**Features:**
- Automatic thread creation for discussion
- Validation buttons for administrators
- Organized suggestion management

### `/ahorcado` - Hangman Game
**Description:** Classic hangman game with extensive word database
**Difficulty Levels:**
- 🟢 **Easy** - Up to 6 letters
- 🟡 **Medium** - 7-10 letters
- 🔴 **Hard** - More than 10 letters
- 🎲 **Random** - Any difficulty

**Features:**
- 8 categories: Technology, Programming, Science, Nature, Animals, Sports, Culture, Geography, Food
- Interactive alphabet display
- Statistics tracking (precision, efficiency, time)
- Word guessing and letter guessing
- Visual hangman progression

**Usage:** `/ahorcado [difficulty]`

### `/chess` - Chess Game
**Description:** Play chess with other users
**Features:**
- Full chess implementation
- Turn-based gameplay
- Move validation

### `/osint` - OSINT Game
**Description:** Open Source Intelligence investigation game
**Features:**
- Investigation challenges
- Educational content about OSINT techniques

### `/8ball` - Magic 8-Ball
**Description:** Ask the magic 8-ball a question
**Usage:** `/8ball [question]`
**Features:**
- 20 different responses in Spanish
- Random answer generation
- Fun interaction for decision making

### Fun Commands
- **`/abrazo [user]`** - Send a hug to someone
- **`/golpe [user]`** - Playful hit action
- **`/amor [user1] [user2]`** - Calculate love compatibility
- **`/beso [user]`** - Send a kiss to someone
- **`/howgay [user]`** - Fun gay percentage calculator
- **`/giveaway`** - Create and manage giveaways

---

## Security Systems

Freewings includes comprehensive security features (configured via `/setup` or dashboard):

### Anti-Spam Systems
- **Anti-ban protection** - Prevents mass banning
- **Anti-bot protection** - Blocks suspicious bot additions
- **Anti-channel spam** - Prevents channel creation/deletion spam
- **Anti-role spam** - Protects against role manipulation
- **Anti-webhook spam** - Prevents webhook abuse
- **Anti-kick protection** - Blocks mass kicking
- **Anti-NSFW** - Content filtering
- **Anti-links** - Link filtering and protection
- **Ghost ping detection** - Detects and logs ghost pings

### Monitoring Systems
- **Audit log permissions** - Track permission changes
- **Owner alerts** - Notify server owners of suspicious activity
- **Mass role detection** - Monitor bulk role changes
- **Client app monitoring** - Track application usage

---

## Setup Commands

### `/setup` - Server Configuration
**Required Permission:** Administrator

**Subcommands:**

#### `/setup autoroles`
Configure automatic role assignment for new members
- **`agregar [role]`** - Add role to auto-assign list
- **`eliminar [role]`** - Remove role from auto-assign list
- **`listar`** - List all configured auto-roles

#### `/setup logs`
Configure server logging system
- **`activar [channel]`** - Enable logs in specified channel
- **`desactivar`** - Disable logging system
- Interactive event selection (channel events, role events, member events, message events, webhook events)

#### `/setup sugerencias`
Configure suggestions system
- **`[channel]`** - Set channel for suggestions

#### `/setup reactionroles`
Create reaction role systems
- Interactive embed creation
- Custom title, description, and color
- Role assignment via reactions

#### `/setup whitelist`
Manage authorized users and roles
- **`add user/role [target]`** - Add to whitelist (Owner only)
- **`remove user/role [target]`** - Remove from whitelist (Owner only)
- **`list user/role [page]`** - List whitelisted items

#### `/setup badwords`
Manage bad words filter
- **`activar`** - Enable bad words filter
- **`desactivar`** - Disable bad words filter
- **`agregar [word]`** - Add word to blacklist
- **`quitar [word]`** - Remove word from blacklist
- **`listar`** - List all blacklisted words

#### `/setup welcome`
Configure welcome system (Dashboard only)
- Redirects to web dashboard for configuration

---

## Support

- **Dashboard:** [https://www.freewingsbot.com](https://www.freewingsbot.com)
- **Developer Community:** [NearDevs Discord](https://discord.gg/Sp9GTrmcQG)
- **Main Developer:** @diamondclass
- **Copyright:** Freewings © 2025


## Soporte

- **Dashboard:** [https://www.freewingsbot.com](https://www.freewingsbot.com)
- **Comunidad de Desarrolladores:** [Discord de NearDevs](https://discord.gg/Sp9GTrmcQG)
- **Desarrollador Principal:** @diamondclass
- **Copyright:** Freewings © 2025
