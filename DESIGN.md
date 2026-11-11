---
name: Monochromatic Intelligence
colors:
  surface: '#121212'
  surface-dim: '#0a0a0a'
  surface-bright: '#333333'
  surface-container-lowest: '#050505'
  surface-container-low: '#141414'
  surface-container: '#181818'
  surface-container-high: '#222222'
  surface-container-highest: '#2a2a2a'
  on-surface: '#ffffff'
  on-surface-variant: '#a3a3a3'
  inverse-surface: '#ffffff'
  inverse-on-surface: '#121212'
  outline: '#666666'
  outline-variant: '#2a2a2a'
  surface-tint: '#ffffff'
  primary: '#ffffff'
  on-primary: '#0a0a0a'
  primary-container: '#ffffff'
  on-primary-container: '#0a0a0a'
  inverse-primary: '#737373'
  secondary: '#d4d4d4'
  on-secondary: '#0a0a0a'
  secondary-container: '#262626'
  on-secondary-container: '#ffffff'
  tertiary: '#a3a3a3'
  on-tertiary: '#0a0a0a'
  tertiary-container: '#262626'
  on-tertiary-container: '#e5e5e5'
  error: '#d4d4d4'
  on-error: '#0a0a0a'
  error-container: '#2e2e2e'
  on-error-container: '#ffffff'
  primary-fixed: '#ffffff'
  primary-fixed-dim: '#d4d4d4'
  on-primary-fixed: '#0a0a0a'
  on-primary-fixed-variant: '#262626'
  secondary-fixed: '#d4d4d4'
  secondary-fixed-dim: '#737373'
  on-secondary-fixed: '#0a0a0a'
  on-secondary-fixed-variant: '#404040'
  tertiary-fixed: '#e5e5e5'
  tertiary-fixed-dim: '#737373'
  on-tertiary-fixed: '#0a0a0a'
  on-tertiary-fixed-variant: '#404040'
  background: '#0a0a0a'
  on-background: '#ffffff'
  surface-variant: '#262626'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 3rem
    fontWeight: '700'
    lineHeight: 3.5rem
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 2rem
    fontWeight: '700'
    lineHeight: 2.5rem
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2rem
    fontWeight: '600'
    lineHeight: 2.5rem
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2rem
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '600'
    lineHeight: 1.5rem
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.625rem
    letterSpacing: -0.011em
  body-md:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.375rem
    letterSpacing: -0.006em
  body-sm:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '400'
    lineHeight: 1.125rem
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: 1.25rem
    letterSpacing: -0.005em
  label-sm:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.02em
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 0.75rem
    fontWeight: '400'
    lineHeight: 1.125rem
    letterSpacing: 0em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system delivers an architectural, restrained interface tailored for high-stakes enterprise workflows, systems telemetry, and data infrastructure platforms. The aesthetic bridges high-performance computing with modern executive clarity: precise, authoritative, and intentionally quiet. 

Drawing from modern precision-minimalism and structured tonal layering, the UI favors content densities calibrated to reduce cognitive fatigue during prolonged operational shifts. Visual weight is articulated through hairline geometry, micro-contrasts, and razor-sharp typographic hierarchy rather than decorative friction. Every pixel conveys stability, auditability, and absolute technical competence.

## Colors

The palette operates in a disciplined monochromatic grayscale and white aesthetic. Pure black, calibrated dark grays, and crisp white create maximum contrast, clarity, and architectural minimalism.

- **Primary (`#FFFFFF`)**: Crisp pure white accent for key callouts, active indicators, and high-impact action buttons.
- **Secondary (`#D4D4D4` / `#262626`)**: Light and dark neutral gray tones for structural framing, interactive states, and badges.
- **Tertiary (`#A3A3A3`)**: Balanced neutral gray for subtext, inactive indicators, and secondary metrics.
- **Substrate Tiers**:
  - Base Background: `#0A0A0A` (Deep dark canvas root)
  - Surface Substrate: `#121212` / `#141414` (Panels, table rows)
  - Surface Container: `#181818` / `#222222` (Cards, dialogs, elevated containers)
  - Text Primary: `#FFFFFF` (Pure white for high-contrast legibility)
  - Text Muted: `#A3A3A3` / `#666666` (Subheadings, body descriptions, and disabled states)
  - Structural Hairlines: `#2A2A2A` / `rgba(255, 255, 255, 0.12)` (Borders, structural dividers)

## Typography

The typographic hierarchy implements a high-clarity dual sans-serif system:

- **Headlines & Section Anchors**: `Plus Jakarta Sans` provides structured geometric rhythm with subtle contemporary nuances in larger sizes, creating confident, authoritative anchoring.
- **Body & Controls**: `Inter` drives interface metrics, narrative explanations, data tables, and input controls. Selected for optimal legibility at micro-scales and neutral rendering of complex information densities.
- **Code & Numerical Telemetry**: `JetBrains Mono` handles hexadecimal references, log strings, cryptographic keys, and tabular operational data.

## Layout & Spacing

The layout is built upon an 8pt structural baseline, ensuring vertical rhythm across varying density modules. 

- **Grid Architecture**: 12-column responsive fluid grid configured with `2rem` outer page margins (`1rem` on mobile) and `1.5rem` gutters. Enterprise dashboard modules span fractional columns (3, 4, 6, 8, 12).
- **Responsive Logic**:
  - **Desktop (>= 1280px)**: 12 columns, multi-pane sidebars with fixed `260px` nav rails and fluid content canvas.
  - **Tablet (768px - 1279px)**: 8 columns, `1.25rem` gutters, collapsible secondary analytical panels.
  - **Mobile (< 768px)**: 4 columns, `1rem` gutters, full-bleed card layouts, vertical stacking of operational metrics.

## Elevation & Depth

Visual hierarchy eschews dramatic drop shadows, relying instead on tonal surface sequencing and subtle border luminance:

- **Tonal Depth**:
  - **Level 0 (Canvas)**: `#0B1120` — The foundational layer.
  - **Level 1 (Substrate & Workspaces)**: `#0F172A` paired with a hairline border (`rgba(148, 163, 184, 0.08)`).
  - **Level 2 (Interactive Modules & Panels)**: `#1E293B` bounded by `rgba(148, 163, 184, 0.15)`.
  - **Level 3 (Overlays, Modals, Menus)**: `#1E293B` with an ambient glow (`box-shadow: 0 16px 32px -8px rgba(0, 0, 0, 0.6), 0 0 1px 1px rgba(56, 189, 248, 0.15)`).
- **Edge Highlighting**: Modals and highlighted focus cards incorporate an interior hairline (`inset 0 1px 0 rgba(241, 245, 249, 0.08)`) to mimic precision beveled glass edges.

## Shapes

The geometric framework favors an engineered, compact aesthetic. Roundedness is strictly disciplined to preserve an architectural silhouette:

- Standard controls, inputs, data badges, and action triggers utilize `0.25rem` (4px).
- Cards, data visualization containers, and modal dialogs use `0.5rem` (8px).
- Complex multi-part views utilize `0.75rem` (12px) outer framing.
- Full pills are forbidden for interactive controls, reserved solely for active status pips and circular user telemetry indicators.

## Components

- **Buttons**:
  - *Primary*: Background `#FFFFFF`, text `#0A0A0A`, border `1px solid rgba(255, 255, 255, 0.4)`. Hover transitions to `#E5E5E5` with a subtle white outer glow (`0 0 12px rgba(255, 255, 255, 0.2)`).
  - *Secondary / Outlined*: Background `#262626`, text `#FFFFFF`, border `1px solid rgba(255, 255, 255, 0.15)`. Hover background `#333333` with border `#FFFFFF`.
  - *Tertiary / Ghost*: Background `transparent`, text `#A3A3A3`, hover text `#FFFFFF` and hover background `rgba(255, 255, 255, 0.05)`.
  - *Height*: `36px` default, `32px` for dense data grids.

- **Inputs & Form Controls**:
  - Background `#050505`, border `1px solid #2A2A2A`, text `#FFFFFF`.
  - Placeholder text `#666666`.
  - Focus state: Border color `#FFFFFF`, accompanied by an ambient ring `0 0 0 1px #FFFFFF`.

- **Chips & Status Badges**:
  - Height `22px`, font size `0.75rem`, weight `600`.
  - Inactive / Neutral: Background `#181818`, text `#A3A3A3`, border `1px solid #2A2A2A`.
  - Active / Primary: Background `rgba(255, 255, 255, 0.1)`, text `#FFFFFF`, border `1px solid rgba(255, 255, 255, 0.25)`.

- **Cards & Data Modules**:
  - Background `#141414`, border `1px solid #2A2A2A`.
  - Inner card headers feature a bottom border `1px solid #222222` and padding of `space-md` (`1rem`).

- **Selection Controls (Checkboxes & Radios)**:
  - Checkbox: Base square with `2px` radius, background `#050505`, border `1px solid #666666`.
  - Selected state: Fill `#FFFFFF`, stroke `#000000`, focus ring in `#FFFFFF`.

- **Data Tables (Enterprise Density)**:
  - Header: `#121212`, text `#A3A3A3`, uppercase `label-sm`, letter spacing `0.05em`.
  - Row: Alternating subtle striping (`#121212` / `#181818`), hover background `#222222`.
  - Hairline row dividers: `1px solid #2A2A2A`.