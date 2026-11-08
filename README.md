# ZEITREISE – Supportwebsite

Statische Support-, Datenschutz- und Anbieterseiten für die kostenlose native ZEITREISE-App von Alexander Pitlik.

Dieses Repository enthält ausschließlich die Informationswebsite. Es enthält keinen App-Quellcode, kein Xcode-Projekt und keine privaten Kontodaten.

## Kostenlos mit GitHub Pages veröffentlichen

1. Ein **neues öffentliches Repository** namens `zeitreise-support` im eigenen GitHub-Konto anlegen. Das Repository der App nicht verwenden und dessen Sichtbarkeit nicht ändern.
2. Nur die Dateien aus diesem Website-Repository hochladen. `index.html`, `datenschutz.html`, `anbieter.html`, `styles.css`, `favicon.svg` und `.nojekyll` liegen direkt im Stammverzeichnis. Kein ZIP als einzelne Datei hochladen.
3. Unter **Settings → Pages → Build and deployment** die Quelle **Deploy from a branch** wählen.
4. Branch **main**, Ordner **/(root)** auswählen und speichern.
5. **Custom domain** leer lassen. **Enforce HTTPS** aktivieren, sobald verfügbar.
6. Nach Bereitstellung sind die Seiten unter `https://BENUTZERNAME.github.io/zeitreise-support/` erreichbar. `BENUTZERNAME` ist durch den tatsächlichen GitHub-Namen zu ersetzen.

Für App Store Connect:
- Support URL: `https://BENUTZERNAME.github.io/zeitreise-support/`
- Privacy Policy URL: `https://BENUTZERNAME.github.io/zeitreise-support/datenschutz.html`

Die Beispieladressen sind keine bereits veröffentlichten URLs. Vor Einreichung beide Seiten ohne GitHub-Anmeldung aufrufen und prüfen.

## Eigenschaften

Kein Build, keine Abhängigkeiten, kein JavaScript, keine externen Schriftarten, keine Analyse, kein Formular, kein Cookie-Banner. GitHub verarbeitet beim Seitenabruf technische Verbindungsdaten; dies wird gesondert erläutert. Alle internen Links sind relativ und funktionieren auch unter einem Repository-Unterpfad.

Die Erklärung beschreibt die native App ohne Hintergrundmusik. Bei späteren Funktionsänderungen oder neuem Hosting muss sie überprüft werden. Die separate Browser-/PWA-Testversion ist nicht erfasst.
