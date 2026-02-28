# Johnny Xue | Portfolio

A modern, responsive personal portfolio website built with vanilla HTML, CSS, and JavaScript.

## ✨ Features

- **Responsive Design** — Mobile-first layout that works on all screen sizes
- **Dark Mode** — Toggle between light and dark themes (respects system preference)
- **Smooth Animations** — Scroll-triggered animations powered by AOS.js
- **Animated Skill Bars** — Progress bars animate into view using Intersection Observer
- **Sticky Navigation** — Transparent navbar that becomes solid on scroll with active section highlighting
- **Timeline Layout** — Professional experience displayed in a clean vertical timeline
- **Project Cards** — Hover effects with image zoom and overlay
- **Back to Top** — Floating button appears on scroll
- **SEO Optimized** — Meta tags, Open Graph, semantic HTML
- **Accessible** — ARIA labels, keyboard navigation, proper heading hierarchy

## 🛠 Tech Stack

- HTML5 (semantic markup)
- CSS3 (custom properties, CSS Grid, Flexbox, `clamp()`, media queries)
- Vanilla JavaScript (Intersection Observer, localStorage, smooth scroll)
- [AOS.js](https://michalsnik.github.io/aos/) for scroll animations
- [Inter](https://fonts.google.com/specimen/Inter) + [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) fonts

## 📁 Project Structure

```
├── index.html              # Main HTML file
├── README.md               # This file
└── static/
    ├── css/
    │   └── resume.css      # All styles (design tokens, components, responsive)
    └── image/
        ├── Group.png       # Hero background
        ├── peason.png      # Profile photo
        ├── LOGO1-5.png     # Project logos
        ├── icon1-8.png     # Skill icons
        └── *ICON.png       # Social media icons
```

## 🚀 Getting Started

No build tools required. Simply open `index.html` in a browser:

```bash
open index.html
```

Or serve locally:

```bash
python3 -m http.server 8000
```

## 📄 License

© 2026 Johnny Xue