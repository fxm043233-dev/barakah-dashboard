# Barakah — Muslim Life & Wealth Dashboard

A responsive, installable personal dashboard built with plain HTML, CSS and JavaScript.

## Run locally
Open `index.html` in a browser. For service-worker/PWA testing, use a local web server (for example VS Code Live Server).

## Publish with GitHub Pages
1. Sign in to GitHub and create a **public** repository, e.g. `barakah-dashboard`.
2. Upload these files to the repository root: `index.html`, `style.css`, `script.js`, `manifest.webmanifest`, `sw.js`, and `icon.svg`.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then Save.
6. Wait for the Pages deployment and open the URL shown there.

## Install on your phone
- Android: open your GitHub Pages URL in Chrome → menu (⋮) → **Install app** or **Add to Home screen**.
- iPhone: open the URL in Safari → Share → **Add to Home Screen**.
- The site uses a web app manifest and service worker so the shell can be cached for repeat visits. Install availability can vary by browser.

## Your data and privacy — important
- Journal, prayer checklists, adhkar, routine, trading records and money records are saved in `localStorage` in the browser on that device.
- GitHub Pages hosts the app files, **not your private records**. Data is not uploaded to GitHub and does not automatically sync between your computer and phone.
- To move data to another device: on the original device open **History & backup → Export JSON**. Transfer that JSON file privately to the other device, open the site there, then use **Import backup**.
- Export backups regularly. Clearing browser data can erase records. Avoid importing a backup from an untrusted source.
- Do not enter bank login details, card numbers, passwords or other highly sensitive information.

## Included features
- Five salah checklists, Tahajjud, Witr, Duha and Quran check-in
- Morning and evening adhkar completion lists
- Morning routine and workout log
- Muslim trading self-review checklist and Naira P/L journal
- Naira income/expense tracker, budget and balance
- Daily journal, date selector, history, JSON export/import
- Responsive layout and installable PWA shell

## Islamic finance note
The trading checklist is a personal educational prompt, not a Sharia certification or fatwa. Whether a particular asset, broker, contract or trading method is permissible can depend on its exact structure and scholarly interpretation. Consult a qualified Islamic finance scholar.
