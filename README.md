# Brian Boran Zhang — personal site

Static academic homepage. Hosted on GitHub Pages.

**Live URL (after deploy):** https://boranzzz.github.io

## Stack

Plain HTML + CSS. No build step. Source Serif 4, Soft paper palette.

## Deploy to GitHub Pages

1. On GitHub, create a **public** repository named exactly:
   ```
   Boranzzz.github.io
   ```
2. In this folder, run:

```bash
cd ~/Desktop/Website
git init
git add .
git commit -m "Initial personal site"
git branch -M main
git remote add origin https://github.com/Boranzzz/Boranzzz.github.io.git
git push -u origin main
```

3. Wait 1–2 minutes, then open https://boranzzz.github.io

Settings → Pages should show: Source = Deploy from branch `main` / root.

## Local preview

Open `index.html` in a browser, or:

```bash
open index.html
```
