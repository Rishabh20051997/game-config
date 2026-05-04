# game-config

Remote JSON for **Wordle Code** lives under **`wordle-code/config/`** (for example `app-config.json`). Static **Privacy Policy** pages for app review live under **`docs/`**.

## GitHub Pages (Privacy Policy)

1. On GitHub: **Settings → Pages → Build and deployment**.
2. **Source**: Deploy from a branch.
3. **Branch**: `main` (or your default branch), folder **`/docs`**.
4. Save. After the build finishes:

   `https://<owner>.github.io/<repo>/privacy-policy.html`

Static files: **`docs/privacy-policy.html`**, **`docs/index.html`** (redirect), **`docs/.nojekyll`**.
