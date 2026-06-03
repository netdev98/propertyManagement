# HAUS — Architecture & Property Website

A premium single-page website for **HAUS Studio**, an architecture and property advisory firm operating across London, Manchester, and Edinburgh.

---

## Overview

HAUS is a high-end, fully static HTML/CSS/JS landing page designed for an architecture and property consultancy. It features a refined editorial aesthetic with smooth animations, a custom cursor, scroll-triggered reveals, and a responsive layout.

---

## Features

- **Custom Cursor** — Animated dot-and-trail cursor with hover state effects
- **Sticky Navigation** — Transparent nav that transitions to a frosted-glass style on scroll
- **Split Hero Section** — Full-viewport diagonal layout with architectural SVG line art
- **Animated Marquee** — Scrolling ticker of service offerings
- **Services Grid** — Six service cards in a two-column layout with hover transitions
- **Stats Band** — Full-width dark panel with key figures (420+ projects, €2.4B AUM, etc.)
- **About Section** — Studio story with layered image composition and team statistics
- **Process Section** — Four-step process grid with staggered reveal animations
- **Reviews Section** — Client testimonials with a 4.9★ Google rating display
- **CTA Section** — Dark call-to-action with background typographic art
- **Footer** — Four-column footer with social links, service/studio/contact columns
- **Scroll Reveal Animations** — IntersectionObserver-powered fade-in transitions

---

## Tech Stack

| Layer | Details |
|---|---|
| Markup | Semantic HTML5 |
| Styling | Vanilla CSS (custom properties, CSS Grid, Flexbox, `clip-path`, `backdrop-filter`) |
| Scripting | Vanilla JavaScript (no frameworks or libraries) |
| Fonts | Google Fonts — Syne, Instrument Serif, Plus Jakarta Sans |
| Animations | CSS keyframes + JS `requestAnimationFrame` |

---

## Project Structure

```
index.html        # All HTML, CSS, and JavaScript in a single file
README.md         # Project documentation
```

---

## Sections

| Section | ID | Description |
|---|---|---|
| Navigation | `#nav` | Fixed top nav with scroll-aware styling |
| Hero | — | Full-viewport split hero with stats footer |
| Marquee | — | Scrolling services ticker |
| Services | `#services` | Six-card service offering grid |
| Stats Band | — | Dark panel with key company metrics |
| About | `#about` | Studio story and team composition |
| Process | `#process` | Four-step engagement process |
| Reviews | `#reviews` | Client testimonials and Google rating |
| Contact / CTA | `#contact` | Call-to-action with enquiry buttons |
| Footer | — | Links, social, legal |

---

## Getting Started

No build tools or dependencies required. Simply open `index.html` in a browser:

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git

# Open in browser
open index.html
```

Or deploy directly to **GitHub Pages** — see the [GitHub Pages docs](https://docs.github.com/en/pages) for setup instructions.

---

## Deployment

This site is fully static and compatible with any static hosting platform:

- **GitHub Pages** — Push to `main` branch and enable Pages in repository settings
- **Netlify** — Drag and drop the folder or connect your GitHub repo
- **Vercel** — Import your GitHub repository and deploy instantly

Live URL format (GitHub Pages): `https://your-username.github.io/your-repo-name`

---

## Customisation

All design tokens are defined as CSS custom properties at the top of the `<style>` block:

```css
:root {
  --w: #FFFFFF;       /* White */
  --off: #F9F8F5;     /* Off-white background */
  --ink: #111010;     /* Primary dark / text */
  --red: #C8281A;     /* Brand accent */
  --red-dim: #E8B8B3; /* Muted red */
  --mid: #878480;     /* Mid-grey text */
  --rule: #E4E2DC;    /* Border / divider colour */
  --faint: #F2F1ED;   /* Faint background tint */
}
```

---

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge). Custom cursor and `clip-path` effects require a standards-compliant browser.

---

## License

© 2026 HAUS Studio Ltd. All rights reserved.
