# Minh-Nhat Nguyen — Personal Research Website v2

A static academic/research website designed around a restrained editorial visual system: strong typography, compact news, a coherent research vision, and publication visuals as the main source of color.

## Included

- `index.html` — single-page research homepage
- `cv.html` — public-safe HTML research CV (phone number intentionally omitted)
- `assets/Minh_Nhat_Nguyen_Research_CV.pdf` — public-safe PDF CV generated from the HTML version
- custom publication illustrations for ESC and the CVPRW moment-retrieval paper
- responsive layout for desktop/mobile
- accessibility basics, metadata, JSON-LD, favicon
- `404.html`, `robots.txt`, `sitemap.xml`, `.nojekyll`
- no framework, package manager, or build step required

## Preview locally

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy to GitHub Pages

Create/use the repository:

`minhnhat2001vt.github.io`

Place the **contents** of this folder at the repository root and push to the default branch. GitHub Pages can then serve:

`https://minhnhat2001vt.github.io/`

## Before publishing

1. Review wording and dates one last time.
2. Decide whether you want to add a portrait later. The current design intentionally works without one.
3. After ECCV, replace the conference-specific news items with a short retrospective / latest research update.
4. Re-generate the public CV PDF after any CV content change.

## Design direction

The site intentionally avoids SaaS-style cards, gradients, glassmorphism, and heavy animation. It is closer to an academic editorial page: off-white paper, serif display typography, one restrained accent color, compact timelines, and publication figures carrying the visual weight.


## Portrait
The homepage hero uses `assets/portrait.jpg` for the profile photo. Replace that file with another 4:5 portrait if you want to update the headshot.
