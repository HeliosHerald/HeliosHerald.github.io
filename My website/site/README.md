# Tristan Krammel — Portfolio Site

A single-page site. Everything lives in one HTML file plus an images folder.

## Structure

```
site/
├── index.html                 ← the whole website (edit this)
├── CNAME                      ← your custom domain (one line)
├── README.md                 ← this file
└── assets/
    ├── logos/                ← project + brand logos
    │   ├── penpals-logo.png
    │   └── rove54-logo.png
    ├── portrait/             ← your headshot(s)  → portrait.jpg
    ├── projects/
    │   ├── pen-pals/         ← photos for the Pen Pals case study
    │   ├── rove-54/          ← photos for the Rove 54 case study
    │   └── high-dive/        ← photos for the High Dive case study
    ├── ephemera/             ← the catch-all image grid
    └── documents/            ← resume PDF, etc.  → Tristan_Krammel_Resume.pdf
```

## How the site finds an image

The browser doesn't guess — every image is named explicitly in index.html, e.g.
`<img src="assets/portrait/portrait.jpg">`. The folders are just to keep YOU
organized. Put a file in the right folder, then point an <img> tag at it.

## Adding images — the routine

1. Resize first. Nothing needs to be wider than ~2000px. Use squoosh.app (free, in-browser).
2. Name it descriptively: `welcome-letter.jpg`, not `IMG_4471.jpg`.
3. Drop it in the matching subfolder.
4. In index.html, point an <img> tag at it (search for the "[Image]" or "[Portrait]" placeholders).
5. Commit + push. GitHub Pages redeploys automatically.

## Publishing (GitHub Pages)

1. This folder's contents go at the ROOT of your repo (index.html must be top-level).
2. Repo Settings → Pages → Source: Deploy from a branch → main / (root).
3. Custom domain goes in the Pages settings AND in the CNAME file.
4. Enforce HTTPS once the domain verifies.

## Placeholders still to fill

- Portrait image (home)
- Bio: through-line paragraph + ambition paragraph (home)
- "What I'm looking for" ask (home)
- The High Dive write-up + logo (projects)
- Ephemera grid images
- Contact intro line
