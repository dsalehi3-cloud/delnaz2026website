# DESA — Delnaz Salehi Architecture

Portfolio website. One self-contained page: `index.html`.

## Editing
- **Projects** — the `PROJECTS` array at the top of the script in `index.html`. One object per project; it fills the Work grid and each project page.
- **Studio, CV, contact** — the `STUDIO` object just below it.
- **Hero film** — set `filmSource` to a short muted video (6–12 s, H.264) placed next to `index.html`; scrolling then scrubs it. Until then a generative corridor plays in the slot.
- **Images** — replace any hatched `.ph` placeholder with an `<img>` of the stated ratio.

## Running locally
Open `index.html` in a browser. Fonts load from Google Fonts and GSAP from cdnjs, so it needs a network connection.

## Deploying
Any static host works (GitHub Pages, Netlify, Vercel). For GitHub Pages: Settings → Pages → deploy from the `main` branch, root folder.
