# Source Realms Docs

Player wiki/documentation site for the Source Realms Nations SMP, built with
[MkDocs](https://www.mkdocs.org/) + [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

Live at **https://docs.source-realms.com**.

## Local development

```
pip install -r requirements.txt
mkdocs serve
```

Then open http://127.0.0.1:8000.

## Deployment

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds the site and publishes it
to GitHub Pages automatically. No manual deploy step needed.

### One-time setup (already done, kept here for reference)

1. Repo Settings → Pages → Source: **GitHub Actions**.
2. Repo Settings → Pages → Custom domain: `docs.source-realms.com` (comes from `docs/CNAME`).
3. DNS: a `CNAME` record for `docs` pointing at `<github-username>.github.io.`
4. Once DNS propagates, enable "Enforce HTTPS" in the Pages settings.

## Content

Content lives under `docs/`, organized by topic (nations, war, economy, skills, reference, FAQ).
Update the nav structure in `mkdocs.yml` when adding new pages.
