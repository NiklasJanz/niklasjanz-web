# niklasjanz.de

Statische Webseite, veröffentlicht mit GitHub Pages. Kein Build-Schritt: jede `index.html` ist eine Seite.

- `gruenzeug/` – Seiten zur App Grünzeug: Übersicht, Support, Datenschutz, Impressum, Nutzungsbedingungen.
  Die Rechtstexte gelten nur hier, die App zeigt diese Seiten an. Änderungen also nur hier machen und das Datum „Stand“ anpassen.
- `assets/` – Stylesheet (Farben wie in der App), Icon, Schriften.
- Schriften Fraunces und DM Sans liegen selbst hier statt bei Google Fonts, damit keine Daten an Google gehen. Lizenz: SIL Open Font License (`assets/fonts/OFL.txt`).
- `.nojekyll` sagt GitHub Pages, dass die Dateien unverändert ausgeliefert werden sollen.

Lokal ansehen: `python3 -m http.server 8000` in diesem Ordner, dann http://localhost:8000/gruenzeug/
