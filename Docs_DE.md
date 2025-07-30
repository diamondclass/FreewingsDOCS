# Freewings Bot Dokumentation

## Inhaltsverzeichnis
1. [Erste Schritte](#erste-schritte)
2. [Befehlskategorien](#befehlskategorien)
3. [Öffentliche Befehle](#öffentliche-befehle)
4. [Sicherheitssysteme](#sicherheitssysteme)
5. [Setup-Befehle](#setup-befehle)
6. [Support](#support)

---

## Erste Schritte

Freewings ist ein umfassender Discord-Bot, entwickelt von [NearDevs](https://discord.gg/Sp9GTrmcQG) und **@diamondclass**. Der Bot bietet Sicherheits-, Moderations-, Community-, Unterhaltungs- und Utility-Funktionen für Discord-Server.

### Schnellstart
1. Verwenden Sie `/empezar`, um alle verfügbaren Funktionen zu erkunden
2. Besuchen Sie das [Dashboard](https://www.freewingsbot.com) für erweiterte Konfiguration
3. Verwenden Sie `/setup`-Befehle, um Serverfunktionen zu konfigurieren (erfordert Administrator-Berechtigungen)

---

## Befehlskategorien

### 🏠 Startseite (Hogar)
- **`/empezar`** - Interaktiver Leitfaden zur Erkundung aller Bot-Funktionen

### 🫂 Community (Comunidad)
- **`/user`** - Benutzerinformationen und -verwaltung
- **`/server`** - Serverinformationen und Statistiken
- **`/channel`** - Kanalinformationen und -verwaltung
- **`/bot`** - Bot-Informationen und Statistiken
- **`/traducir`** - Google Translate-Integration
- **`/seguir`** - Social Media-Konten für Benachrichtigungen folgen
- **`/sugerir`** - Vorschläge an den konfigurierten Kanal senden

### 🎮 Mini-Spiele (Minijuegos)
- **`/ahorcado`** - Galgenmännchen-Spiel mit mehreren Schwierigkeitsgraden
- **`/chess`** - Schachspiel
- **`/osint`** - OSINT (Open Source Intelligence) Spiel

### 🙈 Spaß (Diversión)
- **`/8ball`** - Magische 8-Ball-Antworten
- **`/abrazo`** - Jemanden umarmen
- **`/golpe`** - Spielerische Schlag-Aktion
- **`/amor`** - Liebeskompatibilität
- **`/beso`** - Jemanden küssen
- **`/giveaway`** - Verlosungen erstellen
- **`/howgay`** - Lustige Gay-Prozentrechner

### 🔩 Einrichtung
- **`/setup`** - Serverfunktionen konfigurieren (Nur Administrator)

---

## Öffentliche Befehle

### `/empezar` - Erste Schritte
**Beschreibung:** Interaktiver Leitfaden zur Erkundung aller Freewings-Funktionen
**Verwendung:** `/empezar`
**Funktionen:**
- Interaktives Menüsystem
- Kategorie-basierte Befehlserkundung
- Echtzeit-Bot-Statistiken
- Direkte Links zum Dashboard

### `/user` - Benutzerinformationen
**Beschreibung:** Umfassende Benutzerinformationen und -verwaltung
**Unterbefehle:**
- **`info`** - Vollständige Benutzerinformationen einschließlich Abzeichen, Beitrittsdatum, Rollen
- **`avatar`** - Benutzer-Avatar in hoher Auflösung anzeigen
- **`banner`** - Benutzer-Banner anzeigen (falls verfügbar)
- **`roles`** - Alle Benutzerrollen auf dem Server auflisten
- **`permissions`** - Wichtige Benutzerberechtigungen anzeigen

**Verwendungsbeispiele:**
```
/user info @benutzername
/user avatar
/user banner @benutzername
/user roles @benutzername
/user permissions @benutzername
```

### `/server` - Serverinformationen
**Beschreibung:** Serverstatistiken und -informationen
**Unterbefehle:**
- **`info`** - Allgemeine Serverinformationen
- **`stats`** - Detaillierte Serverstatistiken
- **`icon`** - Server-Icon
- **`banner`** - Server-Banner
- **`boosts`** - Boost-Informationen

### `/channel` - Kanalverwaltung
**Beschreibung:** Kanalinformationen und Verwaltungstools
**Unterbefehle:**
- **`info`** - Vollständige Kanalinformationen
- **`permissions`** - Kanalberechtigungsübersicht
- **`roles`** - Rollen mit Zugang zum Kanal
- **`nuke`** - Alle Nachrichten löschen (Nur Administrator)

### `/bot` - Bot-Informationen
**Beschreibung:** Technische Informationen über Freewings
**Unterbefehle:**
- **`info`** - Allgemeine Bot-Informationen einschließlich Uptime, Latenz, Serveranzahl
- **`icon`** - Bot-Avatar

### `/traducir` - Übersetzung
**Beschreibung:** Text mit Google Translate übersetzen
**Verwendung:** `/traducir`
**Funktionen:**
- Interaktive Modal-Oberfläche
- Unterstützung für mehrere Sprachen (en, fr, de, it, etc.)
- Sofortige Übersetzungsergebnisse
- Fehlerbehandlung für ungültige Sprachen

### `/seguir` - Social Media-Benachrichtigungen
**Beschreibung:** Social Media-Konten für automatische Benachrichtigungen folgen
**Unterstützte Plattformen:**
- YouTube-Kanäle
- Twitter-Konten
- Twitch-Streams
- Kick-Streams
**Funktionen:**
- Automatische Benachrichtigungen im gewählten Kanal
- Echtzeit-Updates
- Mehrere Plattform-Unterstützung

### `/sugerir` - Vorschläge
**Beschreibung:** Vorschläge an den konfigurierten Vorschlagskanal senden
**Funktionen:**
- Automatische Thread-Erstellung für Diskussionen
- Validierungsschaltflächen für Administratoren
- Organisierte Vorschlagsverwaltung

### `/ahorcado` - Galgenmännchen-Spiel
**Beschreibung:** Klassisches Galgenmännchen-Spiel mit umfangreicher Wortdatenbank
**Schwierigkeitsgrade:**
- 🟢 **Einfach** - Bis zu 6 Buchstaben
- 🟡 **Mittel** - 7-10 Buchstaben
- 🔴 **Schwer** - Mehr als 10 Buchstaben
- 🎲 **Zufällig** - Beliebiger Schwierigkeitsgrad

**Funktionen:**
- 8 Kategorien: Technologie, Programmierung, Wissenschaft, Natur, Tiere, Sport, Kultur, Geographie, Essen
- Interaktive Alphabetanzeige
- Statistikverfolgung (Präzision, Effizienz, Zeit)
- Wort- und Buchstabenraten
- Visuelle Galgenmännchen-Progression

**Verwendung:** `/ahorcado [schwierigkeit]`

### `/chess` - Schachspiel
**Beschreibung:** Schach mit anderen Benutzern spielen
**Funktionen:**
- Vollständige Schachimplementierung
- Rundenbasiertes Gameplay
- Zugvalidierung

### `/osint` - OSINT-Spiel
**Beschreibung:** Open Source Intelligence-Ermittlungsspiel
**Funktionen:**
- Ermittlungsherausforderungen
- Bildungsinhalte zu OSINT-Techniken

### `/8ball` - Magische 8-Ball
**Beschreibung:** Der magischen 8-Ball eine Frage stellen
**Verwendung:** `/8ball [frage]`
**Funktionen:**
- 20 verschiedene Antworten auf Spanisch
- Zufällige Antwortgenerierung
- Spaßige Interaktion für Entscheidungsfindung

### Spaß-Befehle
- **`/abrazo [benutzer]`** - Eine Umarmung an jemanden senden
- **`/golpe [benutzer]`** - Spielerische Schlag-Aktion
- **`/amor [benutzer1] [benutzer2]`** - Liebeskompatibilität berechnen
- **`/beso [benutzer]`** - Einen Kuss an jemanden senden
- **`/howgay [benutzer]`** - Lustige Gay-Prozentrechner
- **`/giveaway`** - Verlosungen erstellen und verwalten

---

## Sicherheitssysteme

Freewings beinhaltet umfassende Sicherheitsfunktionen (konfiguriert über `/setup` oder Dashboard):

### Anti-Spam-Systeme
- **Anti-Ban-Schutz** - Verhindert Massenbannungen
- **Anti-Bot-Schutz** - Blockiert verdächtige Bot-Hinzufügungen
- **Anti-Kanal-Spam** - Verhindert Kanal-Erstellungs-/Löschungs-Spam
- **Anti-Rollen-Spam** - Schützt vor Rollenmanipulation
- **Anti-Webhook-Spam** - Verhindert Webhook-Missbrauch
- **Anti-Kick-Schutz** - Blockiert Massen-Kicks
- **Anti-NSFW** - Inhaltsfilterung
- **Anti-Links** - Link-Filterung und Schutz
- **Ghost-Ping-Erkennung** - Erkennt und protokolliert Ghost-Pings

### Überwachungssysteme
- **Audit-Log-Berechtigungen** - Berechtigungsänderungen verfolgen
- **Besitzer-Benachrichtigungen** - Serverbesitzer über verdächtige Aktivitäten benachrichtigen
- **Massen-Rollen-Erkennung** - Massenrollenänderungen überwachen
- **Client-App-Überwachung** - Anwendungsnutzung verfolgen

---

## Setup-Befehle

### `/setup` - Serverkonfiguration
**Erforderliche Berechtigung:** Administrator

**Unterbefehle:**

#### `/setup autoroles`
Automatische Rollenzuweisung für neue Mitglieder konfigurieren
- **`agregar [rolle]`** - Rolle zur Auto-Zuweisungsliste hinzufügen
- **`eliminar [rolle]`** - Rolle aus der Auto-Zuweisungsliste entfernen
- **`listar`** - Alle konfigurierten Auto-Rollen auflisten

#### `/setup logs`
Server-Protokollierungssystem konfigurieren
- **`activar [kanal]`** - Protokolle im angegebenen Kanal aktivieren
- **`desactivar`** - Protokollierungssystem deaktivieren
- Interaktive Ereignisauswahl (Kanalereignisse, Rollenereignisse, Mitgliederereignisse, Nachrichtenereignisse, Webhook-Ereignisse)

#### `/setup sugerencias`
Vorschlagssystem konfigurieren
- **`[kanal]`** - Kanal für Vorschläge festlegen

#### `/setup reactionroles`
Reaction-Role-Systeme erstellen
- Interaktive Embed-Erstellung
- Benutzerdefinierter Titel, Beschreibung und Farbe
- Rollenzuweisung über Reaktionen

#### `/setup whitelist`
Autorisierte Benutzer und Rollen verwalten
- **`add user/role [ziel]`** - Zur Whitelist hinzufügen (Nur Besitzer)
- **`remove user/role [ziel]`** - Von der Whitelist entfernen (Nur Besitzer)
- **`list user/role [seite]`** - Whitelistete Elemente auflisten

#### `/setup badwords`
Schimpfwortfilter verwalten
- **`activar`** - Schimpfwortfilter aktivieren
- **`desactivar`** - Schimpfwortfilter deaktivieren
- **`agregar [wort]`** - Wort zur Blacklist hinzufügen
- **`quitar [wort]`** - Wort von der Blacklist entfernen
- **`listar`** - Alle Blacklist-Wörter auflisten

#### `/setup welcome`
Willkommenssystem konfigurieren (Nur Dashboard)
- Weiterleitung zum Web-Dashboard für Konfiguration

---

## Support

- **Dashboard:** [https://www.freewingsbot.com](https://www.freewingsbot.com)
- **Entwicklergemeinschaft:** [NearDevs Discord](https://discord.gg/Sp9GTrmcQG)
- **Hauptentwickler:** @diamondclass
- **Copyright:** Freewings © 2025
