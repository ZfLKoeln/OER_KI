# Kriterienkatalog: Bewertung von OER- und KI-gestütztem Material zu BNE

Interaktive Checkliste zur Bewertung von Bildungsmaterial zur Bildung für nachhaltige Entwicklung (BNE), das als Open Educational Resource (OER) veröffentlicht und/oder mit KI erstellt wurde.

**➡️ Zur Checkliste:** `https://<dein-github-name>.github.io/<repo-name>/`
*(Link ist erst aktiv, nachdem GitHub Pages wie unten beschrieben eingerichtet wurde.)*

---

## Was macht dieses Tool?

Die Checkliste ist in vier farblich unterschiedene Hauptkategorien gegliedert:

| Kürzel | Kategorie | Farbe |
|---|---|---|
| A | Pädagogisch-didaktische Dimension | `#005176` |
| B | Technische Dimension | `#009DCC` |
| C | KI-Integration (wenn vorhanden und kenntlich gemacht) | `#FBBB33` |
| D | BNE-fachliche Kriterien | `#DC587F` |

Jedes angekreuzte Kriterium fließt live in eine **Analysespinne** am Ende der Seite ein, die den Erfüllungsgrad je Hauptkategorie visualisiert und automatisch eine Einsatzempfehlung ableitet (uneingeschränkt / mit Anpassungen / nicht einsetzbar).

Besonderheiten:
- **A2.1 (KI-Aufgabenkultur)** und **C1 (KI-Kompetenzen)** sind bewusst als eigene Prüfbereiche voneinander abgegrenzt, verweisen aber wechselseitig aufeinander.
- **C2 (Kritische Prüfung KI-generierter Inhalte)** bietet zwei alternative Prüfmethoden (PRÜFE-Framework nach Barbara Geyer *oder* Antwort-Autopsie nach Lucca Spohn) – ein vollständig abgehakter Block entspricht 100 %.

## Nutzung

Einfach die Seite öffnen, Kriterien ankreuzen, Ergebnis unten ablesen. Der Button **„Drucken / PDF"** erzeugt eine druckfreundliche Version, **„Zurücksetzen"** leert alle Häkchen. Es werden keine Daten gespeichert oder übertragen – alles läuft rein lokal im Browser.

## Technisch

Eine einzige, abhängigkeitsfreie HTML-Datei (`index.html`) mit eingebettetem CSS/JavaScript. Die Analysespinne wird als reines SVG direkt im Browser gezeichnet, es wird keine externe Chart-Bibliothek geladen. Einzige externe Ressource ist ein Google-Fonts-Link (Fraunces, IBM Plex Sans/Mono); ohne Internetverbindung fällt die Seite automatisch auf Systemschriften zurück.

## Veröffentlichung / Aktualisierung über GitHub Pages

1. Datei `index.html` im Repository-Root ablegen (ggf. bestehende Version überschreiben).
2. Unter **Settings → Pages** als Quelle den Branch `main` (Ordner `/root`) auswählen und speichern.
3. Nach kurzer Zeit ist die Seite unter `https://<dein-github-name>.github.io/<repo-name>/` erreichbar.
4. Für Änderungen: Datei im Repository ersetzen und committen – GitHub Pages aktualisiert sich automatisch innerhalb weniger Minuten.

## Quellen / Grundlage

- Becker, V., Schaper, F., Schulte-Buskase, A., Tibbe, T. (2024): *(Qualitäts-)Ansprüche an OER.* MedienPädagogik.
- Mayrberger, K. & Zawacki-Richter, O. (2018): *Qualität von OER.*
- Geyer, B. (2025): *Nicht alles glauben, was KI sagt – Das PRÜFE-Framework.* barbarageyer.substack.com
- Falck, J. & Flick, M. (2025): *KI-Didaktik: Eine Planungsvorlage zur Aufgabenkultur im KI-Zeitalter.* joschafalck.de
- Spohn, L. (2026): *Eine KI-Antwort ist kein Text.* luccaspohn.substack.com
- Klein, A. (2026): *KI, OER und OEP – für eine nachhaltige Openness.* hnd-bw.de
- OECD & Europäische Union (2026): *Empowering Learners for the Age of AI (AILit Framework).*

## Lizenz

Der Kriterienkatalog steht, soweit nicht anders gekennzeichnet, unter **CC BY-SA 4.0**. Bei Weitergabe oder Bearbeitung bitte Namensnennung und Weitergabe unter gleichen Bedingungen beachten.
