# Visitenkarte — Webseite und Downloads

Dieses Repository enthält **nur** die veröffentlichte Webseite und die
Installationsdateien. Der Quellcode der App liegt in einem privaten
Repository.

| | |
|---|---|
| Webseite | https://qrcode.cyb8.de/ |
| Datenschutzerklärung | https://qrcode.cyb8.de/privacy.html |
| Downloads (Android + iOS) | [Releases](https://github.com/DrJakeberg/qrcard_pub/releases/latest) |

Die App zeigt eine Visitenkarte mit QR-Code, der sich als vCard mit jeder
Kamera scannen lässt. Sie speichert alles ausschließlich auf dem Gerät und
sendet nichts – Einzelheiten in der Datenschutzerklärung.

Fragen: qrcode@cyb8.de

## Hinweise zur Pflege

* Die Webseite liegt in **`docs/`**. In den Einstellungen muss unter
  *Pages → Build and deployment* „Deploy from a branch“ mit **`main` /
  `/docs`** stehen – dort liegt auch die von GitHub verwaltete `docs/CNAME`
  mit dem eigenen Namen `qrcode.cyb8.de`.
* `index.html` im Wurzelverzeichnis ist nur eine Weiterleitung auf `docs/`,
  damit die Seite auch bei der Einstellung „/ (root)“ erreichbar bleibt.
* Alle Dateien in `docs/` werden **automatisch** aus dem privaten Repository
  gespiegelt. Änderungen hier werden beim nächsten Abgleich überschrieben –
  die Webseite also immer dort bearbeiten.
* Die Releases (`visitenkarte.apk` und das unsignierte iOS-Bundle) werden
  ebenfalls automatisch angelegt.
