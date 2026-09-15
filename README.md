# Street Heat 🚗

A GTA-inspired top-down open world game prototype. Drive around, grab jobs, dodge cops, earn cash.

## Put this on GitHub (no coding needed)

1. Go to https://github.com and log in (or create a free account).
2. Click the **+** icon top right → **New repository**.
3. Name it (e.g. `street-heat`), set it to **Public**, click **Create repository**.
4. On the new repo page, click **"uploading an existing file"**.
5. Drag in ALL the files from this folder: `index.html`, `manifest.json`, `service-worker.js`, `icon-192.png`, `icon-512.png`, `README.md`.
6. Click **Commit changes**.

## Turn it into a live web link (GitHub Pages)

1. In your repo, click **Settings** (top menu).
2. In the left sidebar, click **Pages**.
3. Under "Branch," choose **main** and folder **/ (root)**, then **Save**.
4. Wait ~1 minute, refresh the page — you'll see a link like:
   `https://yourusername.github.io/street-heat/`
5. That's your live game link. Anyone can open it in a browser.

## Install it on a phone

1. Open your GitHub Pages link on your phone in **Chrome** (Android) or **Safari** (iPhone).
2. Chrome: tap the **⋮** menu → **"Add to Home screen"**.
   Safari: tap the **Share** icon → **"Add to Home Screen"**.
3. It now sits on your home screen and opens full-screen like a real app.

## Making money with it

- **itch.io** — upload the same files there for free, set a price or "pay what you want."
- **Ads** — add a simple ad script (e.g. Google AdSense for games) into `index.html`.
- **Ko-fi / Patreon / Buy Me a Coffee** — link it in the game or on your itch.io page for donations.
- Once it has real players, an app store release (via a wrapper like Capacitor) opens up in-app purchases.

## What's already built

- Virtual joystick movement (touch or mouse)
- Enter/exit cars
- Delivery missions with cash rewards
- A wanted level + chasing cop cars
- Installable as a PWA (offline-capable, home screen icon)

## Ideas to add next

- More mission types (chases, races, heists)
- Weapons / combat
- Multiple districts with different themes
- Save progress (localStorage — swap this in yourself, or ask Claude to add it)
- Character customization
- Multiplayer (much bigger step — would need a backend)
