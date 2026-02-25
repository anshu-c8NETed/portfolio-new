<div align="center">

# Anshu Raj — Portfolio

**Full-Stack Developer · 3D & Animation Specialist**

![Built with Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![WebGL](https://img.shields.io/badge/WebGL-990000?style=for-the-badge&logo=webgl&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

[Live Site](https:portfolio-by-ar.vercel.app) · [LinkedIn](https://www.linkedin.com/in/anshu-raj-tech) · [GitHub](https://github.com/anshu-c8NETed)

</div>

---

## Overview

A production-grade personal portfolio engineered to the same standard as a commercial product. Every interaction is deliberate — from the terminal boot sequence on load to the 3D book that turns pages with bone-deformed mesh physics. Built entirely from scratch with no templates, UI kits, or third-party component libraries.

The goal was simple: build something that other developers stop and study.

---

## Technical Highlights

### 🔖 Interactive 3D Portfolio Book
The centrepiece of the works section. A fully custom React Three Fiber implementation featuring a **31-bone skinned mesh rig** that physically simulates page turning. Each page face is a **canvas-rendered WebGL texture** generated at runtime — complete with project metadata, metric bars, tech stack pills, and a full editorial layout. Page transitions trigger real audio feedback.

### ⚡ GSAP ScrollTrigger Architecture
Ten-plus ScrollTrigger instances orchestrate the entire scroll experience — pinned horizontal service panels, 3D perspective fold on the contact hero, clip-path video reveals, scroll-linked image pills embedded inside editorial display text, and scrub-driven parallax throughout. Zero jank, frame-perfect.

### 🌊 WebGL Shader Backgrounds
UnicornStudio shader compositions run as live WebGL canvases behind the hero and contact sections, composited with `mix-blend-mode: screen` so they integrate seamlessly with the page content rather than sitting behind it.

### 🖱️ Section-Aware Custom Cursor
A fully custom arrow cursor that reads the active section via ScrollTrigger and transitions its color through the design system palette (`#00ff88` → `#00d4ff` → `#b77bff`). Magnetic scaling on all interactive elements. Hidden on touch devices.

### 🎬 Cinematic Section Transitions
- **Services Intro** — Text spreads apart as a small rotated video card expands to fill the viewport, then exits via an animated `circle()` clip-path on scroll
- **Works Intro** — Full-viewport pinned video section with scroll-scrubbed content reveal
- **Contact Hero** — Panel performs a `rotationX` perspective fold-back as the form section slides beneath it

### 🖼️ Radial Mask Profile Reveal
The about section profile image uses a CSS `mask-image` with a GSAP-animated `--ms` CSS variable to create a cursor-following circular reveal of a second image layer underneath — no canvas, no JavaScript pixel manipulation.

---

## Stack

| Layer | Technology |
|---|---|
| UI Framework | React 18 + Vite |
| 3D Rendering | Three.js, React Three Fiber, `@react-three/drei` |
| Animation | GSAP, ScrollTrigger, Observer |
| Smooth Scroll | Lenis |
| Styling | Tailwind CSS v4 (custom design tokens) |
| WebGL FX | UnicornStudio |
| Forms | Web3Forms |
| Icons | Iconify |
| Typography | Syne · Space Grotesk · JetBrains Mono |

---

## Performance

- 60fps on mobile devices
- Adaptive quality — reduced particle counts, shadow maps, and antialiasing on low-power devices
- Intersection Observer–gated 3D scene: the book canvas does not initialise until it enters the viewport
- Mobile boot loader uses a simulated timer instead of blocking on `useProgress` to prevent perceived lag

---

## Author

**Anshu Raj** — Full-Stack Developer 
Open to freelance projects and full-time opportunities.

📧 rajanshu2123@gmail.com
