# 🍸 Velvet Pour — GSAP Cocktail Website

<div align="center">
  <img src="showcase/Screenshot 2026-02-25 134149.png" alt="Velvet Pour Hero" width="100%" />
  <br /><br />
  <img src="https://img.shields.io/badge/-React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/-GSAP_3-88CE02?style=for-the-badge&logo=greensock&logoColor=white" />
  <img src="https://img.shields.io/badge/-Tailwind_CSS_4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/-Vite_6-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
</div>

<br />

A visually stunning, scroll-driven cocktail website built with **React**, **GSAP**, and **Tailwind CSS**. Featuring cinematic animations, parallax scrolling, scroll-triggered effects, and a fully responsive design — _Velvet Pour_ is an immersive browsing experience for a premium cocktail brand.

---

## 📸 Screenshots

<div align="center">

### Hero Section

<img src="showcase/Screenshot 2026-02-25 134149.png" alt="Hero — Mojito splash screen with large typography and cocktail glass" width="90%" />

### Cocktails Menu

<img src="showcase/Screenshot 2026-02-25 134159.png" alt="Cocktails — Most popular cocktails and mocktails list" width="90%" />

### About Section

<img src="showcase/Screenshot 2026-02-25 134209.png" alt="About — Where every detail matters, featuring image gallery" width="90%" />

### The Art

<img src="showcase/Screenshot 2026-02-25 134217.png" alt="The Art — Bartender image mask with scroll-triggered animation" width="90%" />

### Menu Carousel

<img src="showcase/Screenshot 2026-02-25 134229.png" alt="Menu — Interactive carousel with cocktail recipes" width="90%" />

</div>

---

## ✨ Features

| Feature                   | Description                                                                |
| ------------------------- | -------------------------------------------------------------------------- |
| **SplitText Animations**  | Bold, dynamic text reveals using GSAP's SplitText plugin                   |
| **ScrollTrigger Effects** | Scroll-based animations and timeline control throughout the site           |
| **Parallax Scrolling**    | Immersive depth and layered motion responding to user scroll               |
| **Pinned Sections**       | Sections lock in place while content animates for an engaging experience   |
| **Scroll-Synced Video**   | Video playback progress tied to scroll position for cinematic storytelling |
| **Image Masking**         | Scroll-triggered image masks create visually striking transitions          |
| **Custom Carousel**       | Fully custom animated carousel with multiple navigation options            |
| **Responsive Design**     | Fluid UI and adaptive GSAP animations across all screen sizes              |

---

## ⚙️ Tech Stack

- **[React 19](https://react.dev/)** — Component-based UI with modular architecture
- **[GSAP 3](https://gsap.com/)** — Animation library powering all scroll-driven visuals, SplitText, ScrollTrigger, parallax, and timeline animations
- **[Tailwind CSS 4](https://tailwindcss.com/)** — Utility-first CSS framework for rapid styling
- **[Vite 6](https://vitejs.dev/)** — Lightning-fast build tool with instant HMR

---

## 🏗️ Project Structure

```
gsap_cocktails/
├── public/              # Static assets (images, videos, fonts)
├── src/
│   ├── components/
│   │   ├── Navbar.jsx   # Navigation bar
│   │   ├── Hero.jsx     # Hero section with Mojito splash
│   │   ├── Cocktails.jsx # Cocktails & mocktails menu
│   │   ├── About.jsx    # About section with image gallery
│   │   ├── Art.jsx      # The Art section with image masking
│   │   ├── Menu.jsx     # Interactive cocktail carousel
│   │   └── Contact.jsx  # Contact / footer section
│   ├── App.jsx          # Main app component
│   ├── main.jsx         # Entry point
│   └── index.css        # Global styles & Tailwind directives
├── constants/           # Data constants
├── showcase/            # Project screenshots
├── package.json
└── vite.config.js
```

---

## 🚀 Quick Start

**Prerequisites**

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/) (v18+)
- [npm](https://www.npmjs.com/)

**Installation**

```bash
# Clone the repository
git clone https://github.com/Sagarchauhan-web/gsap_cocktails.git
cd gsap_cocktails

# Install dependencies
npm install

# Start the development server
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the project.

---

<div align="center">
  <sub>Built with React, GSAP & Tailwind CSS</sub>
</div>
