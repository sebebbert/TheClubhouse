# Link Tree Landing Page (GitHub Pages Template)

This is a minimal template for a personal link landing page (Linktree-like) designed to be hosted on GitHub Pages.

Files created:

- `index.html` — the landing page
- `assets/styles.css` — styling
- `.github/workflows/deploy-pages.yml` — GitHub Action that deploys on push to `main`

How to use

1. Customize `index.html`: replace `Your Name`, `bio`, and the link `href` values with your own URLs.
2. Commit & push to the `main` branch.
3. GitHub Actions will automatically deploy the repository root to GitHub Pages. You can also enable Pages from the repository settings and serve from `main` branch.

Preview locally

Open a terminal at the repository root and run:

```powershell
python -m http.server 8000
# then open http://127.0.0.1:8000 in your browser
```

Notes

- The workflow uses the official GitHub Pages deployment actions and will publish the repository content as your Pages site after the first successful run.
- If you prefer to use a custom domain, add a `CNAME` file at the repository root and configure DNS accordingly.
