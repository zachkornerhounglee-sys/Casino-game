# RNGdle: Totally Normal Casino

This folder is prepared for GitHub Pages. The website entry point is `index.html`.

## Publish on GitHub Pages

1. Download and extract this ZIP.
2. Upload the files inside this folder directly into the root of your GitHub repository (do not upload the containing folder itself).
3. In your repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and `/(root)`, then save.
5. Once GitHub Pages publishes the site, open the URL shown in the Pages settings.

## Notes

- This is a static website; no build step is required.
- An internet connection is required for the external Three.js, PeerJS, and Google Fonts libraries loaded by the page.
- Peer-to-peer features depend on the external PeerJS signaling service and network/browser compatibility. GitHub Pages does not provide a game server or store shared player data.
- Player settings and local progress are stored in the browser's local storage, so they are not automatically shared between different devices.
