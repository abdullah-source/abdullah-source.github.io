# abdullah-source.github.io

Personal portfolio for Abdullah Ali, CS + Math undergraduate at Harvey Mudd
College. Static site, no framework, no build step. Plain HTML, CSS, and a little
vanilla JavaScript.

## Files

| File | What it is |
|------|-----------|
| `index.html` | All the content (hero, about, skills, experience, projects, honors, contact) |
| `styles.css` | Dark, responsive theme. CSS variables at the top for easy recoloring |
| `script.js` | Mobile nav toggle, sticky-nav border on scroll, scroll-reveal animation |

## Run locally

It's just files, so either open `index.html` directly, or serve it:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Publish on GitHub Pages (free URL)

The repo name `abdullah-source.github.io` is special: GitHub serves it as a
website automatically.

1. Create a repo named exactly **`abdullah-source.github.io`**.
2. Push this folder to its `main` branch.
3. In the repo: **Settings → Pages → Source: Deploy from a branch → `main` / root**.
4. Wait about a minute. Your site is live at **https://abdullah-source.github.io**.

## Edit checklist

- Update the LinkedIn URL in `index.html` (currently a placeholder `linkedin.com`).
- Add a `Lighthouse` repo link when it's public (the card currently has no link).
- Drop a `Resume.pdf` in the folder and add a "Resume" button if you want one.
- Recolor by editing the `--accent` / `--accent-2` variables at the top of `styles.css`.
