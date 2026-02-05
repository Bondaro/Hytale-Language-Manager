<p align="center">
  <img src="hytale_banner.png" alt="Hytale Language Manager" width="800">
</p>

---

# Hytale Language Manager

Dieses Tool unterstützt das [Multi-Language-Paket](https://www.curseforge.com/hytale/translations/multi-language-support) von [thedragon95](https://www.curseforge.com/members/thedragon95/projects).

Der **Hytale Language Manager** ist ein kleines Windows-Werkzeug, mit dem du gezielt einzelne Hytale-Sprachen installieren kannst – ohne manuelles Kopieren, ohne komplizierte Ordnerstruktur und ohne Sucherei in ZIP-Dateien.

### Hauptfunktionen
- ✔ Anzeige installierter Sprachen (grün = installiert)
- ✔ Auswahl **einer** Sprache zur Installation  
- ✔ Online-/Lokal-Versionsanzeige im Header  
- ✔ Automatischer Download der neuesten Version von CurseForge  
- ✔ Alternativ: Installation per eigener ZIP-Datei  
- ✔ Drag & Drop von ZIP-Dateien wird unterstützt  
- ✔ Saubere Benutzeroberfläche mit kompakter 3-Spalten-Ansicht  

---

## Was macht das Tool genau?

Der Installer:

- prüft online über die CurseForge-API, ob eine neue Version verfügbar ist  
- lädt bei Bedarf automatisch die aktuelle Übersetzungs-ZIP herunter  
- entpackt die Sprachdateien  
- kopiert sie an die korrekten Hytale-Ordner  
- zeigt dir direkt an, welche Sprachen bereits installiert sind  
- erlaubt zusätzlich die manuelle Auswahl einer ZIP-Datei  
- akzeptiert ZIP-Dateien auch per Drag & Drop  

Du musst **keine Ordner manuell öffnen oder Dateien verschieben.**

---

## Voraussetzungen

- **Windows**
- **Hytale muss installiert sein**
- Das Tool selbst benötigt **keine Installation**  
  → Einfach starten und benutzen.

Du kannst die EXE-Datei **beliebig speichern** und von dort aus ausführen.

---

## Welche Ordner nutzt das Tool?

### Zielordner in Hytale

Das Tool arbeitet mit folgendem Pfad:

`` %APPDATA%\Hytale\``
---

Dort werden Sprachdateien typischerweise hier abgelegt:
``
install\release\package\game\latest\Client\Data\Shared\Language<sprachcode>
install\pre-release\package\game\latest\Client\Data\Shared\Language<sprachcode>
``
Beispiel für Deutsch:
`de-DE `

---

## Temporäre Dateien
Beim automatischen Download wird kurzzeitig eine Datei im Temp-Ordner genutzt:
`%TEMP%\Hytale_Multi_Language.zip`

Diese Datei wird **nach der Installation wieder gelöscht.**

---

## Online-Abfrage (Update-Check)
Das Tool nutzt die offizielle CurseForge-API:
`https://www.curseforge.com/api/v1/mods/1440779/files `

Abgefragt werden:

- Name der neuesten Datei  
- Upload-Datum  
- Download-Link  

So kann zuverlässig geprüft werden, ob eine neue Version verfügbar ist.

---

## Bedienung im Programm

Du wählst **eine Sprache** aus:

- **Grün** → bereits installiert  
- **Weiß** → nicht installiert  

Dann klickst du auf:

**„Ausgewählte Sprache installieren (falls fehlend)“**

Alternativ kannst du:

- eine ZIP-Datei ins Fenster ziehen (Drag & Drop)  
- oder eine ZIP-Datei manuell auswählen.

---
<p align="center">
  <a href="screenshots/screenshot1.png"><img src="screenshots/screenshot1.png" width="200"></a>
  <a href="screenshots/screenshot2.png"><img src="screenshots/screenshot2.png" width="200"></a>
  <a href="screenshots/screenshot3.png"><img src="screenshots/screenshot3.png" width="200"></a>
</p>

## Hinweis

Dieses Tool installiert die Übersetzungen aus dem **[Multi-Language-Support-Paket](https://www.curseforge.com/hytale/translations/multi-language-support) von [thedragon95](https://www.curseforge.com/members/thedragon95/projects)**.  
Es ist **kein offizielles Hytale-Tool** und steht **in keiner Verbindung zu Hypixel Studios.**

---

## Entwickler

Dieses Tool wurde von **Bondaro** entwickelt.  

Feedback, Ideen und Verbesserungsvorschläge sind willkommen.  

Wenn dir das Tool geholfen hat, kannst du mich hier unterstützen:

👉 https://ko-fi.com/bondaro

---

## ⬇️ Download

👉 **Neueste Version herunterladen:**  
https://github.com/Bondaro/hytale-deutsch-installer/releases/latest

---

## Hinweis zu Windows SmartScreen

Da dieses Tool kein kommerziell signiertes Zertifikat besitzt, kann Windows beim ersten Start eine Warnung anzeigen.

In diesem Fall:
> „Weitere Informationen“ → **„Trotzdem ausführen“**

Das Tool enthält **keinen schädlichen Code.**
---


