# Royal Aura Academy Dashboard

A progressive web app and cross-platform app for school management.
**Install and run as web (PWA), desktop (Electron), or Android (Capacitor).**

## 🖥️ Web App / PWA

1. Serve `www/` folder with HTTPS.
2. Open `index.html` in Chrome/Edge/Safari.
3. Use "Install App" from browser menu for desktop/mobile.

## 🖱️ Desktop App (Electron)

1. `npm install` in root directory.
2. `npm start` to launch as Electron app.
3. To build .exe for Windows:
    ```bash
    npx electron-packager . RoyalAuraDesktop --platform=win32 --arch=x64
    ```

## 📱 Android App (Capacitor)

1. Install Capacitor CLI: `npm install -g @capacitor/cli`
2. Run `npm install` in root directory
3. Configure `capacitor.config.json`
4. Add Android with `npx cap add android`
5. Copy files: `npx cap copy android`
6. Open Android Studio: `npx cap open android`
7. Build APK or AAB as usual.

## 📂 Folder Structure

See below for a suggested file structure for easy use and modification.

```
www/
  index.html
  manifest.json
  sw.js
  icon192.png
  icon512.png
electron.js
preload.js
package.json
capacitor.config.json
README.md
```

## 💡 Credits
- Royal Aura Academy ([your name])
