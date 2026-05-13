# Jadoo Travel — React App

## Project Structure

```
src/
├── index.css                  # Global styles + .container-large
├── assets.js                  # All image/icon URLs
├── App.jsx                    # Root component
└── components/
    ├── Navbar.jsx / Navbar.css
    ├── Hero.jsx / Hero.css
    ├── Services.jsx / Services.css
    ├── Destinations.jsx / Destinations.css
    ├── BookTrip.jsx / BookTrip.css
    ├── Testimonials.jsx / Testimonials.css
    ├── Logos.jsx / Logos.css
    ├── Subscribe.jsx / Subscribe.css
    └── Footer.jsx / Footer.css
```

## Getting Started

```bash
npm create vite@latest jadoo-travel -- --template react
cd jadoo-travel

# Copy the src/ folder into the project, then:
npm install
npm run dev
```

## Notes
- Fonts: Volkhov (headings) + Poppins (body) loaded via Google Fonts in index.css
- `.container-large` global class: `width: 100%; max-width: 80rem`
- Testimonials use a custom CSS Swiper (no external library)
- All images are loaded from the original Webflow CDN
