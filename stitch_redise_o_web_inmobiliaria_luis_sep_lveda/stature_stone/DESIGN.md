---
name: Stature & Stone
colors:
  surface: '#fdf8f8'
  surface-dim: '#ddd9d9'
  surface-bright: '#fdf8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3f2'
  surface-container: '#f1edec'
  surface-container-high: '#ebe7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#46474a'
  inverse-surface: '#313030'
  inverse-on-surface: '#f4f0ef'
  outline: '#76777b'
  outline-variant: '#c7c6ca'
  surface-tint: '#5f5e5f'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1b1b1c'
  on-primary-container: '#858384'
  inverse-primary: '#c8c6c7'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1c1b19'
  on-tertiary-container: '#868380'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e3'
  primary-fixed-dim: '#c8c6c7'
  on-primary-fixed: '#1b1b1c'
  on-primary-fixed-variant: '#474647'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e6e2de'
  tertiary-fixed-dim: '#cac6c2'
  on-tertiary-fixed: '#1c1b19'
  on-tertiary-fixed-variant: '#484644'
  background: '#fdf8f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: metropolis
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: metropolis
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: metropolis
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: metropolis
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: metropolis
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  section-gap-desktop: 120px
  section-gap-mobile: 64px
  grid-columns: '12'
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
---

## Brand & Style

This design system establishes a visual language of permanence and prestige for the Chilean real estate market. The aesthetic reflects architectural precision—utilizing heavy-weight foundations and airy, expansive backgrounds to mirror the physical spaces the company creates. 

The style is characterized by high-contrast transitions between deep charcoals and soft off-whites, creating a rhythm that feels both modern and historically solid. Visual elements should prioritize clarity and structural integrity, evoking the "solid foundation" promised by the brand’s engineering expertise. Aspirational qualities are introduced through intentional whitespace and a sophisticated accent palette that suggests warmth and luxury without being ostentatious.

## Colors

The palette is anchored by **Deep Charcoal (#1A1A1B)** and **Black (#000000)**, used for primary typography and structural containers to represent stability. These are balanced against **Off-white (#F9F9F9)** and **Pure White (#FFFFFF)** to maintain a clean, high-end gallery feel.

**Soft Gold (#D4AF37)** is the primary accent for high-value interactions and "Luxury" tier designations, while **Warm Terracotta (#C05746)** is reserved for primary Call-to-Action (CTA) elements, providing a grounded, earthy contrast that nods to traditional construction materials. Neutrals are strictly cool-toned greys to prevent the design from feeling dated, ensuring the UI remains crisp and professional.

## Typography

This design system uses **Metropolis** for headings to project a geometric, architectural feel. Its precise construction aligns with the company's focus on engineering and real estate. For long-form content and UI labels, **Inter** provides exceptional legibility and a neutral, systematic tone.

Large display headings should use tighter letter spacing to feel "locked-in" and heavy. Conversely, the `label-caps` style utilizes generous letter spacing to provide an air of sophistication for secondary metadata, such as project locations or dates.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to maintain an "editorial" look where content is carefully framed. A 12-column system is used, but content is often pushed to the center 8 or 10 columns to create luxurious white space (margins).

Spacing is built on an 8px base unit. Section-to-section transitions require significant vertical breathing room (120px) to distinguish between project showcases and corporate information. On mobile, the layout reflows to a single column with increased padding to maintain the high-end, uncluttered feel.

## Elevation & Depth

To maintain a "solid" and "modern" feel, this design system avoids floating elements or heavy blurs. Depth is conveyed through:

1.  **Tonal Stacking:** Using the Off-white (#F9F9F9) as a base layer and Pure White (#FFFFFF) for elevated cards or interactive elements.
2.  **Architectural Shadows:** Shadows are extremely subtle, using low-opacity charcoal tints with a large spread and minimal offset, making elements feel like they are slightly raised surfaces rather than hovering objects.
3.  **High-Contrast Inversion:** Depth is also signaled by "Heavy" sections where the background becomes Deep Charcoal (#1A1A1B) and text becomes White, effectively creating a visual "cut-out" in the page flow.

## Shapes

The shape language is "Soft" (0.25rem radius). While the brand is modern, sharp 0px corners feel too aggressive and brutalist, whereas fully rounded corners feel too consumer-grade/friendly. A slight 4px radius on buttons and cards softens the geometric rigidity of the typography while maintaining a disciplined, professional appearance. 

Images of properties should maintain these consistent corner radii to unify the photography with the UI.

## Components

### Buttons
- **Primary:** Warm Terracotta (#C05746) background with White text. Subtle 4px shadow on rest; slight lift on hover.
- **Secondary:** Deep Charcoal (#1A1A1B) outline with 1px thickness. No background.
- **Size:** Large padding (16px 32px) to communicate importance and ease of touch.

### Cards (Project Showcase)
- **Structure:** Full-bleed image on top, followed by a tight padding container for metadata.
- **Typography:** Uses `headline-md` for project names and `label-caps` for the "Status" (e.g., SOLD OUT, UNDER CONSTRUCTION).
- **Style:** Pure White background against the Off-white page background to create a subtle lift.

### Input Fields
- **Style:** Underline-only or low-opacity grey border (1px). Focus state moves to a solid 2px Deep Charcoal bottom border. This mimics architectural drafting lines.

### Social Proof / Icons
- **Iconography:** Thin-stroke (1.5pt) monolinear icons. 
- **Treatment:** Icons are always paired with `label-caps` text to serve as "Differentiators" (e.g., Square Meterage, Location, Certification). Use Soft Gold for icons to indicate premium value.