# Insect — Practice Project

This is a practice file built to explore and apply the following front-end topics:

---

## Topics Covered

- **HTML Structure** — Semantic layout using `<main>`, `<nav>`, `<div>`, and `<ul>` elements
- **CSS Flexbox** — Split-screen two-column layout with `display: flex`
- **Positioning** — Centering the dome image across both panels using `position: absolute` and `transform: translate()`
- **Typography** — Pairing Google Fonts (Playfair Display + Inter), font weights, letter spacing, and italic styles
- **CSS Variables** — Reusable color tokens defined in `:root`
- **Forms & Inputs** — Styled search bar and custom toggle switches built with CSS
- **Hover & Transitions** — Smooth color, transform, and opacity transitions on interactive elements
- **Inline SVG Icons** — Hand-coded SVG paths for the beetle silhouette, search icon, location pin, gender symbol, and ruler
- **Responsive Units** — `clamp()` for fluid font sizing, `vh`/`vw` for full-viewport layout

---

## File Structure

```
project/
├── index.html       # Main page (HTML + embedded CSS)
├── style.css        # External stylesheet (starter/reference)
├── README.md
└── Assets/
    └── img.png      # Beetle in glass dome image
```

---

## Design Reference

The layout is a split-screen product page for an insect collection store, featuring **Pachyteria equestris** — a longhorn beetle from Malaysia.

| Panel                 | Content                                       |
| --------------------- | --------------------------------------------- |
| Left (white)          | Logo, search bar, classification list         |
| Centre                | Glass dome specimen image                     |
| Right (red `#bd3d31`) | Nav, species name, specs, price, toggles, CTA |

---

_This project is for learning purposes only._
