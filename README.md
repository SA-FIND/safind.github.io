# Solomon Ahedor — Portfolio

Personal portfolio website for **Solomon Ahedor**, a final-year Metallurgical Engineering student at KNUST, Ghana.

🌐 **Live at:** [safind.github.io](https://safind.github.io)

---

## About

This portfolio showcases my work at the intersection of materials science, AI, and sustainable engineering — from froth flotation optimisation with machine learning to biomass-derived water filtration systems.

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | Semantic HTML5 |
| Styling | Vanilla CSS with M3 Material Design 3 tokens |
| Typography | [Manrope](https://fonts.google.com/specimen/Manrope) via Google Fonts |
| Hosting | GitHub Pages |

## Design System

The site follows a **Material Design 3** inspired design system documented in [`DESIGN.md`](DESIGN.md). Key design decisions:

- **Color:** M3 tonal surface system seeded with Deep Indigo Primary (`#1B6B52`)
- **Shape:** Pill-shaped buttons (`100px` radius), medium-rounded cards (`16px`)
- **Motion:** M3 emphasized easing (`cubic-bezier(0.2, 0, 0, 1)`) on all transitions
- **Layout:** 1200px max-width, 8px base grid, generous whitespace

## Project Structure

```
Portfolio/
├── index.html                    # Main portfolio page
├── style.css                     # M3 design system + all styles
├── DESIGN.md                     # Semantic design system documentation
├── Prophoto.png                  # Professional headshot
├── SOLOMON_AHEDOR_RESUME.pdf     # Downloadable CV
├── .gitignore
└── README.md
```

## Sections

- **Hero** — Name, title, and call-to-action
- **About** — Bio, photo, academic metadata
- **Projects** — Research and engineering work (FYP, ML flotation, MetaForge, silica extraction)
- **Experience** — Timeline of industry internships and leadership roles
- **Skills** — Technical toolkit sourced from CV (metallurgy, computation, lab instrumentation)
- **Contact** — Email, X (Twitter), GitHub, CV download

## Local Development

Open `index.html` directly in a browser, or serve locally:

```bash
npx serve . -l 3000
```

## Deployment

The site is hosted on **GitHub Pages** at [safind.github.io](https://safind.github.io). Any push to the `main` branch triggers automatic deployment.

```bash
git add .
git commit -m "your message"
git push origin main
```

## Contact

- **Email:** [ahedorsolomon@gmail.com](mailto:ahedorsolomon@gmail.com)
- **X:** [@safinderr](https://x.com/safinderr)
- **GitHub:** [SA-FIND](https://github.com/SA-FIND/safind.github.io)

---

© 2026 Solomon Ahedor · Metallurgical Engineer · KNUST, Ghana
