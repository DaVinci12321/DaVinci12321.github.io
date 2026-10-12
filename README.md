# DaVinci12321.github.io

Personal site, served via GitHub Pages at https://DaVinci12321.github.io

- `index.html` / `style.css` — the site
- `lean-paraphrases-paper.pdf` — local copy of the "Lean Paraphrases" preprint, linked from the site (swap this file, or point the link in `index.html` to the arxiv.org page, once the paper is posted on arXiv)

## Publishing

1. Create an empty GitHub repo named exactly `DaVinci12321.github.io` under the DaVinci12321 account (no README/license/gitignore — this folder already has one).
2. From this directory:
   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/DaVinci12321/DaVinci12321.github.io.git
   git push -u origin main
   ```
3. In the repo's Settings → Pages, set the source to the `main` branch, root folder. The site will be live at https://DaVinci12321.github.io within a few minutes.
