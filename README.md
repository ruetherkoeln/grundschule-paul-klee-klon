# grundschule-paul-klee-klon

Statischer **Klon (Snapshot)** der Live-Website
[https://www.grundschule-paul-klee.de/](https://www.grundschule-paul-klee.de/)
zum Stand des Abrufs.

## Inhalt
- Alle 14 Seiten der Live-Site (Willkommen, Allgemeines/Termine/Unterrichtszeiten,
  Anmeldung + Unterseiten, Schule/Team/Schulsozialarbeit, Förderverein, Impressum,
  Kontakt, Datenschutz) als statisches HTML.
- Zugehörige Assets (CSS, JS, Bilder) unter `wp-content/`.

## Bearbeitung
- Interne absolute Links wurden auf **root-relativ** umgeschrieben, damit die Seite
  eigenständig (z. B. auf Vercel) ausgeliefert werden kann.
- **Stealth-Mode:** In jede Seite ist `noindex, nofollow, noarchive` eingefügt und
  `robots.txt` sperrt alle Crawler (`Disallow: /`).

## Hinweis
Rein statischer Spiegel — keine WordPress-Funktionen (Suche, Formulare, wp-json,
Kommentare) aktiv. Externe Ressourcen (falls vorhanden) werden weiterhin vom
jeweiligen Ursprung geladen.
