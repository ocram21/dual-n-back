Dual N-Back – PWA-Paket

Dateien:
- index.html              Einstieg für GitHub Pages; leitet zur eigentlichen Datei weiter
- Dual N-Back.html        Hauptspiel
- manifest.webmanifest    PWA-Metadaten
- service-worker.js       Offline-Funktion / App-Cache
- icon-192.png            App-Icon
- icon-512.png            App-Icon

GitHub Pages:
1. Alle sechs Dateien in dasselbe Repository hochladen.
2. In GitHub: Settings > Pages.
3. Unter "Build and deployment" als Source "Deploy from a branch" wählen.
4. Branch "main" und Ordner "/ (root)" wählen und speichern.
5. Nach kurzer Wartezeit den von GitHub angezeigten Link öffnen.

Installation auf dem Handy:
- Android/Chrome: Seite öffnen > Browsermenü > "App installieren" bzw. "Zum Startbildschirm hinzufügen".
- iPhone/Safari: Seite öffnen > Teilen > "Zum Home-Bildschirm".

Hinweis:
Die PWA-/Offline-Funktion funktioniert über HTTPS (z. B. GitHub Pages).
Wenn "Dual N-Back.html" direkt als lokale Datei geöffnet wird, läuft das Spiel weiterhin,
aber Service Worker und PWA-Installation sind dann nicht aktiv.

Hinweis: Die Druckauswertung wurde für die Handy-/PWA-Version entfernt.
