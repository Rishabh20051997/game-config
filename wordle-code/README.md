# wordle-code (game-config)

Remote JSON for **Wordle Code** (`config/app-config.json`) and a **Privacy Policy** page for app review.

## GitHub Pages (Privacy Policy)

1. On GitHub: **Settings → Pages → Build and deployment**.
2. **Source**: Deploy from a branch.
3. **Branch**: `main` (or your default branch), folder **`/docs`**.
4. Save. After the build finishes, the site URL is:

   `https://<your-github-username-or-org>.github.io/<repository-name>/`

5. Use this URL in App Store Connect / Play Console (append **`privacy-policy.html`** if you want the explicit path):

   `https://<owner>.github.io/<repo>/privacy-policy.html`

Static files live under **`docs/`** (including `.nojekyll` so GitHub does not run Jekyll on this folder).
