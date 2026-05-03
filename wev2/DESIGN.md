---
name: Climate Organic Premium
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#414943'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#717973'
  outline-variant: '#c1c8c1'
  surface-tint: '#3d6751'
  primary: '#3d6751'
  on-primary: '#ffffff'
  primary-container: '#a8d5ba'
  on-primary-container: '#345d48'
  inverse-primary: '#a4d1b6'
  secondary: '#4e6535'
  on-secondary: '#ffffff'
  secondary-container: '#cde9ac'
  on-secondary-container: '#526a39'
  tertiary: '#586155'
  on-tertiary: '#ffffff'
  tertiary-container: '#c4cebf'
  on-tertiary-container: '#4f584c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bfedd1'
  primary-fixed-dim: '#a4d1b6'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#254f3a'
  secondary-fixed: '#d0ecaf'
  secondary-fixed-dim: '#b4cf95'
  on-secondary-fixed: '#0e2000'
  on-secondary-fixed-variant: '#374d20'
  tertiary-fixed: '#dce6d6'
  tertiary-fixed-dim: '#bfc9ba'
  on-tertiary-fixed: '#151e14'
  on-tertiary-fixed-variant: '#40493e'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  unit: 8px
  container-padding: 64px
  gutter: 24px
  section-gap: 128px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The brand identity for this design system is built upon the concept of "Atmospheric Purity." It bridges the gap between high-tech climate agriculture and the grounded, tactile nature of organic rice farming. The personality is serene, sophisticated, and transparent.

The design style utilizes a hybrid of **Organic Minimalism** and **Soft Glassmorphism**. This approach prioritizes a "breathable" interface where information is curated rather than crowded. By combining the precision of modern layout techniques with the softness of natural textures, the design system evokes a sense of trust, premium quality, and environmental stewardship. The aesthetic is heavily influenced by "Japandi" principles—merging Japanese functional minimalism with Scandinavian warmth—tailored for a forward-looking 2026 digital experience.

## Colors

The palette is inspired by the lifecycle of rice and the clarity of the atmosphere. 
- **Primary Green (#A8D5BA):** A muted, pastel green representing climate-positive technology and stability.
- **Young Rice Green (#C5E1A5):** Used for growth-oriented accents, call-to-actions, and highlights.
- **Natural Creams & Whites (#FDFBF7, #F9F9F9):** These form the "canvas" of the design system, replacing harsh pure whites with softer, more organic tones that reduce eye strain and feel premium.
- **Contrast:** High-level typography should use a deep charcoal or muted olive rather than pure black to maintain the soft, natural aesthetic.

## Typography

This design system uses a dual-font strategy to balance character with utility. 

**Plus Jakarta Sans** is the primary headline face. Its soft, open counters and modern geometric build feel welcoming and premium. Headlines should be used with generous leading and occasional negative letter-spacing for a high-end editorial feel.

**Inter** provides the functional backbone for body text and UI labels. It ensures maximum readability across all screen sizes. Body text should maintain a generous line height (1.6x) to support the "minimalist" and "breathable" philosophy of the brand.

## Layout & Spacing

The layout philosophy centers on **Generous Whitespace**. The system uses a 12-column fixed grid for desktop, but with significantly wider margins (64px+) than standard interfaces to create a "frame" effect around the content. 

Spacing follows a strict 8px scale, but is applied aggressively. Elements are never cramped; vertical rhythm is maintained through large section gaps (128px) to allow the "Climate/Organic" imagery to breathe. Use "Safe Areas" around text blocks to prevent content from feeling crowded by the extreme corner radii of the containers.

## Elevation & Depth

Depth in this design system is achieved through **Subtle Stratification** rather than heavy shadows.

1.  **Backdrop Blurs:** High-level containers (like navigation bars or floating cards) should use a `20px` to `40px` backdrop blur with a semi-transparent white or cream fill (`opacity: 70-80%`).
2.  **Cloud Shadows:** Where depth is required, use "Cloud Shadows"—ultra-diffused, large-radius shadows (Blur: 40px, Spread: -5px) with very low opacity (3-5%) and a slight tint of the primary green or beige to avoid "dirty" grey shadows.
3.  **Low-Contrast Borders:** Soften the distinction between layers using thin 1px borders in a color only slightly darker than the background (e.g., #E0EADA).

## Shapes

The shape language is the most defining feature of this design system. It uses **Extreme Roundedness** to evoke a sense of organic growth and friendliness.

- **Main Containers:** All primary cards and sections must use a corner radius of at least `32px`. 
- **Interactive Elements:** Buttons and tags should be fully pill-shaped.
- **Visual Continuity:** Images should follow the same `32px` radius. When cards are nested, use "concentric rounding" (outer radius = inner radius + padding) to maintain geometric harmony.

## Components

- **Buttons:** Large, pill-shaped, and tactile. Primary buttons use the Young Rice Green (#C5E1A5) with a subtle "squishy" micro-interaction on hover.
- **Glass Cards:** Used for product highlights. Features a subtle inner glow (white 1px stroke) and a soft backdrop blur to separate the content from the natural lifestyle photography behind it.
- **Inputs:** Minimalist fields with a thick `2px` bottom border or a fully rounded container with a light cream background. Focus states transition smoothly to the primary green.
- **Climate Badges:** Small, pill-shaped tags used to denote "Organic," "Climate Positive," or "Carbon Neutral" metrics. These should use the secondary green with refined Inter typography.
- **Imagery:** Lifestyle shots should be integrated using large-scale masks with 32px corners. Light should be natural and directional, with compositions following a minimalist, "editorial" layout.