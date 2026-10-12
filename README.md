# 🎨 Personal Portfolio Website 

A responsive personal portfolio website built with **pure HTML5 and CSS3**.

---

## 📑 Table of Contents

- [Live Demo](#-live-demo)
- [Author](#-author)
- [Project Overview](#-project-overview)
- [Design Direction](#-design-direction)
- [Folder Structure](#-folder-structure)
- [Technologies Used](#️-technologies-used)
- [Features](#-features)
- [Mobile Optimizations](#-mobile-optimizations)
- [How to Run Locally](#-how-to-run-locally)
- [Internship Requirements Compliance](#-internship-requirements--compliance)
- [Learning Outcomes](#-learning-outcomes)
- [License](#-license)
- [Acknowledgements](#-acknowledgements)

---

## 🔗 Live Demo

**[→ View Live Site](https://mhr-portfolio-1.netlify.app/)**

Hosted on **Netlify** (free tier, permanent).

---

## 👤 Author

**Marri Harshavardhan Reddy**

- 📧 Email: [marriharshavardhanreddy5@gmail.com](mailto:marriharshavardhanreddy5@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/harshavardhan-reddy-marri-1b137b28b](https://linkedin.com/in/harshavardhan-reddy-marri-1b137b28b)
- 🐙 GitHub: [github.com/harshavardhanreddy020304](https://github.com/harshavardhanreddy020304)
- 🎓 B.Tech · Data Science · AVN Institute of Engineering & Technology (2023–2027)
- 📍 Based in Hyderabad, India

---

## 🎯 Project Overview

A single-page scrolling portfolio that introduces me as an aspiring Full Stack Developer and presents:

- **Hero / Home** — name, role, bio, profile image, quick stats
- **About** — bio, education timeline, career interests
- **Skills** — 10 technology domains displayed as numbered cards
- **Projects** — 4 real-world projects with screenshots, descriptions, and tech stacks
- **Contact** — email, GitHub, LinkedIn
- **Footer** — copyright and social links

---

## 🎨 Design Direction

The visual identity is **Y2K Vaporwave / Retro-Futuristic Neon** — inspired by 90s operating systems, CRT monitors, and synthwave aesthetics.

| Element | Choice |
|---------|--------|
| **Background** | Deep purple `#0A0416` with radial neon glows |
| **Primary colour** | Neon pink `#FF2D95` |
| **Accents** | Cyan `#00F0FF`, Lime `#B4FF3D`, Violet `#9D4EDD` |
| **Headings** | Outfit (bold, gradient chrome text) |
| **Body** | Outfit + VT323 (retro terminal font) |
| **Special effects** | CRT scanline overlay, perspective grid floor, glowing borders, blink cursor |

All UI panels (profile, about, project cards) are styled as **classic OS windows** with traffic-light dots and title bars.

---

## 📁 Folder Structure

```
Marri_Harshavardhan_Reddy_HTML_CSS_Portfolio/
│
├── index.html               # Main HTML file
├── style.css                # All styling
├── README.md                # This file
│
├── images/
│   ├── profile.png
│   ├── portfolio-project.png
│   ├── nxt-trendz-product-output.png
│   ├── jobby-app-output.png
│   └── speed-typing-test.png
│
└── screenshots/
    ├── desktop View/        # 6 desktop screenshots (one per section)
    │   ├── Home.png
    │   ├── about.png
    │   ├── skills.png
    │   ├── projects.png
    │   ├── education.png
    │   └── contact.png
    │
    └── mobile View/         # 5 mobile screenshots
        ├── home.png
        ├── about.png
        ├── skills.png
        ├── projects.png
        └── contact.png
```

---

## 🛠️ Technologies Used

- **HTML5** — semantic markup (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`)
- **CSS3** — CSS Grid, Flexbox, custom properties (variables), gradients, animations, transitions
- **Google Fonts** — VT323, Outfit
- **Netlify** — free static hosting

**No JavaScript. No Bootstrap. No Tailwind. No jQuery. No frameworks of any kind.**

---

## ✨ Features

### HTML5
- ✅ Valid HTML5 document structure
- ✅ Semantic tags throughout (`header`, `nav`, `main`, `section`, `article`, `footer`)
- ✅ Proper heading hierarchy (`h1` → `h2` → `h3` → `h4`)
- ✅ Meaningful `alt` text on all images
- ✅ Section `id` attributes for navigation anchors
- ✅ Viewport meta tag for responsive rendering
- ✅ Character encoding set to UTF-8

### CSS3
- ✅ Separate `style.css` file linked from HTML
- ✅ CSS custom properties for colour palette and spacing
- ✅ **CSS Grid** — hero, about, skills, projects, contact sections
- ✅ **Flexbox** — navbar, buttons, tags, footer
- ✅ Responsive media queries at **1024px**, **720px**, and **400px**
- ✅ Hover and focus states on all interactive elements
- ✅ Smooth transitions on hover (glow, translate, shadow)
- ✅ `prefers-reduced-motion` support for accessibility
- ✅ No horizontal overflow at any screen size
- ✅ `display: contents` trick to reorder hero content on mobile (bio → image → buttons)

### Responsive Behaviour

| Breakpoint | Layout |
|------------|--------|
| **> 1024px** (desktop) | Two-column hero, wide grids |
| **≤ 1024px** (tablet) | Single-column stacked layout, image after bio |
| **≤ 720px** (mobile) | Fully stacked, stacked navbar with pill links, larger hero padding |
| **≤ 400px** (small phone) | Reduced font sizes, tighter spacing |

---

## 📱 Mobile Optimizations

Special attention was paid to the mobile experience:

- **Navbar** stays visible as sticky pills that wrap onto multiple lines
- **Hero section reorders** so the bio paragraph appears **before** the profile image
- **Buttons** become full-width for easier tapping
- **Stats** wrap gracefully
- **Text** remains readable at 375px width with no sideways scroll

---

## 🚀 How to Run Locally

1. Clone or download this repository
2. Open `index.html` in any modern browser (Chrome, Edge, Firefox, Safari)
3. That's it — no build step, no dependencies, no setup

```bash
# Clone the repo
git clone https://github.com/harshavardhanreddy020304/portfolio-project.git

# Open in your default browser (macOS)
open index.html

# Open in your default browser (Windows)
start index.html

# Open in your default browser (Linux)
xdg-open index.html
```

---

## 🎓 Learning Outcomes

Through this project I practised and strengthened:

- Semantic HTML5 document structure
- CSS custom properties (variables) for maintainable theming
- CSS Grid for complex 2D layouts
- Flexbox for 1D alignment and wrapping
- Responsive design with mobile-first thinking
- CSS animations (`@keyframes`) and transitions
- Advanced visual effects — gradients, glows, text-stroke, backdrop-filter
- Accessibility — focus-visible, reduced-motion, colour contrast
- Layout reordering with CSS `order` and `display: contents`
- Organizing project files for clean, professional submission

---

## 📜 License

This project is my own original work, created for the **EWB Courses HTML & CSS Internship**.

Content, code, and design are free to reference for learning purposes, but please do not submit it as your own internship project.

---

## 🙏 Acknowledgements

- **EWB Courses** — for the project brief and clear learning objectives
- **Google Fonts** — for VT323 and Outfit typefaces
- **Netlify** — for free, reliable static hosting
- **MDN Web Docs** — for CSS Grid and Flexbox documentation

---

⭐ **If you found this project helpful or interesting, consider giving the repo a star!**
