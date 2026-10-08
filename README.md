# Visitenkarte — Webseite und Downloads

Dieses Repository enthält **nur** die veröffentlichte Webseite und die
Installationsdateien. Der Quellcode der App liegt in einem privaten
Repository.

| | |
|---|---|
| Webseite | https://qrcode.cyb8.de/ |
| Datenschutzerklärung | https://qrcode.cyb8.de/privacy.html |
| Downloads (Android + iOS) | [Releases](https://github.com/DrJakeberg/qrcard_pub/releases/latest) |
| Fehler melden, Ideen | [Issues](https://github.com/DrJakeberg/qrcard_pub/issues/new/choose) |

Die App zeigt eine Visitenkarte mit QR-Code, der sich als vCard mit jeder
Kamera scannen lässt. Sie speichert alles ausschließlich auf dem Gerät und
sendet nichts – Einzelheiten in der Datenschutzerklärung.

## Fehler melden

Am besten über [Issues](https://github.com/DrJakeberg/qrcard_pub/issues/new/choose)
– dort ist nachvollziehbar, was damit passiert. Es gibt zwei Vorlagen, eine
für Fehler und eine für Ideen.

**Bitte keine persönlichen Daten in ein Issue schreiben** – dieses Repository
ist öffentlich. Namen, Telefonnummern oder Adressen aus einer Visitenkarte
wären hier für jeden lesbar. Für alles, was nicht öffentlich stehen soll, und
für Fragen ohne GitHub-Konto: **qrcode@cyb8.de**

## Hinweise zur Pflege

* Die Webseite liegt in **`docs/`**, und Pages liefert genau diesen Ordner
  aus – belegt durch das Bau-Protokoll, das `index.html` und `privacy.html`
  auf oberster Ebene veröffentlicht. Die Adressen lauten deshalb
  `qrcode.cyb8.de/` und `qrcode.cyb8.de/privacy.html`, **ohne** `/docs/`.
* `docs/CNAME` ist die von GitHub verwaltete Datei mit dem eigenen Namen –
  nicht löschen, nicht verschieben. Die `CNAME` im Wurzelverzeichnis ist
  eine wirkungslose Dublette.
* `index.html` im Wurzelverzeichnis wird **nicht** ausgeliefert. Es ist nur
  ein Sicherheitsnetz, falls die Pages-Einstellung je auf „/ (root)“
  wechselt.
* Alle Dateien in `docs/` werden **automatisch** aus dem privaten Repository
  gespiegelt. Änderungen hier werden beim nächsten Abgleich überschrieben –
  die Webseite also immer dort bearbeiten.
* Die Releases (`visitenkarte.apk` und das unsignierte iOS-Bundle) werden
  ebenfalls automatisch angelegt.
