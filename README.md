# Asham Preet Saini — Portfolio

Personal portfolio site for a PharmD working in drug safety and pharmacovigilance.
The page is structured around the lifecycle of a safety case: intake, triage, coding,
assessment, narrative and quality review.

## Features

- Single static page: no framework, no build step, no dependencies
- Scroll-driven case workflow with a pinned stage tracker
- Reveal, count-up and line-draw animations using only opacity and transforms
- Responsive from phone to desktop
- Honours the `prefers-reduced-motion` setting
- Content stays readable with JavaScript disabled

## Setup

Open `index.html` in a browser, or serve the folder locally:

```bash
python -m http.server 4190
```

Then visit http://localhost:4190.

## Configuration

All content, styles and scripts live in `index.html`.

- Colours and fonts are CSS variables at the top of the `<style>` block
- To update the résumé, replace `Asham-Preet-Saini-Resume.pdf` and keep the file name

## Deploy

The site is plain static files, so any static host works (GitHub Pages, Netlify,
Cloudflare Pages). For GitHub Pages, serve the root of the `main` branch.

## Tests

There is no build or test suite. Before publishing, check the page at phone and
desktop widths and confirm the browser console is clean.
