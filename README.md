# MAISON-ELARA
MAISON ÉLARA — Contemporary Indian Luxury Fine Dining

Where every moment becomes an experience.

MAISON ÉLARA is a luxury hospitality web experience built around the creative vision: "The soul of Indian heritage, reimagined through modern luxury." Blending restrained Indian architectural references with international fine-dining art direction, this repository currently houses the Phase 1 (Design System) and Phase 2 (Homepage & Cinematic 3D Experience) interactive prototype.

✨ Key Features

1. Cinematic 3D Hero Experience (Three.js)

Candlelit Dining Composition: Procedural dark veined marble tabletop, projected jaali light-shadow geometry, antique brushed-brass charger & cutlery, matte charcoal ceramic plate, sculpted saffron signature dish, stemmed crystal wine glass, and a softly flickering candle flame.

Art-Directed Motion: Smooth cinematic camera entrance sweep, cursor-driven depth parallax, scroll-linked camera glide, and slow-drifting warm dust motes.

Graceful Fallback & Accessibility: Automatically respects prefers-reduced-motion and falls back to a high-resolution dining hall photograph if WebGL is unavailable.

2. Luxury Editorial Design System

Alternating Visual Rhythm: Balances deep midnight-black (#171613) and royal charcoal (#211F1A) cinematic sections with warm ivory (#F2EBDD) editorial sections.

Restrained Palette: Antique Champagne Gold (#B99A64), Burnished Bronze (#806747), Deep Espresso (#51443A), Muted Warm Stone (#A9A193), and Deep Burgundy (#542B2D).

Typography: Editorial pairing of Cormorant Garamond (headings & italic accents) with Inter (clean UI & body copy).

3. Interactive Hospitality Sections

Preloader & Floating Navigation: Minimal 1px champagne-gold preloader, top viewport scroll-progress bar, backdrop-blurred floating header, and staggered fullscreen mobile drawer.

Our Story: Asymmetric editorial storytelling paired with real fine-dining photography and three craftsmanship pillars.

Signature Creations: Four alternating showcases with subtle 3D hover tilt and an interactive Tasting Notes Modal (flavor profile, sommelier pairing, provenance ingredients, and wishlist toggle).

The Menu: Printed-sheet fine-dining digital menu featuring live search, category tabs, dietary filter pills (All, Vegetarian, Chef's Selection, Gluten-Free), availability badges, and a slide-out Saved Selections (Wishlist) drawer.

Dining Experiences & Architecture: Interactive switcher for The Royal Dining Room, Chef's Tasting Table, Private Heritage Suite, and Candlelit Courtyard & Bar, plus a dedicated Architecture & Ambience grid.

Masonry Gallery & Lightbox: Responsive masonry archive with keyboard-navigable (ArrowLeft, ArrowRight, Escape) fullscreen lightbox.

Reservation Interface: Validated dining reservation form with seating time-slot selection and an honest Phase 2 Frontend Preview Modal (ready to connect to Supabase in Phase 4).

🛠️ Tech Stack (Current Prototype)

Core: Semantic HTML5, Vanilla JavaScript (ES6+)

Styling: Tailwind CSS (via CDN) + custom CSS editorial motion & chiaroscuro photo-grading tokens

3D Graphics: Three.js (r128)

Typography: Google Fonts (Cormorant Garamond, Inter)

Photography: Curated high-resolution fine-dining & hospitality photography via Unsplash

🚀 Getting Started

Because the Phase 1 & Phase 2 prototype is engineered as a self-contained single-file web application, no build step is required to preview it locally.

Clone the repository

git clone https://github.com/your-username/maison-elara.git
cd maison-elara


Run locally

Open maison_elara.html directly in any modern browser, or

Serve it with a local development server for the best experience:

npx serve .


Then navigate to http://localhost:3000/maison_elara.html.

🗺️ Full-Stack Roadmap

[x] Phase 1 — Brand & Design System: Color tokens, typography hierarchy, spacing, grain & lighting language.

[x] Phase 2 — Homepage & Cinematic 3D Experience: Three.js hero scene, editorial sections, interactive digital menu, gallery lightbox, and reservation preview.

[ ] Phase 3 — Multi-Page App Router Architecture: Migrate to Next.js (App Router), React, TypeScript, Framer Motion, and React Three Fiber.

[ ] Phase 4 — Backend & Database: Supabase PostgreSQL schema, Row Level Security (RLS), authentication, live menu sync, and real-time reservation availability.

[ ] Phase 5 — Ordering & Payments: Shopping cart, server-side order creation, and Razorpay payment verification & webhooks.

[ ] Phase 6 — Admin Dashboard: Role-protected management for menus, reservations, orders, gallery, and restaurant settings.

[ ] Phase 7 — Optimization & Deployment: SEO structured data, 3D asset compression, accessibility audit, and Vercel deployment.

📸 Assets & Licensing

Photography: Sourced from Unsplash under the Unsplash License for prototype and editorial demonstration purposes. Replace with original restaurant photography prior to production launch.

License: This project is open for portfolio and development use. Add a LICENSE file (e.g., MIT) if you plan to distribute it publicly.

Crafted with restraint, heritage, and contemporary digital artistry.
