---
name: Climate-Positive Minimalist
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#414943'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#717973'
  outline-variant: '#c0c9c1'
  surface-tint: '#3a674f'
  primary: '#14422d'
  on-primary: '#ffffff'
  primary-container: '#2d5a43'
  on-primary-container: '#9fcfb2'
  inverse-primary: '#a1d1b4'
  secondary: '#56615c'
  on-secondary: '#ffffff'
  secondary-container: '#dae5df'
  on-secondary-container: '#5c6762'
  tertiary: '#1e4132'
  on-tertiary: '#ffffff'
  tertiary-container: '#355848'
  on-tertiary-container: '#a6cdb8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bceecf'
  primary-fixed-dim: '#a1d1b4'
  on-primary-fixed: '#002112'
  on-primary-fixed-variant: '#224f39'
  secondary-fixed: '#dae5df'
  secondary-fixed-dim: '#bec9c3'
  on-secondary-fixed: '#141e1a'
  on-secondary-fixed-variant: '#3f4945'
  tertiary-fixed: '#c4ebd6'
  tertiary-fixed-dim: '#a9cfbb'
  on-tertiary-fixed: '#002115'
  on-tertiary-fixed-variant: '#2b4e3e'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  section-gap: 120px
---

## Brand & Style

The design system is anchored in the concept of "Cinematic Sustainability." It bridges the gap between high-end luxury and environmental consciousness. The visual narrative is ethereal and airy, evoking the feeling of a sun-drenched, mist-covered rice paddy at dawn. 

The aesthetic is rooted in **Minimalism** and **Glassmorphism**. By prioritizing expansive white space and high-quality atmospheric imagery, the system communicates transparency and purity—core values of a climate-positive brand. It avoids the "earthy" cliches of traditional organic brands, instead opting for a sophisticated, professional digital presence that feels both futuristic and grounded in nature.

## Colors

The palette for this design system is a sophisticated interpretation of "Rice and Earth." 

- **Primary:** A deep, forest green used sparingly for high-contrast elements and critical calls to action, representing the strength of the ecosystem.
- **Secondary:** A soft, mint-tinted pastel green that serves as the primary background wash for sections, providing a gentle alternative to stark white.
- **Tertiary:** A mid-tone sage used for accents, iconography, and subtle UI cues.
- **Neutral:** A foundation of pure white to maintain the high-end, clean minimalist aesthetic.

The color system relies on low-saturation transitions to maintain a "cinematic" look, avoiding jarring vibrations between hues.

## Typography

This design system utilizes a dual-font strategy to balance character with utility. 

**Plus Jakarta Sans** is used for headings to inject a modern, slightly geometric personality. At larger scales (Display XL/LG), tight letter-spacing is applied to create a "editorial" feel suitable for high-end product photography.

**Inter** is utilized for all body copy and UI labels. Its neutral, highly legible nature ensures that complex sustainability data or product descriptions remain clear and professional. Labels utilize a slight tracking increase and uppercase styling to provide a distinct hierarchy against body text.

## Layout & Spacing

The layout philosophy follows a **Fixed-Fluid Hybrid** model. Content is contained within a 1280px maximum width to ensure readability on large cinematic displays, while the internal grid is a 12-column fluid system.

The rhythm is intentionally spacious. Large vertical gaps (120px+) between sections allow the product story to breathe, emphasizing the "minimalist" brand pillar. On mobile, the system shifts to a single-column layout with generous internal padding to maintain the premium feel without crowding the small screen.

## Elevation & Depth

Depth in this design system is achieved through two primary techniques: **Glassmorphism** and **Ambient Tints.**

1.  **Headers and Overlays:** Use a "Frosted Glass" effect. This involves a high-opacity backdrop blur (20px-30px) combined with a 60% translucent white fill. A very thin, 1px semi-transparent white border defines the edge of the glass.
2.  **Product Cards:** Instead of traditional grey shadows, cards use "Ambient Elevations." These are extra-diffused shadows (30px-40px blur) with a very low opacity tint derived from the Primary Green color (#2D5A43 at 5% opacity). This creates a soft, lifted effect that feels more natural and organic than standard drop shadows.

## Shapes

The shape language is refined and approachable. A `Rounded` (0.5rem) base is applied to standard UI elements like input fields and buttons. 

For larger containers, such as product feature cards or image carousels, `rounded-xl` (1.5rem) is used to soften the composition and mirror the organic shapes found in nature. Interactive elements should never be sharp, as the brand seeks to evoke a "soft" environmental footprint.

## Components

### Buttons
Primary buttons are solid `primary-color` with white text, using a 0.5rem corner radius. Secondary buttons use a ghost style with a 1px `tertiary-color` border. All buttons feature a subtle scale-up transition (1.02x) on hover to enhance the "tactile" feel.

### Chips & Tags
Used for sustainability certifications (e.g., "Carbon Neutral"). These should be pill-shaped with a light `secondary-color` fill and `primary-color` text at the `label-md` typographic scale.

### Input Fields
Inputs are minimalist: a soft grey-green bottom border that transforms into a full `tertiary-color` focus state. Backgrounds are pure white or slightly translucent.

### Cards
Cards are the primary storytelling vehicle. They utilize the "Ambient Elevation" shadow and `rounded-xl` corners. Imagery within cards should always use a subtle zoom-on-hover effect to maintain the "cinematic" quality.

### Glass Header
The global navigation header is a persistent glassmorphic bar. It should remain fixed to the top of the viewport, blurring the content as it scrolls beneath it to maintain a sense of layered depth.