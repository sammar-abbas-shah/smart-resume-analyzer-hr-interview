---
name: PakTalent AI Design System
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#434655'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#006243'
  on-tertiary: '#ffffff'
  tertiary-container: '#007d57'
  on-tertiary-container: '#bdffdc'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#85f8c4'
  tertiary-fixed-dim: '#68dba9'
  on-tertiary-fixed: '#002114'
  on-tertiary-fixed-variant: '#005137'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1rem
  gutter-tablet: 1.25rem
  margin-tablet: 1.5rem
  gutter-desktop: 1.5rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system drives a next-generation AI-powered HR platform built for mobile-first agility, speed, and absolute clarity. The brand identity balances institutional trust with high-velocity intelligent automation. Designed primarily for HR leaders, recruiters, and enterprise talent managers navigating high-volume pipelines on the move, the visual language prioritizes high information density, razor-sharp legibility, and zero cognitive friction.

The aesthetic fuses **Corporate Modernism** with crisp **High-Contrast Utility**. Rather than relying on gratuitous ornamentation, the UI communicates authority through structural discipline: ultra-refined borders, crisp white elevation planes, punchy deep slate typography, and decisive royal blue focal points that signify AI actions and primary decisions.

## Colors

The palette establishes an immediate optical hierarchy anchored by deep slate contrast against luminous neutral backgrounds.

- **Primary Accent (`#2563EB`)**: Royal Blue serves as the decisive interactive layer—used for key candidate actions, primary triggers, active AI insights, and system-level focus rings. Interactive hover/press states descend to `#1D4ED8`.
- **Secondary / Headings (`#0F172A`)**: Slate 900 provides authoritative high-contrast typography and structural anchors.
- **Muted Text / Subtle Tones (`#64748B`)**: Slate 500 maintains WCAG AA contrast for supporting metadata, form hints, and secondary metrics.
- **Canvas Base (`#F8FAFC`)**: A cool, clinical off-white canvas that eliminates glare while providing contrast for elevated elements.
- **Surfaces (`#FFFFFF`)**: Pristine white for interactive cards, sheets, navigation, and modal dialogues.
- **Borders & Dividers (`#E2E8F0`)**: Crisp 1px structural boundaries defining clear spatial compartments across small screens.
- **Functional Semantics**:
  - Success/Shortlisted: `#059669` (Emerald 600) with `#ECFDF5` container.
  - Pending/Review: `#D97706` (Amber 600) with `#FFFBEB` container.
  - High Risk/Rejected: `#DC2626` (Red 600) with `#FEF2F2` container.
  - AI Suggestion/Match: `#7C3AED` (Violet 600) with `#F5F3FF` container.

## Typography

The design system standardizes exclusively on **Plus Jakarta Sans**. Its sculpted geometric curves and open apertures provide exceptional readability on dense, mobile data interfaces without sacrificing character.

- **Headlines**: Set in Slate 900 (`#0F172A`) with tightened tracking (`-0.01em` to `-0.02em`) to produce authoritative, confident anchors for candidate profiles, requisition metrics, and screen headers.
- **Body**: Uses neutral weights (400) with deliberate line-heights (1.4x–1.5x) to maintain effortless parsing across candidate resumes, feedback summaries, and AI rationale briefs.
- **Labels & Microcopy**: Medium and SemiBold treatments in `label-md` and `label-sm` are deployed for status badges, table data keys, navigation tab indicators, and metadata pills, utilizing uppercase transformations only when applied to strict categorical indicators (`label-sm`).

## Layout & Spacing

A strict **8pt dynamic layout framework** underpins the interface, adapting across mobile, tablet, and compact desktop viewport configurations.

- **Mobile Rhythm (360px – 639px)**: Implements a 4-column fluid layout with an edge margin of `1rem` (16px) and internal column gutters of `1rem`. All touch targets strictly respect a minimum 44px hit-box.
- **Tablet Reflow (640px – 1023px)**: Expands to an 8-column fluid layout with `1.5rem` margins and `1.25rem` gutters. Profile screens split into a 3:5 master-detail view.
- **Desktop/Docked Reflow (1024px+)**: Transitions to a 12-column structured layout capped at a maximum container width of `1280px`, retaining `2rem` outer margins.
- **Vertical Hierarchy**: Spacing between unrelated card groups relies on `space-lg` (24px). Spacing within grouped card modules uses `space-md` (16px). Form elements and compact meta rows leverage `space-xs` (4px) and `space-sm` (8px).

## Elevation & Depth

This design system avoids heavy shadows, maintaining crisp contrast through **low-contrast outlines combined with subtle ambient light diffusion**:

- **Ground Level (Canvas)**: `#F8FAFC`. All primary content sits over this non-reflective base plane.
- **Level 1 (Card & Containers)**: Solid `#FFFFFF` backdrops bound by a hairline 1px border of `#E2E8F0`. Depth is reinforced with an ambient micro-shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.02)`.
- **Level 2 (Popovers, Sticky Headers, Segmented Active States)**: Elevated controls use `#FFFFFF`, a 1px border of `#CBD5E1`, and a directional soft drop: `0 4px 6px -1px rgba(15, 23, 42, 0.07), 0 2px 4px -2px rgba(15, 23, 42, 0.04)`.
- **Level 3 (Modals, Action Drawers, Bottom Sheets)**: Grounded by a dark backdrop filter (`rgba(15, 23, 42, 0.45)` with `backdrop-filter: blur(4px)`). The container utilizes `#FFFFFF` with `0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 8px 10px -6px rgba(15, 23, 42, 0.04)`.

## Shapes

The geometric architecture balances modern ergonomics with high enterprise efficiency. By adhering to **Level 2 roundedness**, standard interface controls feel approachable yet strictly structural.

- **Base Radius (0.5rem / 8px)**: Applied to table cells, inner chips, sub-module badges, and compact interactive badges.
- **Large Radius (1rem / 16px)**: Applied to primary containers, modal sheets, candidate overview cards, and navigation bars.
- **XL Radius (1.5rem / 24px)**: Applied strictly to form inputs, search bars, segmented tab container pills, and floating action prompts.
- **Full Radius (9999px)**: Reserved for numeric counters, status tags, avatars, and quick-filter toggle chips.

## Components

### Buttons
- **Primary**: Solid `#2563EB` background with white text, 12px vertical and 20px horizontal padding, rounded-xl border radius (`1.5rem`), font `label-lg`. Active/Hover descends to `#1D4ED8`. Focus ring: 3px `#93C5FD` outline offset by 2px.
- **Secondary**: `#FFFFFF` background with 1px `#E2E8F0` border, `#0F172A` text. Active/Hover shifts to `#F1F5F9`.
- **Ghost/Destructive**: Ghost buttons use transparent backgrounds with `#64748B` text. Destructive triggers use `#FEF2F2` background, `#DC2626` text, and `#FCA5A5` active borders.

### Form Fields & Inputs
- **Base Style**: Pristine white background (`#FFFFFF`), 1px `#E2E8F0` border, `rounded-xl` geometry (24px radius), 14px horizontal padding, 12px vertical padding. Placeholder text sits at `#94A3B8`.
- **Focused State**: Border shifts directly to `#2563EB` with an ambient glow (`box-shadow: 0 0 0 3px rgba(37, 99, 235, 0.15)`).
- **Labeling**: Labels sit outside above the input in `label-md` Slate 900 (`#0F172A`), paired with optional sub-labels in Slate 500 (`#64748B`).

### Segmented Controls
- **Track**: `#F1F5F9` container, `rounded-xl`, 4px inner padding.
- **Segments**: Unselected states use transparent fills with Slate 500 text (`label-md`). The active selected segment uses pure `#FFFFFF`, `rounded-lg`, Slate 900 text, 1px `#E2E8F0` border, and Level 1 micro-shadow. Transition spans 150ms ease-out.

### Status Indicators & Badges
- **Shape & Layout**: Fully rounded pill shapes (`9999px`), 4px vertical by 10px horizontal padding. Typography is `label-sm`.
- **Tokens**:
  - *Shortlisted/Hired*: Background `#ECFDF5`, text `#047857`, dot indicator `#10B981`.
  - *Under Review*: Background `#FFFBEB`, text `#B45309`, dot indicator `#F59E0B`.
  - *AI Matched*: Background `#F5F3FF`, text `#6D28D9`, dot indicator `#8B5CF6`.
  - *Archived/Rejected*: Background `#FEF2F2`, text `#B91C1C`, dot indicator `#EF4444`.

### Cards & Candidate Modules
- Built on pristine white (`#FFFFFF`) containers with 1px `#E2E8F0` borders, `rounded-lg` or `rounded-xl` corners, and `1rem` internal padding.
- Cards host clear content zones: candidate header with avatar and score pill at top, collapsible qualification tags across the center, and a dedicated action footer split between quick-screen buttons.

### Candidate AI Score Pill
- Dedicated metric badge displaying AI fit percentage: 28px height, `9999px` radius, bold geometric numerical value, encased in a `#EFF6FF` background with `#1D4ED8` text and a subtle `#DBEAFE` border.