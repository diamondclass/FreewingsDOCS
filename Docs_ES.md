# Freewings Bot - Documentación en Español

## Tabla de Contenidos
1. [Primeros Pasos](#primeros-pasos)
2. [Categorías de Comandos](#categorías-de-comandos)
3. [Comandos Públicos](#comandos-públicos)
4. [Sistemas de Seguridad](#sistemas-de-seguridad)
5. [Comandos de Configuración](#comandos-de-configuración)
6. [Soporte](#soporte)

---

## Primeros Pasos

Freewings es un bot integral de Discord desarrollado por [Citymoon Dynamics](https://discord.gg/Sp9GTrmcQG) y **@diamondclass**. El bot proporciona características de seguridad, moderación, comunidad, entretenimiento y utilidad para servidores de Discord.

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
- **`/howgay`** - Calculadora divertida de porcentaje gay
- **`/giveaway`** - Crear y gestionar sorteos

### 🎵 Música
- **`/play`** - Reproducir música de varias fuentes
- **`/pause`** - Pausar reproducción actual
- **`/resume`** - Reanudar reproducción pausada
- **`/stop`** - Detener reproducción y limpiar cola
- **`/skip`** - Saltar canción actual
- **`/queue`** - Mostrar cola actual
- **`/nowplaying`** - Mostrar canción reproduciéndose actualmente
- **`/volume`** - Ajustar volumen de reproducción
- **`/shuffle`** - Mezclar la cola
- **`/loop`** - Alternar modo de bucle
- **`/clear`** - Limpiar cola de reproducción
- **`/remove`** - Remover canción específica de la cola

### 🛡️ Seguridad
- **`/antilinks`** - Sistema de protección anti-enlaces
- **`/antibot`** - Protección contra bots no autorizados
- **`/antiban`** - Protección contra baneos masivos
- **`/antikick`** - Protección contra expulsiones masivas
- **`/antichannels`** - Protección contra creación masiva de canales
- **`/antirole`** - Protección contra creación masiva de roles
- **`/antiwebhookcreate`** - Protección contra creación de webhooks
- **`/antiwebhookspam`** - Protección contra spam de webhooks
- **`/antinsfw`** - Filtro de contenido NSFW
- **`/anticlientapp`** - Protección contra aplicaciones cliente modificadas
- **`/ghostping`** - Detección de ghost pings
- **`/massrole`** - Protección contra asignación masiva de roles
- **`/estado`** - Estado de todos los sistemas de seguridad
- **`/owneralerts`** - Alertas para el propietario del servidor

### 🔨 Moderación
- **`/ban`** - Banear usuarios
- **`/kick`** - Expulsar usuarios
- **`/timeout`** - Silenciar usuarios temporalmente
- **`/purge`** - Limpiar mensajes
- **`/historial`** - Ver historial de sanciones
- **`/notas`** - Sistema de notas de moderación

### 🎫 Tickets
- **`/ticket create`** - Crear un nuevo ticket
- **`/ticket claim`** - Reclamar un ticket existente
- **`/ticket rename [nombre]`** - Renombrar el ticket actual
- **`/ticket adduser [usuario]`** - Agregar usuario al ticket
- **`/ticket removeuser [usuario]`** - Remover usuario del ticket
- **`/ticket done`** - Cerrar el ticket
- **`/ticket setup`** - Configuración interactiva del sistema de tickets
- **`/ticket updatepanel`** - Actualizar panel de tickets
- **`/ticket setlimit [límite]`** - Establecer límite de tickets por usuario

### ⚙️ Configuración
- **`/setup`** - Comando principal de configuración con varios subcomandos para configuración del servidor

---

## Comandos Públicos

### Comandos de Comunidad

#### `/user [usuario]`
Mostrar información detallada del usuario
- **Subcomandos:**
  - `info` - Información completa del usuario
  - `avatar` - Avatar del usuario
  - `banner` - Banner del usuario
  - `roles` - Roles del usuario
  - `permissions` - Permisos del usuario
- Incluye badges, estado de actividad y navegación interactiva

#### `/server`
Información y estadísticas del servidor
- **Subcomandos:**
  - `info` - Información general del servidor
  - `stats` - Estadísticas detalladas
  - `icon` - Icono del servidor
  - `banner` - Banner del servidor
  - `boosts` - Información de boosts
- Incluye estadísticas en tiempo real y características especiales

#### `/channel [canal]`
Información y gestión de canales
- **Subcomandos:**
  - `info` - Información completa del canal
  - `permissions` - Ver permisos del canal
  - `roles` - Roles con acceso al canal
  - `nuke` - Limpia completamente el canal
- ⚠️ **Nuke** requiere permisos de administrador y elimina TODOS los mensajes

#### `/bot`
Información y estadísticas del bot
- **Subcomandos:**
  - `info` - Información general del bot
  - `icon` - Icono del bot
- Incluye estadísticas de servidores, usuarios, latencia y uso de memoria

#### `/traducir [texto] [idioma_destino]`
Traducir texto usando Google Translate
- Modal interactivo para traducir cualquier texto
- Soporte para múltiples idiomas (en, fr, de, it, etc.)
- Auto-detección del idioma fuente
- Traducción instantánea y precisa

#### `/seguir`
Activar notificaciones para nuevas publicaciones
- Sigue canales de YouTube, Twitter, Twitch y Kick
- Notificaciones automáticas en tu canal elegido
- Mantén a tu comunidad actualizada

#### `/sugerir`
Enviar sugerencias al canal configurado
- Sistema de sugerencias con botones de validación
- Creación automática de hilos para discusión
- Moderación por administradores

### Comandos de Entretenimiento

#### `/8ball [pregunta]`
Obtener respuestas místicas a tus preguntas
- Respuestas aleatorias
- Divertido y entretenido
- Experiencia clásica de bola mágica 8

#### `/ahorcado [dificultad]`
Jugar al ahorcado
- Múltiples niveles de dificultad
- Categorías de palabras
- Jugabilidad interactiva

#### `/chess [oponente]`
Jugar ajedrez con otros usuarios
- Implementación completa de ajedrez
- Jugabilidad por turnos
- Validación de movimientos

#### `/osint [dificultad]`
Juego de OSINT (Inteligencia de Fuentes Abiertas)
- Educativo y divertido
- Múltiples niveles de dificultad
- Aprender técnicas de investigación

#### `/amor [usuario1] [usuario2]`
Calcular compatibilidad amorosa entre usuarios
- Algoritmo de compatibilidad
- Resultados divertidos y detallados

#### `/abrazo [usuario]`
Abrazar a otro usuario
- Animaciones y mensajes personalizados
- Interacción social divertida

#### `/beso [usuario]`
Besar a otro usuario
- Animaciones y mensajes personalizados
- Interacción social divertida

#### `/golpe [usuario]`
Golpear juguetonamente a otro usuario
- Animaciones y mensajes personalizados
- Interacción social divertida

#### `/howgay [usuario]`
Calculadora divertida de porcentaje gay
- Resultados aleatorios y divertidos
- Sin intención ofensiva

#### `/giveaway`
Crear y gestionar sorteos
- Sistema completo de sorteos
- Configuración de premios y duración
- Selección automática de ganadores

### Comandos de Música

#### `/play [canción/url]`
Reproducir música de varias fuentes
- Soporte para YouTube, Spotify, SoundCloud
- Gestión de cola
- Audio de alta calidad

#### `/search [término]`
Buscar canciones en YouTube
- Resultados interactivos
- Selección múltiple de canciones

#### `/pause`
Pausar la reproducción actual

#### `/resume`
Reanudar la reproducción pausada

#### `/stop`
Detener reproducción y limpiar cola

#### `/skip`
Saltar canción actual

#### `/queue`
Mostrar cola de música actual
- Lista de canciones con duraciones
- Indicadores de posición en cola
- Tiempo total de cola

#### `/nowplaying`
Mostrar canción reproduciéndose actualmente
- Información y progreso de la canción
- Miniatura y duración
- Información del solicitante

#### `/volume [nivel]`
Ajustar volumen de reproducción (0-100)

#### `/shuffle`
Mezclar la cola

#### `/loop`
Alternar modo de bucle

#### `/clear`
Limpiar cola de reproducción

#### `/remove [posición]`
Remover canción específica de la cola

---

## Sistemas de Seguridad

### Protección Anti-Enlaces (`/antilinks`)
- Solo el propietario del servidor puede configurar
- Sanciona automáticamente a usuarios que envíen enlaces no autorizados
- Sistema de confirmación para activar/desactivar

### Protección Anti-Bot (`/antibot`)
- Detecta y previene la entrada de bots no autorizados
- Configuración automática de verificación

### Protección Anti-Ban (`/antiban`)
- Previene baneos masivos de miembros
- Alertas automáticas al propietario

### Protección Anti-Kick (`/antikick`)
- Previene expulsiones masivas de miembros
- Sistema de detección automática

### Protección Anti-Canales (`/antichannels`)
- Previene la creación masiva de canales
- Protección contra raids

### Protección Anti-Roles (`/antirole`)
- Previene la creación masiva de roles
- Protección contra modificaciones no autorizadas

### Protección Anti-Webhook (`/antiwebhookcreate`, `/antiwebhookspam`)
- Previene la creación no autorizada de webhooks
- Protección contra spam de webhooks

### Filtro NSFW (`/antinsfw`)
- Detecta y filtra contenido inapropiado
- Configuración automática

### Protección Anti-Client (`/anticlientapp`)
- Detecta aplicaciones cliente modificadas
- Prevención de exploits

### Detección de Ghost Ping (`/ghostping`)
- Detecta mensajes que son eliminados rápidamente
- Prevención de acoso sutil

### Protección Anti-Mass Role (`/massrole`)
- Previene la asignación masiva de roles
- Protección contra modificaciones no autorizadas

### Estado de Seguridad (`/estado`)
- Muestra el estado de todos los sistemas de seguridad
- Información detallada de cada protección

### Alertas del Propietario (`/owneralerts`)
- Sistema de alertas especiales para el propietario
- Notificaciones de eventos importantes

---

## Comandos de Configuración

### `/setup autoroles`
Gestiona roles automáticos
- **`agregar`** - Agregar rol automático
- **`eliminar`** - Eliminar rol automático
- **`listar`** - Listar roles automáticos

### `/setup logs`
Activa o desactiva los logs del servidor
- **`activar`** - Habilitar sistema de logs
- **`desactivar`** - Deshabilitar sistema de logs
- **`[canal]`** - Canal para los logs (opcional)

### `/setup sugerencias`
Configura el canal de sugerencias
- **`[canal]`** - Canal donde se enviarán las sugerencias

### `/setup reactionroles`
Configura un sistema de reaction roles
- Sistema interactivo de configuración
- Creación de mensajes con reacciones automáticas

### `/setup whitelist`
Configura usuarios o roles autorizados
- **`add`** - Agregar usuario/rol a la whitelist
- **`remove`** - Remover usuario/rol de la whitelist
- **`list`** - Listar usuarios/roles en la whitelist

### `/setup badwords`
Configura el sistema de filtrado de malas palabras
- **`add`** - Agregar palabra a la lista negra
- **`remove`** - Remover palabra de la lista negra
- **`list`** - Listar palabras en la lista negra

### `/setup welcome`
Configura el sistema de bienvenida
- Redirige al dashboard web para configuración avanzada
- Mensajes y embeds personalizados
- Opciones de asignación de roles

---

## Comandos de Moderación

### `/ban [usuario]`
Banear usuarios del servidor
- Modal interactivo para razón, duración y pruebas
- Confirmación antes de ejecutar
- Registro automático de sanciones

### `/kick [usuario]`
Expulsar usuarios del servidor
- Modal interactivo para razón y pruebas
- Confirmación antes de ejecutar
- Registro automático de sanciones

### `/timeout [usuario]`
Silenciar usuarios temporalmente
- Configuración de duración
- Modal para razón y pruebas
- Confirmación antes de ejecutar

### `/purge [cantidad]`
Limpiar mensajes del canal
- Eliminación masiva de mensajes
- Filtros por usuario o tipo
- Confirmación antes de ejecutar

### `/historial [usuario]`
Ver historial de sanciones
- Lista completa de sanciones
- Información detallada de cada caso
- Navegación interactiva

### `/notas`
Sistema de notas de moderación
- Agregar notas sobre usuarios
- Consultar notas existentes
- Gestión de información de moderación

---

## Sistema de Tickets

### `/ticket create`
Crear un nuevo ticket
- Sistema automático de creación de canales
- Configuración de permisos automática
- Mensaje de bienvenida personalizado

### `/ticket claim`
Reclamar un ticket existente
- Para moderadores y administradores
- Asignación de responsabilidad

### `/ticket rename [nombre]`
Renombrar el ticket actual
- Cambio de nombre del canal
- Registro de cambios

### `/ticket adduser [usuario]`
Agregar usuario al ticket
- Dar acceso a usuarios específicos
- Gestión de permisos

### `/ticket removeuser [usuario]`
Remover usuario del ticket
- Revocar acceso de usuarios
- Gestión de permisos

### `/ticket done`
Cerrar el ticket
- Cierre automático del canal
- Generación de transcripción
- Archivo de conversación

### `/ticket setup`
Configuración interactiva del sistema de tickets
- Flujo guiado de configuración
- Configuración de roles y permisos
- Personalización de mensajes

### `/ticket updatepanel`
Actualizar panel de tickets
- Actualización automática del panel principal
- Sincronización con configuración

### `/ticket setlimit [límite]`
Establecer límite de tickets por usuario
- Control de spam de tickets
- Configuración por administradores

---

## Soporte

- **Dashboard:** [https://www.freewingsbot.com](https://www.freewingsbot.com)
- **Servidor de Soporte:** [https://discord.gg/Sp9GTrmcQG](https://discord.gg/Sp9GTrmcQG)
- **Desarrollador:** @diamondclass
- **Organización:** Citymoon Dynamics

### Obtener Ayuda
1. Usa `/empezar` para ayuda interactiva
2. Visita nuestro servidor de soporte para asistencia de la comunidad
3. Revisa el dashboard para guías detalladas de configuración
4. Contacta al equipo de desarrollo para problemas técnicos

---

*Freewings Bot - Gestión Integral de Servidores de Discord*
*Desarrollado con ❤️ por Citymoon Dynamics y @diamondclass*
