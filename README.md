# zaziszaz.github.io

Placeholder "coming soon" landing page for [Your Name]'s portfolio site.

This is a lightweight, static `index.html` (no build step) that serves at the account root via
GitHub Pages while the full portfolio — built with Vite + React + TypeScript + Tailwind CSS —
is developed privately in [`zaz-portfolio-githubio`](https://github.com/zaziszaz/zaz-portfolio-githubio).

## Deployment

GitHub Pages is configured to deploy from the `main` branch (root). Any push to `main` updates
the live page at https://zaziszaz.github.io/ automatically — no build/CI step required since
this is plain static HTML/CSS.

## Replacing this teaser

When the full portfolio is ready to launch, either:

1. Make `zaz-portfolio-githubio` public and deploy it as a project page at
   `zaziszaz.github.io/zaz-portfolio-githubio/`, or
2. Replace the contents of this repo with the full site's production build (adjusting its
   `base`/`basename` back to `/`) so it serves from the account root instead.
