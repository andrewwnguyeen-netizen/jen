# Cycle — Meal & Routine Planner

Jennifer's personalised cycle-synced nutrition app.

## Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `cycle`)
2. Upload all files from this zip into the root of the repo
3. Go to **Settings → Pages**
4. Set source to **Deploy from a branch → main → / (root)**
5. Click Save — your app will be live at `https://yourusername.github.io/cycle`

## Install on iPhone

1. Open the URL in **Safari** (must be Safari, not Chrome)
2. Tap the **Share** button (box with arrow)
3. Tap **Add to Home Screen**
4. Tap **Add**

The app installs with the 🌸 icon and the name **Cycle**.
It works offline after the first load.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The entire app — all code in one file |
| `manifest.json` | PWA manifest for Android/Chrome install |
| `icon-180.png` | iPhone home screen icon (180×180) |
| `icon-167.png` | iPad Pro icon (167×167) |
| `icon-152.png` | iPad icon (152×152) |
| `icon-120.png` | iPhone icon @2x (120×120) |

## Notes

- Light/dark mode follows iPhone system setting automatically
- Data is stored locally on your device (localStorage)
- No server, no account, no data leaves your phone
