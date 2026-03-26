<div align="center">

<img src="https://img.shields.io/badge/NexaCore-Company%20Landing%20Page-00d4ff?style=for-the-badge&logo=javascript&logoColor=black" alt="NexaCore Banner"/>

# 🌐 NexaCore — Company Landing Page

### *Professional 3D Landing Page with Particle FX, Custom Cursor & Scroll Animations*

<br/>

[![Live Demo](https://img.shields.io/badge/🌐%20Live%20Demo-GitHub%20Pages-00d4ff?style=for-the-badge)](https://manikanta-04.github.io/Company-_Landing_Page_website/)

<br/>

[![HTML5](https://img.shields.io/badge/HTML5-Structure-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-3D%20Animations-1572B6?style=flat-square&logo=css3)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/Vanilla%20JS-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-brightgreen?style=flat-square)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=flat-square)](CONTRIBUTING.md)

</div>

---

## 🚀 Live Demo

| Service | URL |
|---|---|
| 🌐 **NexaCore Landing Page** | [manikanta-04.github.io/Company-_Landing_Page_website](https://manikanta-04.github.io/Company-_Landing_Page_website/) |

> ⚡ No login. No install. Just open and experience.
> *(Update with your actual deployed URL)*

---

## 🎥 Demo Video

> 📽️ *(Add a Loom / YouTube demo walkthrough here)*
>
> [![Watch Demo](https://img.shields.io/badge/▶%20Watch%20Demo-YouTube-red?style=for-the-badge&logo=youtube)](https://youtube.com)

---

## 🧠 Problem Statement

Most company landing pages are template-heavy, visually flat, and fail to create a lasting impression. Current problems:

- 😐 Generic layouts with stock photos and boring grids
- 🐌 Heavy React/Next.js setups just to render a marketing page
- 🎨 No visual personality — every SaaS landing page looks the same
- 📵 Framework-dependent builds that are complex to deploy and maintain

**A company's landing page is its digital storefront — it should stop visitors in their tracks.**

---

## 💡 Solution

**NexaCore** is a visually stunning, framework-free company landing page built entirely with HTML, CSS & JavaScript. Features a 3D rotating cube hero, custom animated cursor, particle system, scroll-triggered counters, mouse-reactive card tilt, and infinite testimonial ticker — zero dependencies, instant load.

> *"Where innovation meets performance."*

---

## 🖼️ Screenshots

| Hero — 3D Cube & Particles | Services Grid |
|---|---|
| ![Hero](screenshots/hero.png) | ![Services](screenshots/services.png) |

| 3D Tilt Cards | Process Timeline |
|---|---|
| ![Tilt](screenshots/tilt.png) | ![Process](screenshots/process.png) |

| Auto-Scroll Testimonials | CTA Section |
|---|---|
| ![Testimonials](screenshots/testimonials.png) | ![CTA](screenshots/cta.png) |

> 📌 *(Replace with actual screenshots from your deployed page)*

---

## 🏗️ Architecture

```
┌──────────────────────────────────────────────────────────┐
│              3-FILE STATIC APP                            │
│                                                           │
│  index.html   →  Page structure + semantic markup         │
│  style.css    →  All animations, 3D transforms, layouts   │
│  script.js    →  Cursor, tilt, particles, counters        │
│                                                           │
│  ┌──────────────────────────────────────────────────┐     │
│  │              CSS ANIMATION ENGINE                 │     │
│  │  3D cube (preserve-3d) | Perspective grid floor   │     │
│  │  Gradient glow system | Scroll reveal fades       │     │
│  │  Navbar blur + shrink | Infinite ticker           │     │
│  └──────────────────────────────────────────────────┘     │
│                                                           │
│  ┌──────────────────────────────────────────────────┐     │
│  │              JAVASCRIPT MODULES                   │     │
│  │  customCursor()      → dot + ring + blend mode    │     │
│  │  particleSystem()    → 40 dynamic floating DOM    │     │
│  │  cardTilt()          → mousemove 3D perspective   │     │
│  │  countUpStats()      → IntersectionObserver       │     │
│  │  scrollReveal()      → fade-slide on viewport     │     │
│  │  testimonialsLoop()  → infinite horizontal scroll │     │
│  └──────────────────────────────────────────────────┘     │
│                                                           │
│  Zero CDN. Zero external libraries.                       │
└──────────────────────────────────────────────────────────┘
```

---

## ⚙️ Tech Stack

| Layer | Technology | Purpose |
|---|---|---|
| **Structure** | HTML5 | Semantic page markup |
| **Styling** | CSS3 | 3D transforms, keyframe animations, grid/flex |
| **Effects** | CSS `preserve-3d`, `clip-path`, `conic-gradient` | Visual design system |
| **Logic** | Vanilla JavaScript ES6+ | Cursor, particles, tilt, counters, reveal |
| **Observer** | IntersectionObserver API | Scroll-triggered animations |

> ⚡ **Zero dependencies** — no frameworks, no libraries, no build tools required.

---

## ✨ Features

### 🎲 3D Rotating Cube (Hero)
- CSS `preserve-3d` cube animation in the hero section
- Continuous auto-rotation on all axes
- Teal/violet gradient faces with glow borders

### 🖱️ Custom Animated Cursor
- Animated dot + trailing ring cursor
- `mix-blend-mode` inversion effect
- Smooth lerp follow on mouse movement

### 🌌 Particle System
- **40 floating particles** dynamically generated via JS
- Random size, speed, opacity, and drift direction
- Continuously looping — no gaps

### 📊 Scroll-Triggered Count-Up Stats
- Numbers animate from 0 to target when scrolled into view
- `IntersectionObserver` API — fires only once per visit
- Smooth easing via `requestAnimationFrame`

### 🃏 3D Card Tilt (Mouse-Tracked)
- Feature cards tilt in 3D space following the mouse
- CSS perspective + `rotateX` / `rotateY` applied live
- Resets smoothly on `mouseleave`

### 🔁 Auto-Scrolling Testimonials Ticker
- Infinite horizontal scroll — seamlessly loops
- Pauses on hover for readability
- CSS animation with JS clone-and-append loop

### 👁️ Scroll Reveal Animations
- Sections fade and slide in as user scrolls
- Staggered delays per card/element
- `IntersectionObserver` — performant, no layout thrash

### 📐 Animated 3D Grid Floor
- Perspective grid background in hero section
- Subtle forward-motion animation
- Creates depth and sci-fi atmosphere

### 🌈 Gradient & Glow Design System
- Teal (`#00d4ff`) + Violet (`#7b2ff7`) accent pair
- CSS glow via `box-shadow` + `text-shadow`
- Consistent across all interactive elements

### 📱 Fully Responsive
- Mobile, tablet, and desktop ready
- CSS Grid + Flexbox layout
- Navbar collapses cleanly on mobile

---

## 📄 Page Sections

| # | Section | Description |
|---|---|---|
| 1 | **Navbar** | Fixed, backdrop-blur, shrinks on scroll |
| 2 | **Hero** | 3D cube + animated grid + particle system + CTA buttons |
| 3 | **Services** | 6-card grid with hover glow animations |
| 4 | **Performance** | 3D interactive cards with mouse tilt effect |
| 5 | **Process** | 4-step workflow with gradient connector line |
| 6 | **Testimonials** | Auto-scrolling client review ticker (infinite loop) |
| 7 | **CTA** | Email signup with glowing submit button |
| 8 | **Footer** | Links and copyright |

---

## 📊 System Design

```
Page Load Flow:

[Browser opens index.html]
         │
         ├── style.css loaded → base layout + animations applied
         ├── script.js loaded → JS modules initialize
         │
         ▼
[customCursor()]         → replaces default cursor with dot + ring
[particleSystem()]       → 40 particles injected into hero DOM
[scrollReveal()]         → IntersectionObserver watches all sections
         │
         ▼
[User scrolls]
         │
         ├── Navbar shrinks (scroll event)
         ├── Sections fade-slide in (IntersectionObserver fires)
         └── countUpStats() triggers when stats section enters viewport
                  │
                  ▼
             requestAnimationFrame loop → 0 → target number

[User hovers cards]
         │
         └── mousemove → rotateX/Y calculated → CSS transform applied
             mouseleave → transform reset with CSS transition
```

```
JavaScript Module Map:

script.js
  ├── customCursor()        → tracks mousemove, updates dot + ring positions
  ├── particleSystem()      → creates 40 divs, CSS animation handles movement
  ├── cardTilt()            → mousemove on .card → perspective 3D rotation
  ├── countUpStats()        → IntersectionObserver → rAF count-up animation
  ├── scrollReveal()        → IntersectionObserver → adds .visible class
  └── testimonialsLoop()    → clones testimonial items → CSS infinite scroll
```

---

## 🔄 Workflow

```
1. User opens page          →  CSS cube + grid animation begins immediately
2. Custom cursor activates  →  Dot + ring follow mouse with blend mode
3. Particles spawn          →  40 floating particles fill the hero
4. User scrolls down        →  Navbar shrinks, sections fade-slide in
5. Stats section visible    →  Count-up animation triggers (fires once)
6. User hovers service card →  3D tilt perspective activates
7. Testimonials section     →  Infinite auto-scroll ticker runs
8. User reaches CTA         →  Glowing email input + submit button
```

---

## 📈 Performance & Metrics

| Metric | Value |
|---|---|
| Total files | 3 (HTML + CSS + JS) |
| External dependencies | 0 |
| Particle count | 40 dynamic DOM particles |
| Page sections | 8 |
| Service cards | 6 |
| Process steps | 4 |
| Build step required | None |
| Framework required | None |
| Time to load | < 1s (pure static) |
| CSS animations | GPU-accelerated (`transform`, `opacity`) |

---

## 🧪 Testing

```bash
# Open directly in browser
open index.html

# Or serve locally (recommended)
npx serve .
# Visit: http://localhost:3000

# Manual test checklist:
# ✅ 3D cube rotates continuously in hero
# ✅ Custom cursor (dot + ring) follows mouse
# ✅ 40 particles float across hero section
# ✅ Navbar shrinks on scroll past hero
# ✅ Sections fade-slide in on scroll
# ✅ Stats count from 0 to target when visible
# ✅ Performance cards tilt on mousemove
# ✅ Testimonials auto-scroll + pause on hover
# ✅ CTA email input + glow button works
# ✅ Fully responsive at 375px (mobile)
# ✅ Works on Chrome, Firefox, Safari, Edge
```

### Browser Compatibility

| Browser | Support |
|---|---|
| Chrome 90+ | ✅ Full |
| Firefox 88+ | ✅ Full |
| Safari 14+ | ✅ Full |
| Edge 90+ | ✅ Full |
| Mobile Chrome | ✅ Full |

---

## 📁 Project Structure

```
Company-_Landing_Page_website/
│
├── index.html      # Page structure + semantic markup
├── style.css       # All styles, 3D transforms, animations, responsive design
├── script.js       # Cursor, particles, tilt, counters, scroll reveal, ticker
└── README.md       # Project documentation
```

---

## 🎨 Design System

| Token | Value |
|---|---|
| Primary (Teal) | `#00d4ff` |
| Accent (Violet) | `#7b2ff7` |
| Background | `#050510` (Deep Space) |
| Surface | `rgba(255,255,255,0.05)` (Glassmorphism) |
| Glow Effect | `box-shadow: 0 0 20px #00d4ff` |
| Layout | CSS Grid + Flexbox |
| Effects | `preserve-3d`, `clip-path`, `conic-gradient`, `backdrop-filter` |

---

## 🔐 Security

- **No user data stored** — email CTA is client-side UI only (no backend)
- **No backend** — zero server-side attack surface
- **No eval()** — all JavaScript is safe DOM manipulation
- **No external scripts** — zero CDN attack surface
- **GitHub Pages HTTPS** — all traffic served over SSL

---

## ⚙️ Local Development Setup

### Prerequisites

- Any modern browser
- No Node.js, Python, or runtime required

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Manikanta-04/Company-_Landing_Page_website.git
cd Company-_Landing_Page_website
```

### 2️⃣ Open in Browser

```bash
# Direct open
open index.html

# Or serve locally
npx serve .
# Visit: http://localhost:3000
```

---

## 🔑 Environment Variables

No environment variables required — fully static app.

---

## 🚀 Deployment

### GitHub Pages *(Recommended)*

1. Push all files to `main` branch
2. Go to **Settings → Pages**
3. Source: `main` branch → `/ (root)`
4. Live at: `https://manikanta-04.github.io/Company-_Landing_Page_website/`

### Vercel / Netlify

```bash
# Drag & drop the project folder OR connect GitHub repo
# No build command needed
```

| Setting | Value |
|---|---|
| Framework | Other / Static |
| Build Command | *(leave empty)* |
| Output Directory | `./` |

---

## 🔮 Future Improvements

- [ ] 🔗 Backend contact form with EmailJS or Formspree
- [ ] 🌙 Light / dark mode toggle
- [ ] 🎵 Subtle ambient background audio (muted by default)
- [ ] 🎬 Page transition animations between sections
- [ ] 📊 Real-time stats via API (GitHub stars, users, etc.)
- [ ] 🌐 Multi-language support (i18n)
- [ ] 📱 PWA support — installable as mobile app
- [ ] ♿ Accessibility audit — ARIA labels, keyboard navigation

---

## 🤝 Contributing

Contributions are welcome!

```bash
# 1. Fork this repository
# 2. Create your feature branch
git checkout -b feature/your-feature-name

# 3. Commit with conventional commits
git commit -m "feat: describe your change"

# 4. Push and open a Pull Request
git push origin feature/your-feature-name
```

---

## 👨‍💻 Author

**Manikanta Naripeddi** — Full Stack & Creative Developer

[![GitHub](https://img.shields.io/badge/GitHub-Manikanta--04-181717?style=flat-square&logo=github)](https://github.com/Manikanta-04)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Manikanta%20Naripeddi-0077b5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/manikanta-naripeddi-4326232a5/)
[![Email](https://img.shields.io/badge/Email-manikantachowdary296@gmail.com-D14836?style=flat-square&logo=gmail)](mailto:manikantachowdary296@gmail.com)

---

## 📜 License

This project is open source and available under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgements

- [MDN Web Docs](https://developer.mozilla.org/) — CSS 3D transforms & IntersectionObserver reference
- [GitHub Pages](https://pages.github.com/) — Free static hosting
- Inspired by modern SaaS design systems

---

<div align="center">

**Built with ❤️ for immersive, zero-dependency web experiences**

⭐ **Star this repo** if NexaCore impressed you!

[![GitHub Stars](https://img.shields.io/github/stars/Manikanta-04/Company-_Landing_Page_website?style=social)](https://github.com/Manikanta-04/Company-_Landing_Page_website)

---

*🌐 Where innovation meets performance.*

</div>
