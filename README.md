# Muhammad Zaman — Academic Portfolio

A static site (HTML, CSS and JavaScript) that needs no build step. It adapts to mobile and desktop.

```
index.html              the website
assets/img/             headshot.jpg, portrait.jpg
assets/thumbs/          first-page previews of each document
docs/                   CV + official notifications/certificates (PDF)
```

## Deploy to GitHub Pages
1. Create a repository, e.g. `muhammad-zaman` (or `<username>.github.io` for a root URL).
2. Upload **everything in this folder**, keeping the folder structure.
3. Go to Settings → Pages → Build and deployment → *Deploy from a branch* → `main` / `(root)` → Save.
4. After about a minute the site is live at `https://<username>.github.io/<repo>/`.
5. Optional: add a custom domain such as `dr-zaman.com` under Settings → Pages → Custom domain, then point the domain's DNS to GitHub.

## Updating
- **Citations / h-index**: edit the `SCHOLAR` object near the bottom of `index.html`.
- **Publications**: add a line to the `PUBS` array (`y` year, `t` title, `v` venue, `q` Q1/Q2/Conf, `c` category).
- **New document**: put the PDF in `docs/`, add a first-page JPG to `assets/thumbs/` with the same name, and add an entry to `DOCS`.
- **CV**: replace `docs/Muhammad_Zaman_CV.pdf` (keep the same filename).
