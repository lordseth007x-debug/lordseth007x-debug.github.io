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

## Produkt-Links und Preise eintragen
In `products.json` pro Produkt `link` (TikTok-Shop-/Affiliate-Link) und `preis` (z. B. "29,99 €") eintragen. Leerer Preis → "Preis auf TikTok"; Link = Profil → Button "Auf TikTok ansehen".
Noch offen (Link + Preis fehlen): alle 14 Produkte –
- Mobiler Smoothie-Mixer
- Ninja SLUSHI Slush-Eismaschine
- Ninja Blast kabelloser Mixer
- Holylegend Kreuzkette 14K vergoldet
- MONSGA MR7 PRO Saug- und Wischroboter
- DRFLASH Dampfglätter für Kleidung
- TRAVANDO SLYDE Kartenetui aus Aluminium
- Philips Steam Airfryer 5000
- Dr.Melaxin Calcium Multi Balm
- YOFIDRA Akku-Bohrschrauber-Set 53-teilig
- Herz-Tasse mit Farbwechsel
- Fanttik S1 Pro Elektroschraubendreher
- VALLSERO 5-teiliges Kofferset
- Pammys Step-Ins Sneaker
