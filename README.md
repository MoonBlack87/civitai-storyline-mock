# Civitai Storylines — interactive concept mockup

[**Open the live demo on GitHub Pages**](https://moonblack87.github.io/civitai-storyline-mock/)

An interactive, **unofficial** concept for connecting independently published images and videos by different creators into shared Storylines. This repository hosts **only the mockup**, not a Civitai feature or backend.

## Explore the demo

Open the live link above, or open `index.html` locally. Start in **Feed**, then explore **Work**, **Storyline**, **100+ chapters**, **Discovery**, and **Queue**. The interface also demonstrates chapter navigation, following stories, suggestions, cross-work links, and a Storyline-wide discussion area.

All interactions are simulated in the browser; nothing is submitted to Civitai, and the example accounts/comments are demonstration content. Original artworks remain credited to their respective creators. The mockup does not grant rights to reuse those works.

## Deployment

This repository publishes its self-contained `index.html` via **GitHub Actions** using [`.github/workflows/deploy-pages.yml`](.github/workflows/deploy-pages.yml). Every push to `main` triggers deployment; the workflow can also be started manually from **Actions**.

In **Settings → Pages**, set **Build and deployment → Source** to **GitHub Actions**. No extra build tools or repository secrets are required for this static demo.

**Demo:** https://moonblack87.github.io/civitai-storyline-mock/  
**Source:** [`index.html`](index.html)
