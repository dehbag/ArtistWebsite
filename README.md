# ArtistWebsite
RasheDige is a static, responsive portfolio site for Hadi Rezaei (aka RasheDige), showcasing his work as a music composer and producer. It’s built with HTML5, SCSS (compiled to a single minified app.min.css), and modern JavaScript (bundled into vendor.min.js and main.min.js), and optimized for performance, SEO, and accessibility.
# RasheDige – Music Composer & Producer Website

## Key Features

- **Performance-First**
  - Single HTTP requests for CSS & JS (minified & bundled)  
  - Preload critical assets (fonts & CSS)  
  - `defer`-loaded scripts and lazy-loaded images  
  - CLS-friendly `<img width height>` attributes  

- **SEO & Social Sharing**
  - Fully localized `<meta>` tags (description, keywords, canonical)  
  - Open Graph & Twitter Card support  
  - JSON-LD Structured Data for a "Person" schema  

- **Responsive & Accessible**
  - Mobile-first layout via Bootstrap 4  
  - ARIA attributes and semantic tags  
  - Keyboard-navigable forms and menus  

## Getting Started

1. **Serve locally**
   ```bash
   python3 -m http.server 8000
   ```
2. **Visit** `http://localhost:8000` in your browser.
