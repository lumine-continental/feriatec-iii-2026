# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack
Static HTML5 (`index.html`), inline CSS3 scoped under `.feria-tec-landing`, and minimal Vanilla JavaScript (designed for direct embedding inside an existing WordPress website without global style collisions or external framework dependencies).

## Users
Recent high school graduates and young prospective students (ages 16–22) in Peru exploring technical and professional careers, often attending with friends or family. They want an immersive, hands-on festival experience where they can test real career spaces, experience campus life, connect with top employers, and unlock admission perks before deciding where to study.

## Product Purpose
Generate registrations and qualified prospective student leads for **Feria TEC** by **Instituto Continental** through a high-conversion, single-page campaign landing page that sells the event as an unmissable, multi-zone campus experience.

## Positioning
Unlike a conventional academic open house or numbered lecture tour, Feria TEC is positioned as an all-in-one campus takeover comprising **7 independent thematic zones** (Admission + Electric Motorcycle & Gaming Chair Giveaway, Break & Entertainment with DJ/Food Trucks, IConecta Networking, Employability with top partner companies, Fashion & Styling, Gastronomic Festival, and Green/Sustainability Zone) alongside **11 interactive career spaces** where visitors experience their future profession firsthand.

## Operating Context
Embedded inside an existing WordPress installation for Instituto Continental. Must inherit the host WordPress theme's typography (with `Inter` as a fallback only if unavailable), isolate all styles under `.feria-tec-landing`, avoid global selectors (`body`, `html`, bare headings/buttons), and render the registration form via the real WordPress shortcode `[gravityform id="91" title="true"]` (accompanied by a styled fallback preview form when viewed outside WordPress).

## Capabilities and Constraints
- **Nine core campaign sections:**
  1. **Hero section:** Full-width dark campaign composition, oversized expressive typography with strategic `#E4000B` highlights, event pitch, and prominent floating registration form container (`[gravityform id="91" title="true"]`).
  2. **Discover the 7 Feria TEC Zones:** Editorial, asymmetric rectangular composition (not 7 identical cards and not a numbered sequential itinerary) covering:
     - **ZONE 01 — Zona de Admisión:** Simulacro de admisión en vivo, Portal "Postula Aquí" (laptops/tablets), exclusive enrollment benefit, and high-prominence promo highlight: *"Matricúlate en la feria y participa del sorteo de una moto eléctrica y una silla gamer"*.
     - **ZONE 02 — Zona Break & Entretenimiento:** Relaxation area, food trucks & music, main show with host & DJ, Photobooth `#FeriaTecContinental`.
     - **ZONE 03 — Zona IConecta:** Networking space, vocational guidance, short talks *"Mi futuro profesional"*, hourly talks with graduates and teachers.
     - **ZONE 04 — Zona de Empleabilidad | ¡Empléate Ya!:** Stands from partner companies (Ferreyros, SUNAT, BCP, and others), job opportunities, internships, and career development.
     - **ZONE 05 — Zona A la Moda:** Hairstyles & personal styling, fashion & trends, quick makeup experiences, participation of Graphic Design and Communication students.
     - **ZONE 06 — Festival Gastronómico:** Culinary exhibitions, sale of student-prepared products, participation of local partners.
     - **ZONE 07 — Zona Verde:** Sustainability & recycling, ecological initiatives, environmental awareness activities and interactive dynamics (monochromatic UI; natural colors only in photography).
  3. **Discover Your Future Career (11 Programs):** Editorial rectangular grid with oversized numeric/short identifiers, dark surfaces, and photography for:
     - Administración de Empresas
     - Administración de Negocios Bancarios y Financieros
     - Contabilidad
     - Desarrollo de Sistemas de Información
     - Diseño Gráfico Publicitario
     - Administración de Negocios Internacionales
     - Marketing
     - Ciencia de Datos e Inteligencia Artificial (listed once, no duplication)
     - Diseño de Interiores
     - Farmacia
     - Enfermería
  4. **Promotional Video / The Feria TEC Experience:** Cinematic event atmosphere preview with prominent red play affordance and dark photographic treatment.
  5. **Exclusive Giveaway:** High-impact conversion section showcasing the **Electric Motorcycle** and **Gaming Chair** enrollment giveaway with bold typography and red emphasis on the enrollment condition.
  6. **Institutional Campaign Image:** Edge-to-edge cinematic photographic banner highlighting authentic Instituto Continental student experiences.
  7. **Institutional Statistics:** Rectangular metrics grid with oversized numbers and strategic red accents using verified Instituto Continental figures.
  8. **Frequently Asked Questions (FAQ):** Accessible accordion with square geometric controls, dark surfaces, subtle gray dividers, and `#E4000B` active states.
  9. **Footer:** Minimal dark institutional footer with brand identification and copyright.

## Brand Commitments
- **Institution:** Instituto Continental.
- **Campaign:** Feria TEC.
- **Pinned Global Art Direction:** **Bauhaus × Contemporary Gaming × Editorial Design (High-Contrast B/N Rhythm with Surgical Red Accents)**.
  - **Alternating Black & White Architectural Rhythm (User Steer):** Alternate bold black-background sections (`#0A0A0A`, `#111111`, `#1C1C1C`) with high-visibility white typography (`#FFFFFF`, `#EAEAEA`) and stark white/off-white editorial sections (`#FFFFFF`, `#F4F4F4`) with deep black typography and structural rules (`#0A0A0A`, `#1C1C1C`, `#333333`).
  - **Surgical Red Accent (`#E4000B`):** Used with strict restraint (≤ 3% of viewport) for the pulsing header CTA, form submit button, and active TV indicator—never flooding sections in red.
  - **70% Text Reduction & Visual-First Hierarchy (Phase 2 User Steer):** Strip dense copy by 70%; prioritize photography, ultra-concise 2–5 word tags, minimalist stroke SVG icons, floating geometric SVGs, and dedicated **Spline 3D embed containers** (`<spline-viewer>` / `<iframe>` slots with interactive 3D floating geometry).
  - **Comic-Style Hard 2-Sided Offset Shadows (Phase 2 User Steer):** Frame key cards and modules with crisp `2px`–`3px` borders and two-sided hard extruded comic shadows (`6px 6px 0 #0A0A0A` on white, `6px 6px 0 #FFFFFF` on black).
  - **Pre-Hero Retro TV Video Frame + 5% Pixel/Videogame Winks (Phase 2 User Steer):** Precede the main registration Hero with a physical **Retro CRT Television Frame** that embeds the campaign video (YouTube `<iframe>` or self-hosted `<video>`) and pair it with ~5% crisp pixel-art / videogame SVG winks (`shape-rendering="crispEdges"`).
  - **Live Event Countdown (Phase 2 User Steer):** Include a dedicated countdown section below the Hero counting down to **December 5, 2026** (`5 de diciembre 2026`).
  - No blue, purple, green, or neon gradients in the interface (natural colors appear only inside photography).
  - Strict 90-degree Bauhaus geometry: sharp square corners, asymmetric rectangular grids, overlapping rectangular planes, oversized numerals.

## Evidence on Hand
- Verified Instituto Continental institutional statistics:
  - `+104K` profesionales y egresados
  - `+78K` estudiantes
  - `+15K` convenios
  - `+24K` empresas aliadas
  - `90%` empleabilidad
  - `+8K` egresados con trabajo
  - `+54` programas
  - `+40` años de trayectoria
- Named employability partners: Ferreyros, SUNAT, BCP.
- Verified FAQ items covering what Feria TEC is, free admission, who can attend, event schedule/venue, giveaway requirements, and attending with parents/friends.

## Product Principles
1. **Sell the Festival Experience First:** Present the 7 thematic zones and 11 career spaces as distinct, high-energy destinations rather than a dry institutional syllabus.
2. **Dark Bauhaus × Gaming Atmospheric Discipline:** Commit 100% to sharp 90-degree geometry, monochromatic dark architectural planes (`#0A0A0A`–`#252525`), high-contrast white editorial typography, and surgical `#E4000B` red punctuation.
3. **Conversion Velocity:** Anchor the hero around the floating `[gravityform id="91" title="true"]` container and reinforce the registration incentive (electric motorcycle & gaming chair giveaway upon enrollment) throughout the scroll narrative.
4. **Zero-Leak WordPress Encapsulation:** Keep every rule scoped inside `.feria-tec-landing`, inherit theme typography gracefully, and deliver a self-contained `index.html`.
