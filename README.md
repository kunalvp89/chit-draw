# Chit Draw PWA

A responsive Progressive Web App for random chit drawing.

## Run locally
Because service workers require a secure context, serve this folder with a local HTTP server:

```bash
python -m http.server 8080
```

Then open http://localhost:8080

## Features
- Enter one chit per line
- Random selection using Web Crypto when available
- Pick from a grid of identical chits
- Touch/mouse scratch-to-reveal effect
- Confetti on reveal
- Draw again without repeating already-drawn entries
- Start over
- Installable PWA with offline cache

## Saved list
The list entered on the first page is automatically saved in the browser's localStorage and restored when the app is reopened. It stays on that device/browser until the browser's site data is cleared.
