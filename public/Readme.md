# Vishal - Minimalist Indigo Portfolio

A premium, modern Single Page Application (SPA) portfolio engineered with raw HTML5 and Tailwind CSS, featuring high-end animations powered by GSAP and dynamic particle backgrounds. 

This repository moves away from clunky bootstrap templates, utilizing modern glassmorphism, procedural glowing gradients, and modal-based project showcases to dramatically elevate the core aesthetic. 

## Features
- **Minimalist Indigo Aesthetic:** Deep `0B0914` background with `7B3BFF` neon purple glowing accents. 
- **Physics Particle Background:** Reacts seamlessly to mouse interactions, giving the site a "living" presentation.
- **Top 4 Featured Showcase:** Innovative overlapping hero blocks to heavily highlight top tier AI and Fullstack projects.
- **GSAP Animations:** Butter-smooth ScrollTrigger entering effects map sequentially as the user scrolls.
- **Responsive Iframe Modals:** Displays live web-app demos directly from Vercel without navigating away from the portfolio.

## Tech Stack
- **Structure:** Raw HTML5
- **Styling:** Vanilla Tailwind CSS via CDN (zero-build environment)
- **Interactivity:** Vanilla JS
- **Animation Libs:** GSAP ScrollTrigger, Typed.js, particles.js 
- **Icons:** Boxicons

## Project Setup & Assets
All unused legacy Bootstrap dependencies (`assets/css`, `assets/vendor`, `assets/js`, `firebase`) have been rigorously stripped from this repository resulting in a blazing fast, zero-bloat environment. 

To update visual assets:
- **Resume:** Replace `public/assets/Vishal_Aggarwal_Resume.pdf`
- **Dashboards:** Replace screenshot assets inside `public/assets/img/projects/`

## Deployment
Because this site operates entirely dependency-free and uses CDN links directly, it can be hosted absolutely anywhere:
- Vercel (Recommended)
- GitHub Pages
- Netlify 

Just point your build engine to the `public/` directory and it acts instantly as a pre-built static site.

---
*Created by Vishal Aggarwal.*
