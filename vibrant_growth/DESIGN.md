---
name: Vibrant Growth
colors:
  surface: '#f9f9fc'
  surface-dim: '#dadadc'
  surface-bright: '#f9f9fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f6'
  surface-container: '#eeeef0'
  surface-container-high: '#e8e8ea'
  surface-container-highest: '#e2e2e5'
  on-surface: '#1a1c1e'
  on-surface-variant: '#404940'
  inverse-surface: '#2f3133'
  inverse-on-surface: '#f0f0f3'
  outline: '#707a6f'
  outline-variant: '#bfc9bd'
  surface-tint: '#196c37'
  primary: '#00441d'
  on-primary: '#ffffff'
  primary-container: '#005e2b'
  on-primary-container: '#85d595'
  inverse-primary: '#88d898'
  secondary: '#226d00'
  on-secondary: '#ffffff'
  secondary-container: '#9ff979'
  on-secondary-container: '#257400'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cca830'
  on-tertiary-container: '#4f3e00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a3f5b2'
  primary-fixed-dim: '#88d898'
  on-primary-fixed: '#00210b'
  on-primary-fixed-variant: '#005225'
  secondary-fixed: '#9ff979'
  secondary-fixed-dim: '#84db60'
  on-secondary-fixed: '#052100'
  on-secondary-fixed-variant: '#185200'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#f9f9fc'
  on-background: '#1a1c1e'
  surface-variant: '#e2e2e5'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  title-md:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
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
  lg: 40px
  xl: 64px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style

This design system is built to bridge the gap between institutional trust and the energetic aspiration of a modern fintech user. The visual language is rooted in **Modern Corporate** aesthetics but infused with a high-energy color palette that evokes a sense of momentum and "winning." 

The emotional goal is to make financial management feel like a rewarding community experience rather than a cold utility. We achieve this through:
- **Optimistic Modernism:** A clean, structured layout that feels secure, paired with vibrant greens that suggest growth.
- **Value Accents:** The strategic use of gold to highlight rewards, wins, and high-value opportunities.
- **Human-Centric Tech:** Imagery that balances high-end hardware with genuine human smiles, reinforcing the idea that technology serves the community.

## Colors

The palette is a tiered green system designed for maximum brand recognition and functional clarity.

- **Primary (Deep Green):** Used for primary navigation, core branding, and "Trust" elements like headers and heavy-weighted buttons.
- **Secondary (Bright Green):** The "Energy" color. Used for success states, growth indicators, and primary call-to-actions that require high visibility.
- **Tertiary (Gold):** Reserved specifically for "Winning" moments—referral rewards, investment gains, premium badges, and high-value tech product highlights.
- **Neutrals:** We utilize a "Warm Slate" for text and a very soft "Mint-tinted Off-White" for backgrounds to reduce eye strain and maintain a friendly atmosphere.

## Typography

This design system employs a dual-font strategy to balance character with readability.

- **Headlines (Hanken Grotesk):** A sharp, contemporary sans-serif that provides a tech-forward edge. Use it for all display text and major section titles to establish brand authority.
- **Body & Interface (Manrope):** A refined, balanced sans-serif chosen for its exceptional legibility in data-dense environments. Its geometric roots complement the headlines while offering a softer, more accessible feel for long-form reading.

**Scaling:** On mobile devices, headline sizes should reduce by 15-20% to maintain a clean visual hierarchy without overwhelming the viewport.

## Layout & Spacing

The layout philosophy follows a **Fixed-Fluid Hybrid** model. On desktop, content is contained within a 1280px max-width 12-column grid to ensure readability. On mobile, the system transitions to a fluid 4-column grid.

- **Generous Whitespace:** We use a base-8 spacing scale. Larger gaps (40px+) are encouraged between major sections to emphasize a premium, "uncluttered" feel.
- **Rhythm:** Elements within a card or group should use tight spacing (8px-12px), while the space between cards should be significantly larger (24px+) to create distinct visual buckets of information.

## Elevation & Depth

We utilize **Tonal Layers** combined with **Ambient Shadows** to create a structured sense of depth.

- **Surface Levels:** The primary background is the lowest level. Content sits on white cards (Surface-1). Contextual menus or modals sit on Surface-2.
- **Shadow Profile:** Shadows should be extremely soft, using a deep green tint (`rgba(0, 94, 43, 0.08)`) rather than pure black. This keeps the interface feeling "organic" and tied to the brand colors.
- **Interaction Depth:** Buttons should use a subtle 2px vertical offset on hover to simulate "pressing" into the screen, reinforcing the tactile nature of the platform.

## Shapes

The shape language of this design system is **Rounded (Level 2)**. This specific curvature is designed to feel friendly and modern without appearing too casual or "bubbly."

- **Standard Elements:** 0.5rem (8px) for buttons and input fields.
- **Container Elements:** 1rem (16px) for cards, banners, and feature blocks.
- **Promotional Elements:** 1.5rem (24px) for high-value "Win" notifications or community spotlight cards to make them stand out from the standard utility UI.
- **Icons:** Should always feature rounded terminals and corners to match the UI container style.

## Components

### Buttons
- **Primary:** Deep Green background with white text. High emphasis.
- **Secondary:** Bright Green background with Deep Green text. Used for growth-related actions.
- **Winning/Gold:** Gold background with Deep Green text. Reserved for claiming rewards or "cashing out."

### Cards
Cards should be white with a 1px border in a very light grey-green (`#E0EADF`) and a subtle ambient shadow. Use 1rem rounded corners.

### Input Fields
Inputs use a clean, 1px outline. When focused, the border transitions to Bright Green with a soft glow (2px spread). Labels are always visible above the field in `label-sm` style.

### Progress Bars & Gauges
As a fintech platform focused on growth, progress indicators should use a gradient from Deep Green to Bright Green to symbolize movement toward a goal.

### Community Snippets
Small, circular avatars (reminiscent of the dots in the logo) should be used in "stack" formations to show community participation in specific "pots" or investment groups.