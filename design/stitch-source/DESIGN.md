---
name: Precision Minimalist Mobile
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#3d4a43'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#6d7a72'
  outline-variant: '#bccac1'
  surface-tint: '#006c4d'
  primary: '#006c4d'
  on-primary: '#ffffff'
  primary-container: '#3db88b'
  on-primary-container: '#00432e'
  inverse-primary: '#65dcac'
  secondary: '#3d6754'
  on-secondary: '#ffffff'
  secondary-container: '#bfedd5'
  on-secondary-container: '#436d5a'
  tertiary: '#9e403e'
  on-tertiary: '#ffffff'
  tertiary-container: '#f5837f'
  on-tertiary-container: '#6e1c1e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#83f8c7'
  primary-fixed-dim: '#65dcac'
  on-primary-fixed: '#002115'
  on-primary-fixed-variant: '#005139'
  secondary-fixed: '#bfedd5'
  secondary-fixed-dim: '#a4d0b9'
  on-secondary-fixed: '#002115'
  on-secondary-fixed-variant: '#254e3d'
  tertiary-fixed: '#ffdad7'
  tertiary-fixed-dim: '#ffb3af'
  on-tertiary-fixed: '#410005'
  on-tertiary-fixed-variant: '#7f2929'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.03em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1.5rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 2rem
  space-xl: 3rem
---

## Brand & Style

The design system embodies utilitarian restraint, high operational clarity, and immediate cognitive relief for job seekers. Stripped of decorative cards, illustrative filler, shadows, and gradients, the interface behaves like an exacting analytical instrument.

Key attributes:
- **Aesthetic Direction:** Extreme functional minimalism. Pure flat design anchored by intentional void space and structural boundaries.
- **Audience:** Job applicants, hiring candidates, and professionals reviewing career documents under stress who need instantaneous, unambiguous document intelligence.
- **Emotional Response:** Confidence, efficiency, and clinical precision. The visual quietness removes anxiety, allowing content evaluation and actionable metrics to command attention.
- **View Density:** Strictly restrained views with a maximum of 3–5 interactive or structural elements per screen view, ensuring focused decision loops.

## Colors

The palette is rigorously constrained to a single active emerald green against pristine white canvas layers, structured exclusively by neutral carbon values.

### Color Hierarchy
- **Canvas (`#FFFFFF`):** Base canvas applied to 100% of application backgrounds. Gradients, tints, and off-white backdrops are prohibited.
- **Primary Brand & Interactive (`#3DB88B`):** Applied to the signature top application bar, primary action buttons, active toggles, and critical score callouts.
- **Primary Text (`#1A1A1A`):** Deep carbon black used for high-contrast headlines, key data scores, and critical inputs.
- **Secondary Text (`#2D3748`):** Subdued slate used for labels, field descriptors, meta attributes, and parsing body copy.
- **Border & Rule Neutral (`#E2E8F0`):** Hairline structural borders (`1px`) for inputs, divider lines, and discrete element bounding without drop shadows.
- **Secondary Border / Hairline (`#EEEEEE`):** Secondary low-contrast row separations within minimalist lists.
- **Inverse Neutral (`#FFFFFF`):** High-legibility text and glyphs rendered over `#3DB88B` solid fills.

## Typography

Type scale is built entirely around `Inter` for immediate legibility and geometric balance across vertical mobile screen geometries.

- **Scale Approach:** Large, declarative headlines paired with uncluttered body text. Tight tracking (`letter-spacing`) on display sizes enhances structural gravity.
- **Hierarchy:** Primary headings communicate state and metric outcomes directly; labels guide data entry without adding graphic ornamentation.
- **Formatting:** Monospace numbers (`tnum`) enabled for tabular data, score counters, and character limits to preserve alignment in strictly flat views.

## Layout & Spacing

Designed specifically for iPhone portrait orientation with an emphasis on breathing room and strict limits on visual density.

- **Grid & Flow:** Single-column fluid vertical flow locked between outer canvas margins of `24px` (`1.5rem`).
- **Whitespace Principle:** Layouts enforce wide separation between functional nodes. Empty space functions as the primary visual organizer, replacing cards and elevated containers.
- **Screen Budget:** A strict ceiling of 5 primary elements per view viewport (e.g., Header Bar, Metric Callout, Key Issue List, Primary Action Button, Sub-action Link).
- **Vertical Rhythm:** Generous spacing (`space-lg` to `space-xl`) between distinct functional steps, giving the app an open, uncluttered cadence.

## Elevation & Depth

This system operates on a zero-elevation paradigm:
- **No Shadows:** `box-shadow`, `drop-shadow`, and skeuomorphic inner bevels are strictly forbidden across all screen components.
- **Flat Spatial Hierarchy:** Layer separation is achieved solely through crisp `1px` lines (`#E2E8F0`) and solid color fills against `#FFFFFF`.
- **Z-Index Layering:** The only elevated structural element is the fixed top header bar (`#3DB88B`), which terminates cleanly along a rounded bottom margin without under-shadows or translucent backdrop blur.

## Shapes

The geometric identity balances hard spatial edges with soft interactive points:
- **Buttons and Inputs:** Uniform `8px` (`0.5rem`) corner radii, establishing an approachable yet disciplined contour.
- **Top App Header:** Bottom corners utilize `16px` (`1rem`) curvature, visually delineating the application anchor against the flat white viewport.
- **Divider Rules:** Sharp, unrounded hairline segments spanning the horizontal grid width.

## Components

### Header Bar
- **Geometry & Fill:** Full-width container colored `#3DB88B` extending through the top safe area, terminated at the bottom with `16px` rounded corners.
- **Content:** Single centered or leading title set in `headline-sm` with `#FFFFFF` weight `600`, flanked only by essential flat icons in pure `#FFFFFF`.
- **Effects:** Completely opaque; zero shadow, border, or gradient.

### Buttons
- **Primary Button:** Height `52px`, background `#3DB88B`, shape `8px` rounded-rectangle. Text is `#FFFFFF`, bold `label-lg`, center-aligned.
- **Secondary / Ghost Button:** Height `52px`, background `transparent`, flat `1px` solid border in `#3DB88B`. Text is `#3DB88B`, bold `label-lg`.
- **States:** Active/Pressed shifts background to `#329C75` instantly with no depth depression or scale alteration. Disabled uses `#FFFFFF` canvas with `#E2E8F0` border and `#2D3748` (40% opacity) text.

### Input Fields
- **Appearance:** Height `48px`, background `#FFFFFF`, bordered by flat `1px` `#E2E8F0`. Corner radius `8px`.
- **Text:** Input value rendered in `body-lg` `#1A1A1A`. Placeholder text rendered in `#2D3748` at 60% opacity.
- **Active State:** Focus transitions border color cleanly to `#3DB88B` (`1.5px` border width). No glowing halos or ring offsets.

### Lists & Dividers
- **Dividers:** Minimalist horizontal borders `1px` solid `#E2E8F0` or `#EEEEEE`.
- **List Items:** Directly laid on `#FFFFFF` without containing cards or drop surfaces. Padding of `16px` vertically.
- **Metadata:** Key scores or feedback points presented inline with primary `#1A1A1A` text and `#2D3748` supporting labels.

### Checkboxes & Radios
- **Structure:** Flat `20px × 20px` square (checkbox, `4px` radius) or circle (radio).
- **Unchecked:** Flat `1.5px` border `#E2E8F0`, background `#FFFFFF`.
- **Checked:** Solid `#3DB88B` fill with crisp white indicator glyph. Zero glow.

### Score & Status Display
- **Format:** Giant typographic display (e.g., `headline-lg` 30px or custom numerical readout) in `#3DB88B` or `#1A1A1A`, positioned freely within white space without enclosing badges or circular meters.