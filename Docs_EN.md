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

---

# Documentación en Español

## Tabla de Contenidos
1. [Comenzando](#comenzando)
2. [Categorías de Comandos](#categorías-de-comandos)
3. [Comandos Públicos](#comandos-públicos)
4. [Sistemas de Seguridad](#sistemas-de-seguridad)
5. [Comandos de Configuración](#comandos-de-configuración)
6. [Soporte](#soporte)

---

## Comenzando

Freewings es un bot de Discord integral desarrollado por [NearDevs](https://discord.gg/Sp9GTrmcQG) y **@diamondclass**. El bot proporciona funciones de seguridad, moderación, comunidad, entretenimiento y utilidades para servidores de Discord.

### Inicio Rápido
1. Usa `/empezar` para explorar todas las características disponibles
2. Visita el [Dashboard](https://www.freewingsbot.com) para configuración avanzada
3. Usa comandos `/setup` para configurar características del servidor (requiere permisos de Administrador)

---

## Categorías de Comandos

### 🏠 Hogar
- **`/empezar`** - Guía interactiva para explorar todas las características del bot

### 🫂 Comunidad
- **`/user`** - Información y gestión de usuarios
- **`/server`** - Información y estadísticas del servidor
- **`/channel`** - Información y gestión de canales
- **`/bot`** - Información y estadísticas del bot
- **`/traducir`** - Integración con Google Translate
- **`/seguir`** - Seguir cuentas de redes sociales para notificaciones
- **`/sugerir`** - Enviar sugerencias al canal configurado

### 🎮 Minijuegos
- **`/ahorcado`** - Juego del ahorcado con múltiples niveles de dificultad
- **`/chess`** - Juego de ajedrez
- **`/osint`** - Juego de OSINT (Inteligencia de Fuentes Abiertas)

### 🙈 Diversión
- **`/8ball`** - Respuestas de la bola mágica 8
- **`/abrazo`** - Abrazar a alguien
- **`/golpe`** - Acción de golpe juguetón
- **`/amor`** - Compatibilidad amorosa
- **`/beso`** - Besar a alguien
- **`/giveaway`** - Crear sorteos
- **`/howgay`** - Calculadora divertida de porcentaje gay

### 🔩 Configuración
- **`/setup`** - Configurar características del servidor (Solo Administrador)

---

## Comandos Públicos

### `/empezar` - Comenzando
**Descripción:** Guía interactiva para explorar todas las características de Freewings
**Uso:** `/empezar`
**Características:**
- Sistema de menú interactivo
- Exploración de comandos por categorías
- Estadísticas del bot en tiempo real
- Enlaces directos al dashboard

### `/user` - Información de Usuario
**Descripción:** Información y gestión integral de usuarios
**Subcomandos:**
- **`info`** - Información completa del usuario incluyendo badges, fecha de ingreso, roles
- **`avatar`** - Mostrar avatar del usuario en alta resolución
- **`banner`** - Mostrar banner del usuario (si está disponible)
- **`roles`** - Listar todos los roles del usuario en el servidor
- **`permissions`** - Mostrar permisos clave del usuario

**Ejemplos de Uso:**
```
/user info @usuario
/user avatar
/user banner @usuario
/user roles @usuario
/user permissions @usuario
```

### `/server` - Información del Servidor
**Descripción:** Estadísticas e información del servidor
**Subcomandos:**
- **`info`** - Información general del servidor
- **`stats`** - Estadísticas detalladas del servidor
- **`icon`** - Icono del servidor
- **`banner`** - Banner del servidor
- **`boosts`** - Información de boosts

### `/channel` - Gestión de Canales
**Descripción:** Información de canales y herramientas de gestión
**Subcomandos:**
- **`info`** - Información completa del canal
- **`permissions`** - Resumen de permisos del canal
- **`roles`** - Roles con acceso al canal
- **`nuke`** - Limpiar todos los mensajes (Solo Administrador)

### `/bot` - Información del Bot
**Descripción:** Información técnica sobre Freewings
**Subcomandos:**
- **`info`** - Información general del bot incluyendo uptime, latencia, cantidad de servidores
- **`icon`** - Avatar del bot

### `/traducir` - Traducción
**Descripción:** Traducir texto usando Google Translate
**Uso:** `/traducir`
**Características:**
- Interfaz modal interactiva
- Soporte para múltiples idiomas (en, fr, de, it, etc.)
- Resultados de traducción instantáneos
- Manejo de errores para idiomas inválidos

### `/seguir` - Notificaciones de Redes Sociales
**Descripción:** Seguir cuentas de redes sociales para notificaciones automáticas
**Plataformas Soportadas:**
- Canales de YouTube
- Cuentas de Twitter
- Streams de Twitch
- Streams de Kick
**Características:**
- Notificaciones automáticas en el canal elegido
- Actualizaciones en tiempo real
- Soporte para múltiples plataformas

### `/sugerir` - Sugerencias
**Descripción:** Enviar sugerencias al canal de sugerencias configurado
**Características:**
- Creación automática de hilos para discusión
- Botones de validación para administradores
- Gestión organizada de sugerencias

### `/ahorcado` - Juego del Ahorcado
**Descripción:** Juego clásico del ahorcado con extensa base de datos de palabras
**Niveles de Dificultad:**
- 🟢 **Fácil** - Hasta 6 letras
- 🟡 **Medio** - 7-10 letras
- 🔴 **Difícil** - Más de 10 letras
- 🎲 **Aleatoria** - Cualquier dificultad

**Características:**
- 8 categorías: Tecnología, Programación, Ciencia, Naturaleza, Animales, Deportes, Cultura, Geografía, Alimentos
- Visualización interactiva del alfabeto
- Seguimiento de estadísticas (precisión, eficiencia, tiempo)
- Adivinanza de palabras y letras
- Progresión visual del ahorcado

**Uso:** `/ahorcado [dificultad]`

### `/chess` - Juego de Ajedrez
**Descripción:** Jugar ajedrez con otros usuarios
**Características:**
- Implementación completa de ajedrez
- Juego por turnos
- Validación de movimientos

### `/osint` - Juego OSINT
**Descripción:** Juego de investigación de Inteligencia de Fuentes Abiertas
**Características:**
- Desafíos de investigación
- Contenido educativo sobre técnicas OSINT

### `/8ball` - Bola Mágica 8
**Descripción:** Hazle una pregunta a la bola mágica 8
**Uso:** `/8ball [pregunta]`
**Características:**
- 20 respuestas diferentes en español
- Generación de respuestas aleatorias
- Interacción divertida para tomar decisiones

### Comandos de Diversión
- **`/abrazo [usuario]`** - Enviar un abrazo a alguien
- **`/golpe [usuario]`** - Acción de golpe juguetón
- **`/amor [usuario1] [usuario2]`** - Calcular compatibilidad amorosa
- **`/beso [usuario]`** - Enviar un beso a alguien
- **`/howgay [usuario]`** - Calculadora divertida de porcentaje gay
- **`/giveaway`** - Crear y gestionar sorteos

---

## Sistemas de Seguridad

Freewings incluye características de seguridad integrales (configuradas vía `/setup` o dashboard):

### Sistemas Anti-Spam
- **Protección anti-ban** - Previene baneos masivos
- **Protección anti-bot** - Bloquea adiciones sospechosas de bots
- **Anti-spam de canales** - Previene spam de creación/eliminación de canales
- **Anti-spam de roles** - Protege contra manipulación de roles
- **Anti-spam de webhooks** - Previene abuso de webhooks
- **Protección anti-kick** - Bloquea expulsiones masivas
- **Anti-NSFW** - Filtrado de contenido
- **Anti-enlaces** - Filtrado y protección de enlaces
- **Detección de ghost ping** - Detecta y registra ghost pings

### Sistemas de Monitoreo
- **Permisos de audit log** - Rastrear cambios de permisos
- **Alertas del propietario** - Notificar a propietarios del servidor sobre actividad sospechosa
- **Detección de roles masivos** - Monitorear cambios masivos de roles
- **Monitoreo de aplicaciones cliente** - Rastrear uso de aplicaciones

---

## Comandos de Configuración

### `/setup` - Configuración del Servidor
**Permiso Requerido:** Administrador

**Subcomandos:**

#### `/setup autoroles`
Configurar asignación automática de roles para nuevos miembros
- **`agregar [rol]`** - Agregar rol a la lista de auto-asignación
- **`eliminar [rol]`** - Remover rol de la lista de auto-asignación
- **`listar`** - Listar todos los auto-roles configurados

#### `/setup logs`
Configurar sistema de registro del servidor
- **`activar [canal]`** - Habilitar logs en el canal especificado
- **`desactivar`** - Deshabilitar sistema de registro
- Selección interactiva de eventos (eventos de canal, eventos de rol, eventos de miembro, eventos de mensaje, eventos de webhook)

#### `/setup sugerencias`
Configurar sistema de sugerencias
- **`[canal]`** - Establecer canal para sugerencias

#### `/setup reactionroles`
Crear sistemas de reaction roles
- Creación interactiva de embeds
- Título, descripción y color personalizados
- Asignación de roles vía reacciones

#### `/setup whitelist`
Gestionar usuarios y roles autorizados
- **`add user/role [objetivo]`** - Agregar a whitelist (Solo Propietario)
- **`remove user/role [objetivo]`** - Remover de whitelist (Solo Propietario)
- **`list user/role [página]`** - Listar elementos en whitelist

#### `/setup badwords`
Gestionar filtro de malas palabras
- **`activar`** - Habilitar filtro de malas palabras
- **`desactivar`** - Deshabilitar filtro de malas palabras
- **`agregar [palabra]`** - Agregar palabra a lista negra
- **`quitar [palabra]`** - Remover palabra de lista negra
- **`listar`** - Listar todas las palabras en lista negra

#### `/setup welcome`
Configurar sistema de bienvenida (Solo Dashboard)
- Redirige al dashboard web para configuración

---

## Soporte

- **Dashboard:** [https://www.freewingsbot.com](https://www.freewingsbot.com)
- **Comunidad de Desarrolladores:** [Discord de NearDevs](https://discord.gg/Sp9GTrmcQG)
- **Desarrollador Principal:** @diamondclass
- **Copyright:** Freewings © 2025
