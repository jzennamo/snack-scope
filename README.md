# Snack Scope

Set your protein, carbs, fat and fiber targets, and Snack Scope builds recipes from your pantry with gram amounts solved to hit them. It's a single HTML page. It installs to your home screen, works offline after the first load, and keeps your targets, pantry and label edits on your phone.

## Put it on GitHub Pages

1. On github.com, create a new repository, for example `snack-scope`. It can be public or private (private Pages needs a paid plan).
2. Upload everything in this folder to the repository root: `index.html`, `manifest.webmanifest`, `sw.js`, `README.md` and the `icons` folder. You can drag and drop them under **Add file → Upload files**.
3. Go to **Settings → Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, the branch to `main` and the folder to `/ (root)`, then save.
4. After a minute or two the site is live at `https://<your-username>.github.io/snack-scope/`.

## Install it on your phone

**Android (Chrome):** open the link, then tap the ⋮ menu and choose **Add to home screen**, then **Install**.

**iPhone (Safari):** open the link, tap Share and choose **Add to Home Screen**.

## Updating it later

Edit `index.html` in the repository, then open `sw.js` and bump `VERSION` (for example `snack-scope-v2`) so installed copies fetch the new version. Close and reopen the app once to pick it up.

Your settings live in your phone's browser storage for this site. Changing the files doesn't touch them, but clearing Chrome's site data for github.io will.
