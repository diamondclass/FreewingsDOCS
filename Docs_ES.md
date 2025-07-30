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
