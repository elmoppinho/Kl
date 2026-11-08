# KLACK! – Die Samstagmorgen-Spielshow (Fan-Edition)

15 **spielbare** Browser-Minispiele, inspiriert von der RTL-Plus-Kinderspielshow *Klack* (1989–1992). Darunter sind **Hit-Klack**, **Tele-Klack**, **Knobel-Klack**, **Logo-Klack**, **Klack-Piraten**, **Kroko-Klack**, **Skill-Klack**, **Monster-Mix**, **Klack-Familie** und weitere Spiele.

## Auf GitHub Pages veröffentlichen

1. Dieses ZIP entpacken – **nicht das ZIP selbst** im Repository ablegen.
2. Ein neues GitHub-Repository anlegen (für GitHub Free am einfachsten **Public**).
3. **`index.html`** und **`README.md`** aus diesem ZIP in das Hauptverzeichnis des Repositorys hochladen (optional auch `.nojekyll`). Auf GitHub: **Add file → Upload files → Commit changes**.
4. Im Repository **Settings → Pages** öffnen.
5. Unter **Build and deployment**: **Source = Deploy from a branch**, **Branch = main**, Verzeichnis **/(root)**, dann **Save**.
6. Die Webseite kann anschließend unter `https://DEIN-NAME.github.io/REPOSITORY-NAME/` geöffnet werden. GitHub zeigt den genauen Link auch unter **Settings → Pages → Visit site**.

Die Veröffentlichung kann einige Minuten dauern. Wenn die Seite zunächst 404 meldet, nach einer Weile noch einmal nachsehen und überprüfen, ob `index.html` **direkt im Hauptverzeichnis** liegt, nicht in einem zusätzlichen Unterordner.

## Bedienung

- Startseite: Auf ein Spiel tippen und **JETZT SPIELEN** wählen. Für Hit-Klack gibt es oben einen Direktstart.
- **Hit-Klack:** Vier Farbtasten (Grün oben, Rot links, Blau rechts, Gelb unten). Auf dem Computer auch Pfeiltasten.
- **Tele-Klack:** Gelb wählt die Stufe 1–6; Rot oder Blau stoppt die Markierung. Am Computer Leertaste und S.
- **Knobel-Klack:** Zahlen 1–6 anklicken oder tippen.
- **Logo-Klack:** Buchstaben in der richtigen Reihenfolge antippen.
- **Team-Duell:** Zwei Teams spielen nacheinander auf demselben Gerät.

Diese Browser-Ausgabe braucht **keine Installation, keine Build-Tools, keinen Servercode und keine externen Bibliotheken**. Sie ist absichtlich vollständig in der einzigen Datei `index.html` enthalten. Die Highscores werden im lokalen Browser-Speicher abgelegt; im privaten Modus stehen sie möglicherweise nicht dauerhaft zur Verfügung.

**Hinweis zum Online-Duell:** Zwei getrennte Geräte können sich in dieser Fassung nicht miteinander verbinden. Das lokale Team-Duell auf einem Gerät funktioniert.

## Historische Vorbilder und Abgrenzung

Die Gestaltung nimmt Formen, Farben und Tastenanordnung der Mephisto-Klack-LCD-Geräte und das bunte Studio der RTL-Plus-Sendung auf. Als technische und gestalterische Referenz diente unter anderem [TobseFs HitKlack-Fanprojekt](https://github.com/TobseF/HitKlack), dessen dokumentierte *Box Game*-Spielregeln als Vergleich herangezogen wurden; **dessen Code oder Assets sind nicht in dieses Projekt kopiert worden**.

Dies ist eine **inoffizielle, selbständig gestaltete Fan-Adaption**, keine Emulation der historischen Originalgeräte und keine offizielle Veröffentlichung von RTL, Mephisto, Hegener & Glaser oder Yeno. Manche Details und Bonusspiele sind frei ergänzt. Alle Rechte an den historischen Marken und Originalspielen bleiben bei ihren jeweiligen Inhabern.


## Logo-Vorlage

Der pixelige „HIT KLaCK“-Schriftzug wird im Browser direkt als Ausschnitt der Vergleichsgrafik des Fanprojekts geladen:
https://tobsef.github.io/HitKlack/images/hitklack_console_and_app.jpg
Ohne Internet wird ein klar erkennbarer, aber nicht originalgetreuer Ersatzschriftzug angezeigt.
Quelle: https://github.com/TobseF/HitKlack

Die Verwendung fremder Grafiken und Marken bei öffentlicher Veröffentlichung sollte bei Bedarf mit den Rechteinhabern geklärt werden.
