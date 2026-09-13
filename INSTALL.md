# Installing Sprachheft on your phone

This app is built as a **PWA (Progressive Web App)** — the closest real equivalent to an APK
without needing the Android developer toolchain. Once installed, it has its own home-screen
icon, opens full-screen with no browser bar, and keeps working with no internet connection.

A browser can only install a PWA from a real web address (not directly from a file on your
computer), so you need to put these files online first. Two easy, free ways:

## Option A — Netlify Drop (easiest, ~1 minute, no account needed)
1. Go to **https://app.netlify.com/drop** on your computer.
2. Drag the whole `sprachheft` folder (this folder, containing `index.html`, `manifest.json`,
   `sw.js`, `icons/`) onto the page.
3. Netlify gives you a link like `https://random-name.netlify.app`.
4. Open that link on your phone.

## Option B — GitHub Pages (free, keeps a permanent link)
1. Create a new GitHub repository and upload these files (keep the folder structure).
2. In the repo settings, enable **GitHub Pages** for the main branch.
3. Open the resulting `https://yourname.github.io/reponame/` link on your phone.

## Then, to install it as an app:

**On Android (Chrome):**
1. Open the link.
2. Tap the **⋮** menu → **Install app** (or **Add to Home screen**).
3. It now appears as a normal app icon and opens full-screen.

**On iPhone (Safari):**
1. Open the link in Safari (must be Safari, not Chrome).
2. Tap the **Share** icon → **Add to Home Screen**.
3. It now appears as a normal app icon and opens full-screen.

Once installed, it will keep working offline — the first visit caches everything it needs.
