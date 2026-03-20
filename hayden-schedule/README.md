# Hayden — Senior Spring Schedule App

A personal PWA (Progressive Web App) for your Ole Miss Senior Spring 2026 schedule.

## Features
- Full Mon–Sun schedule with time blocks
- Check off blocks as you complete them (resets daily)
- Countdown to May 8 graduation
- Block reminders via browser notifications (5 min before each block)
- Works offline once installed
- Installs to your phone or laptop like a real app

---

## How to install (2 options)

### Option A — GitHub Pages (recommended, free, works on all devices)

1. Go to https://github.com and sign in (or create a free account)
2. Click the **+** → **New repository**
3. Name it: `schedule` (or anything you want)
4. Check **"Add a README file"**, set visibility to **Public**, click **Create repository**
5. On the repo page, click **Add file → Upload files**
6. Drag in ALL files from this folder: `index.html`, `manifest.json`, `sw.js`, and the `icons/` folder
7. Click **Commit changes**
8. Go to **Settings → Pages → Source → Deploy from branch → main → / (root) → Save**
9. Wait ~60 seconds. Your app is live at: `https://YOUR-USERNAME.github.io/schedule`

**On iPhone:** Open that URL in Safari → Share → Add to Home Screen
**On Mac:** Open in Chrome or Edge → click the install icon in the address bar
**On Android:** Chrome will prompt you to install automatically

---

### Option B — Local only (laptop only, no hosting needed)

1. Unzip this folder anywhere on your computer
2. Double-click `index.html` — it opens in your browser
3. You won't get push notifications locally (browser security requirement), but everything else works

---

## Notes
- Checks reset automatically each day
- Notifications fire 5 minutes before each block for today's schedule
- The countdown ticks down to May 8, 2026 at 10:00 AM
- Works fully offline after first load (service worker caches everything)
