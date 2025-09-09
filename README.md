Couchy

Elevator Pitch
A Netflix-style catalog website with Responsive Web Design, using JavaScript, to demonstrate recommendations, search, filters, favorites, watched before, and new releases.

Live Demo
https://couchy.vercel.app/

Status: Under Construction

Features (Minimum Viable Product)

Home Page (Hero Section + Content Rows/Carousels)

Title Detail Page (banner, description, cast, genres, rating)

Search Page (Search with Debounce)

My List (LocalStorage API)

Client-Side Routing (Hash Routing)

Responsive Web Design

Basic Accessibility (Web Content Accessibility Guidelines, WCAG)

Error Handling & Empty States

Local JSON (JavaScript Object Notation) dataset

Nice-to-Have (Future Work)

Multiple User Profiles

Continue Watching Section

Recommendation System (genre-based heuristics)

Progressive Web App (PWA)

Internationalization (i18n) ES/EN

Mock Authentication

Design Tokens (v1.2)
Color Palette (roles)

Primary: #FABF0E (calls to action, highlights)

Primary-Contrast: #003249 (text on yellow buttons)

Background: #051216 (app background)

Surface: #003249 (cards/rows)

Accent: #007EA7 (chips, focus rings)

Text-Primary: #FFFFFF

Text-Secondary: #B3C2C8 (secondary text on dark)

Typography

Font: Roboto

Base size: 16px

Type scale (approx.): H1 32–36, H2 24–28, H3 20–22, Body 16, Caption 14

Spacing & Shape

Spacing scale (px): 0, 4, 8, 12, 16, 24, 32, 40, 48
(Base-8 with 4/12 micro-steps)

Border radius: 8px (chips), 12px (cards), 20px (modals)

Shadow elevations:

Level 1 (cards): subtle separation from background

Level 2 (modals/dropdowns): stronger emphasis

Layout & Theming

Breakpoints: 360, 768, 1024, 1280 px

Theme: Dark Theme (default) — dark backgrounds, light text

Image Sizing (single-size policy)

Thumbnail Aspect Ratio: 16:9 (landscape)

Thumbnail Size (single): 640×360

Banner Aspect Ratio: 16:9 (landscape)

Banner Size (single): 1920×1080

Row/Card sizing by breakpoint (approx. width × height):

360 px: 160×90

768 px: 220×124

1024 px: 280×158

1280 px+: 320×180

Gutters & Padding

Row gutter: 8 px (mobile), 12 px (tablet), 16 px (desktop)

Row padding: 12 px (mobile), 16 px (tablet), 24 px (desktop)

Card shadow (Elevation 1): subtle for emphasis

Architecture Overview

Semantic HTML5 structure

CSS (Flexbox & Grid Layout) + Design Tokens (colors, typography, spacing, breakpoints, shadows, border radius)

JavaScript modules: router, store, services, components, app

Data model in JSON: id, title, type, year, genres[], rating, cast[], description, runtime, thumbnail, banner, trailer (optional)

Accessibility (a11y)

ARIA Attributes, Keyboard Navigation, Color Contrast (WCAG basics)

Performance

Lazy Loading (images), Responsive Layout, Lighthouse Audit (later)

How to Run (no build tools)

Open index.html in a browser (once the pages exist).

Non-Goals

No real authentication or user accounts (mock only)

No real streaming or DRM

No backend or server-side rendering (static client-side demo)

Images & Asset Policy

Thumbnails: 640×360 (JPG quality ~75–82 or WebP). Target ≤150 KB.

Banners: 1920×1080 (JPG ~75–82 or WebP). Target ≤600 KB.

Folder structure:

/assets/images/
  /thumbnails/
  /banners/
  /wireframes/
  /logos/


Naming convention: kebab-case

Thumbnails: title-640w.jpg

Banners: title-banner-1920w.jpg

Best practices:

Hero banner loads with high priority (not lazy)

Other thumbnails use lazy loading

Maintain ~5–10% safe area on banners to avoid awkward cropping across screens

Content & Licensing

The images and content belong to me (Central de las Escrituras Kids) and are provided exclusively for non-commercial, educational, and portfolio purposes.

Project Highlights

(To be added later.)

Lessons Learned

(To be added later.)
