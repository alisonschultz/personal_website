# Personal website

Hugo site using the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme, modeled on
[immanuelfeld.github.io](https://immanuelfeld.github.io/).

## One-time setup

1. **Install Hugo** (extended). On Windows with winget:
   ```powershell
   winget install Hugo.Hugo.Extended
   ```
   Or download from https://github.com/gohugoio/hugo/releases.

2. **Initialize git and add the theme** (PaperMod is included as a submodule):
   ```bash
   git init
   git submodule add --depth=1 https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
   git submodule update --init --recursive
   ```

3. **Add your assets** to `static/`:
   - `profile.jpg` — the headshot shown on the homepage
   - `cv.pdf` — the CV linked from the homepage button
   - (optional) favicons

## Run locally

```bash
hugo server -D
```

Open http://localhost:1313.

## Deploy to GitHub Pages

1. Create a repo named `alisonschultz.github.io`.
2. Update `baseURL` in `hugo.toml` if your username differs.
3. Push, then enable GitHub Pages via GitHub Actions using the standard Hugo workflow
   (`.github/workflows/hugo.yml`) — I can scaffold this on request.

## Structure

- `hugo.toml` — site config: title, bio, social links, nav buttons.
- `content/papers/` — one Markdown file per published/working paper.
- `content/wip/` — one Markdown file per work-in-progress item.
- `static/` — images, CV, favicons (served at site root).

## TODO before publishing

- [ ] Replace the bio in `hugo.toml` (`params.profileMode.subtitle`) with your preferred wording and affiliation.
- [ ] Add `static/profile.jpg` and `static/cv.pdf`.
- [ ] Fill in the abstract and links in `content/papers/broken-relationships.md`.
- [ ] Add any additional papers to `content/papers/`.
- [ ] Confirm or update the GitHub / Scholar URLs in `hugo.toml`.
