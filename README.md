# Legal Office Services

- A professional, pixel-accurate clone
- Kuwait's premier law firm and legal consulting group.

## 🏗️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Semantic structure, ARIA accessibility |
| **CSS3** | Custom properties, Grid/Flexbox, animations |
| **Vanilla JS (ES6+)** | Intersection Observer, smooth scroll, form handling |
| **Google Fonts** | Cormorant Garamond (display), Inter (body) |

## 📁 Project Structure

```
maljasem-clone/
├── index.html                  ← Main page (single-page app)
├── assets/
│   ├── css/
│   │   ├── main.css            ← Core styles, dark luxury theme
│   │   ├── animations.css      ← Reveal, shimmer, float animations
│   │   └── responsive.css      ← Mobile-first breakpoints (480/768/1024px)
│   ├── js/
│   │   └── main.js             ← All interactivity
│   └── icons/
│       └── favicon.svg         ← SVG favicon
├── README.md
├── .gitignore
└── LICENSE
```

## ✨ Features

- **Dark luxury theme** with gold (#C9A84C) accents throughout
- **Scroll-triggered reveal animations** via Intersection Observer
- **Sticky header** with glassmorphism blur on scroll
- **Mobile hamburger menu** with slide-out panel
- **Animated counter** on hero stats
- **9 service cards** with hover micro-interactions and top-border reveal
- **4 credential cards** with staggered entrance animations
- **Contact form** with validation, success state, and auto-reset
- **Gold shimmer text** on all heading highlights
- **Floating SVG glyph** and decorative background lines
- **Back-to-top** button with scroll detection
- **Smooth scroll** navigation
- **Responsive** across all screen sizes (320px → 1440px+)
- **Bilingual toggle** (EN/عربي) placeholder in header

## 🚀 Deployment

### Local Preview
Simply open `index.html` in a browser — no build step required.

### GitHub Pages
1. Fork or clone this repository
2. Push to your GitHub account
3. Go to **Settings → Pages**
4. Set source to `main` branch, root folder
5. Your site will be live at `https://[username].github.io/[repo-name]/`

## 📱 Responsive Breakpoints

| Breakpoint | Layout |
|---|---|
| **1024px+** | Full desktop — 3-col services, 4-col team, side-by-side about |
| **768–1024px** | Tablet — stacked about/why-us, 2-col services & team |
| **480–768px** | Mobile — 2-col services, stacked everything |
| **≤480px** | Small mobile — single column everywhere, simplified hero |

## ⚡ Performance Notes

- Zero external JS dependencies (no jQuery, no frameworks)
- Fonts loaded with `font-display: swap` via Google Fonts
- All animations use `transform` and `opacity` for GPU acceleration
- Intersection Observer used instead of scroll event listeners for reveals
- CSS custom properties for easy theming

