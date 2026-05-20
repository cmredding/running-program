# Running Program

A standalone training hub that can be hosted on GitHub Pages or stored as a folder in MEGA.

## Use With GitHub Pages

1. Create a new GitHub repository.
2. Upload these files to the repository root:
   - `index.html`
   - `manifest.json`
   - `service-worker.js`
   - `icon-192.png`
   - `icon-512.png`
   - `.nojekyll`
3. In GitHub, open **Settings > Pages**.
4. Set **Source** to deploy from the main branch root.
5. Open the Pages URL GitHub gives you.

## Install On Android

1. Publish the folder with GitHub Pages so the app has an `https://` URL.
2. On your Android phone, open that URL in Chrome.
3. Tap **Install App** if the button appears.
4. If Chrome does not show the button, tap the three-dot menu and choose **Add to Home screen** or **Install app**.
5. Open **Running Program** from the new icon on your phone.

Android will not install this as an app from a plain local file or a MEGA preview page. MEGA is still useful for storing the folder or progress backups, but GitHub Pages is the better way to install it on your phone.

## Use With MEGA

MEGA is best for storing and sharing the app files or keeping progress backups. Put this folder in MEGA, download it on a device, and open `index.html` in a browser.

## Progress Backup

The app saves checkmarks in the browser on each device. Use **Progress > Export Backup** to download a JSON backup, then store that file in MEGA, GitHub, or another cloud folder. Use **Import Backup** on another device to restore the checkmarks.

## Audio Files

The MP3 coaching tracks are included in the app folder and are referenced by filename. If you publish to GitHub Pages or move the app to MEGA, keep the `.mp3` files in the same folder as `index.html`.
