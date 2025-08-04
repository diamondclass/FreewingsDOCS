# Freewings Bot - Deutsche Dokumentation

## Inhaltsverzeichnis
1. [Erste Schritte](#erste-schritte)
2. [Befehlskategorien](#befehlskategorien)
3. [Öffentliche Befehle](#öffentliche-befehle)
4. [Sicherheitssysteme](#sicherheitssysteme)
5. [Setup-Befehle](#setup-befehle)
6. [Support](#support)

---

## Erste Schritte

Freewings ist ein umfassender Discord-Bot, entwickelt von [Citymoon Dynamics](https://discord.gg/Sp9GTrmcQG) und **@diamondclass**. Der Bot bietet Sicherheits-, Moderations-, Community-, Unterhaltungs- und Utility-Funktionen für Discord-Server.

### Schnellstart
1. Verwenden Sie `/empezar`, um alle verfügbaren Funktionen zu erkunden
2. Besuchen Sie das [Dashboard](https://www.freewingsbot.com) für erweiterte Konfiguration
3. Verwenden Sie `/setup`-Befehle zur Konfiguration von Server-Funktionen (erfordert Administrator-Berechtigung)

---

## Befehlskategorien

### 🏠 Startseite
- **`/empezar`** - Interaktiver Leitfaden zur Erkundung aller Bot-Funktionen

### 🫂 Community
- **`/user`** - Benutzerinformationen und -verwaltung
- **`/server`** - Serverinformationen und -statistiken
- **`/channel`** - Kanalinformationen und -verwaltung
- **`/bot`** - Bot-Informationen und -statistiken
- **`/traducir`** - Google Translate-Integration
- **`/seguir`** - Social Media-Konten für Benachrichtigungen folgen
- **`/sugerir`** - Vorschläge an den konfigurierten Kanal senden

### 🎮 Mini-Spiele
- **`/ahorcado`** - Galgenmännchen-Spiel mit mehreren Schwierigkeitsstufen
- **`/chess`** - Schachspiel
- **`/osint`** - OSINT (Open Source Intelligence) Spiel

### 🙈 Spaß
- **`/8ball`** - Magische 8-Ball-Antworten
- **`/abrazo`** - Jemanden umarmen
- **`/golpe`** - Spielerische Schlag-Aktion
- **`/amor`** - Liebeskompatibilität
- **`/beso`** - Jemanden küssen
- **`/howgay`** - Spaßiger Gay-Prozentsatz-Rechner
- **`/giveaway`** - Giveaways erstellen und verwalten

### 🎵 Musik
- **`/play`** - Musik aus verschiedenen Quellen abspielen
- **`/pause`** - Aktuelle Wiedergabe pausieren
- **`/resume`** - Pausierte Wiedergabe fortsetzen
- **`/stop`** - Wiedergabe stoppen und Warteschlange löschen
- **`/skip`** - Aktuellen Song überspringen
- **`/queue`** - Aktuelle Warteschlange anzeigen
- **`/nowplaying`** - Aktuell abgespielten Song anzeigen
- **`/volume`** - Wiedergabelautstärke anpassen
- **`/shuffle`** - Warteschlange mischen
- **`/loop`** - Loop-Modus umschalten
- **`/clear`** - Wiedergabewarteschlange löschen
- **`/remove`** - Bestimmten Song aus der Warteschlange entfernen

### 🛡️ Sicherheit
- **`/antilinks`** - Anti-Links-Schutzsystem
- **`/antibot`** - Schutz vor nicht autorisierten Bots
- **`/antiban`** - Schutz vor Massen-Banns
- **`/antikick`** - Schutz vor Massen-Kicks
- **`/antichannels`** - Schutz vor Massen-Kanalerstellung
- **`/antirole`** - Schutz vor Massen-Rollenerstellung
- **`/antiwebhookcreate`** - Schutz vor Webhook-Erstellung
- **`/antiwebhookspam`** - Schutz vor Webhook-Spam
- **`/antinsfw`** - NSFW-Inhaltsfilter
- **`/anticlientapp`** - Schutz vor modifizierten Client-Anwendungen
- **`/ghostping`** - Ghost-Ping-Erkennung
- **`/massrole`** - Schutz vor Massen-Rollenzuweisung
- **`/estado`** - Status aller Sicherheitssysteme
- **`/owneralerts`** - Owner-Alert-System

### 🔨 Moderation
- **`/ban`** - Benutzer bannen
- **`/kick`** - Benutzer kicken
- **`/timeout`** - Benutzer timeout geben
- **`/purge`** - Nachrichten löschen
- **`/historial`** - Sanktionsverlauf anzeigen
- **`/notas`** - Moderationsnotizen-System

### 🎫 Tickets
- **`/ticket create`** - Ein neues Ticket erstellen
- **`/ticket claim`** - Ein bestehendes Ticket beanspruchen
- **`/ticket rename [name]`** - Das aktuelle Ticket umbenennen
- **`/ticket adduser [user]`** - Benutzer zum Ticket hinzufügen
- **`/ticket removeuser [user]`** - Benutzer aus Ticket entfernen
- **`/ticket done`** - Das Ticket schließen
- **`/ticket setup`** - Interaktive Ticket-System-Konfiguration
- **`/ticket updatepanel`** - Ticket-Panel aktualisieren
- **`/ticket setlimit [limit]`** - Ticket-Limit pro Benutzer festlegen

### ⚙️ Setup
- **`/setup`** - Haupt-Setup-Befehl mit verschiedenen Unterbefehlen für Serverkonfiguration

---

## Öffentliche Befehle

### Community-Befehle

#### `/user [user]`
Detaillierte Benutzerinformationen anzeigen
- **Unterbefehle:**
  - `info` - Vollständige Benutzerinformationen
  - `avatar` - Benutzer-Avatar
  - `banner` - Benutzer-Banner
  - `roles` - Benutzer-Rollen
  - `permissions` - Benutzer-Berechtigungen
- Enthält Badges, Aktivitätsstatus und interaktive Navigation

#### `/server`
Serverinformationen und -statistiken anzeigen
- **Unterbefehle:**
  - `info` - Allgemeine Serverinformationen
  - `stats` - Detaillierte Statistiken
  - `icon` - Server-Icon
  - `banner` - Server-Banner
  - `boosts` - Boost-Informationen
- Enthält Echtzeit-Statistiken und spezielle Funktionen

#### `/channel [channel]`
Kanalinformationen und -verwaltung
- **Unterbefehle:**
  - `info` - Vollständige Kanalinformationen
  - `permissions` - Kanal-Berechtigungen anzeigen
  - `roles` - Rollen mit Kanalzugang
  - `nuke` - Kanal vollständig bereinigen
- ⚠️ **Nuke** erfordert Administrator-Berechtigungen und löscht ALLE Nachrichten

#### `/bot`
Bot-Informationen und -statistiken anzeigen
- **Unterbefehle:**
  - `info` - Allgemeine Bot-Informationen
  - `icon` - Bot-Icon
- Enthält Server- und Benutzerstatistiken, Latenz und Speichernutzung

#### `/traducir [text] [target_language]`
Text mit Google Translate übersetzen
- Interaktives Modal zum Übersetzen von beliebigem Text
- Unterstützung für mehrere Sprachen (en, fr, de, it, etc.)
- Auto-Erkennung der Quellsprache
- Sofortige und präzise Übersetzung

#### `/seguir`
Benachrichtigungen für neue Beiträge aktivieren
- Folgen Sie YouTube-, Twitter-, Twitch- und Kick-Kanälen
- Automatische Benachrichtigungen in Ihrem gewählten Kanal
- Halten Sie Ihre Community auf dem Laufenden

#### `/sugerir`
Vorschläge an den konfigurierten Kanal senden
- Vorschlagssystem mit Validierungsbuttons
- Automatische Thread-Erstellung für Diskussionen
- Moderation durch Administratoren

### Unterhaltungsbefehle

#### `/8ball [question]`
Mystische Antworten auf Ihre Fragen erhalten
- Zufällige Antworten
- Spaßig und unterhaltsam
- Klassisches Magischer-8-Ball-Erlebnis

#### `/ahorcado [difficulty]`
Galgenmännchen-Spiel spielen
- Mehrere Schwierigkeitsstufen
- Wortkategorien
- Interaktives Gameplay

#### `/chess [opponent]`
Schach mit anderen Benutzern spielen
- Vollständige Schach-Implementierung
- Rundenbasiertes Gameplay
- Zug-Validierung

#### `/osint [difficulty]`
OSINT (Open Source Intelligence) Spiel
- Lehrreich und spaßig
- Mehrere Schwierigkeitsstufen
- Untersuchungstechniken lernen

#### `/amor [user1] [user2]`
Liebeskompatibilität zwischen Benutzern berechnen
- Kompatibilitätsalgorithmus
- Spaßige und detaillierte Ergebnisse

#### `/abrazo [user]`
Jemanden umarmen
- Benutzerdefinierte Animationen und Nachrichten
- Spaßige soziale Interaktion

#### `/beso [user]`
Jemanden küssen
- Benutzerdefinierte Animationen und Nachrichten
- Spaßige soziale Interaktion

#### `/golpe [user]`
Jemanden spielerisch schlagen
- Benutzerdefinierte Animationen und Nachrichten
- Spaßige soziale Interaktion

#### `/howgay [user]`
Spaßiger Gay-Prozentsatz-Rechner
- Zufällige und spaßige Ergebnisse
- Keine beleidigende Absicht

#### `/giveaway`
Giveaways erstellen und verwalten
- Vollständiges Giveaway-System
- Preis- und Dauerkonfiguration
- Automatische Gewinnerauswahl

### Musik-Befehle

#### `/play [song/url]`
Musik aus verschiedenen Quellen abspielen
- YouTube-, Spotify-, SoundCloud-Unterstützung
- Warteschlangen-Verwaltung
- Hochwertige Audioqualität

#### `/search [term]`
Nach Songs auf YouTube suchen
- Interaktive Ergebnisse
- Mehrfache Songauswahl

#### `/pause`
Aktuelle Wiedergabe pausieren

#### `/resume`
Pausierte Wiedergabe fortsetzen

#### `/stop`
Wiedergabe stoppen und Warteschlange löschen

#### `/skip`
Aktuellen Song überspringen

#### `/queue`
Aktuelle Musik-Warteschlange anzeigen
- Song-Liste mit Dauern
- Warteschlangen-Positionsanzeiger
- Gesamte Warteschlangenzeit

#### `/nowplaying`
Aktuell abgespielten Song anzeigen
- Song-Informationen und Fortschritt
- Thumbnail und Dauer
- Anforderer-Informationen

#### `/volume [level]`
Wiedergabelautstärke anpassen (0-100)

#### `/shuffle`
Warteschlange mischen

#### `/loop`
Loop-Modus umschalten

#### `/clear`
Wiedergabewarteschlange löschen

#### `/remove [position]`
Bestimmten Song aus der Warteschlange entfernen

---

## Sicherheitssysteme

### Anti-Links-Schutz (`/antilinks`)
- Nur der Serverbesitzer kann konfigurieren
- Sanktioniert automatisch Benutzer, die nicht autorisierte Links senden
- Bestätigungssystem zum Aktivieren/Deaktivieren

### Anti-Bot-Schutz (`/antibot`)
- Erkennt und verhindert nicht autorisierten Bot-Eintritt
- Automatische Verifikationskonfiguration

### Anti-Ban-Schutz (`/antiban`)
- Verhindert Massen-Banns von Mitgliedern
- Automatische Alerts an den Besitzer

### Anti-Kick-Schutz (`/antikick`)
- Verhindert Massen-Kicks von Mitgliedern
- Automatisches Erkennungssystem

### Anti-Kanal-Schutz (`/antichannels`)
- Verhindert Massen-Kanalerstellung
- Schutz vor Raids

### Anti-Rollen-Schutz (`/antirole`)
- Verhindert Massen-Rollenerstellung
- Schutz vor nicht autorisierten Änderungen

### Anti-Webhook-Schutz (`/antiwebhookcreate`, `/antiwebhookspam`)
- Verhindert nicht autorisierte Webhook-Erstellung
- Schutz vor Webhook-Spam

### NSFW-Filter (`/antinsfw`)
- Erkennt und filtert unangemessene Inhalte
- Automatische Konfiguration

### Anti-Client-Schutz (`/anticlientapp`)
- Erkennt modifizierte Client-Anwendungen
- Exploit-Prävention

### Ghost-Ping-Erkennung (`/ghostping`)
- Erkennt schnell gelöschte Nachrichten
- Prävention subtiler Belästigung

### Anti-Massen-Rollen-Schutz (`/massrole`)
- Verhindert Massen-Rollenzuweisung
- Schutz vor nicht autorisierten Änderungen

### Sicherheitsstatus (`/estado`)
- Zeigt Status aller Sicherheitssysteme
- Detaillierte Informationen für jeden Schutz

### Owner-Alerts (`/owneralerts`)
- Spezielles Alert-System für den Besitzer
- Wichtige Ereignisbenachrichtigungen

---

## Setup-Befehle

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
Vorschlagskanal konfigurieren
- **`[channel]`** - Kanal, in den Vorschläge gesendet werden

### `/setup reactionroles`
Reaction-Rollen-System konfigurieren
- Interaktives Konfigurationssystem
- Erstellung von Nachrichten mit automatischen Reaktionen

### `/setup whitelist`
Autorisierte Benutzer oder Rollen konfigurieren
- **`add`** - Benutzer/Rolle zur Whitelist hinzufügen
- **`remove`** - Benutzer/Rolle aus Whitelist entfernen
- **`list`** - Benutzer/Rollen in Whitelist auflisten

### `/setup badwords`
Schimpfwort-Filtersystem konfigurieren
- **`add`** - Wort zur Blacklist hinzufügen
- **`remove`** - Wort aus Blacklist entfernen
- **`list`** - Wörter in Blacklist auflisten

### `/setup welcome`
Willkommenssystem konfigurieren
- Leitet zum Web-Dashboard für erweiterte Konfiguration weiter
- Benutzerdefinierte Nachrichten und Embeds
- Rollenzuweisungsoptionen

---

## Moderationsbefehle

### `/ban [user]`
Benutzer vom Server bannen
- Interaktives Modal für Grund, Dauer und Beweis
- Bestätigung vor Ausführung
- Automatische Sanktionsprotokollierung

### `/kick [user]`
Benutzer vom Server kicken
- Interaktives Modal für Grund und Beweis
- Bestätigung vor Ausführung
- Automatische Sanktionsprotokollierung

### `/timeout [user]`
Benutzer temporär stummschalten
- Dauerkonfiguration
- Modal für Grund und Beweis
- Bestätigung vor Ausführung

### `/purge [amount]`
Nachrichten aus Kanal löschen
- Massen-Nachrichtenlöschung
- Filter nach Benutzer oder Typ
- Bestätigung vor Ausführung

### `/historial [user]`
Sanktionsverlauf anzeigen
- Vollständige Liste der Sanktionen
- Detaillierte Informationen für jeden Fall
- Interaktive Navigation

### `/notas`
Moderationsnotizen-System
- Notizen über Benutzer hinzufügen
- Bestehende Notizen abfragen
- Moderationsinformationsverwaltung

---

## Ticket-System

### `/ticket create`
Neues Ticket erstellen
- Automatisches Kanalerstellungssystem
- Automatische Berechtigungskonfiguration
- Benutzerdefinierte Willkommensnachricht

### `/ticket claim`
Bestehendes Ticket beanspruchen
- Für Moderatoren und Administratoren
- Verantwortungszuweisung

### `/ticket rename [name]`
Aktuelles Ticket umbenennen
- Kanalname-Änderung
- Änderungsprotokollierung

### `/ticket adduser [user]`
Benutzer zum Ticket hinzufügen
- Zugang für bestimmte Benutzer gewähren
- Berechtigungsverwaltung

### `/ticket removeuser [user]`
Benutzer aus Ticket entfernen
- Benutzerzugang widerrufen
- Berechtigungsverwaltung

### `/ticket done`
Ticket schließen
- Automatische Kanal-Schließung
- Transkript-Generierung
- Gesprächsarchivierung

### `/ticket setup`
Interaktive Ticket-System-Konfiguration
- Geführter Konfigurationsablauf
- Rollen- und Berechtigungskonfiguration
- Nachrichtenanpassung

### `/ticket updatepanel`
Ticket-Panel aktualisieren
- Automatische Hauptpanel-Aktualisierung
- Konfigurationssynchronisation

### `/ticket setlimit [limit]`
Ticket-Limit pro Benutzer festlegen
- Ticket-Spam-Kontrolle
- Administrator-Konfiguration

---

## Support

- **Dashboard:** [https://www.freewingsbot.com](https://www.freewingsbot.com)
- **Support-Server:** [https://discord.gg/Sp9GTrmcQG](https://discord.gg/Sp9GTrmcQG)
- **Entwickler:** @diamondclass
- **Organisation:** Citymoon Dynamics

### Hilfe erhalten
1. Verwenden Sie `/empezar` für interaktive Hilfe
2. Besuchen Sie unseren Support-Server für Community-Unterstützung
3. Schauen Sie im Dashboard nach detaillierten Konfigurationsleitfäden
4. Kontaktieren Sie das Entwicklungsteam bei technischen Problemen

---

*Freewings Bot - Umfassende Discord-Server-Verwaltung*
*Mit ❤️ entwickelt von Citymoon Dynamics und @diamondclass*
