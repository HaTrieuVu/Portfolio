# Trieu Vu Ha — Portfolio

Personal portfolio site for **Trieu Vu Ha**, Frontend Developer (React · Next.js · TypeScript).

🔗 **Live:** https://hatrieuvu.github.io/

## Stack

Deliberately dependency-free — pure HTML, CSS and vanilla JavaScript. No build step,
no framework, no tracker. It deploys to GitHub Pages exactly as it sits in the repo.

## Features

- **Dark / light theme** — respects `prefers-color-scheme`, remembers your choice in `localStorage`
- **Responsive** from 320px to ultrawide, with a proper mobile menu
- **Scrollspy navigation** and a scroll-progress bar
- **Reveal-on-scroll** animations via `IntersectionObserver`
- **Accessible** — skip link, focus-visible rings, ARIA state on the menu, semantic landmarks
- **Respects `prefers-reduced-motion`** and has a dedicated print stylesheet
- **SEO / social** — description, Open Graph and Twitter card meta, inline SVG favicon
- Downloadable CV in PDF

## Structure

```
.
├── index.html
├── assets/
│   ├── css/style.css      # design tokens + all styling
│   ├── js/main.js         # theme, nav, scrollspy, reveal
│   ├── img/avatar.jpg
│   └── files/*.pdf        # downloadable CV
└── .nojekyll              # serve files verbatim on GitHub Pages
```

## Running locally

Any static server works — there is nothing to build:

```bash
python -m http.server 8000
# or
npx serve .
```

Then open http://localhost:8000

## Customising

Colours, spacing, radii and fonts are all CSS custom properties at the top of
[`assets/css/style.css`](assets/css/style.css). Change `--accent` and the whole site
re-themes.

## Contact

- ✉️ trieuvuha123@gmail.com
- 📱 0868 091 736
- 📍 Noi Bai, Ha Noi, Vietnam
