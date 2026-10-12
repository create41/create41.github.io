# Jared Walters Portfolio

A static portfolio website (HTML, CSS, JavaScript) hosted on GitHub Pages. No backend, no build step, no API keys, no AI/chatbot features.

All content lives in **`portfolio.json`**; the page is generated from it in the browser. You update the site by editing files and pushing to `main`.

## Files

| Path | Purpose |
| --- | --- |
| `index.html` | Page structure and navigation |
| `css/styles.css` | Styling (white/light gray, burgundy accents) |
| `js/app.js` | Renders content from `portfolio.json`, filtering, link validation |
| `portfolio.json` | **All editable content** |
| `assets/resume.pdf` | Your resume (you add this) |
| `assets/images/` | Project images and photos |
| `assets/files/` | Reports and presentations |
| `.github/workflows/deploy.yml` | Deploys to GitHub Pages on push to `main` |

## Preview locally

The site loads `portfolio.json` with `fetch`, so open it through a local server (not by double-clicking):

```bash
python3 -m http.server 8000
