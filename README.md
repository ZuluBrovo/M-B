# M&B NAV v15

Mass, Balance & Nav Log Planner for the Tecnam P2006T and Cessna 152.
Works on a laptop and on a phone. It can be installed on the phone's home screen
and keeps working with no signal.

## What's in this folder

| File | What it does |
|---|---|
| `index.html` | The app itself (M&B NAV v15). |
| `manifest.webmanifest` | Tells the phone the app's name, icon and colours, so it can be installed. |
| `sw.js` | Offline support: keeps a copy of the app on the phone. |
| `icon-*.png`, `apple-touch-icon.png`, `favicon.png` | App icons. |
| `.nojekyll` | Tells GitHub to publish the files as they are. |

## Put it on GitHub (one time, about 5 minutes)

1. Sign in at github.com and click **New repository**.
2. Give it a name, for example `mb-nav`. Choose **Public** (free GitHub Pages needs a public repository). Click **Create repository**.
3. Click **uploading an existing file**. Drag in **all the files from this folder** (not the folder itself) and click **Commit changes**.
   - `.nojekyll` is a hidden file on Mac. If it doesn't drag across, that's fine; the app still works.
4. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to *Deploy from a branch*, **Branch** to `main` and the folder to `/ (root)`. Click **Save**.
5. Wait one or two minutes. The page shows your link, like
   `https://YOUR-USERNAME.github.io/mb-nav/`

## Install it on your phone

**iPhone (Safari):** open the link, tap **Share** → **Add to Home Screen** → **Add**.
**Android (Chrome):** open the link, tap **⋮** → **Install app** (or **Add to Home screen**).

Open it once while you have internet. After that it opens with no signal too.
Weather & NOTAM links still need internet, because they are live websites.

## Updating to a new version later

Upload the new `index.html` to the same repository (it replaces the old one) and commit.
The phone picks up the new version the next time the app is opened with internet.

## Good to know

- Saved profiles stay on each device. The phone and the laptop each keep their own.
- The date prints on the PDFs as DD.MM.YYYY (for example 14.10.2026).
- On iPhone, "Download Filled PDF" opens the PDF; tap **Share** to save it to Files or send it.
