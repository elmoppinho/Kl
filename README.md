# KLACK! – Anzeigenprüfung (November 2026)

Standalone-Spielesammlung für GitHub Pages. Alle 16 Spiele in `index.html`, keine Installation und keine externen JavaScript-Bibliotheken.

## Korrekturen in dieser Version
- Tele-Klack: vorherige Korrektur der sichtbaren Zielzahl bleibt erhalten.
- Knobel-Klack: Zahlen: Zeitbalken wird unter dem Handgerät angezeigt, damit das kleine Geräte-LCD für die Zahl frei bleibt.
- Knobel-Klack: Code: Meldungen über gelöschte/fertige Ziffern werden unter dem Gerät angezeigt; Restzeit steht in der Informationsleiste.
- Klack-Familie: kontrastreiche Beschriftung der Karten und der Spieltasten, einschließlich der späteren Kartenansicht.
- Skill-Klack: bessere Lesbarkeit der Auswahl 7 / 9 / 11 Kugeln.
- Startzählung: besserer Kontrast vor schwarzem Hintergrund.

## Prüfumfang
- Start jedes der 16 Spiele bei 320, 390 und 1280 Pixel Bildschirmbreite; keine JavaScript-Fehler, kein seitliches Überlaufen.
- Mehrere tatsächliche Tasteneingaben in den Klack-Handspielen und in den Studio-Spielen.
- Zusatzkontrolle der Darstellung nach Ablauf des Countdowns bei den anderen Spielen.
- Browserprüfung mit Chromium; Safari auf dem persönlichen iPhone wurde nicht getestet.

## Veröffentlichen
Lade `index.html` in das Hauptverzeichnis des GitHub-Repositories hoch und aktiviere GitHub Pages unter `Settings → Pages` mit `Deploy from a branch`, `main`, `/(root)`.
