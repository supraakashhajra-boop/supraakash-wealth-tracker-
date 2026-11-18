SUPRAAKASH WEALTH TRACKER V4.1.7 — FINAL GITHUB PWA PACKAGE
===========================================================

This package contains the tested V4.1.7 app with the approved clean,
borderless Midnight Navy + Metallic Gold brand logo.

FILES (all six are at the repository ROOT):
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png
- README.txt

GITHUB PAGES UPLOAD
1. Keep your current repository and old app files untouched until the new
   deployment is checked.
2. Extract this ZIP.
3. Upload all six files directly into the intended GitHub repository ROOT.
   Do not put them inside a new folder.
4. Commit to the branch configured in Settings > Pages.
5. Wait for GitHub Pages to finish publishing, then open the published URL.

DATA SAFETY
- The app's existing localStorage key is retained: mwt_v1_data.
- Browser-local data does not automatically move between different website
  origins. Before changing origins, export a JSON backup from the old app.
- Restore that backup in the new app and verify transactions, portfolio,
  settings and PIN before deleting or clearing anything.
- Do not clear the old app's browser/site data during this process.

PWA IDENTITY
- The existing manifest id and start_url identifier are retained from the
  supplied PWA shell to preserve the installed app identity on the same origin.
- The service-worker cache has a new V4.1.7 final-brand version so the updated
  logo and app shell can be fetched.
- App data logic and trading/accounting features have not been intentionally
  changed in preparing this package.

VERIFICATION LIMIT
- HTML/JavaScript syntax, manifest JSON, service-worker syntax, file paths and
  icon dimensions are checked before delivery.
- GitHub deployment, actual Android installation, icon refresh and offline
  behavior still need to be checked on the published site.
