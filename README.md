# Abhay MBA Portfolio (Quarto)

Live site: https://ab4072g-debug.github.io/abhay-mba-portfolio/

## Overview
This repository contains a single-page MBA portfolio webpage built with **Quarto** and **Markdown**. It is designed to function as a concise digital business card and includes sections for About, Education, Professional Experience, Key Skills, Projects/Highlights, and Contact.

## Repository structure
- `index.qmd` — main single-page portfolio content
- `_quarto.yml` — Quarto project configuration (outputs to `docs/` for GitHub Pages)
- `styles.css` — light custom styling + mobile responsiveness
- `images/` — headshot image(s)
- `appendix.md` — LLM draft/output + revision commentary + references (submission appendix)
- `docs/` — rendered site output (published by GitHub Pages)

## Build locally
Prerequisite: Install Quarto (https://quarto.org).

From the repository root:

```bash
quarto render
```

Then open:

```bash
open docs/index.html
```

## GitHub Pages deployment
This site is deployed via **GitHub Pages** from:
- Branch: `main`
- Folder: `/docs`

Note: `docs/.nojekyll` is used to prevent Jekyll processing.

## LLM use and academic integrity
An LLM (ChatGPT) was used to generate an initial outline and sample draft text. The final portfolio content was reviewed for accuracy and rewritten/edited to reflect the author’s authentic background and voice. Full details are documented in `appendix.md`.

## License
This repository is intended for academic submission and personal portfolio use. If you want an explicit open-source license, add a `LICENSE` file (e.g., MIT).
