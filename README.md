# Pref Group

This repository now contains a minimal [Astro](https://astro.build/) site that can
be deployed to GitHub Pages with the existing Actions workflow.

## Local development

1. Install dependencies with `npm install`
2. Start the dev server with `npm run dev`
3. Build the production site with `npm run build`

## Deployment

Pushes to `main` trigger `.github/workflows/astro.yml`, which installs dependencies,
builds the Astro site, and deploys the generated `dist/` output to GitHub Pages.
