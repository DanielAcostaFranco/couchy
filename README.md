Project Name: 

  Couchy
  

Elevator Pitch: 

  A Netflix-style catalog website with Responsive Web Design, using JavaScript, to demonstrate recommendations, search, filters, favorites, watched before, and new releases.


Live Demo (URL): 

https://couchy.vercel.app/

Under Construction
  

Features (MVP):

  Home Page (Hero Section + Content Rows/Carousels)
  Title Detail Page (banner, description, cast, genres, rating)
  Search Page (Search with Debounce)
  My List (LocalStorage API)
  Client-Side Routing (Hash Routing)
  Responsive Web Design
  Basic Accessibility (Web Content Accessibility Guidelines, WCAG)
  Error Handling & Empty States
  Local JSON (JavaScript Object Notation) dataset

Nice to Have: 
  Multiple User Profiles
  Continue Watching Section
  Recommendation System
  Progressive Web App (PWA)
  Internationalization (i18n) ES/EN
  Mock Authentication
  

Design Tokens
  Color Palette (roles):
  Primary: #FABF0E (calls to action, highlights)
  Primary-Contrast: #003249 (texto dentro de botones amarillos)
  Background: #051216 (app background)
  Surface: #003249 (cards/rows)
  Accent: #007EA7 (chips, focus rings)
  Text-Primary: #FFFFFF
  Text-Secondary: #B3C2C8 (texto secundario sobre dark)
  Typography: Roboto; Base size: 16px; Type Scale (ej. headings):
  H1 ~ 32–36, H2 ~ 24–28, H3 ~ 20–22, Body 16, Caption 14.
  Spacing Scale: (en px) 0, 4, 8, 12, 16, 24, 32, 40, 48.
  (Base 8 con un paso de 4/12 para micro-ajustes.)
  Border Radius: 8px (chips), 12px (cards), 20px (modals).
  Shadow Elevations:
  Level 1 (cards): sutil para separar del fondo.Level 2 (modals, dropdowns): más marcado.
  Breakpoints: 360, 768, 1024, 1280 px.
  Theme: Dark Theme por defecto; fondos oscuros, texto claro.
  Thumbnail Aspect Ratio: 16:9 (landscape)
  Thumbnail Base Size: 640×360
  Row/Card sizing por breakpoint (anchura × altura aprox.):
  360 px: 160×90
  768 px: 220×124
  1024 px: 280×158
  1280 px+: 320×180
  Row Gutter: 8 px (mobile), 12 px (tablet), 16 px (desktop)
  Row Padding: 12 px (mobile), 16 px (tablet), 24 px (desktop)
  Card Border Radius: 12 px
  Card Shadow (Elevation 1): sutil para destacar sobre fondo oscuro
  Banners (Detail/Hero): 1280×720 o 1920×1080 (también 16:9)

  
Architecture Overview

  Semantic HTML5 structure
  CSS (Flexbox & Grid Layout) + Design Tokens (colors, typography, spacing, breakpoints, shadows, border radius)
  JavaScript modules: router, store, services, components, app
  Data model in JSON: (id, title, type, year, genres[], rating, cast[], description, runtime, thumbnail, banner, trailer)
  

Accessibility (a11y)

  ARIA Attributes, Keyboard Navigation, Color Contrast
  

Performance

  Lazy Loading (images), Responsive Images (srcset/sizes), Lighthouse Audit (later)
  

How to Run (no build tools)

  Open index.html in a browser (once the pages exist).
  

Project Highlights
------------------

Lessons Learned
-----------------

Content & Licensing

  The content is my property and is intended only for non commercial use. 


  
