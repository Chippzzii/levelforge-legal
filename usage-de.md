# LevelForge Anleitung

Diese Seite erklärt die grundlegende Nutzung, nachdem du LevelForge auf deinen Discord-Server eingeladen hast.

## 1. Bot einladen

1. Öffne den offiziellen LevelForge-Invite-Link.
2. Wähle deinen Discord-Server aus.
3. Bestätige die benötigten Berechtigungen.
4. Schließe die Discord-Autorisierung ab.

- Offizieller Invite-Link: [LevelForge hinzufügen](https://discord.com/oauth2/authorize?client_id=1501623866257051780)

## 2. Bot-Berechtigungen prüfen

Prüfe nach dem Einladen, ob LevelForge:

- Nachrichten in Channels lesen kann, in denen XP erfasst werden soll
- Nachrichten in Channels senden kann, in denen Level-Up- oder Statusmeldungen erscheinen sollen
- Slash-Commands verwenden kann

Wenn Commands fehlen, prüfe Rollenrechte und Channel-Overrides in Discord.

## 3. Basis-Setup durchführen

Nutze die Bot-Commands, um deinen Server zu konfigurieren:

- XP pro Nachricht festlegen
- Cooldown gegen Spam-Farming festlegen
- Level-Up-Channel festlegen
- Ignorierte Channels und ignorierte Kategorien konfigurieren

Bei vielen Channels zuerst Ignore-Regeln setzen.

## 4. So funktionieren XP und Level

Im normalen Betrieb:

- Nutzer erhalten XP für gültige Aktivität
- Cooldowns reduzieren Missbrauch/Spam-Farming
- Level werden aus den gespeicherten XP berechnet
- Leaderboards sind server-spezifisch

LevelForge trennt Daten pro Server (`guild_id`), damit Server sich nicht gegenseitig beeinflussen.

## 5. Admin-Aktionen

Server-Admins können typischerweise:

- Nutzer-XP anpassen
- Level-/Rangdaten prüfen
- Konfigurationswerte abstimmen

Nutze Admin-Aktionen sorgfältig und dokumentiere größere Änderungen für dein Mod-Team.

## 6. Premium-/Plan-Hinweise

LevelForge kann Plan-Status wie `FREE`, `VIP`, `TESTER` oder `LIFETIME` enthalten.

- Payment ist aktuell noch nicht implementiert.
- Premium-bezogenes Verhalten kann später ergänzt werden.
- Limits und Feature-Zugriff können vom Plan-Status abhängen.

## 7. Fehlerbehebung

Wenn etwas nicht funktioniert:

1. Bot-Berechtigungen und Channel-Overrides erneut prüfen.
2. Command-Berechtigungen für deine Rolle prüfen.
3. Prüfen, ob Cooldown/Settings zu streng sind.
4. In einem separaten Test-Channel testen.
5. Support kontaktieren.

- TODO: Support-Discord-URL (zum Beispiel: `https://discord.gg/NsVbrUpM`)
- TODO: Support-Kontakt-E-Mail

## 8. Kurz-Checkliste

- Bot erfolgreich eingeladen
- Benötigte Berechtigungen gesetzt
- XP/Cooldown konfiguriert
- Level-Up-Channel konfiguriert
- Ignore-Regeln konfiguriert
- Basis-Command-Test erfolgreich

Letzte Aktualisierung: 2026-05-07
