# Personal website

MkDocs Material site for Rita González Márquez, scaffolded from `wedding-site`.

## Develop locally

```
uv sync
uv run mkdocs serve
```

Then open http://127.0.0.1:8000.

## Deploy

Pushing to `main` builds and publishes to GitHub Pages via `.github/workflows/deploy.yml`
(same pattern as the wedding site). Update `site_url` in `mkdocs.yml` and the repo remote
before the first deploy.

## Structure

- `docs/<page>.en.md` / `docs/<page>.de.md` — one file per language per page (mkdocs-static-i18n,
  suffix structure). English is the default language.
- `docs/stylesheets/extra.css` — colors, fonts, and the `.hero`, `.card`/`.grid`, `.pub`,
  `.page-header-banner` and `.btn` components used across pages.
- `docs/images/header.jpeg` — generated placeholder banner (node/edge motif) used at the top of
  every non-home page. `docs/images/logo.svg` / `favicon.svg` — "RG" monogram.
- `docs/images/profile.svg` — placeholder avatar on the home page.

## TODO before publishing

- [x] in contact change exchange over ...
- [ ] Where to add teaching and supervision?
- [ ] Add your CV PDF at `docs/files/CV_Rita_Gonzalez_Marquez.pdf` (see `docs/files/README.txt`).
- [x] Update `site_url` and the `social` links in `mkdocs.yml`.
- [ ] Double-check the German translations.
