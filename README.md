# gobadiah-site

The Gobadiah Inc. studio site, served at **apps.gobadiah.com** via GitHub Pages.

- `index.html` — studio landing (lists products)
- `loglens/` — LogLens for CloudWatch product page
- `privacy.html` — company privacy policy (covers all products)
- `style.css` — shared styles
- `CNAME` — custom domain

Static, no build step. `.github/workflows/pages.yml` deploys on every push to
`main`.

## One-time setup
1. Settings → Pages → Build and deployment → Source: **GitHub Actions**
2. Settings → Pages → Custom domain: `apps.gobadiah.com`
3. DNS on gobadiah.com: add a `CNAME` record `apps` → `gobadiah.github.io`

Adding a product = a new folder + a card on the landing page.
