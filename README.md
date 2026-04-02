# Shivan Vazikati

Shivan Vazikati is a Tamil-first static web application for exploring the 276 Paadal Petra Sthalams, the Shiva temples praised in the Thevaram hymns of Sambandar, Appar, and Sundarar. The app helps devotees and travelers browse temples by region, read temple significance and history, view images, plan pilgrimages, and open directions in Google Maps.

## Repository Description

Use this as your GitHub repository description:

`Tamil-first web app for exploring the 276 Paadal Petra Sthalams with temple history, images, filters, and Google Maps guidance.`

## Suggested Repository Details

- Repository name: `shivan-vazikati`
- Website/About URL:
  Add your deployed GitHub Pages URL after publishing
- Suggested topics:
  `tamil`, `shivatemple`, `paadal-petra-sthalam`, `thevaram`, `temple-guide`, `static-site`, `javascript`, `pwa`

## What This App Includes

- Canonical 276-entry Paadal Petra Sthalam directory
- Traditional regional grouping
- Dedicated profile view for every temple
- Tamil-first interface
- Expanded history and significance for curated major temples
- Temple legends, architecture notes, and spiritual highlights
- Search by temple name, deity, town, region, and hymn-related text
- Filter by Nayanmar where data is available
- Google Maps search, directions, and embedded location map
- Nearby temple suggestions
- Favorites and pilgrimage planner
- Personal local travel notes saved in the browser
- Offline-ready app shell using a service worker
- Temple image loading through Wikipedia and Wikimedia Commons sources

## Project Files

- [index.html](C:/Users/91915/Downloads/codex/index.html): main app page
- [styles.css](C:/Users/91915/Downloads/codex/styles.css): UI styling
- [app.js](C:/Users/91915/Downloads/codex/app.js): app logic, filtering, rendering, Tamil UI behavior
- [catalog.js](C:/Users/91915/Downloads/codex/catalog.js): canonical 276-temple catalog
- [profiles.js](C:/Users/91915/Downloads/codex/profiles.js): expanded temple profiles and notes
- [sw.js](C:/Users/91915/Downloads/codex/sw.js): offline caching
- [manifest.webmanifest](C:/Users/91915/Downloads/codex/manifest.webmanifest): installable web app manifest
- [icon.svg](C:/Users/91915/Downloads/codex/icon.svg): app icon

## Run Locally

This is a static site. No package install or build step is needed.

Recommended:

```powershell
cd C:\Users\91915\Downloads\codex
python -m http.server 5500
```

Then open:

[http://localhost:5500/index.html](http://localhost:5500/index.html)

## Run On Phone

To open the site on a phone connected to the same Wi-Fi:

1. Start the local server on your computer.
2. Run `ipconfig` in PowerShell.
3. Find your computer's `IPv4 Address`.
4. On your phone, open:

```text
http://YOUR-IP-ADDRESS:5500/index.html
```

Example:

```text
http://192.168.1.5:5500/index.html
```

## iPhone Usage

After opening the site in Safari:

1. Tap `Share`
2. Tap `Add to Home Screen`
3. Save it as an app-like shortcut

## Deploy Online

The easiest way is GitHub Pages.

1. Create a GitHub repository
2. Upload all project files
3. Push to the `main` branch
4. Open repository `Settings`
5. Open `Pages`
6. Set source to deploy from the main branch
7. Save and wait for the public site URL

After publishing, your site will be available through a shareable URL that works on iPhone, Android, desktop, and tablet browsers.

## Notes

- Temple photos depend on online public image sources. If an image match is unavailable, a fallback placeholder is shown.
- The app is designed to work best when served through a local or online web server, not through direct `file://` opening.
- Some temple names remain in canonical romanized form internally for search compatibility and map lookup reliability.
- Expanded long-form history content is currently richer for selected major temples, while all 276 entries are present in the directory and profile system.

## Verification

JavaScript syntax checked with:

```powershell
node --check app.js
node --check sw.js
```
