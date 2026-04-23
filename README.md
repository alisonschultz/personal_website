# Personal website

Hugo site for alisonschultz.com, built with the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.

## Run locally

1. Install Hugo (extended). On Windows:
   ```powershell
   winget install Hugo.Hugo.Extended
   ```
2. Start the dev server:
   ```bash
   hugo server
   ```
   Open http://localhost:1313.

## Deploy

Pushing to `main` triggers `.github/workflows/hugo.yml`, which builds and publishes to GitHub Pages. The `static/CNAME` file configures the custom domain.

## Structure

- `config.yml` — site config: title, bio, nav, social links.
- `content/papers/` — research papers (page bundles).
- `content/policy/` — policy-oriented reports.
- `content/media/` — media list (single page).
- `static/` — photo, CV, favicon (served at site root).
- `layouts/`, `assets/` — template and CSS overrides.
- `themes/PaperMod/` — underlying theme.
