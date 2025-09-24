# Momentum Labs Logbook

This repository powers the Momentum Labs minimalist blog hosted on [GitHub Pages](https://pages.github.com/). The site is built with Jekyll and styled to echo a retro-futuristic control room using the blue, red, and yellow palette inspired by the DESY institute magnets in Hamburg.

## GitHub Pages (gh-pages) workflow

- The `github-pages` gem (see [`Gemfile`](Gemfile)) locks the Jekyll and plugin versions to those used by GitHub Pages, so deployments stay in sync with the platform.
- Because this repository follows the `<username>.github.io` naming convention, GitHub Pages automatically publishes the contents of the default branch—no additional branch configuration is required.
- Metadata such as `url` and `enforce_ssl` in [`_config.yml`](_config.yml) are set to the GitHub Pages domain to ensure canonical links and the sitemap point to the live site.

## Local development

1. Install Ruby (the same major version that GitHub Pages uses) and Bundler.
2. Install dependencies with `bundle install`. If a network restriction blocks access to `rubygems.org`, retry from a network with access or rely on GitHub Pages to perform the install during deployment.
3. Start the local preview server with `bundle exec jekyll serve` and open `http://localhost:4000`.
4. Edit content in `_posts/`, tweak the homepage in `index.html`, or adjust global styles within `_layouts/default.html`.

## Content & styling notes

- The homepage hero introduces the "Hello, world" broadcast and links directly to the latest posts.
- Posts are rendered in a neon-inspired card layout that highlights publish dates and excerpts.
- Colours throughout the layout are pulled from the DESY magnet palette and the typography pairs Space Grotesk with Orbitron for a retro-futuristic feel.

## Deployment checklist

- Commit changes to the default branch.
- Push to GitHub; the GitHub Pages build pipeline will regenerate the site automatically.
- Verify the published site at <https://jtrudeau.github.io> once the build completes.
