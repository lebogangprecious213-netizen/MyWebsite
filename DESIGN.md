---
name: Luminous Editorial Glam
colors:
  surface: '#fff8f7'
  surface-dim: '#e1d8d7'
  surface-bright: '#fff8f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf1f1'
  surface-container: '#f5eceb'
  surface-container-high: '#efe6e6'
  surface-container-highest: '#e9e0e0'
  on-surface: '#1f1b1b'
  on-surface-variant: '#50453b'
  inverse-surface: '#342f2f'
  inverse-on-surface: '#f8efee'
  outline: '#82756a'
  outline-variant: '#d4c4b7'
  surface-tint: '#7d562d'
  primary: '#7d562d'
  on-primary: '#ffffff'
  primary-container: '#d4a373'
  on-primary-container: '#5b3912'
  inverse-primary: '#f0bd8b'
  secondary: '#a03b56'
  on-secondary: '#ffffff'
  secondary-container: '#ff86a1'
  on-secondary-container: '#771b37'
  tertiary: '#7c5357'
  on-tertiary: '#ffffff'
  tertiary-container: '#d2a0a4'
  on-tertiary-container: '#5b363a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcbd'
  primary-fixed-dim: '#f0bd8b'
  on-primary-fixed: '#2c1600'
  on-primary-fixed-variant: '#623f18'
  secondary-fixed: '#ffd9df'
  secondary-fixed-dim: '#ffb1c0'
  on-secondary-fixed: '#3f0016'
  on-secondary-fixed-variant: '#81233f'
  tertiary-fixed: '#ffdadc'
  tertiary-fixed-dim: '#eeb9bd'
  on-tertiary-fixed: '#301216'
  on-tertiary-fixed-variant: '#623c40'
  background: '#fff8f7'
  on-background: '#1f1b1b'
  surface-variant: '#e9e0e0'
typography:
  display-hero:
    fontFamily: Newsreader
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Newsreader
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Newsreader
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Newsreader
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.06em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.1em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses modern glam and color cosmetics through a balance of playful luxury, tactile radiance, and high-fashion editorial rigor. Built for beauty enthusiasts, trendsetters, and luxury cosmetics consumers, the interface must feel warm, luminous, and tactile—evoking the sensory indulgence of opening a bespoke lacquer compact or feeling a silk-finish highlighter catch the light.

The design movement synthesizes **Modern Editorial Glam** and **Luminous Glassmorphism**:
- Generous, airy negative space inspired by luxury fashion lookbooks.
- Frosted, pearlescent glass cards that softly catch backdrop warmth without clouding readability.
- Warm champagne gold highlights and deep berry velvet anchors to ground dynamic cosmetic swatches.
- High-contrast typography marrying a timeless, razor-sharp editorial serif with a buoyant, approachable geometric sans.

## Colors

The color palette centers on warm radiance, tactile pigments, and editorial depth:

- **Primary (`#D4A373` - Champagne Gold):** Used for high-impact call-to-actions, radiant borders, shimmer indicators, and key checkout moments. Radiates warmth and prestige.
- **Secondary (`#7B1E3A` - Deep Berry Noir):** Provides authoritative contrast for editorial subheadings, luxury badges, active state indicators, and dramatic cosmetic accents.
- **Tertiary (`#E8B4B8` - Rose Quartz Shimmer):** A delicate, luminous blush used for pill tags, seasonal highlights, swatch containers, and soft ambient glows.
- **Neutral (`#211D1D` - Black Velvet Noir):** Anchors high-fashion typography, deep contrast buttons, and primary structural glyphs, steering away from stark digital grays.
- **Surface & Backgrounds:** The base canvas operates on warm alabaster and milk-glass hues (`#FAF7F5` to `#F4EDE8`), avoiding sterile clinical whites to preserve a warm boudoir ambiance.

## Typography

The typography couples the editorial authority of high-fashion print (`Newsreader`) with the modern, friendly readability of `Plus Jakarta Sans`.

- **Headlines (`Newsreader`):** Applied with deliberate italic flourishes on hero titles and product tier introductions to echo high-end editorial styling. Never condensed; always set with optical tracking and generous line heights.
- **Body & Labels (`Plus Jakarta Sans`):** Offers a crisp, human geometry ensuring ingredient decks, shade names, customer reviews, and cart drawers remain effortless to read.
- **Caps & Micro-copy:** Labels (`label-md`, `label-sm`) default to uppercase styling with wider letter spacing (`0.06em` to `0.1em`) for luxury cosmetic categorization (e.g., "SATIN FINISH", "CLEAN BEAUTY").

## Layout & Spacing

The layout model balances an asymmetrical, magazine-style flow with rigorous e-commerce conversion grids.

- **Desktop (1024px+):** 12-column responsive fluid grid constrained to a maximum width of 1440px. Gutters maintain `1.5rem` (24px) with expansive outer canvas margins of `3rem` (48px) to emphasize bespoke exclusivity.
- **Tablet (768px - 1023px):** 8-column grid with `1.5rem` gutters and `2rem` margins. Complex product comparison tables collapse into layered horizontal swiping drawers.
- **Mobile (<768px):** 4-column layout with `1rem` gutters and `1.25rem` margins. Product grids convert cleanly to 2-column or full-width editorial carousels with peek margins.
- **Rhythm:** Macro vertical spacing relies on `space-xl` (40px) and double-steps (`5rem`) between editorial showcases, giving makeup collections ample breathing room.

## Elevation & Depth

Visual hierarchy rejects harsh digital drop shadows in favor of **pearlescent translucence and champagne-tinted ambient glow**.

1. **Frosted Base Layer (Elevation 1):** Floating navigation bars and product badges use `backdrop-filter: blur(16px)` with a 75% opaque warm-milk fill (`rgba(250, 247, 245, 0.75)`) bordered by an ultra-fine `0.5px` border in translucent rose quartz (`rgba(232, 180, 184, 0.4)`).
2. **Elevated Product Cards (Elevation 2):** Feature soft, dual-tier diffusion:
   - Primary: `0 10px 30px -10px rgba(123, 30, 58, 0.06)` (a faint berry haze).
   - Ambient: `0 2px 12px 0 rgba(212, 163, 115, 0.08)` (warm golden contact reflection).
3. **Modal & Floating Checkout Overlays (Elevation 3):** Grounded with a deep, diffused drop shadow: `0 24px 48px -12px rgba(33, 29, 29, 0.14)`, enclosed in a soft metallic champagne rim highlight.

## Shapes

The shape vocabulary is defined by **Pill-shaped Fluidity (`roundedness: 3`)** paired with organic cosmetic geometry.

- **Buttons & Badges:** Use full pill radiuses (`rounded-full` / `9999px`) reflecting lipstick bullets, smooth cosmetic compacts, and cream balm silhouettes.
- **Product Cards & Surfaces:** Scaled to `rounded-xl` (2rem / 32px on desktop; 1.5rem / 24px on mobile) producing a friendly, sculpted hand-feel.
- **Form Controls:** Text inputs and quantity steppers mirror soft pill or generously rounded contours (`1rem`), eliminating sharp clinical corners across the customer journey.

## Components

### Buttons
- **Primary (Glow Gold):** Solid Champagne Gold (`#D4A373`) background with crisp Velvet Noir (`#211D1D`) text, fully pill-shaped. Hover triggers an ambient golden halo: `box-shadow: 0 4px 20px rgba(212, 163, 115, 0.45)`.
- **Secondary (Velvet Noir):** Deep Noir background with White/Alabaster text; ideal for "Add to Bag" conversion states.
- **Tertiary (Ghost Rose):** Transparent fill with a `1px` Rose Quartz (`#E8B4B8`) border and Berry Noir (`#7B1E3A`) typography.

### Chips & Badges
- **Pill Badges:** Capsule form with `label-sm` tracking. Formats include translucent rose quartz fills for benefits ("HYDRATING", "VEGAN") and metallic champagne fills for editorial markers ("AWARD WINNER", "LIMITED EDITION").

### Product Cards
- Glass-like, alabaster surfaces (`#FAF7F5` with `0.5px` border in `#E8B4B8`/20%). Cards incorporate an integrated shade selector (circular swatches with concentric gold active rings) and instant hover image cross-fades showing pigment swatches on real skin tones.

### Input Fields
- Fully rounded (`1rem`), warm-tinted cream backgrounds (`#F4EDE8`) with subtle interior inset tinting. Focus states illuminate the border to Champagne Gold (`#D4A373`) with a soft matching ambient ring.

### Checkboxes & Radio Buttons
- Radios feature circular pill targets that transition to a solid Berry Noir core enclosed by a shimmering gold ring. Checkboxes use smooth rounded squares (`rounded-md`) with custom gold tick glyphs.

### Specialized Beauty Components
- **Shade Swatch Carousel:** Circular buttons (`36px`) featuring dynamic multi-tone pigment pours, shimmering glitter overlays, and concentric gold selection rings.
- **Formula Texture Zoom:** Circular lens preview with subtle glass-edge refraction revealing powder, gloss, and cream finishes in ultra-high resolution.