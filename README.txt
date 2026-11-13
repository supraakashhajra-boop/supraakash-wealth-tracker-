SUPRAAKASH WEALTH TRACKER V4.1.2 — GITHUB ROOT UPLOAD PACKAGE
=============================================================

IMPORTANT: This version is designed for GitHub's MOBILE upload screen.
Upload ALL SIX files directly into the repository ROOT. Do NOT create an icons folder.

Files:
- index.html
- manifest.webmanifest
- sw.js
- README.txt
- icon-192.png
- icon-512.png

The manifest, app header and service worker all reference icons in the root folder.
This fixes broken icon paths caused when mobile GitHub upload places selected icon files at repository root.

Upload:
1. In the NEW repository, open Add file > Upload files.
2. Select all six files above.
3. Ensure the list shows them as root files.
4. Commit changes to main.
5. Settings > Pages > Deploy from a branch > main > /(root) > Save.
6. Wait for deployment to complete, then open the Pages URL and reload.

If the previous files were already uploaded to this new repository, upload these six files again to replace them.

DATA:
A new GitHub Pages origin does not share browser-local data with the old app.
Export JSON backup from old app and restore it in the new app only after deployment.
Do not clear old browser/site data until the restored data is verified.

Verification:
Archive integrity and references have been checked. Final installability must be confirmed after GitHub Pages publishes the files.
