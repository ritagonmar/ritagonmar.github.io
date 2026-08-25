# Personal website

MkDocs Material personal website, scaffolded from `wedding-site`.

## Develop locally

```
uv sync
uv run mkdocs serve
```

Then open http://127.0.0.1:8000.

## Deploy

Pushing to `main` builds and publishes to GitHub Pages via `.github/workflows/deploy.yml`.

## Structure

- `docs/<page>.en.md` / `docs/<page>.de.md`: one file per language per page (mkdocs-static-i18n, suffix structure). English is the default language.
- `docs/stylesheets/extra.css`: colors, fonts, and the `.hero`, `.card`/`.grid`, `.pub`, `.page-header-banner` and `.btn` components used across pages.
- `docs/images/`: Folder with images like different headers, my picture and "RG" monogram.

