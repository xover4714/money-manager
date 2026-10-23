MY MONEY MANAGER — iPHONE SETUP

Files:
- index.html: the finance app
- manifest.json and icons: app identity
- sw.js: offline cache for supported browsers

IMPORTANT:
This is a client-side prototype. Transactions and savings are stored in local browser storage on the device. There is no bank/mobile-money connection, no account login, and no cloud sync. Export backups regularly. Do not treat the app as a bank statement.

TO INSTALL ON IPHONE:
1. The app files need to be hosted on an HTTPS website for reliable Home Screen/PWA installation and offline support. Opening index.html directly from Files is not the full install process.
2. Upload the contents of this folder (not the enclosing folder) to an HTTPS static host such as GitHub Pages or Netlify. You will need to complete the hosting provider's account/setup steps.
3. Open the resulting HTTPS site in Safari on your iPhone.
4. Tap Share (the square with the upward arrow), choose Add to Home Screen, edit the name if desired, and tap Add.
5. Launch My Money Manager from the Home Screen. Add a test transaction and export a backup to check the flow.
6. Keep the same site address and browser storage; clearing Safari website data can remove records. Export JSON backups regularly.

If the app is hosted under a subfolder, keep all included files together in that same folder.
