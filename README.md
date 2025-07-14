# 🎓 H5P to SCORM Converter (via GitHub Actions)

Dieses Repository ermöglicht es dir, interaktive H5P-Inhalte automatisch in SCORM-kompatible Pakete umzuwandeln – ganz einfach über GitHub Actions.

## 🚀 Funktionsweise

Sobald du eine `.h5p`-Datei in das Repository hochlädst (als `input.h5p`), wird automatisch ein SCORM-Paket (`output.zip`) generiert. Dieses kannst du anschließend in dein LMS (z. B. Moodle, ILIAS, etc.) hochladen.

## 📁 Projektstruktur

- `input.h5p` – Deine H5P-Datei (einfach ersetzen)
- `output.zip` – Das generierte SCORM-Paket (wird automatisch erstellt)
- `.github/workflows/build.yml` – GitHub Actions Workflow
- `package.json` – Abhängigkeiten und Build-Skript

## 🛠️ Voraussetzungen

- Ein GitHub-Konto
- Eine `.h5p`-Datei, die du konvertieren möchtest

## 📝 Anleitung

1. Forke dieses Repository oder erstelle ein neues.
2. Lade deine `.h5p`-Datei hoch und benenne sie in `input.h5p` um.
3. Push die Datei ins Repository.
4. GitHub Actions startet automatisch den Export.
5. Lade das SCORM-Paket unter **Actions > Letzter Workflow > Artifacts** herunter.

## 📦 SCORM-Version

Aktuell wird **SCORM 1.2** verwendet. Du kannst dies in der Datei `package.json` oder im Workflow-Skript anpassen.

## 🧑‍💻 Basierend auf

- [Lumi Education CLI](https://githubs]## 📄 Lizenz

MIT License – frei zur Nutzung, Anpassung und Weitergabe.
