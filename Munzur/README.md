# Munzur Kandern Kebap Haus — Website

Statische Website (HTML/CSS/JS, keine Build-Tools nötig) für Munzur Kandern Kebap Haus.

## Dateien

```
index.html            Landing Page
speisekarte-1.html     Speisekarte Seite 1 — Pizza
speisekarte-2.html     Speisekarte Seite 2 — Salate & Kebap
speisekarte-3.html     Speisekarte Seite 3 — Teller & mehr
styles.css             gesamtes Styling
script.js              mobiles Menü + Öffnungszeiten-Hervorhebung
assets/logo.png        Logo, freigestellt (transparenter Hintergrund)
```

## Als GitHub Pages hosten

1. Repository anlegen und diesen ganzen Ordnerinhalt (inkl. `assets/`) ins Root des Repos pushen.
   Wichtig: `index.html` muss im Root-Verzeichnis liegen, nicht in einem Unterordner.
2. Im Repo unter **Settings → Pages** als Quelle den Branch `main` und Ordner `/ (root)` wählen.
3. Nach ein bis zwei Minuten ist die Seite unter `https://<username>.github.io/<repo-name>/` erreichbar.

Lokal testen: einfach `index.html` per Live Server (VS Code) oder `python3 -m http.server` öffnen — alle Pfade sind relativ und funktionieren ohne Anpassung auch auf GitHub Pages.

## Inhalte, die noch geprüft werden sollten

- **Adresse & Öffnungszeiten**: Hauptstraße 33, 79400 Kandern, Di–So 11:30–21:30 Uhr, Montag Ruhetag — recherchiert über offizielle Einträge (u. a. Stadt Kandern, Schwarzwald Tourismus). Bitte kurz gegenchecken, falls sich seither etwas geändert hat.
- **Telefonnummer**: Auf der Speisekarte stand "07621 97 28 99", öffentliche Verzeichnisse listen "07626 97 28 99" — ich habe die Verzeichnis-Version verwendet. Bitte die richtige Nummer bestätigen.
- **Preis "Kandertal"-Pizza**: Auf dem Speisekarten-Foto lagen bei dieser Zeile zwei Preisboxen (9,50 € und 10,00 €) übereinander, vermutlich ein Layout-Artefakt der Vorlage. Ich habe 9,50 € übernommen — bitte den tatsächlichen Preis bestätigen.

## Design

- Farben: warmes Anthrazit/Kohle als Basis, Ember-Rot und Curry-Gold als Akzente (angelehnt an das Logo).
- Schriften: "Big Shoulders Display" für Überschriften, "Work Sans" für Fließtext, "JetBrains Mono" für Preise/Labels (Bon-Optik).
- Signatur-Element: rotierender Döner-Spieß als CSS/SVG-Animation im Hero-Bereich der Startseite.
