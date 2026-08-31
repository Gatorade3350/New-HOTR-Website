# HOTR — Proof of Concept Website

This repository contains a minimal static website scaffold located in the `docs/` folder intended for publishing with GitHub Pages.

Quick publish options:

- Use the `docs/` folder as Pages source: go to repository Settings → Pages → Source → select `main` branch and `/docs` folder.
- Or enable the included GitHub Actions workflow to publish `docs/` to the `gh-pages` branch automatically on pushes to `main`.

What I added:

- `docs/index.html` — main HTML
- `docs/styles.css` — simple responsive styling
- `docs/.nojekyll` — disable Jekyll processing
- `.github/workflows/deploy.yml` — optional automatic deploy to GitHub Pages

Next steps:

1. Push this repository to GitHub.
2. If you prefer the GitHub Pages UI, set the site source to `/docs` as described above.
3. If you want automatic deployments, enable Actions and push to `main` (the workflow uses the repository `GITHUB_TOKEN`).
