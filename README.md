# Hakenheld – Website

Statische Website für die Android-App **Hakenheld** (Paketname `de.hakenheld.app`).
Gedacht für GitHub Pages in einem **eigenen, neuen Repository** `hakenheld`.
Keine Cookies, kein Tracking, keine externen Schriften oder CDNs.

## Dateien

| Datei | Inhalt |
|---|---|
| `index.html` | Startseite (Beschreibung, 6 Module, Preis, Kontakt) |
| `datenschutz.html` | Datenschutzerklärung (App + Website, inkl. Google-Limited-Use-Hinweis) |
| `impressum.html` | Impressum nach § 5 DDG / § 18 Abs. 2 MStV |
| `style.css` | Gestaltung (Grün #2E7D32, Mint, Weiß), mobilfreundlich |
| `favicon.ico`, `favicon.png`, `apple-touch-icon.png` | Icons |
| `img/` | Logo, App-Icon (`icon-512.png` / `.webp`), Screenshot, Beispiel-PDF |
| `.nojekyll` | sorgt dafür, dass GitHub Pages die Dateien unverändert ausliefert |

## Platzhalter / offene Punkte

Platzhalter sind auf der Seite **gelb markiert** (CSS-Klasse `todo`). Aktuell ist nichts sichtbar offen,
nur zwei auskommentierte, optionale Stellen:

1. **Telefonnummer** (optional) – `impressum.html` (HTML-Kommentar unter „Kontakt“) und
   `index.html` (Kommentar im Kontaktbereich). Zum Aktivieren Kommentar entfernen und Nummer eintragen.
2. **Download-Link zur APK** – `index.html`, Kommentar `TODO Download-Link` im oberen Bereich.
   Erst einfügen, wenn die APK öffentlich angeboten werden soll.

Impressum/Verantwortlicher: Chris Lippert, Hauptstraße 267, 04416 Markkleeberg.
Zuständige Datenschutz-Aufsichtsbehörde: Sächsische Datenschutz- und Transparenzbeauftragte (Dresden).

## Veröffentlichen (GitHub Pages)

1. Auf github.com anmelden → oben rechts **+** → **New repository**.
2. Name: `hakenheld`, Sichtbarkeit **Public**, ohne README anlegen → **Create repository**.
3. **uploading an existing file** anklicken und alle Dateien und den Ordner `img` aus diesem Ordner
   hineinziehen (auch `.nojekyll`; versteckte Dateien ggf. einblenden) → **Commit changes**.
4. Im Repository **Settings → Pages** → *Source*: **Deploy from a branch**, Branch **main**, Ordner **/ (root)** → **Save**.
5. Nach 1–2 Minuten ist die Seite erreichbar.

## Links für Google Cloud (Google Auth Platform → Branding)

`BENUTZERNAME` = dein GitHub-Benutzername.

| Feld | URL |
|---|---|
| Startseite der Anwendung | `https://BENUTZERNAME.github.io/hakenheld/` |
| Link zur Datenschutzerklärung | `https://BENUTZERNAME.github.io/hakenheld/datenschutz.html` |
| Link zu den Nutzungsbedingungen (optional) | leer lassen (oder später eine eigene Seite) |
| Autorisierte Domain | `BENUTZERNAME.github.io` |

Kein Logo in der Branding-Seite hochladen (sonst prüft Google das Branding zusätzlich).
Danach unter **Zielgruppe → App veröffentlichen**.
