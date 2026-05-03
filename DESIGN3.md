---
name: Climate Harvest
colors:
  surface: '#f9f9f7'
  surface-dim: '#dadad8'
  surface-bright: '#f9f9f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f4f1'
  surface-container: '#eeeeec'
  surface-container-high: '#e8e8e6'
  surface-container-highest: '#e2e3e0'
  on-surface: '#1a1c1b'
  on-surface-variant: '#414943'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f1ef'
  outline: '#717973'
  outline-variant: '#c1c8c1'
  surface-tint: '#3d6751'
  primary: '#254f3a'
  on-primary: '#ffffff'
  primary-container: '#3d6751'
  on-primary-container: '#b5e3c8'
  inverse-primary: '#a3d1b6'
  secondary: '#59605d'
  on-secondary: '#ffffff'
  secondary-container: '#dae1dd'
  on-secondary-container: '#5d6461'
  tertiary: '#444746'
  on-tertiary: '#ffffff'
  tertiary-container: '#5c5f5e'
  on-tertiary-container: '#d7d9d7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bfedd1'
  primary-fixed-dim: '#a3d1b6'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#254f3a'
  secondary-fixed: '#dde4e0'
  secondary-fixed-dim: '#c1c8c4'
  on-secondary-fixed: '#161d1b'
  on-secondary-fixed-variant: '#414846'
  tertiary-fixed: '#e1e3e1'
  tertiary-fixed-dim: '#c5c7c5'
  on-tertiary-fixed: '#191c1b'
  on-tertiary-fixed-variant: '#444746'
  background: '#f9f9f7'
  on-background: '#1a1c1b'
  surface-variant: '#e2e3e0'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h1:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
  h2:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.3'
  h3:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: '1.4'
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
  caption:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.01em
  button:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1200px
  gutter: 24px
---

## Brand & Style

The design system is anchored in the concept of "Pure Sustainability." It reflects a premium agricultural brand that bridges the gap between traditional farming and modern climate consciousness. The aesthetic is **Modern Minimalism**, characterized by expansive white space, a rhythmic use of organic greens, and an editorial-grade clarity.

The interface should evoke a sense of serenity, transparency, and vitality. By stripping away unnecessary decorative elements, the focus remains entirely on the product's origin and health benefits. The visual language is soft yet structured, communicating a trustworthy, high-end experience for health-conscious consumers.

## Colors

The palette is centered on a deep, sophisticated **Forest Green (#3d6751)** that represents the authority and stability of the KTNN brand. This is balanced by a secondary **Pastel Mint (#eef5f1)** used for large surface areas to provide breathability and a fresh, "climate-controlled" feel.

- **Primary:** Used for key brand moments, primary buttons, and active states.
- **Surface/Secondary:** Used for container backgrounds to distinguish sections without harsh lines.
- **Background:** Pure White (#FFFFFF) is the dominant color to maintain a minimalist and clean aesthetic.
- **Text:** A high-contrast Charcoal (#1a1c1b) is used for body text to ensure maximum readability against light backgrounds.

## Typography

This design system utilizes a dual-font strategy to balance character with functionality. 

**Plus Jakarta Sans** is the voice of the brand, used for all headlines and display titles. Its soft curves and optimistic geometry align with the "climate-friendly" narrative. **Inter** provides a utilitarian contrast for all body copy and UI labels, ensuring that complex nutritional or agricultural data remains highly legible at any size. 

Line heights are intentionally generous to reinforce the airy, minimalist feel of the brand.

## Layout & Spacing

The layout follows a **Fixed Grid** system for desktop (12 columns) and a fluid model for mobile. The philosophy is "Space over Borders"—using distance rather than lines to separate content. 

Margins are wide to prevent the UI from feeling cramped. Vertical rhythm is established using a base-8 increment, with significant "breathing gaps" (XL spacing) between major sections to emphasize the premium positioning of the product.

## Elevation & Depth

To achieve the "Cloud-Shadow" effect, this design system avoids heavy, dark shadows in favor of highly diffused, low-opacity ambient occlusion. 

- **Cloud Shadow:** `0px 20px 40px rgba(61, 103, 81, 0.08)`. The shadow is slightly tinted with the primary green color to make it feel organic and integrated with the environment rather than a sterile grey.
- **Layers:** Most components sit on the base surface. Only floating elements or "hero cards" use the cloud shadow to denote importance. 
- **Glassmorphism:** Subtle use of backdrop blurs (20px) on navigation bars maintains the sense of transparency and light.

## Shapes

The shape language is defined by "Large Softness." By using **rounded-xl (1.5rem)** and **rounded-2xl (2rem)** as the standard, the UI feels approachable and organic, mimicking shapes found in nature rather than the sharp angles of traditional industrial tech.

Containers use the largest radius (24px+), while interactive elements like buttons use a slightly smaller radius or full "pill" shapes to differentiate themselves as clickable objects.

## Components

- **Buttons:** Primary buttons are solid #3d6751 with white text, featuring a pill-shaped radius. Secondary buttons use the Pastel Green background with the primary green text.
- **Cards:** White background with a soft `2xl` corner radius and a "Cloud Shadow." Cards should have generous internal padding (32px) to keep content centered and focused.
- **Inputs:** Minimalist style with a subtle 1px border in a pale green-grey. Upon focus, the border transitions to the primary green with a soft outer glow.
- **Eco-Badges:** Small, rounded-full chips using the pastel green background. These are used to highlight "Organic," "Low Carbon," or "Heart Healthy" traits.
- **Progress Indicators:** Used for sustainability metrics (e.g., water saved). Use smooth, rounded bars in the primary color with soft, tinted tracks.
- **Imagery:** Photography should be bright, high-contrast, and focused on natural textures—macro shots of rice grains or wide-angle, misty paddy fields. Use `2xl` rounded corners for all embedded images.