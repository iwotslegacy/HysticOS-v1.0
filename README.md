# HysticOS — GitHub Pages Edition

A browser-based desktop inspired by modern desktop operating systems. Built with plain HTML, CSS, and JavaScript.

## Run it locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser. For screen recording and offline caching, use HTTPS or a local server.
3. For a local server, install Node.js and run `npx serve .` in this folder.

## Publish on GitHub Pages
1. Create a GitHub repository and upload `index.html`, `favicon.svg`, `sw.js`, and this README.
2. Open **Settings → Pages**.
3. Choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
4. Wait for the Pages URL to appear.

## Included
- Sign-in/sign-up demo profile flow
- Windows-style draggable, resizable app windows, start menu, taskbar, clock
- Hystic Store with installable apps
- Terminal commands: `help`, `clear`, `date`, `whoami`, `uname`, `ls`, `pwd`, `echo`, `neofetch`, `apps`, `open`, `install`, `calc`, `theme`, `note`, `uptime`, `matrix`, `fortune`
- Code Studio with sandboxed preview and HTML export
- File Explorer, Notepad, calculator, music/video players, iframe browser with open-new-tab fallback
- Screen recording via browser screen-capture permission
- Task Manager, appearance settings, credits
- Three playable games: Neon Snake, Orbit Defender, Crystal Clicker
- Favicon and basic offline cache

## Important limitations
GitHub Pages is static hosting. It cannot run `server.js`, host a database, or securely validate shared accounts. This demo stores profile records and settings in this browser's `localStorage`; it is **not secure authentication** and won't sync across browsers/devices. Do not reuse a real password here. To support real cross-browser accounts, connect a separately hosted backend/auth provider and database.

The File Explorer currently stores imported file metadata, not the contents of all imported files. The music/video apps play files selected directly from your device. Browser iframe access depends on the target website's embedding policy. Screen recording requires HTTPS or localhost and user permission.

Credits in Settings:
- `@iwotslegacy` — Creator / Developer
- `@phillycheese704` — Inspired
