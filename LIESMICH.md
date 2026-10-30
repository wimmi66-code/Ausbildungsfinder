# Ausbildungs- und Praktikumsfinder – Handy-App (PWA)

Diese App erstellt Suchaufträge für Ausbildungs- und Praktikumsstellen. Ausgeführt werden die Aufträge im kostenlosen Claude-Chat mit eingeschalteter Websuche. Die App funktioniert nach dem ersten Öffnen auch offline. Sie speichert nichts auf einem Server.

## Inhalt dieses Ordners

- index.html – die App
- manifest.webmanifest – Name, Farben und Symbole für die Installation
- sw.js – sorgt dafür, dass die App offline funktioniert
- icons/ – App-Symbole

Alle Dateien müssen zusammen im selben Ordner bleiben.

## 1. Kostenlos veröffentlichen mit GitHub Pages (einmalig, ca. 10 Minuten)

Eine App zum Installieren braucht eine https-Adresse. GitHub Pages stellt sie kostenlos bereit.

1. Auf github.com ein kostenloses Konto anlegen.
2. Oben rechts auf „+“ und dann „New repository“ klicken. Als Namen z. B. `stellenfinder` eintragen, „Public“ auswählen und „Create repository“ klicken.
3. Auf „uploading an existing file“ klicken. Den **Inhalt** dieses Ordners (index.html, manifest.webmanifest, sw.js und den Ordner icons) in das Fenster ziehen, dann „Commit changes“ klicken.
4. Zu „Settings“ → „Pages“ wechseln. Unter „Branch“ `main` und `/ (root)` auswählen und „Save“ klicken.
5. Nach 1–2 Minuten ist die App erreichbar unter:
   `https://DEIN-BENUTZERNAME.github.io/stellenfinder/`

Diesen Link kannst du an Kolleginnen und Kollegen weitergeben. Für die Nutzung brauchen sie kein GitHub-Konto.

## 2. Auf dem Handy installieren

**Android (Chrome):** Link öffnen, dann in der App auf „App installieren“ tippen, oder im Chrome-Menü (⋮) „App installieren“ bzw. „Zum Startbildschirm hinzufügen“ wählen.

**iPhone/iPad (Safari):** Link in Safari öffnen, auf „Teilen“ (Quadrat mit Pfeil) tippen und „Zum Home-Bildschirm“ wählen.

**PC (Chrome oder Edge):** Rechts in der Adressleiste auf das Installieren-Symbol klicken.

## 3. Benutzung

1. In der App ein Modul wählen und die Felder ausfüllen.
2. Auf „Auftrag kopieren“ tippen.
3. Auf „Claude öffnen“ tippen, im Chat die **Websuche einschalten** und den Auftrag einfügen.

Tipp: Mit der Claude-App auf dem Handy geht das genauso.

## 4. App aktualisieren

Geänderte Dateien bei GitHub einfach erneut hochladen. In `sw.js` die Zeile `const VERSION = 'stellenfinder-v1';` hochzählen (v2, v3 …). Dann laden alle installierten Apps beim nächsten Öffnen die neue Fassung.

## Datenschutz

Keine Namen, Anschriften, Geburtsdaten oder Gesundheitsdaten von Jugendlichen in die App oder den Chat eingeben. Kürzel und anonyme Merkmale reichen.
