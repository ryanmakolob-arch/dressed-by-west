# Dressed by West

This repository contains a simple static website for the "Dressed by West" shop.

Files:
- index.html — the site
- .nojekyll — prevents GitHub Pages from ignoring files that start with an underscore

Deployment (GitHub Pages):
1. Go to this repository's Settings → Pages.
2. Under "Build and deployment", set the source to the `main` branch and the root folder (/).
3. Save; the site will be published at: https://ryanmakolob-arch.github.io/dressed-by-west/

Notes:
- The WhatsApp order button is configured to send to +256740969377. To change it, edit `index.html` and modify the number in the `window.open("https://wa.me/...")` call.
- Images are loaded from Unsplash. For reliability, consider adding local images in an `assets/` folder.
