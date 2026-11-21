# Zaara Palasara — Portfolio

A static site: `index.html` plus the `img/` folder. No build step needed.

## Preview locally
Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000

## Deploy
- **Vercel / Netlify:** import this folder (or its GitHub repo); framework preset "Other", no build command, output directory = root.
- **GitHub Pages:** push to a repo, then Settings → Pages → Deploy from branch → `main` / root.

## Editing
- Project details and gallery captions live in the `P` object near the bottom of `index.html`.
- Board pins are plain HTML inside `<div class="board">`. Each pin's `data-c` sets which filter chips show it.
- Images go in `img/` as .webp (around 1600px wide).
