# Nova — SaaS Landing Page

A fast, responsive, one-page landing page for **Nova**, a fictional project-management platform. Built as a freelance portfolio sample with plain HTML, CSS and JavaScript — no frameworks or build step.

## Technologies
HTML5 · CSS3 (custom properties, grid, flexbox) · Vanilla JavaScript · DM Sans (Google Fonts)

## Features
- Sticky blurred navigation with accessible hamburger menu (`aria-expanded`, `aria-label`, Esc to close)
- Hero with a dashboard mockup built entirely in HTML/CSS (3D tilt on desktop, flat on mobile)
- Features, workflow, testimonials and dark CTA sections
- Scroll-reveal via `IntersectionObserver`, smooth scrolling
- Email form with validation and success message (frontend demo only)
- Semantic markup, visible focus states, reduced-motion support, SEO + Open Graph tags
- Responsive from 320px to large desktop, no horizontal scroll

## Run locally
Open `index.html` in any modern browser. Optionally: `python3 -m http.server 8000` and visit `http://localhost:8000`.

## Deploy
**GitHub Pages:** push the folder to a repo → Settings → Pages → deploy from `main` / root.
**Netlify:** drag the folder onto app.netlify.com/drop, or connect the repo (no build command, publish directory `.`).
**Vercel:** run `npx vercel` in the folder, or import the repo (Framework: Other, no build command).

## Browser compatibility
Latest Chrome, Edge, Firefox, Safari and mobile browsers. Falls back gracefully without `IntersectionObserver` or `backdrop-filter`.
