---
name: Glow & Wax
colors:
  surface: '#fef9f0'
  surface-dim: '#ded9d1'
  surface-bright: '#fef9f0'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f3ea'
  surface-container: '#f2ede4'
  surface-container-high: '#ece8df'
  surface-container-highest: '#e7e2d9'
  on-surface: '#1d1c16'
  on-surface-variant: '#4e4639'
  inverse-surface: '#32302b'
  inverse-on-surface: '#f5f0e7'
  outline: '#7f7667'
  outline-variant: '#d1c5b4'
  surface-tint: '#775a1a'
  primary: '#775a1a'
  on-primary: '#ffffff'
  primary-container: '#c6a15b'
  on-primary-container: '#4f3800'
  inverse-primary: '#e9c178'
  secondary: '#795551'
  on-secondary: '#ffffff'
  secondary-container: '#ffcfc9'
  on-secondary-container: '#7a5652'
  tertiary: '#695b57'
  on-tertiary: '#ffffff'
  tertiary-container: '#b4a39e'
  on-tertiary-container: '#453936'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdea5'
  primary-fixed-dim: '#e9c178'
  on-primary-fixed: '#271900'
  on-primary-fixed-variant: '#5d4202'
  secondary-fixed: '#ffdad6'
  secondary-fixed-dim: '#eabcb6'
  on-secondary-fixed: '#2e1412'
  on-secondary-fixed-variant: '#5f3e3b'
  tertiary-fixed: '#f2ded9'
  tertiary-fixed-dim: '#d5c3bd'
  on-tertiary-fixed: '#231916'
  on-tertiary-fixed-variant: '#514440'
  background: '#fef9f0'
  on-background: '#1d1c16'
  surface-variant: '#e7e2d9'
typography:
  display-hero:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '500'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '500'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 17px
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
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
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
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style

The visual identity embodies warm-lit luxury, artisanal heritage, and intimate sensory indulgence. Designed for an audience with an appreciation for slow living, olfactory art, and tactile interior aesthetics, the experience must evoke the serene atmosphere of golden hour and amber candlelight.

The design movement combines **Minimalist Editorial Luxury** with **Sensory Soft-Touch Tactility**. High-contrast, stately serifs frame editorial vignettes, resting on creamy, illuminated fields. Soft, generous radii cushion the UI elements, counterbalancing the classical typographic structure with modern, organic accessibility. The emotional tone is whisper-quiet, grounded, opulent, and welcoming.

## Colors

The palette draws inspiration from melting beeswax, amber flame illumination, and raw linen paper.

- **Primary (`#C6A15B` - Champagne Gold):** Reserved for prestige focal points, subtle metallic accents, active interactive highlights, rating stars, and refined borders.
- **Secondary (`#B98F8A` - Muted Rose):** Infuses botanical notes, seasonal badges, delicate hover states, and celebratory notices with soft warmth.
- **Tertiary (`#241A17` - Deep Espresso):** Functions as the supreme contrasting anchor for primary buttons, dense editorial headings, and rich, grounding footer modules.
- **Neutral Surface (`#F8F3EA` - Warm Ivory):** The core canvas tone, replacing stark digital white to preserve an organic, atmospheric feel.
- **Neutral Accent (`#EAE3D5` - Warm Taupe Tint):** Provides gentle delineations, pill fills, and quiet secondary containers.

## Typography

The typography establishes an editorial hierarchy through intentional contrast between traditional bookcraft and crisp, contemporary readability.

- **Editorial Headings (`Playfair Display`):** Reserved for product titles, sensory narratives, collection titles, and quote testimonials. It should default to regular and medium weights to preserve delicate line flourishes.
- **Functional Interface (`Plus Jakarta Sans`):** Carries product specifications, burn times, scent pyramids, pricing, checkout flows, and body copy. Its gentle geometric terminals match the rounded aesthetic of the interface.
- **Micro-labels and Overlines:** Styled with `label-sm` or `label-lg`, using uppercase styling and wide tracking (+0.06em to +0.1em) to emulate luxury boutique labeling.

## Layout & Spacing

The layout employs an airy 12-column fluid grid on desktop (max content boundary: 1360px), shifting to an 8-column layout on tablet, and a 4-column layout on mobile.

- **Rhythm:** Generous vertical rhythm prioritizes breathing room, allowing candle photography and olfactory notes to command unhurried focus. Vertical spacing between editorial sections scales dynamically from `4rem` on mobile to `7rem` on desktop.
- **Asymmetric Composition:** Product features combine high-aspect ratio imagery (3:4 or 4:5) alongside offset text columns to simulate the cadence of luxury print magazines.
- **Padding:** Outer page margins maintain a minimum of `1.25rem` on mobile and expand up to `3rem` on desktop screens to avoid edge crowding.

## Elevation & Depth

Elevation eschews deep digital drops in favor of warm ambient luminosity and soft surface layering:

- **Ambient Candlelight Glow:** Layered shadows utilize tinted warm umber tones (`rgba(36, 26, 23, 0.06)` combined with `rgba(198, 161, 91, 0.08)`) with broad blur radii (24px to 48px) to emulate gentle radiance rather than direct vertical sunlight.
- **Tonal Stepping:** Inset and resting cards rely on delicate contrast against `#F8F3EA`, utilizing `#FFFFFF` for primary cards and `#F3ECE0` for nested sub-surfaces.
- **Hairline Framing:** Borders remain crisp at 1px using semi-transparent Champagne Gold (`rgba(198, 161, 91, 0.35)`) or soft warm sand (`rgba(36, 26, 23, 0.08)`), imparting an architectural, framed presentation without heaviness.

## Shapes

With `roundedness: 3`, the design language balances organic softness with tailored discipline:

- **Tags & Floating Actions:** Rendered as full pills (`rounded-full`), conveying tactility and hand-poured candle forms.
- **Interactive Buttons:** Use generous rounding (`1rem` / `rounded-2xl` up to full pill form factor) for an approachable, touch-friendly presence.
- **Cards & Visual Containers:** Utilize `2rem` (`rounded-lg`) to `3rem` (`rounded-xl`) outer corners, softening architectural photography and product displays into smooth, cohesive frames.

## Components

### Buttons
- **Primary Action:** Solid Deep Espresso (`#241A17`) with Warm Ivory (`#F8F3EA`) text, 1rem border radius or pill, and subtle Champagne Gold focus ring. On hover, background lightens slightly to warm charcoal with a subtle scale transformation (1.015).
- **Secondary Action:** Transparent base framed by a 1px Champagne Gold border (`#C6A15B`), text in `#241A17`. Hover applies a 6% wash of Champagne Gold.
- **Tertiary / Text Link:** Understated uppercase `label-lg` with an offset underline in Champagne Gold that transitions smoothly from 0% to 100% width on hover.

### Scent Note Chips & Badges
- Compact pill forms (`rounded-full`) filled with `#F3ECE0` and framed with 1px `rgba(198, 161, 91, 0.25)`.
- Typographic style is set to `label-sm` with Deep Espresso copy.
- Active or filtered state transitions to solid Champagne Gold with Warm Ivory typography.

### Form Inputs & Selectors
- Background: `#FFFFFF` or translucent `#FAF6EF`.
- Border: 1px continuous solid border in `rgba(36, 26, 23, 0.15)`, transitioning to `#C6A15B` with an ambient glow on focus.
- Floating labels set in `Plus Jakarta Sans` with relaxed vertical padding (`1rem` top and bottom) for high touch fidelity.

### Product & Editorial Cards
- Background: `#FFFFFF` resting on `#F8F3EA`.
- Corners: `rounded-2xl` (desktop: `2rem`), subtle warm ambient drop-shadow.
- Card Footer: Scent profile indicators (Top, Heart, Base notes) structured with clean vertical hairline dividers.
- Hover State: Candle imagery subtly cross-fades into lifestyle/ambiance photography with a +4px upward float.

### Olfactory Accord Pyramids (Domain-Specific)
- Layered horizontal pill strips representing Top, Heart, and Base notes.
- Uses subtle gradient fills transitioning from Warm Ivory to Muted Rose to Deep Espresso to visually represent scent longevity and depth.