# 🛠️ ConfigViewr – Smarter JSON/YAML Konfigurationseditor für Windows

**ConfigViewr** ist ein plattformgebundenes Desktop-Tool für Windows, um JSON- und YAML-Dateien übersichtlich zu visualisieren, zu bearbeiten und zu validieren – vollständig offline und ohne Cloud-Integration. Entwickelt in C# mit WinForms und ideal für Admins, Entwickler und Power-User.

---

## 🚀 Features

- ✅ Anzeige & Bearbeitung von `.json` & `.yaml`/`.yml`
- ✅ TreeView für strukturierte Darstellung
- ✅ Auto-Formatierung & Prettify
- ✅ Fehlerprüfung & JSON-Validation
- ✅ Suchen & Ersetzen im Key/Value
- ✅ Dark Mode (optional)
- ✅ Komplett lokal, keine Telemetrie

---

## ⚙️ Tech Stack

| Komponente          | Technologie            |
|---------------------|------------------------|
| Sprache             | C# (.NET 6+)           |
| IDE                 | Visual Studio 2022+    |
| GUI                 | WinForms (.NET)        |
| Buildsystem         | VS Build Tools / GitLab|
| CI/CD               | GitLab CI (optional)   |
| Plattform           | Windows (x64)          |

---

## 🧰 Lokales Setup mit Visual Studio

> Voraussetzungen:
> - [Visual Studio 2022 Community Edition](https://visualstudio.microsoft.com/)
> - .NET 6+ Desktop Runtime

### 🔧 Öffnen & Ausführen
1. Repo klonen  
2. Projekt `ConfigViewr.sln` in VS öffnen  
3. Zielplattform: **Windows x64**, Build-Configuration: **Release**  
4. F5 – Ausführen

---

## 📄 Lizenz & Nutzungshinweis

> 📌 Hinweis: Dieses Repository ist **öffentlich einsehbar**, aber **nicht Open Source**.  
> Eine **Nutzung, Veränderung oder Weitergabe ist ausschließlich mit schriftlicher Genehmigung** des Eigentümers erlaubt.  
> Der Inhalt dieses README ist **nicht final** und wird regelmäßig erweitert.

---

## 📝 Lizenz

Dieses Projekt unterliegt einer benutzerdefinierten Lizenz.  
Details findest du in der Datei [LICENSE.md](./LICENSE.md).  
**Eine Nutzung oder Verbreitung ist nur mit ausdrücklicher Genehmigung erlaubt.**

---
## 🔮 Roadmap

Eine Übersicht geplanter Features und Verbesserungen für zukünftige Releases von **ConfigViewr**:

| Status     | Feature / Idee                                        | Beschreibung                                                 |
|------------|-------------------------------------------------------|---------------------------------------------------------------|
| 🧠 Geplant  | JSON & YAML Editor                                    | Grundfunktion für Anzeige und Bearbeitung                    |
| 🧠 Geplant  | Dark Mode                                             | Dunkles UI-Theme zur besseren Lesbarkeit                     |
| 🧠 Geplant  | Drag & Drop Support                                   | Dateien direkt ins Tool ziehen zum Öffnen                    |
| 🧠 Geplant  | TOML- und INI-Support                                 | Unterstützung weiterer Konfigurationsformate                 |
| 🧠 Geplant  | Konvertierung YAML ↔ JSON                             | Umwandlung zwischen den Formaten                             |
| 🧠 Geplant  | PDF/CSV Export                                        | Exportstruktur für Dokumentation oder Datenweitergabe        |
| 🧠 Geplant  | Lokalisierung                                         | Mehrsprachige Benutzeroberfläche (Deutsch, Englisch, etc.)   |
| 🧠 Geplant  | Portable Mode                                         | Startbar ohne Installation                                   |

---

## 🧠 Zielgruppe

**ConfigViewr** richtet sich an folgende Nutzergruppen:

- 🧑‍💻 **Entwickler & Software Engineers**  
  Für schnelles Bearbeiten, Testen und Validieren von JSON/YAML-Dateien im lokalen Umfeld.

- 🧑‍🔧 **DevOps & Systemadministratoren**  
  Zum Anpassen von Konfigurationsdateien ohne Webzugriff oder Drittanbieter-Tools.

- 👨‍🏫 **IT-Trainer & Schulungsteilnehmer**  
  Als Offline-Tool für den Unterricht oder zur Demonstration von Konfigurationslogik.

- 🔐 **Privacy-orientierte Nutzer**  
  Die explizit Tools ohne Cloud- oder Internetanbindung bevorzugen.

- 🧪 **QA & Tester**  
  Zur Validierung und Analyse von Response-Daten oder lokalen Config-Dumps.

---
