# wasessen.de

Statische Website fuer die App `WasEssen Menueplan`.

Die Seite ist als leicht deploybares HTML/CSS-Projekt aufgebaut und deckt die typischen Apple-/App-Store-Seiten ab:

- `index.html`: Landingpage / Marketing URL
- `support.html`: Support URL
- `privacy.html`: Privacy Policy URL
- `impressum.html`: Impressum
- `en/`: englische Versionen der Seiten
- `styles.css`: gemeinsames Styling

## Design

Die Gestaltung orientiert sich an einer hellen, schlanken Catppuccin-Latte-Richtung mit warmen und frischen Akzentfarben aus dem WasEssen-Branding.

## App-Kontext

Die Texte auf Datenschutz- und Support-Seite basieren auf dem aktuellen Stand des App-Projekts:

- lokale Speicherung von Rezepten, Wochenplan und Einstellungen
- optionaler iCloud-/CloudKit-Sync fuer Listen und Familienfreigabe
- Rezeptimport per URL und PDF
- keine eingebauten Analytics- oder Werbe-SDKs

## Deployment

Da das Projekt statisch ist, kann es direkt auf jeden einfachen Webserver oder Static Hosting Dienst gelegt werden.
