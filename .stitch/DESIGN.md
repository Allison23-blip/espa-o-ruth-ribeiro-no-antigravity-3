## Brand & Style
This design system defines an upscale, organic, and welcoming digital experience for a specialized beauty clinic and hair atelier catering to textured and curly hair, facial aesthetics, and holistic self-care. It bridges clinical expertise with the tranquil warmth of an earthy sanctuary. The brand architecture accommodates a diverse family audience—women, men, and children—without falling into clinical coldness or gendered clichés.

The design movement combines **Warm Organic Minimalism** with **Editorial High-End Wellness**:
- Generous breathing room, rhythmic white/creme space, and subtle organic line art.
- Human-centric imagery displaying natural hair textures, authentic smiles, and calm restorative procedures.
- A grounded, approachable luxury that feels inclusive, tactile, and protective.

## Layout & Spacing
A 12-column responsive fluid grid anchored by generous vertical rhythm:

- **Desktop (1200px+):** Max content width capped at `1280px`. 12-column grid with `24px` gutters and `48px` outer margins. Hero and testimonial blocks lean into asymmetric groupings (e.g., 5-column editorial text balanced against 7-column portrait photography).
- **Tablet (768px - 1199px):** 8 columns, `20px` gutters, `32px` outer margins. Service tiers collapse into 2-column card structures.
- **Mobile (< 768px):** 4 columns with `16px` gutters and `20px` margins. Visual stacks collapse vertically, maintaining horizontal snap-scrolling carousels for treatment cards and stylist showcases.
- **Vertical Rhythm:** Minimum `space-3xl` (`4.5rem`) section separations on desktop, reducing to `space-2xl` (`3rem`) on mobile to preserve spa-like expansiveness.

## Elevation & Depth
In place of heavy drop shadows or glassy gradients, visual hierarchy is established through **warm tonal layering** and **whisper-soft ambient diffusion**:

- **Tonal Stepping:** The canvas rests at `#FAF7F2`. Raised service cards and containers elevate to `#FFFFFF` or sink gently to `#F3ECE2`, framed by a fine border (`1px solid #E8DDD2`).
- **Warm Ambient Shadow:** Floating dropdowns, sticky booking headers, and modal dialogues employ a low-opacity shadow tinted with warm café umber:
  `box-shadow: 0 12px 32px -8px rgba(44, 35, 32, 0.07), 0 4px 12px -2px rgba(44, 35, 32, 0.04)`.
- **Active / Hover State:** Cards scale smoothly (`translateY(-2px)`) with shadow bloom increasing to `rgba(155, 98, 80, 0.12)`.

## Components

### Buttons
- **Primary Action (Agendar / Reservar):** Solid Terracota (`#9B6250`) background, crisp `#FAF7F2` text, `0.5rem` radius, with subtle hover lift and color transition to `#875343`.
- **Secondary Action (Conhecer Tratamentos):** Bordered variant with `1.5px solid #52604D`, Sálvia text, transparent background transitioning to soft olive tint (`#52604D0F`) on hover.
- **Tertiary / Link Action:** Editorial underline in `#9B6250` with trailing inline arrow.

### Cards & Service Tiles
- **Treatment Card:** Background `#FFFFFF`, border `1px solid #E8DDD2`, padding `1.5rem`, `rounded-lg` (`16px`). Upper half hosts portrait photography with subtle zoom on hover. Includes category tag, service title, duration indicator, and starting price.
- **Audience Segment Card (Cachos, Masculino, Infantil, Estética Facial):** Subtle tonal container in `#F3ECE2` paired with an earthy icon and high-legibility sans-serif copy.

### Chips & Filters
- **Filter Chips:** Pill-shaped (`9999px`), `0.75rem` vertical by `1rem` horizontal padding. Inactive: `#FFFFFF` with `1px solid #E8DDD2` and `#2C2320` text. Active: Filled `#52604D` with `#FAF7F2` text.

### Form Inputs & Booking Pickers
- **Text Inputs & Dropdowns:** Background `#FFFFFF` or `#F3ECE2` with `1px solid #E8DDD2`, `8px` radius. Focus ring: `2px solid #9B6250` with `2px` offset. Placeholder text in `#8C817B`.
- **Date & Specialist Selection:** Square-rounded tiles with day, date, and availability status. Selected state utilizes Terracota border with warm tint fill.

### Testimonials & Reviews
- Quotation blocks featuring a large decorative Playfair quotation mark in `#C48B77`, star ratings in `#9B6250`, accompanied by client hair type and procedure tags (e.g., *Transição Capilar*, *Harmonização Natural*, *Corte Infantil Afetivo*).