# Blas Kolic — Academic Website

Welcome to my personal website's repo. ChatGPT helped me build it using plain HTML, CSS, and JavaScript. Deployed via GitHub Pages.

---

##  Purpose

This static site serves as my research portfolio, featuring my background, publications, software, blog, and contact information.

---

##  Structure

| Folder / File         | Description                                           |
|-----------------------|-------------------------------------------------------|
| `index.html`          | Main landing page (with Hero, About, Research, etc.) |
| `*.html` (e.g., `publications.html`) | Section-specific layouts (loaded dynamically) |
| `assets/`             | Static resources: CSS, images, audio, placeholder media |
| `assets/site.css`     | Central stylesheet for layout, theming, and visuals  |
| `README.md`           | This documentation file                              |

---

##  Local Development

To preview the site locally with includes and styles correctly loaded:
```bash
cd blas-ko.github.io
python3 -m http.server 8000
# Open http://localhost:8000 in your browser
