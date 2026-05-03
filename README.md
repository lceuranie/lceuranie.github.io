# L. Chris Euranie — Portfolio Website

Static HTML/CSS portfolio. No build step. No dependencies. Edit any page in a text editor, push to GitHub, and the site is live.

---

## Files

```
index.html                          Homepage
about.html                          About / story / education
publications.html                   Publications list
404.html                            Error page

project-titan.html                  Featured: TitanMBSE + Titan Swarm (combined)
project-rwanda-eo.html              Featured: Rwanda EO/AI app
project-terroir.html                Featured: Terroir Prediction Engine
project-eyesat-cubesat.html         Eyesat-1 CubeSat
project-deep-space-comms.html       Deep Space Communication / IAC 2026
project-space-defense.html          European Space Defense Administration
project-orbital-mission-design.html Orbital mission design / STK
project-astronomical.html           NGC 4852 / Gaia DR3
project-sbsp.html                   SBSP individual report
project-geosciences.html            10 yrs geophysics at SLB
project-management.html             Digital transformation / programme management

assets/
  css/style.css                     All styling
  js/main.js                        Mobile nav toggle (~25 lines)
  images/                           Project images go here (currently empty)
  L_Chris_Euranie_CV.pdf            CV download — drop yours here
```

---

## Deploying to GitHub Pages

1. Push everything in this folder to your `lceuranie.github.io` repo (root, not a subfolder).
2. In repo Settings → Pages, source: Deploy from branch → `main` → `/ (root)`.
3. Site live at `https://lceuranie.github.io/` within a minute.

The `titan-mbse/` directory should sit at the same level as `index.html` so the launch button on the Titan page resolves to `https://lceuranie.github.io/titan-mbse/`. Just unzip your `titan-mbse.zip` into the website folder and the link works.

---

## Content TODO — what to fill in before sending the link to anyone

### 1. Images (highest priority)

Every project page currently has placeholder figure boxes. They are clearly marked and they look intentional, but real images will transform the site. Drop PNGs into `assets/images/` and replace the `<div class="figure-placeholder">…</div>` blocks with `<img src="assets/images/your-file.png" alt="…">`.

Suggested priority order:

- **Titan combined** — three TitanMBSE screenshots (Overview, Traceability, Power Budget mode grid). Then Nina's CAD trade study figure and Unreal Engine still (with her credit retained in the captions).
- **Deep Space Comms** — the 3-phase 91-strategy roadmap diagram (Figure 14 from the report) and the Roadmap Project Tool Kenya use-case screenshot.
- **Rwanda EO** — split-panel GEE app screenshot.
- **Terroir** — GEE app screenshot, eight-step pipeline diagram.
- **Eyesat-1** — prototype photo, block diagram, V&V matrix excerpt.
- **Space Defense** — three-pillar architecture diagram, organisational chart.
- **NGC 4852** — proper-motion diagram, CMD with isochrone, literature cross-match overlay.
- **Orbital design** — STK 3D scenario, access plot.
- **SBSP** — phylogeny tree.

### 2. Publications page metadata

`publications.html` has placeholder entries marked `[Placeholder]` for the industry papers. Copy the exact title / venue / DOI / author list from your existing publications listing into those slots.

### 3. CV download

Save your latest CV as `assets/L_Chris_Euranie_CV.pdf`. The Download CV button on the homepage already points to it.

### 4. Optional content tweaks

- Hero headline, lead paragraph, about-page text — read through and tweak to your voice. I wrote in the register of an industrial engineer's technical statement; you may want it warmer or more personal in places, particularly the about page.
- ResearchGate URL — I guessed at `/profile/Ludivine-Euranie`. Replace with the real URL.
- The "dual-use" framing is woven through the homepage (hero, contact section), about page, and the Space Defense project page. If at any point you decide to deemphasise this for a specific audience, it's three places to edit.
- Deep Space Comms page section 06 mentions your Report Head role explicitly. If there are specific anecdotes from running the editorial process across 20 authors that you'd like to add, that would strengthen this section further.

### 5. Engagements section

I included WIA Strasbourg, IPGP Alumni, and ISU Alumni. Remove, edit, or add as appropriate.

---

## Editing notes

- All pages share the same CSS file, so any visual change in `assets/css/style.css` propagates everywhere.
- The colour palette is set via CSS custom properties at the top of `style.css` (lines 7–35). Change `--rust` and `--navy` and the whole site re-skins.
- Typography is loaded from Google Fonts (Newsreader serif + IBM Plex Mono). If you want to self-host instead, drop the `.woff2` files into `assets/fonts/` and replace the Google Fonts `<link>` tags.
- The site is static and works fully offline — open `index.html` directly in a browser to preview locally. No server needed.

---

## Design intent

The aesthetic is "engineering report, refined." Warm paper background, serif body type at scientific-publication weight, mono metadata in small caps, section numbering like report chapters. The choice was deliberate: the audience for this site (ESA, CNES, EUSPA, primes, defense primes) reads portfolios looking for evidence and rigour. The visual language signals both before they read a word.

Don't add motion, gradients, or interactive flourishes. The signal is restraint.
