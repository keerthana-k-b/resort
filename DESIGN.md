---
name: Obsidian Tropics
colors:
  surface: '#fbf9f8'
  surface-dim: '#dbd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#444748'
  inverse-surface: '#303030'
  inverse-on-surface: '#f2f0f0'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#6c5e06'
  on-secondary: '#ffffff'
  secondary-container: '#f7e382'
  on-secondary-container: '#73640e'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1b1c19'
  on-tertiary-container: '#848480'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#f7e382'
  secondary-fixed-dim: '#dac769'
  on-secondary-fixed: '#211b00'
  on-secondary-fixed-variant: '#524700'
  tertiary-fixed: '#e4e2dd'
  tertiary-fixed-dim: '#c8c6c2'
  on-tertiary-fixed: '#1b1c19'
  on-tertiary-fixed-variant: '#474744'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e2'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.4'
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.7'
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: DM Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.15em
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 32px
  margin-desktop: 80px
  margin-mobile: 24px
  section-gap: 160px
---

## Brand & Style
The brand personality is rooted in "Silent Luxury"—an aesthetic that prioritizes space, silence, and intentionality over ornamentation. Targeted at high-net-worth travelers seeking sanctuary, the UI must evoke an immediate sense of calm, exclusivity, and effortless service.

The design style is a sophisticated blend of **High-End Minimalism** and **Editorial Elegance**. It moves away from digital-first trends like glassmorphism in favor of structural purity and a tactile, print-inspired layout. Key visual drivers include:
- **Generous Negative Space:** Using whitespace as a luxury material to frame content.
- **Architectural Alignment:** A rigid adherence to grid structures that mirrors high-end resort architecture.
- **Cinematic Photography:** Large, edge-to-edge imagery serves as the primary "texture" of the interface.

## Colors
The palette is inspired by natural volcanic stone and sun-bleached organic fibers.
- **Primary (Obsidian):** `#1A1A1A` - Used for primary typography and structural lines. It is never pure black, ensuring a softer, more premium appearance.
- **Secondary (Pale Gold):** `#C5B358` - Used sparingly for subtle accents, active states, or "Book Now" highlights to signify value.
- **Tertiary (Alabaster):** `#F9F7F2` - The primary background color. This warm cream reduces eye strain and feels more "editorial" than stark white.
- **Neutral (Warm Grey):** `#4A4A4A` - Used for secondary body copy and borders.

## Typography
Typography follows a strict hierarchical contrast between serif headlines and sans-serif functional text.
- **Headlines:** Use *Playfair Display*. The high contrast between thick and thin strokes provides an immediate editorial feel. Tracking should be tightened slightly for larger displays.
- **Body & UI:** Use *DM Sans*. Its low-contrast, geometric forms remain legible even at small sizes and complement the serif headings without competing for attention.
- **Labels:** Always use *DM Sans* in uppercase with generous letter spacing to denote navigation and metadata.

## Layout & Spacing
This design system utilizes a **Fixed-Fluid Hybrid Grid**. Content is centered within a 1440px container, but high-impact photography is permitted to break the grid and extend to the edge of the viewport (Full-Bleed).

- **The 8px Rhythm:** All spacing must be a multiple of 8px.
- **Vertical Air:** Section gaps are intentionally large (160px+) to ensure the user never feels overwhelmed by information.
- **Masonry Patterns:** For galleries, use a 3-column staggered masonry layout with a fixed 32px gutter. Images should maintain their natural aspect ratios to reflect the unforced beauty of the destinations.
- **Mobile:** On mobile, margins shrink to 24px, and section gaps reduce to 80px.

## Elevation & Depth
In alignment with the "Silent Luxury" philosophy, shadows are almost entirely avoided. Depth is instead communicated through **Tonal Layering** and **Line Work**.
- **Tiers:** Use subtle shifts between the Alabaster background and slightly darker warm-grey surfaces to indicate container nesting.
- **Borders:** Use 1px solid lines in a very faint grey (`#E5E5E5`) to define zones without adding visual weight.
- **Interaction:** Hover states should involve subtle opacity shifts or "growing" image fills rather than lifting elements off the page with shadows.

## Shapes
To maintain an architectural and high-fashion aesthetic, this design system uses **Sharp (0px)** corners.
- **Buttons, Cards, and Inputs:** All elements must have 90-degree angles. This conveys stability, precision, and a premium "cut stone" feel.
- **Exceptions:** Circular elements are permitted only for icon buttons (like a "Play" video button) to provide a soft focal point against the rigid grid.

## Components
- **Primary Buttons:** High-contrast Obsidian background with Alabaster text. No border. On hover, the background transitions to the Gold accent. The width should be generous to accommodate longer text.
- **Secondary Buttons:** 1px Obsidian border with a transparent background. Text is in Obsidian, uppercase. 
- **Input Fields:** A single 1px bottom border (underline style) rather than a full box, using DM Sans for placeholder text. This mimics high-end stationery.
- **Cards:** No borders or shadows. Cards are defined by the image they contain. Typography sits below the image, never overlaid, to preserve the integrity of the photography.
- **Chips/Tags:** Small, uppercase text with 1px borders, used for "Availability" or "Amenities."
- **Masonry Gallery:** Images should utilize a "reveal on scroll" animation. Captions appear only on hover in a small, elegant serif font.