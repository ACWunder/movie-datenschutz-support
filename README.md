# Movie · Datenschutz & Support

Statische Website für die Movie-iOS-App. Drei Seiten, ein CSS, kein Build-Step.

## Vorm Veröffentlichen ausfüllen

In `impressum.html` die Platzhalter ersetzen:

- `[Straße + Hausnummer]`
- `[PLZ + Ort]`

Optional in `datenschutz.html`: aktuelles Jahr im Lead-Absatz prüfen.

## Deployment via GitHub Pages

1. Repo auf GitHub öffnen → **Settings → Pages**
2. **Source**: `Deploy from a branch`
3. **Branch**: `main` / Folder: `/ (root)` → Save
4. Nach ~1 Minute live unter `https://acwunder.github.io/movie-datenschutz-support/`

## URLs für App Store Connect

Im App Store Connect unter „App-Datenschutz" und „Allgemeine App-Informationen":

- **Datenschutzrichtlinie-URL**: `https://acwunder.github.io/movie-datenschutz-support/datenschutz.html`
- **Support-URL**: `https://acwunder.github.io/movie-datenschutz-support/`

## Lokal testen

```
open index.html
```

Oder mit beliebigem Static-Server (z.B. `python3 -m http.server 8000`).

## Updates

Wenn die App neue Datenverarbeitungen einführt (z.B. Analytics, Push), den entsprechenden Abschnitt in `datenschutz.html` ergänzen und neu pushen — GitHub Pages deployed automatisch.
