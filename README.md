# Michael Wuergler — Design Timeline

A single-page portfolio of selected past and present design work: product design, design systems, games, websites and branding.

**Live site:** `https://radiovisual.github.io/design-temeline/`

---

## Projects

| # | Project | Type |
| --- | --- | --- |
| 01 | **redSight** | Personal project · Design system, product |
| 02 | **AppGate & Mastercard Mini Games + Portal** | Client work · Games, portal |
| 03 | **Stickr Store** | Ongoing personal project · Editor, e-commerce |
| 04 | **Immunity Inc.** | Client work · Web, brand |
| 05 | **Infiltrate Security Conference** | Client work · Web, print, swag |

## Features

- **No build step.** One `index.html` file with the CSS and JavaScript inside, plus an `images/` folder.
- **Responsive.** Galleries go from 3 columns to 2 to 1. The nav becomes a menu button on mobile.
- **Smooth-scroll navigation** with active-section highlighting.
- **Lightbox.** Click any image or video to view it full size. Use the ← → keys to browse and Esc to close. Tall full-page screenshots scroll.
- **Fade-in on scroll.** This respects `prefers-reduced-motion`.
- **Autoplaying videos.** Muted, looping, and only playing while on screen.
- **Missing-file placeholders.** A broken image or video path shows a striped tile with the file name, so it's easy to spot.

## Project structure

```
.
├── index.html            # The entire site (HTML + CSS + JS)
├── .nojekyll             # Tells GitHub Pages to serve files as-is
├── README.md
└── images/
    └── web-portfolio/
        ├── redsight/
        ├── appgate/
        ├── stickr-store/
        └── immunity/
```

## Run locally

Use a local server rather than double-clicking `index.html`. That's the closest match to how GitHub Pages serves the site.

```bash
# from the repo folder
python3 -m http.server 8000
```

Then open **http://localhost:8000**.

<details>
<summary>No Python? Other options</summary>

```bash
npx serve .            # Node.js
php -S localhost:8000  # PHP
```

Or use the **Live Server** extension in VS Code.
</details>

---

© Michael Wuergler. All rights reserved.
