# Lord seth4 – TikTok-Shop Empfehlungen

Statische Website (reines HTML/CSS, kein Build-Schritt), gehostet mit GitHub Pages.

## Struktur
- `index.html` – Startseite (Hero, Affiliate-Hinweis, Produktgrid). Produkte werden aus `products.json` geladen.
- `products.json` – Produktliste. Neues Produkt = neuer Eintrag mit `name`, `beschreibung`, `bild`, `link`.
- `img/` – Produktbilder und Logo (`logo.svg`). Bilder sind SVG-Dateien mit eingebettetem JPEG; normale `.jpg`/`.webp` funktionieren genauso.
- `style.css` – Design (dunkel, mobilfreundlich).
- `impressum.html`, `datenschutz.html` – Rechtstexte.

## Ändern
Datei bearbeiten und auf `main` committen – GitHub Pages veröffentlicht automatisch nach ca. 1 Minute.
