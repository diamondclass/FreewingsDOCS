# Freewings Bot - Deutsche Dokumentation

## Inhaltsverzeichnis
1. [Erste Schritte](#erste-schritte)
2. [Befehls-Kategorien](#befehls-kategorien)
3. [Öffentliche Befehle](#öffentliche-befehle)
4. [Sicherheitssysteme](#sicherheitssysteme)
5. [Konfigurations-Befehle](#konfigurations-befehle)
6. [Support](#support)

---

## Erste Schritte

Freewings ist ein umfassender Discord-Bot, entwickelt von [Citymoon Dynamics](https://citymoon.es) und **@diamondclass**. Der Bot bietet Sicherheits-, Moderations-, Community-, Unterhaltungs- und Utility-Funktionen für Discord-Server.

### Schnellstart
1. Verwende `/empezar` um alle verfügbaren Funktionen zu erkunden
2. Besuche das [Dashboard](https://freewings.citymoon.es) für erweiterte Konfiguration
3. Verwende `/setup`-Befehle um Server-Funktionen zu konfigurieren (erfordert Administrator-Berechtigungen)

---

## Befehls-Kategorien

### 🏠 Zuhause
- **`/empezar`** - Interaktiver Guide um alle Bot-Funktionen zu erkunden

### 🫂 Community
- **`/user`** - Benutzer-Informationen und -Verwaltung
- **`/server`** - Server-Informationen und -Statistiken
- **`/channel`** - Kanal-Informationen und -Verwaltung
- **`/bot`** - Bot-Informationen und -Statistiken
- **`/traducir`** - Google Translate Integration
- **`/seguir`** - Social Media Accounts für Benachrichtigungen folgen
- **`/sugerir`** - Vorschläge an konfigurierten Kanal senden
- **`/recordatorio`** - Persönliches Erinnerungssystem per DM
- **`/nivel`** - Level- und XP-System mit Ranglisten

### 🎮 Minispiele
- **`/ahorcado`** - Galgenmännchen-Spiel mit mehreren Schwierigkeitsgraden
- **`/chess`** - Schachspiel
- **`/osint`** - OSINT (Open Source Intelligence) Spiel

### 🙈 Spaß
- **`/8ball`** - Magic 8 Ball Antworten
- **`/abrazo`** - Jemanden umarmen
- **`/golpe`** - Spielerischer Schlag
- **`/amor`** - Liebes-Kompatibilität
- **`/beso`** - Jemanden küssen
- **`/howgay`** - Lustiger Gay-Prozentsatz-Rechner
- **`/giveaway`** - Giveaways erstellen und verwalten

### 🎵 Musik
- **`/play`** - Musik von verschiedenen Quellen abspielen
- **`/pause`** - Aktuelle Wiedergabe pausieren
- **`/resume`** - Pausierte Wiedergabe fortsetzen
- **`/stop`** - Wiedergabe stoppen und Warteschlange leeren
- **`/skip`** - Aktuellen Song überspringen
- **`/queue`** - Aktuelle Warteschlange anzeigen
- **`/nowplaying`** - Aktuell abgespielten Song anzeigen
- **`/volume`** - Wiedergabe-Lautstärke anpassen
- **`/shuffle`** - Warteschlange mischen
- **`/loop`** - Loop-Modus umschalten
- **`/clear`** - Wiedergabe-Warteschlange leeren
- **`/remove`** - Bestimmten Song aus Warteschlange entfernen

### 🛡️ Sicherheit
- **`/antilinks`** - Erweitertes Anti-Link-Schutzsystem
- **`/filescan`** - Datei-Scanning mit VirusTotal
- **`/securitylogs`** - Sicherheits-Verletzungsverlauf
- **`/antibot`** - Schutz vor unbefugten Bots
- **`/antiban`** - Schutz vor Massen-Banns
- **`/antikick`** - Schutz vor Massen-Kicks
- **`/antichannels`** - Schutz vor Massen-Kanalerstellung
- **`/antirole`** - Schutz vor Massen-Rollenerstellung
- **`/antiwebhookcreate`** - Schutz vor Webhook-Erstellung
- **`/antiwebhookspam`** - Schutz vor Webhook-Spam
- **`/antinsfw`** - NSFW-Inhaltsfilter
- **`/anticlientapp`** - Schutz vor modifizierten Client-Anwendungen
- **`/ghostping`** - Ghost Ping-Erkennung
- **`/massrole`** - Schutz vor Massen-Rollenvergabe
- **`/estado`** - Status aller Sicherheitssysteme
- **`/owneralerts`** - Warnungen für Server-Besitzer

### 🔨 Moderation
- **`/ban`** - Benutzer bannen
- **`/kick`** - Benutzer kicken
- **`/timeout`** - Benutzer temporär stumm schalten
- **`/purge`** - Nachrichten löschen
- **`/historial`** - Sanktionsverlauf anzeigen
- **`/notas`** - Moderations-Notizen-System

### 🎫 Tickets
- **`/ticket create`** - Neues Ticket erstellen
- **`/ticket claim`** - Bestehendes Ticket beanspruchen
- **`/ticket rename [name]`** - Aktuelles Ticket umbenennen
- **`/ticket adduser [user]`** - Benutzer zum Ticket hinzufügen
- **`/ticket removeuser [user]`** - Benutzer vom Ticket entfernen
- **`/ticket done`** - Ticket schließen
- **`/ticket setup`** - Interaktive Ticket-System-Konfiguration
- **`/ticket updatepanel`** - Ticket-Panel aktualisieren
- **`/ticket setlimit [limit]`** - Ticket-Limit pro Benutzer setzen

### ⚙️ Konfiguration
- **`/setup`** - Haupt-Konfigurationsbefehl mit verschiedenen Unterbefehlen für Server-Konfiguration

---

## Öffentliche Befehle

### Community-Befehle

#### `/user [user]`
Detaillierte Benutzer-Informationen anzeigen
- **Unterbefehle:**
  - `info` - Vollständige Benutzer-Informationen
  - `avatar` - Benutzer-Avatar
  - `banner` - Benutzer-Banner
  - `roles` - Benutzer-Rollen
  - `permissions` - Benutzer-Berechtigungen
- Enthält Badges, Aktivitätsstatus und interaktive Navigation

#### `/server`
Server-Informationen und -Statistiken
- **Unterbefehle:**
  - `info` - Allgemeine Server-Informationen
  - `stats` - Detaillierte Statistiken
  - `icon` - Server-Icon
  - `banner` - Server-Banner
  - `boosts` - Boost-Informationen
- Enthält Echtzeit-Statistiken und Spezialfunktionen

#### `/channel [channel]`
Kanal-Informationen und -Verwaltung
- **Unterbefehle:**
  - `info` - Vollständige Kanal-Informationen
  - `permissions` - Kanal-Berechtigungen anzeigen
  - `roles` - Rollen mit Kanal-Zugang
  - `nuke` - Kanal vollständig säubern
- ⚠️ **Nuke** erfordert Administrator-Berechtigungen und löscht ALLE Nachrichten

#### `/bot`
Bot-Informationen und -Statistiken
- **Unterbefehle:**
  - `info` - Allgemeine Bot-Informationen
  - `icon` - Bot-Icon
- Enthält Server-Statistiken, Benutzer, Latenz und Speichernutzung

#### `/traducir [text] [zielsprache]`
Text mit Google Translate übersetzen
- Interaktives Modal zum Übersetzen von beliebigem Text
- Unterstützung für mehrere Sprachen (en, fr, de, it, etc.)
- Auto-Erkennung der Quellsprache
- Sofortige und präzise Übersetzung

#### `/seguir`
Benachrichtigungen für neue Posts aktivieren
- YouTube, Twitter, Twitch und Kick Kanäle folgen
- Automatische Benachrichtigungen in deinem gewählten Kanal
- Halte deine Community auf dem Laufenden

#### `/sugerir`
Vorschläge an konfigurierten Kanal senden
- Vorschlags-System mit Validierungs-Buttons
- Automatische Thread-Erstellung für Diskussion
- Moderation durch Administratoren

#### `/recordatorio`
Persönliches Erinnerungssystem
- **Grundverwendung:** `/recordatorio mensaje:"Meeting erinnern" fecha:"2024-12-25 15:30"`
- **Unterbefehle:**
  - `listar` - Aktive Erinnerungen anzeigen
  - `eliminar` - Bestimmte Erinnerung löschen
- **Funktionen:**
  - Automatische DM-Benachrichtigungen
  - Mehrere unterstützte Datumsformate
  - Persönliche Erinnerungsverwaltung
  - Automatische Überprüfung jede Minute

#### `/nivel`
Vollständiges Level- und XP-System
- **Unterbefehle:**
  - `perfil [user]` - Persönliche Statistiken oder das eines anderen Benutzers anzeigen
  - `leaderboard [page]` - Server-Rangliste mit Paginierung
  - `global [page]` - Globale Rangliste über alle Server
  - `config` - System-Konfiguration (nur Administratoren)
- **Funktionen:**
  - Automatisches XP durch Nachrichten und Sprachzeit
  - Freischaltbares Achievement-System
  - Anpassbare Level-Up-Nachrichten
  - Konfigurierbare Cooldowns zwischen Nachrichten
  - Detaillierte Aktivitätsstatistiken

### Unterhaltungs-Befehle

#### `/8ball [frage]`
Mystische Antworten auf deine Fragen erhalten
- Zufällige Antworten
- Lustig und unterhaltsam
- Klassische Magic 8 Ball Erfahrung

#### `/ahorcado [schwierigkeit]`
Galgenmännchen spielen
- Mehrere Schwierigkeitsgrade
- Wort-Kategorien
- Interaktives Gameplay

#### `/chess [gegner]`
Schach mit anderen Benutzern spielen
- Vollständige Schach-Implementierung
- Rundenbasiertes Gameplay
- Zug-Validierung

#### `/osint [schwierigkeit]`
OSINT (Open Source Intelligence) Spiel
- Lehrreich und lustig
- Mehrere Schwierigkeitsgrade
- Untersuchungstechniken lernen

#### `/amor [user1] [user2]`
Liebes-Kompatibilität zwischen Benutzern berechnen
- Kompatibilitäts-Algorithmus
- Lustige und detaillierte Ergebnisse

#### `/abrazo [user]`
Jemanden umarmen
- Angepasste Animationen und Nachrichten
- Lustige soziale Interaktion

#### `/beso [user]`
Jemanden küssen
- Angepasste Animationen und Nachrichten
- Lustige soziale Interaktion

#### `/golpe [user]`
Jemanden spielerisch schlagen
- Angepasste Animationen und Nachrichten
- Lustige soziale Interaktion

#### `/howgay [user]`
Lustiger Gay-Prozentsatz-Rechner
- Zufällige und lustige Ergebnisse
- Keine beleidigende Absicht

#### `/giveaway`
Giveaways erstellen und verwalten
- Vollständiges Giveaway-System
- Preis- und Dauer-Konfiguration
- Automatische Gewinner-Auswahl

### Musik-Befehle

#### `/play [song/url]`
Musik von verschiedenen Quellen abspielen
- Unterstützung für YouTube, Spotify, SoundCloud
- Warteschlangen-Verwaltung
- Hochwertiges Audio

#### `/search [term]`
Songs auf YouTube suchen
- Interaktive Ergebnisse
- Mehrfache Song-Auswahl

#### `/pause`
Aktuelle Wiedergabe pausieren

#### `/resume`
Pausierte Wiedergabe fortsetzen

#### `/stop`
Wiedergabe stoppen und Warteschlange leeren

#### `/skip`
Aktuellen Song überspringen

#### `/queue`
Aktuelle Musik-Warteschlange anzeigen
- Song-Liste mit Dauern
- Warteschlangen-Positions-Indikatoren
- Gesamte Warteschlangen-Zeit

#### `/nowplaying`
Aktuell abgespielten Song anzeigen
- Song-Informationen und Fortschritt
- Thumbnail und Dauer
- Anforderer-Informationen

#### `/volume [level]`
Wiedergabe-Lautstärke anpassen (0-100)

#### `/shuffle`
Warteschlange mischen

#### `/loop`
Loop-Modus umschalten

#### `/clear`
Wiedergabe-Warteschlange leeren

#### `/remove [position]`
Bestimmten Song aus Warteschlange entfernen

---

## Sicherheitssysteme

### Erweitertes Anti-Link-System (`/antilinks`)
**Neue Funktionen:**
- **Flexible Konfiguration:** Erlaubt Discord-Links, Bilder und Videos
- **Anpassbare Whitelist:** Erlaubte Domains pro Server
- **Strenger Modus:** Vollständige Blockierung nicht autorisierter Links
- **Sicherheitsanalyse:** Automatische Überprüfung verdächtiger URLs
- **Konfigurierbare Grenze:** Maximum Links pro Nachricht
- **Unterbefehle:**
  - `toggle` - System aktivieren/deaktivieren
  - `whitelist` - Erlaubte Domains verwalten
  - `config` - Erweiterte Konfiguration

### Datei-Scanning (`/filescan`)
**Neues Sicherheitssystem:**
- **VirusTotal-Integration:** Vollständige Datei-Analyse
- **API-Konfiguration:** Unterbefehl zum Konfigurieren des API-Schlüssels
- **Mehrere Formate:** Unterstützung für Anhänge und URLs
- **Detaillierte Analyse:** Erkennungsstatistiken und Empfehlungen
- **Größenlimit:** Bis zu 32MB pro Datei
- **Hash-Verifizierung:** Für bereits analysierte Dateien
- **Unterbefehle:**
  - `config` - VirusTotal API-Schlüssel konfigurieren
  - Direkte Verwendung mit Dateianhang oder URL

### Sicherheitsverlauf (`/securitylogs`)
**Neues Überwachungssystem:**
- **Vollständige Verfolgung:** Alle Sicherheitsverletzungen
- **Detaillierte Statistiken:** Nach Benutzer und Verletzungstyp
- **Automatische Eskalation:** 4 Schweregrade
- **Unterbefehle:**
  - `usuario` - Verlauf bestimmten Benutzers anzeigen
  - `servidor` - Allgemeine Server-Statistiken
  - `limpiar` - Alte Einträge löschen

### Level- und XP-System (`/nivel`)
**Neues Gamification-System:**
- **Automatisches XP:** Durch Nachrichten und Sprachzeit
- **Level-System:** Exponentielle Progression
- **Ranglisten:** Server und global
- **Freischaltbare Achievements:** Durch Aktivität und Level
- **Flexible Konfiguration:** XP, Cooldowns, Nachrichten
- **Unterbefehle:**
  - `perfil` - Persönliche Statistiken anzeigen
  - `leaderboard` - Server-Rangliste
  - `global` - Globale Rangliste
  - `config` - System-Konfiguration

### Erweitertes Anti-Spam-System
**Erweiterte Funktionen:**
- **Rate Limiting:** 5 Nachrichten in 10 Sekunden
- **Mustererkennung:** Spam, wiederholte Zeichen, Großbuchstaben
- **Inhaltsanalyse:** NSFW, Toxizität, verdächtige Links
- **Automatische Eskalation:** 4 Schweregrade (MINOR, MODERATE, SEVERE, EXTREME)
- **Automatische Timeouts:** Von 5 Minuten bis 7 Tage
- **Detaillierte Logs:** Vollständige Aufzeichnung im mod-logs Kanal

### Anti-Bot-Schutz (`/antibot`)
- Erkennt und verhindert unbefugten Bot-Eintritt
- Automatische Verifikations-Konfiguration

### Anti-Ban-Schutz (`/antiban`)
- Verhindert Massen-Banns von Mitgliedern
- Automatische Besitzer-Warnungen

### Anti-Kick-Schutz (`/antikick`)
- Verhindert Massen-Kicks von Mitgliedern
- Automatisches Erkennungssystem

### Anti-Kanal-Schutz (`/antichannels`)
- Verhindert Massen-Kanalerstellung
- Schutz vor Raids

### Anti-Rollen-Schutz (`/antirole`)
- Verhindert Massen-Rollenerstellung
- Schutz vor unbefugten Änderungen

### Anti-Webhook-Schutz (`/antiwebhookcreate`, `/antiwebhookspam`)
- Verhindert unbefugte Webhook-Erstellung
- Schutz vor Webhook-Spam

### NSFW-Filter (`/antinsfw`)
- Erkennt und filtert unangemessene Inhalte
- Automatische Konfiguration

### Anti-Client-Schutz (`/anticlientapp`)
- Erkennt modifizierte Client-Anwendungen
- Exploit-Prävention

### Ghost Ping-Erkennung (`/ghostping`)
- Erkennt schnell gelöschte Nachrichten
- Prävention subtiler Belästigung

### Anti-Massen-Rollen-Schutz (`/massrole`)
- Verhindert Massen-Rollenvergabe
- Schutz vor unbefugten Änderungen

### Sicherheitsstatus (`/estado`)
- Zeigt Status aller Sicherheitssysteme
- Detaillierte Informationen für jeden Schutz

### Besitzer-Warnungen (`/owneralerts`)
- Spezielles Warnungssystem für Besitzer
- Wichtige Ereignis-Benachrichtigungen

---

## Konfigurations-Befehle

### `/setup autoroles`
Automatische Rollen verwalten
- **`agregar`** - Automatische Rolle hinzufügen
- **`eliminar`** - Automatische Rolle entfernen
- **`listar`** - Automatische Rollen auflisten

### `/setup logs`
Server-Logs aktivieren oder deaktivieren
- **`activar`** - Logging-System aktivieren
- **`desactivar`** - Logging-System deaktivieren
- **`[channel]`** - Kanal für Logs (optional)

### `/setup sugerencias`
Vorschlags-Kanal konfigurieren
- **`[channel]`** - Kanal wo Vorschläge gesendet werden

### `/setup reactionroles`
Reaction-Roles-System konfigurieren
- Interaktives Konfigurationssystem
- Automatische Reaction-Nachrichten-Erstellung

### `/setup whitelist`
Autorisierte Benutzer oder Rollen konfigurieren
- **`add`** - Benutzer/Rolle zur Whitelist hinzufügen
- **`remove`** - Benutzer/Rolle von Whitelist entfernen
- **`list`** - Benutzer/Rollen in Whitelist auflisten

### `/setup badwords`
Schlechte-Wörter-Filterungssystem konfigurieren
- **`add`** - Wort zur Blacklist hinzufügen
- **`remove`** - Wort von Blacklist entfernen
- **`list`** - Wörter in Blacklist auflisten

### `/setup welcome`
Willkommens-System konfigurieren
- Leitet zum Web-Dashboard für erweiterte Konfiguration weiter
- Angepasste Nachrichten und Embeds
- Rollen-Zuweisungsoptionen

---

## Moderations-Befehle

### `/ban [user]`
Benutzer vom Server bannen
- Interaktives Modal für Grund, Dauer und Beweise
- Bestätigung vor Ausführung
- Automatische Sanktions-Aufzeichnung

### `/kick [user]`
Benutzer vom Server kicken
- Interaktives Modal für Grund und Beweise
- Bestätigung vor Ausführung
- Automatische Sanktions-Aufzeichnung

### `/timeout [user]`
Benutzer temporär stumm schalten
- Dauer-Konfiguration
- Modal für Grund und Beweise
- Bestätigung vor Ausführung

### `/purge [amount]`
Kanal-Nachrichten säubern
- Massen-Nachrichtenlöschung
- Benutzer- oder Typ-Filter
- Bestätigung vor Ausführung

### `/historial [user]`
Sanktionsverlauf anzeigen
- Vollständige Sanktionsliste
- Detaillierte Informationen für jeden Fall
- Interaktive Navigation

### `/notas`
Moderations-Notizen-System
- Notizen über Benutzer hinzufügen
- Bestehende Notizen konsultieren
- Moderations-Informationsverwaltung

---

## Ticket-System

### `/ticket create`
Neues Ticket erstellen
- Automatisches Kanal-Erstellungssystem
- Automatische Berechtigungs-Konfiguration
- Angepasste Willkommensnachricht

### `/ticket claim`
Bestehendes Ticket beanspruchen
- Für Moderatoren und Administratoren
- Verantwortlichkeits-Zuweisung

### `/ticket rename [name]`
Aktuelles Ticket umbenennen
- Kanal-Namenänderung
- Änderungs-Aufzeichnung

### `/ticket adduser [user]`
Benutzer zum Ticket hinzufügen
- Zugang für bestimmte Benutzer gewähren
- Berechtigungs-Verwaltung

### `/ticket removeuser [user]`
Benutzer vom Ticket entfernen
- Benutzer-Zugang widerrufen
- Berechtigungs-Verwaltung

### `/ticket done`
Ticket schließen
- Automatische Kanal-Schließung
- Transkript-Generierung
- Gesprächs-Archivierung

### `/ticket setup`
Interaktive Ticket-System-Konfiguration
- Geführter Konfigurationsablauf
- Rollen- und Berechtigungs-Konfiguration
- Nachrichten-Anpassung

### `/ticket updatepanel`
Ticket-Panel aktualisieren
- Automatische Haupt-Panel-Aktualisierung
- Konfigurations-Synchronisation

### `/ticket setlimit [limit]`
Ticket-Limit pro Benutzer setzen
- Ticket-Spam-Kontrolle
- Administrator-Konfiguration

---

## Support

- **Dashboard:** [https://www.freewingsbot.com](https://www.freewingsbot.com)
- **Support-Server:** [https://discord.gg/Sp9GTrmcQG](https://discord.gg/Sp9GTrmcQG)
- **Entwickler:** @diamondclass
- **Organisation:** Citymoon Dynamics

### Hilfe erhalten
1. Verwende `/empezar` für interaktive Hilfe
2. Besuche unseren Support-Server für Community-Unterstützung
3. Überprüfe das Dashboard für detaillierte Konfigurationsanleitungen
4. Kontaktiere das Entwicklungsteam für technische Probleme

---

*Freewings Bot - Umfassende Discord-Server-Verwaltung*
*Entwickelt mit ❤️ von Citymoon Dynamics und @diamondclass*
