# Command Notebook

An iPhone-style learning app for IC200 and IC300 incident command: lessons, glossary, sources, spaced review and scenario exercises. Everything runs in the browser; progress is stored on the device.

## Publish with GitHub Pages

1. Create a new repository on GitHub.
2. Choose **Add file › Upload files**, drag in every file from this folder, and commit.
3. Open **Settings › Pages**. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then save.
4. After a minute the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Add to your iPhone Home Screen

1. Open the Pages address in Safari.
2. Tap **Share › Add to Home Screen**, then **Add**.
3. Launch it from the Home Screen icon. It opens full screen on Today and works offline after the first visit.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole app: layout, content and logic |
| `manifest.webmanifest` | Home Screen name, icons and standalone launch |
| `sw.js` | Offline caching (needs HTTPS, which GitHub Pages provides) |
| `apple-touch-icon.png` | iPhone Home Screen icon (180 × 180) |
| `icon-192.png`, `icon-512.png`, `icon-512-maskable.png` | Icons for other platforms |
| `icon.svg` | Editable source for the icon |
| `.nojekyll` | Tells GitHub Pages to serve the files exactly as they are |

## Updating

After you change `index.html`, also change the cache name in `sw.js` (for example `command-notebook-v2`) so installed copies pick up the new version.

Content summarises public ICS training material and doesn't replace an accredited course.
