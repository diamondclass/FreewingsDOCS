# Freewings Bot - Documentación en Español

## Tabla de Contenidos
1. [Primeros Pasos](#primeros-pasos)
2. [Categorías de Comandos](#categorías-de-comandos)
3. [Comandos Públicos](#comandos-públicos)
4. [Sistemas de Seguridad](#sistemas-de-seguridad)
5. [Comandos de Configuración](#comandos-de-configuración)
6. [Actualizaciones Recientes](#actualizaciones-recientes)
7. [Soporte](#soporte)

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

### 🛡️ Seguridad
- **`/antiraid`** - Sistema de protección anti-raid
- **`/antispam`** - Protección anti-spam
- **`/antilink`** - Sistema de filtrado de enlaces
- **`/captcha`** - Sistema de verificación CAPTCHA
- **`/automod`** - Moderación automática
- **`/badwords`** - Filtro de malas palabras
- **`/whitelist`** - Gestión de lista blanca
- **`/blacklist`** - Gestión de lista negra
- **`/verification`** - Sistema de verificación de usuarios
- **`/autorole`** - Asignación automática de roles
- **`/welcome`** - Sistema de mensajes de bienvenida
- **`/goodbye`** - Sistema de mensajes de despedida
- **`/logs`** - Sistema de registro del servidor
- **`/backup`** - Respaldo y restauración del servidor

### 🔨 Moderación
- **`/ban`** - Banear usuarios
- **`/unban`** - Desbanear usuarios
- **`/kick`** - Expulsar usuarios
- **`/timeout`** - Silenciar usuarios temporalmente
- **`/warn`** - Advertir usuarios
- **`/clear`** - Limpiar mensajes

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

### 👥 Staff
- **`/staff`** - Comandos de gestión de staff (acceso restringido)

---

## Comandos Públicos

### Comandos de Comunidad

#### `/user [usuario]`
Mostrar información detallada del usuario
- Perfil y estadísticas del usuario
- Fechas de unión y actividad
- Roles y permisos

#### `/server`
Mostrar información y estadísticas del servidor
- Conteo de miembros y estado en línea
- Fecha de creación del servidor
- Nivel de boost y características

#### `/channel [canal]`
Mostrar información del canal
- Tipo de canal y permisos
- Fecha de creación y estadísticas
- Información de acceso de miembros

#### `/bot`
Mostrar información y estadísticas del bot
- Tiempo de actividad y rendimiento
- Conteo de servidores y usuarios
- Versión y características

#### `/traducir [texto] [idioma_destino]`
Traducir texto usando Google Translate
- Soporte para múltiples idiomas
- Auto-detección del idioma fuente
- Traducciones de alta calidad

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

### Comandos de Música

#### `/play [canción/url]`
Reproducir música de varias fuentes
- Soporte para YouTube, Spotify, SoundCloud
- Gestión de cola
- Audio de alta calidad

#### `/nowplaying`
Mostrar canción reproduciéndose actualmente
- Información y progreso de la canción
- Miniatura y duración
- Información del solicitante

#### `/queue`
Mostrar cola de música actual
- Lista de canciones con duraciones
- Indicadores de posición en cola
- Tiempo total de cola

---

## Sistemas de Seguridad

### Protección Anti-Raid
Protección integral contra raids del servidor
- Detección de uniones masivas
- Acciones de moderación automática
- Umbrales configurables

### Sistema Anti-Spam
Detección y prevención avanzada de spam
- Análisis de frecuencia de mensajes
- Detección de mensajes duplicados
- Castigos automáticos

### Verificación CAPTCHA
Sistema de verificación humana
- Desafíos basados en imágenes
- Asignación automática de roles
- Prevención de detección de bots

### Gestión de Lista Blanca/Negra
Control de acceso de usuarios y roles
- Lista blanca para usuarios confiables
- Lista negra para usuarios problemáticos
- Sistema de permisos flexible

---

## Comandos de Configuración

### `/setup antiraid`
Configurar protección anti-raid
- **`activar`** - Habilitar sistema anti-raid
- **`desactivar`** - Deshabilitar sistema anti-raid
- **`configurar`** - Configuración interactiva

### `/setup antispam`
Configurar protección anti-spam
- **`activar`** - Habilitar sistema anti-spam
- **`desactivar`** - Deshabilitar sistema anti-spam
- **`configurar`** - Establecer umbrales de spam

### `/setup captcha`
Configurar verificación CAPTCHA
- **`activar [canal]`** - Habilitar CAPTCHA en canal especificado
- **`desactivar`** - Deshabilitar sistema CAPTCHA

### `/setup logs`
Configurar registro del servidor
- **`[canal]`** - Establecer canal de registro
- Registro integral de eventos
- Seguimiento de acciones de moderación

### `/setup welcome`
Configurar sistema de bienvenida
- Redirige al dashboard web
- Mensajes y embeds personalizados
- Opciones de asignación de roles

### `/setup sugerencias`
Configurar sistema de sugerencias
- **`[canal]`** - Establecer canal de sugerencias
- Sistema de reacciones automático
- Recopilación de comentarios de la comunidad

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
