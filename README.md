# Hometek High School Website

A modern, responsive landing website for Hometek High School (Soroti, Kampala, Uganda). It showcases the school’s programs, facilities, admissions details, and contact information with smooth interactions and accessible design.

## Overview
- Hero section with branded overlay and CTAs
- Sticky navigation with mobile menu, link highlighting, and smooth scrolling
- Scroll-triggered animations and parallax hero image
- Animated stats counters
- Admissions quick-application and contact forms with client-side validation
- Back-to-top button and toast-style notifications
- Dark mode support (system preference and `data-color-scheme` attribute)
- Accessible enhancements (skip link, keyboard support, focus styles)

## Tech Stack
- HTML5 (semantic sections) – `index.html`
- Modern CSS with custom design tokens – `style.css`
- Vanilla JavaScript for interactions – `app.js`
- Google Fonts (Inter) and Font Awesome icons

## Site Sections
- Home (Hero, Stats)
- About (History, Mission, Vision, Core Values)
- Academics (Programs)
- Admissions (Requirements, Tuition, Quick Application Form)
- Student Life (Activities)
- Facilities (Cards)
- News & Updates
- Contact (Info, Social links, Form, Map placeholder)
- Footer (Quick links, contact, copyright)

## Key Features (from `app.js`)
- Mobile nav toggle and outside-click to close
- Sticky/hidden-on-scroll navbar and active link highlighting
- IntersectionObserver-powered fade-in and staggered animations
- Parallax effect for the hero background image
- Animated counters for statistics
- Smooth anchor scrolling with navbar offset
- Form validation (email/phone), inline error messages, and success/error notifications
- Back-to-top button visibility and smooth scroll-to-top
- Basic performance optimizations (throttled scroll, image preloading)
- Accessibility: skip link, improved keyboard activation for links/buttons

## Getting Started
1. Clone or download this repository.
2. Open `index.html` directly in your browser.
   - No build step is required; all assets are served locally or via CDNs.

## Project Structure
```
hometek-high-school/
  ├─ index.html   # Main HTML with all sections and markup
  ├─ style.css    # Global styles, tokens, responsive and dark mode rules
  ├─ app.js       # Interactivity: nav, animations, counters, forms, utilities
  ├─ LICENSE      # MIT License
  └─ README.md    # This file
```

## Customization
- Colors and design tokens: edit CSS variables in `style.css` (root and theme blocks).
- Hero background image: update the `src` on the `.hero-image` in `index.html`.
  - Currently uses a Pexels hotlink suitable for education contexts.
- Dark mode: tweak rules under media query `prefers-color-scheme: dark` or use `data-color-scheme="dark"` on `<html>` or `<body>` to force.
- Sections/cards: modify content blocks in `index.html` and matching styles.

## Attribution
- Fonts: Google Fonts – Inter
- Icons: Font Awesome
- Hero Image (Pexels): `https://images.pexels.com/photos/5212345/pexels-photo-5212345.jpeg?auto=compress&cs=tinysrgb&dpr=2&w=1920&h=1080`
  - Ensure usage complies with Pexels licensing.

## License
This project is licensed under the MIT License. See `LICENSE` for details.
