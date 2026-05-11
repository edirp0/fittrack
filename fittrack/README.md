# FitTrack AI

Coach personale per l'allenamento — PWA completa.

## Deploy su GitHub Pages

1. Crea un repo su GitHub (es. `fittrack`)
2. Carica i file: `index.html`, `sw.js`, `manifest.json`
3. Vai su **Settings → Pages → Source → main branch / root**
4. Il sito sarà live su `https://tuousername.github.io/fittrack/`

## File

| File | Descrizione |
|------|-------------|
| `index.html` | App completa (HTML + CSS + JS) |
| `sw.js` | Service Worker per funzionamento offline |
| `manifest.json` | Metadati PWA (icone, nome, tema) |

## Login supportato

- ✉️ Email / Password (Firebase)
- 🔵 Google (Firebase Auth)  
- 🍎 Apple Sign In (Firebase Auth — richiede dominio HTTPS)

> **Nota Apple Sign In:** funziona solo su dominio HTTPS verificato.
> Su GitHub Pages funziona. Su `localhost` usa Google o Email.
