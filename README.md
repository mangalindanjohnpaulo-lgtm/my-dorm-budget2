# Budget Tracker — iOS Home Screen Web App

## Deploy to GitHub Pages
1. Extract this ZIP.
2. Upload **the contents** of this folder to the root of `my-dorm-budget2` on branch `main`. Do not upload the ZIP itself.
3. Commit the files. Wait for GitHub Pages to publish.
4. Open `https://mangalindanjohnpaulo-lgtm.github.io/my-dorm-budget2/` in Safari on your iPhone.
5. Tap Share → Add to Home Screen. If shown, enable **Open as Web App**, then tap Add.

## Included
- `index.html`: Budget Tracker app and iOS web-app metadata
- `manifest.webmanifest`: install metadata
- `service-worker.js`: app-shell caching for offline launch after first successful load
- `icons/`: Home Screen and PWA icons
- `.nojekyll`: prevents GitHub Pages/Jekyll processing

## Important
This package preserves the existing HTML. It does not implement Supabase sign-in or cloud synchronization. Existing browser-local data is not automatically transferred between devices. The app should first be tested on the live site before relying on offline behavior.
