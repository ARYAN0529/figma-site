# Area — Landing Page

A responsive landing page for **Area**, a fictional data-analytics/insights product. Built while learning front-end development, focused on practicing responsive layouts, Tailwind CSS, and clean section-based page structure.

🔗 Live Demo: *(add your GitHub Pages / Netlify / Vercel link here)*

## Preview

*(Add a screenshot here — drag an image into this file on GitHub, or add `![Preview](./pics/preview.png)` once you have one saved in the repo)*

## Features

- **Fully responsive** — custom layouts for mobile, tablet, and desktop breakpoints (not just simple stacking, but separate hero mockups for each screen size)
- **Hero section** with device mockups (phone / tablet / laptop) inside a styled card
- **Trusted-by logo strip**
- **Benefits grid** using Material Symbols icons
- **Comparison table** (Area vs. competitors) with a highlighted column
- **Testimonials section** with adaptive layout per screen size
- **Call-to-action sections** and a responsive footer
- Styled with **Tailwind CSS** and **Google Fonts** (Crimson Text for headings)

## Tech Stack

- HTML5
- [Tailwind CSS](https://tailwindcss.com/) (compiled to `src/output.css`)
- [Material Symbols](https://fonts.google.com/icons) for icons
- Google Fonts (Crimson Text)

## Project Structure

```
├── index.html          # Main page
├── src/
│   └── output.css      # Compiled Tailwind CSS
└── pics/                # Images used across sections
```

## Getting Started

Since this is a static site with a pre-built Tailwind CSS file, you don't need a build step to view it:

1. Clone the repo:
   ```bash
   git clone https://github.com/ARYAN0529/your-repo-name.git
   ```
2. Open `index.html` directly in your browser, or serve it locally (e.g. with the VS Code Live Server extension).

### If you want to edit styles with Tailwind

If you make changes and need to rebuild `src/output.css`, install Tailwind and run the build:

```bash
npm install -D tailwindcss
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```

## What I Practiced

This project was built early in my coding journey to practice:
- Responsive design using breakpoint-specific markup (`md:`, `lg:` variants)
- Structuring a multi-section marketing/landing page
- Working with utility-first CSS (Tailwind)
- Basic layout composition — grids, flexbox, cards, and typography hierarchy

## Notes

This was one of my earlier projects, so some sections (like the responsive image/testimonial blocks) are handled with separate markup per breakpoint rather than fully fluid layouts. A good next step would be refactoring these into a single fluid layout using Tailwind's responsive utilities more efficiently.

## Author

**Aryan** — [GitHub](https://github.com/ARYAN0529)
