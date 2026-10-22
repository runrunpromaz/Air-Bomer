# Air Bomer

A lightweight English-language airplane shooter PWA. No frameworks, external assets, accounts, or network needed after first visit.

## Run locally
Serve the folder over HTTP (not `file://`):

```bash
python -m http.server 8000
```

Open http://localhost:8000

## Publish on GitHub Pages
1. Create a public repository (for example `air-bomer`).
2. Upload all files and the `icons` folder to the repository root.
3. Open **Settings → Pages → Build and deployment → Deploy from a branch**.
4. Choose `main` and `/ (root)` and save.
5. Your URL will usually be `https://USERNAME.github.io/air-bomer/`.

## Package as PWA
Open the deployed HTTPS URL in a browser and install the app, or enter the URL into a PWA packaging service such as PWABuilder to generate platform-specific packages. Check the target store's current technical and policy requirements before submission.

## Controls
Mouse / touch / arrow keys / WASD to move. Automatic shooting. P to pause. Best score is stored locally.

## Notes
All assets are local. The game works offline after the first successful installation/cache. Update the `CACHE` version in `sw.js` when deploying changes.
