# Ping Liu website

Source of https://intuitionquant.github.io/. Plain HTML and CSS served by GitHub Pages from the `main` branch; there is no build step.

- `index.html`, `research.html`, `teaching.html`: the three pages.
- `assets/css/style.css`: the only stylesheet.
- `assets/docs/`: CV, research statement, teaching statement. Replace a PDF under the same filename to update it without touching any link.
- `assets/img/`: portrait and classroom photos, JPEG copies sized for the web.

To publish a change: edit, then `git add -A && git commit -m "..." && git push`. GitHub Pages redeploys within about a minute.
