SHK TOOLBOX PRO – Installierbare iPhone-Web-App
=================================================

DATEIEN
- index.html: Rechner und Benutzeroberfläche
- manifest.webmanifest: App-Name, Symbol, Startverhalten
- service-worker.js: Offline-Caching nach dem ersten Laden
- icons/: App-Symbole

WICHTIG
Die App muss über eine HTTPS-Webadresse bereitgestellt werden. Eine lokale Datei (file://) reicht für die Installation und den Service Worker nicht aus.

EINFACHER ABLAUF
1. ZIP entpacken.
2. Den gesamten Ordnerinhalt auf einen statischen HTTPS-Webhost laden (z. B. GitHub Pages oder einen vergleichbaren Static-Hosting-Dienst).
3. Die veröffentlichte HTTPS-Adresse auf dem iPhone in Safari öffnen.
4. Teilen -> Zum Home-Bildschirm -> „Als Web-App öffnen“ aktivieren (falls angezeigt) -> Hinzufügen.
5. Die App einmal online öffnen. Danach stehen die gecachten App-Dateien auch offline zur Verfügung.

RECHNERHINWEISE
- Die Durchmesserliste ist eine editierbare Vergleichsreihe und keine Hersteller- oder DN-Tabelle.
- Vor dem Einsatz müssen reale Innendurchmesser, Werkstoffrauigkeit, Mediumsdaten und Herstellerwerte geprüft werden.
- Die Berechnung ersetzt keine vollständige Rohrnetzberechnung, keinen hydraulischen Abgleich und keine Fachplanung.
- Volumenstrom aus Heizleistung basiert auf Wasser-Näherungswerten; Glykol und andere Medien sind nicht abgebildet.

Wenn du den Ordner veröffentlichst, teile die HTTPS-Adresse nicht öffentlich, falls du die App privat halten möchtest. Beachte außerdem, dass jeder mit der Adresse die statische App öffnen kann, solange keine Zugriffssperre eingerichtet ist.
