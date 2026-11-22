SUPRAAKASH WEALTH TRACKER V4.1.9 — PWA deployment package

Upload these THREE files to the ROOT of the existing GitHub Pages repository:
1. index.html
2. manifest.webmanifest
3. sw.js

These are intended to REPLACE the three existing files with the same names.
Do not replace or delete icon-192.png or icon-512.png. The manifest keeps the
existing app id, start_url, scope, and icon paths.

Before updating, export a backup JSON from the currently installed app and keep
it safely. The V4.1.9 HTML uses the existing localStorage keys:
mwt_v1_data and mwt_v1_market_prices.

After all three files are committed, wait for GitHub Pages to publish. Then
open the existing app URL in Chrome, refresh it, and allow the service worker
to update. Verify the Version 4.1.9 badge before installing/updating the
home-screen app. Do not uninstall or clear browser data.
