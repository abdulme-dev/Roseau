---
name: Imperial Heritage
colors:
  surface: '#fbf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#4d4635'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#7f7663'
  outline-variant: '#d0c5af'
  surface-tint: '#735c00'
  primary: '#735c00'
  on-primary: '#ffffff'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#e9c349'
  secondary: '#b22b1d'
  on-secondary: '#ffffff'
  secondary-container: '#fe624e'
  on-secondary-container: '#650000'
  tertiary: '#5e5f5d'
  on-tertiary: '#ffffff'
  tertiary-container: '#b3b3b0'
  on-tertiary-container: '#444543'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#ffdad4'
  secondary-fixed-dim: '#ffb4a8'
  on-secondary-fixed: '#410000'
  on-secondary-fixed-variant: '#8f0f07'
  tertiary-fixed: '#e3e2e0'
  tertiary-fixed-dim: '#c7c6c4'
  on-tertiary-fixed: '#1a1c1a'
  on-tertiary-fixed-variant: '#464745'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.15em
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 32px
  margin-mobile: 20px
  section-padding-lg: 120px
---

## Brand & Style
The design system for this luxury hotel and spa evokes the regal heritage of Gondar, often called the "Camelot of Africa." The brand personality is **distinguished, timeless, and hospitable**, merging the architectural grandeur of Ethiopian stone castles with modern high-end wellness. 

The aesthetic follows a **Minimalist-Luxury** movement: it prioritizes vast whitespace to represent the "breath" of the highlands, accented by precise, jewelry-like details. The emotional response should be one of immediate tranquility and exclusivity, signaling a retreat where history and modern comfort intersect.

## Colors
The palette is rooted in power and earth. **Deep Royal Gold** is used as the primary accent to denote quality and the sun, while **Oxblood Red** serves as a secondary weight for calls to action and heritage-rich details. 

- **Primary (Gold):** Used for interactive states, thin borders, and decorative icons.
- **Secondary (Crimson):** Reserved for high-priority buttons and seasonal motifs.
- **Backgrounds:** Pure White (#FFFFFF) provides the base canvas, while the Off-White/Cream (#FAF9F6) is used for section differentiation to create a layered, "parchment" feel.
- **Text:** Sophisticated Charcoal (#333333) ensures perfect legibility against the light backgrounds, avoiding the harshness of pure black.

## Typography
The system uses a high-contrast typographic pairing. **Playfair Display** provides a serif look that is authoritative yet graceful, reminiscent of historical manuscripts and luxury editorial magazines. It should be used for all headlines and quotes.

**Montserrat** provides a clean, geometric counterpoint for body copy and UI labels. It ensures that even dense information—like spa menus or booking details—remains modern and accessible.

- Use **label-caps** for small headers, categories, and eyebrow text.
- Maintain wide line-heights in body copy to reinforce the airy, relaxed atmosphere of a spa.

## Layout & Spacing
The layout uses a **12-column fixed grid** on desktop, centered to create a generous frame around content. On mobile, it transitions to a fluid single-column layout with 20px side margins.

Key spacing rules:
- **Vertical Rhythm:** Large vertical gaps (80px–120px) between sections to prevent the UI from feeling "crowded."
- **Safe Zones:** Use the 8px base unit for all component internals (paddings, gaps).
- **Asymmetry:** Occasionally break the grid with high-quality imagery to create a premium, editorial flow.

## Elevation & Depth
This design system avoids heavy shadows in favor of **Tonal Layers and Thin Outlines**. 
- **Depth:** Conveyed through subtle #333333 shadows with very high diffusion (Blur: 30px, Opacity: 4%) to make cards feel like they are floating just above the surface.
- **Accents:** Use 1px #D4AF37 (Gold) borders to define premium containers or to separate navigation.
- **Glass:** In the fixed header, a backdrop-blur (10px) with a semi-transparent White (90% opacity) allows imagery to peek through as the user scrolls.

## Shapes
The shape language is **Sharp (0px)**. To maintain an architectural and regal feel, buttons and cards use crisp 90-degree corners. This evokes the stonework of the Gondar castles and communicates a sense of formal precision and structure. Softness is introduced through photography and typography rather than corner radii.

## Components
- **Buttons:** 
    - *Primary:* Solid Gold (#D4AF37) with White text. Use for the 'Book Now' CTA.
    - *Secondary:* Ghost style with a 1px Gold border and Gold text.
    - *Hover State:* Primary buttons should shift slightly darker or introduce a very subtle inner glow.
- **Cards:** 
    - Minimalist containers with no visible border, utilizing the soft ambient shadow. 
    - Typography inside cards must be center-aligned for a formal, balanced look.
- **Navigation:** 
    - The header is fixed with a 1px Gold bottom border. 
    - Navigation links use the **label-caps** style. 
    - The 'Book Now' CTA in the header remains the most prominent element.
- **Inputs:** 
    - Underline-only style for text fields to maintain a high-end "registry book" aesthetic. 
    - Labels float above the line in Montserrat 12px caps.
- **Dividers:** 
    - Horizontal lines should be 1px thick, utilizing the Gold color, often centered with 50% width of the container for decorative flair.