# Eternal — Releases

Öffentliches Release-Repo des Eternal-Minecraft-Netzwerks. Hier liegen **nur Binaries**;
der Quellcode ist privat.

Jedes Release enthält:

| Asset | Was | Wohin |
| --- | --- | --- |
| `Eternal-<ver>.jar` | Plugin für Spigot **und** BungeeCord/Waterfall (alle Module in einem Jar) | `plugins/Eternal.jar` |
| `EternalApi-<ver>.jar` | REST-API (liegt beim Plugin-Host) | API-Ordner, `java -jar` |
| `eternal-web-<ver>.zip` | Dashboard (Angular-Build) | Web-Root, oder per Web-Updater |

Die Auto-Update-Funktion (API → Plugins, Web-Updater → Dashboard) liest dieses Repo
über die GitHub-API; es braucht keinen Token.

## Lizenz

EternalSystem ist kostenlos nutzbar – privat und gewerblich, mit allen Funktionen, die ohne Lizenzschlüssel freigeschaltet sind. Einzelheiten in [LICENSE](LICENSE); für gekaufte Module gelten die [Lizenzbedingungen](https://eternal.adambn.dev/lizenzbedingungen).
