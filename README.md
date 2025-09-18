# jtrudeau.github.io

This repository now contains a lightweight, static landing page that is ready
for GitHub Pages publishing. Everything was rebuilt from scratch—only this
README survived from the previous iteration.

## Local preview

Open `index.html` in any modern browser to view the site locally. All assets
are bundled alongside the page under `assets/` so no build step is required.

## Publishing with GitHub Pages

1. Push your changes to the `work` branch (or `main`, depending on the default).
2. In the repository settings on GitHub, enable **Pages** with the following:
   - **Source:** Deploy from a branch
   - **Branch:** `work` (or your default branch) / `/ (root)`
3. Save the settings and GitHub Pages will rebuild the site after each push.

> Tip: Update the placeholder content in `index.html` and drop any images you
> want to feature into `assets/img/`.

## Customization ideas

- Replace the contact links with your real destinations.
- Add new sections (for example, a blog feed or photo gallery) by extending the
  HTML.
- Add a custom domain by creating a `CNAME` file at the repository root.
