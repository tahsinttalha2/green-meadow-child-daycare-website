# Green Meadow Daycare — Pure HTML & CSS Website

A calm, play-led children's daycare website built **exclusively with semantic HTML5 and modern CSS3** (zero JavaScript). Designed with Swiss typography, generous whitespace, an invisible acrylic fixed navigation bar, pure CSS infographics, and built-in accessibility features.

---

## Key Features

- **Zero JavaScript**: Interactive components—including the responsive mobile navigation menu and FAQ accordion—are built using native HTML `<details>` and `<summary>` elements.
- **Swiss Design & Typography**: Clean sans-serif hierarchy, tight display tracking, fluid `clamp()` spacing, and `tabular-nums` alignment for schedules and metrics.
- **Invisible Acrylic Fixed Navbar**: Uses `position: fixed`, `backdrop-filter: blur(18px)`, and a vertical `mask-image` gradient on a `::before` pseudo-element so scrolled content blurs softly like smoke without a visible bar or border.
- **Playful 3D Overlapping Program Cards**: Age-group cards (`Nestlings`, `Sprouts`, `Explorers`) feature overlapping 3D clay-style illustrations positioned with CSS.
- **Pure CSS Infographics**:
  - **Daily Time Allocation**: Flexbox stacked proportion bar driven by CSS custom properties (`--pct`).
  - **Developmental Focus Pillars**: CSS Grid vertical meter chart driven by CSS custom properties (`--val`) with bottom-aligned tracks.
- **Accessibility-First (HTML & CSS)**:
  - Skip-to-main-content link (`.skip-link`) for keyboard navigation
  - Semantic landmarks (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<footer>`)
  - High-contrast dark ink (`#181b1a`) on pastel and parrot-green surfaces
  - Clear `:focus-visible` outlines and `44px+` touch targets
  - Screen-reader-only (`.sr-only`) chart summaries and form `<legend>`
  - `@media (prefers-reduced-motion: reduce)` and `@media (prefers-contrast: more)` support

---

## Color Palette

| Role | Hex | Preview |
| :--- | :--- | :--- |
| White | `#FFFFFF` | Primary background |
| Beige | `#F7F3EC` | Alternating section surface |
| Pastel Blue | `#CBE4F9` | Nestlings card & chart accent |
| Parrot Green | `#62D84E` | Primary CTA, Sprouts card & brand accent |
| Pastel Orange | `#FFCBA4` | Explorers card & chart accent |
| Charcoal Ink | `#181B1A` | High-contrast text & borders |

---

## Project Structure

```text
daycare-website/
├── index.html                    # Semantic HTML5 structure & content
├── styles.css                    # Swiss layout, acrylic nav, infographics & accessibility
├── README.md                     # Project documentation
└── assets/
    ├── green-meadow-logo-01.svg  # Brand logo
    ├── nestlings-3d.jpg          # 3D clay-style icon (12–24 months)
    ├── sprouts-3d.jpg            # 3D clay-style icon (2–3 years)
    └── explorers-3d.jpg          # 3D clay-style icon (3–5 years)
```

---

## Getting Started

1. Clone or download the repository.
2. Open `index.html` directly in any modern web browser—no build step, package manager, or server required.

---

## What I Practiced

- Structuring accessible, semantic HTML without relying on JavaScript frameworks
- Building responsive layouts with CSS Grid, Flexbox, and `clamp()`
- Creating glassmorphism/acrylic blur effects with `backdrop-filter` and `mask-image`
- Designing data visualizations and interactive UI patterns purely in CSS
