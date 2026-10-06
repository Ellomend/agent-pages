# Agent Pages

A public collection of small interactive HTML/JavaScript pages created with agents.

Live collection: https://ellomend.github.io/agent-pages/

First sample: https://ellomend.github.io/agent-pages/colour-lab.html

The site uses plain files, system fonts and browser JavaScript. There is no build step or backend.

## Publishing

GitHub Pages publishes the `main` branch from the repository root. A commit to `main` triggers publishing; wait for the Pages deployment to finish before checking the live URL.

Add another HTML page or a folder containing `index.html`, link it from the collection's `index.html`, and commit the changes. Use relative asset paths so pages work below `/agent-pages/`.

## Local preview

Run `python3 -m http.server 8000` in this directory, then open `http://localhost:8000/`.

Created 6 October 2026 as the first GitHub Pages publishing experiment.
