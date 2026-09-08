---
name: Obsidian Precision
colors:
  surface: '#101418'
  surface-dim: '#101418'
  surface-bright: '#353a3e'
  surface-container-lowest: '#0a0f13'
  surface-container-low: '#181c20'
  surface-container: '#1c2024'
  surface-container-high: '#262a2f'
  surface-container-highest: '#31353a'
  on-surface: '#dfe3e9'
  on-surface-variant: '#bacbb9'
  inverse-surface: '#dfe3e9'
  inverse-on-surface: '#2d3135'
  outline: '#859584'
  outline-variant: '#3c4a3d'
  surface-tint: '#1ce473'
  primary: '#c3ffca'
  on-primary: '#003917'
  primary-container: '#38f27f'
  on-primary-container: '#006a31'
  inverse-primary: '#006d32'
  secondary: '#c2c7ce'
  on-secondary: '#2c3136'
  secondary-container: '#42474d'
  on-secondary-container: '#b1b5bc'
  tertiary: '#ebf1fb'
  on-tertiary: '#2a3138'
  tertiary-container: '#ced5de'
  on-tertiary-container: '#555c64'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#64ff93'
  primary-fixed-dim: '#1ce473'
  on-primary-fixed: '#00210b'
  on-primary-fixed-variant: '#005224'
  secondary-fixed: '#dee3ea'
  secondary-fixed-dim: '#c2c7ce'
  on-secondary-fixed: '#171c21'
  on-secondary-fixed-variant: '#42474d'
  tertiary-fixed: '#dce3ed'
  tertiary-fixed-dim: '#c0c7d0'
  on-tertiary-fixed: '#151c23'
  on-tertiary-fixed-variant: '#40474f'
  background: '#101418'
  on-background: '#dfe3e9'
  surface-variant: '#31353a'
typography:
  display:
    fontFamily: Space Grotesk
    fontSize: 5rem
    fontWeight: '700'
    lineHeight: '1.02'
    letterSpacing: -0.04em
  display-mobile:
    fontFamily: Space Grotesk
    fontSize: 2.75rem
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 3.5rem
    fontWeight: '600'
    lineHeight: '1.08'
    letterSpacing: -0.035em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 2.25rem
    fontWeight: '600'
    lineHeight: '1.15'
    letterSpacing: -0.025em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 2.25rem
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: -0.025em
  headline-md-mobile:
    fontFamily: Space Grotesk
    fontSize: 1.75rem
    fontWeight: '500'
    lineHeight: '1.25'
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 1.5rem
    fontWeight: '500'
    lineHeight: '1.3'
    letterSpacing: -0.02em
  title:
    fontFamily: Geist
    fontSize: 1.25rem
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: -0.015em
  body-lg:
    fontFamily: Geist
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: -0.01em
  body-md:
    fontFamily: Geist
    fontSize: 0.9375rem
    fontWeight: '400'
    lineHeight: '1.55'
    letterSpacing: -0.005em
  body-sm:
    fontFamily: Geist
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0em
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 0.75rem
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.06em
  label-micro:
    fontFamily: JetBrains Mono
    fontSize: 0.6875rem
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  grid-margin-desktop: 4rem
  grid-margin-tablet: 2rem
  grid-margin-mobile: 1.25rem
  gutter: 1.5rem
  section-gap-desktop: 10rem
  section-gap-mobile: 5rem
  module-padding-lg: 2.5rem
  module-padding-md: 1.5rem
  module-padding-sm: 1rem
---

## Brand & Style
This design system defines a luxury digital studio aesthetic forged at the intersection of Cupertino industrial minimalism, Linear-style operational speed, and Awwwards-tier kinetic storytelling. Built for high-tier engineering and creative technology leadership, the interface evokes mathematical precision, cinematic restraint, and high-performance craftsmanship.

The visual direction merges **Technical Brutalism** and **Refined Dark Glassmorphism**:
- Extreme deep-space black canvases with hairline micro-borders (1px) simulating anodized aluminum edges and laser-etched substrate interfaces.
- Hyper-curated, tactical glow highlights in neon mint against muted slate substrates.
- High typographic contrast where ultra-dense, technical metadata labels frame massive, cinematic display titles.
- Restrained motion physics resembling calibrated mechanical hardware rather than floaty UI decoration.

## Colors
The palette operates on calibrated low-reflectance surfaces contrasted against a hyper-focused laser emission color.

### Palette Architecture
- **Canvas Base (`#070B0F`)**: Absolute foundation. Eliminates blue bloom while retaining deep ink-density.
- **Surface Elevation 1 (`#0D1117`)**: Structural modules, section backdrops, sticky navigation ribbons.
- **Surface Elevation 2 (`#11161B`)**: Active interactive cards, command palettes, and floating surfaces.
- **Hairline Border (`#1E252C`)**: Precision structural line defining all edge geometry.
- **Primary Accent Mint (`#38F27F`)**: Kinetic energy marker. Reserved exclusively for micro-status indicators, focus rings, cursor interactions, terminal outputs, and interactive states.
- **Text Primary (`#FFFFFF`)**: Crisp display headers, focal data, and terminal execution statements.
- **Text Secondary (`#9CA3AF`)**: Long-form body copy, explanatory documentation, and metadata strings.
- **Text Muted (`#4B5563`)**: Watermarks, index keys, and timeline coordinate labels.

### Functional Rules
- Never use solid color fill buttons with the accent color unless it is a primary conversion trigger.
- Surfaces leverage radial spotlight overlays: `radial-gradient(600px circle at var(--mouse-x) var(--mouse-y), rgba(56, 242, 127, 0.06), transparent 40%)`.
- Hairline dividers should use directional opacity masks: `linear-gradient(90deg, transparent, #1E252C 20%, #1E252C 80%, transparent)`.

## Typography
Typographic hierarchy relies on the pairing of three functional voices:
1. **Space Grotesk (Display & Headlines)**: Technical, geometric, engineered posture. Tight negative tracking (-0.04em) and compressed line heights produce an editorial, architectural silhouette.
2. **Geist (Body & Structural Content)**: Neutral, hyper-legible, utilitarian readability. Optimized for technical case studies, long-form system documentation, and interactive project manifests.
3. **JetBrains Mono (Metadata, Tags & Terminal Data)**: Monospaced machine voice. Always uppercase when used as section anchors (e.g., `// 01. SELECTED WORKS`, `SYS.STATUS // NOMINAL`), grounding high-concept visuals in engineering reality.

## Layout & Spacing
The layout follows a 12-column dynamic grid governed by mathematical rigor and cinematic viewport framing.

### Structural Parameters
- **Maximum Content Container**: 1440px with auto margins.
- **Desktop (>= 1280px)**: 12 columns, 24px (1.5rem) gutters, 64px (4rem) margins.
- **Tablet (768px - 1279px)**: 8 columns, 16px (1rem) gutters, 32px (2rem) margins.
- **Mobile (<= 767px)**: 4 columns, 12px (0.75rem) gutters, 20px (1.25rem) margins.

### Rhythmic Rules
- **Viewport Cadence**: Major project transitions use 100vh hero sections anchored with sticky status ribbons.
- **Asymmetric Offsets**: Pair 7-column media viewports with 5-column technical specification lists to break corporate predictability.
- **Hairline Guides**: Grid lines can be made visible using 1px `#1E252C` borders extending to the edge of the viewport to establish blueprint structure.

## Elevation & Depth
Depth is created through chromatic density, edge illumination, and optical physics rather than diffuse drop shadows.

### Surface Tiers
- **Tier 0 (Base)**: `#070B0F` (Zero elevation, absolute grounding).
- **Tier 1 (Panels & Shells)**: `#0D1117` enclosed with a 1px continuous border of `#1E252C`.
- **Tier 2 (Floating Cards & Dialogs)**: `#11161B` with backdrop blur (`backdrop-filter: blur(16px) saturate(180%)`) and an inner top highlight border (`border-top: 1px solid rgba(255, 255, 255, 0.08)`).

### Lighting & Glows
- **Laser Edge Accent**: Interactive cards apply dynamic localized borders via CSS `radial-gradient` tracking the pointer along `#1E252C` to `#38F27F` at 20% opacity.
- **Mint Diffuse Bloom**: Reserved for active telemetry dots and state transitions:
  `box-shadow: 0 0 24px -4px rgba(56, 242, 127, 0.35), 0 0 8px 0px rgba(56, 242, 127, 0.2)`.
- **Shadow Profile**: Deep, zero-ambient dark occlusions:
  `box-shadow: 0 24px 48px -12px rgba(0, 0, 0, 0.75), 0 1px 1px 0 rgba(255, 255, 255, 0.03) inset`.

## Shapes
The shape language implements **Soft Architectural Geometry (Factor 1)**.

- Base elements (buttons, inputs, micro-badges): `0.25rem` (4px).
- Structural elements (cards, modal panes, project previews): `0.5rem` (8px).
- Special containers (floating docks, island navigations): `0.75rem` (12px).
- Strictly avoid stadium/pill geometry (`9999px`) on functional components to preserve an engineered, non-childish form factor. Telemetry chips remain clipped rectangles.
- All SVG icons and line graphics follow a strict 1.5px stroke width with sharp square or minimally filleted joins.

## Components

### 1. Interactive Buttons
- **Primary Technical**: Background `#38F27F`, text `#070B0F`, font `JetBrains Mono` 12px uppercase bold. Radius 4px. Hover transforms background to `#45FF8B` with a calibrated mint bloom `0 0 20px rgba(56, 242, 127, 0.4)`. Active scale `0.98`.
- **Secondary Ghost**: Background `#11161B` at 70% opacity, border 1px `#1E252C`, text `#FFFFFF`. Hover changes border to `rgba(56, 242, 127, 0.4)` and text to `#38F27F`.
- **System Command Link**: Monospaced text string with a prefix prompt `>_` that shifts right 4px on hover with trailing arrow animation.

### 2. Status Chips & Telemetry Badges
- Surface: Background `#0D1117`, border 1px `#1E252C`, padding `4px 8px`.
- Typography: `label-micro`, text `#9CA3AF`.
- Includes a 6px circular indicator: Active items use `#38F27F` with a continuous `2s` CSS pulse bloom; archived items use `#4B5563`.

### 3. Project Showcase Cards
- Container: Background `#11161B`, 1px border `#1E252C`, 8px corner radius.
- Overflow: Hidden, with inner image scaling `1.03` on hover with a 500ms ease-out cubic-bezier transition (`cubic-bezier(0.16, 1, 0.3, 1)`).
- Header: Monospace project coordinate index (e.g., `[ 001 // CREATIVE DEV ]`) in `#9CA3AF` floating top-left over a darkened glass chip.

### 4. Input Fields & Terminal Console
- Background: `#0D1117`, border 1px `#1E252C`, font `Geist` 14px, text `#FFFFFF`.
- Focus State: Border snaps to `#38F27F`, subtle box-shadow `0 0 0 1px #38F27F`, background darkens to `#070B0F`.
- Placeholder: `#4B5563`.

### 5. Checkboxes & Toggles
- Checkbox: 16px square, `#0D1117` fill, 1px border `#1E252C`, 3px radius. Checked state fills with `#38F27F` displaying an `#070B0F` checkmark.
- Switch: 36px x 20px track in `#11161B` with 1px border `#1E252C`. Thumb is 14px square (2px radius) transitioning from `#9CA3AF` to active `#38F27F`.

### 6. Architectural Navigation Dock
- Fixed floating island centered horizontally at screen bottom (`bottom: 2rem`).
- Background: `#0D1117` at 80% opacity with `backdrop-filter: blur(20px)`.
- Border: 1px `#1E252C` with top edge hairline highlight (`rgba(255, 255, 255, 0.1)`).
- Items: Monospaced labels with micro mint underline markers indicating active scroll location.