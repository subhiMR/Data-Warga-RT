---
name: Civic Community Portal
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#41493e'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#717a6d'
  outline-variant: '#c0c9bb'
  surface-tint: '#2a6b2c'
  primary: '#00450d'
  on-primary: '#ffffff'
  primary-container: '#1b5e20'
  on-primary-container: '#90d689'
  inverse-primary: '#91d78a'
  secondary: '#126d27'
  on-secondary: '#ffffff'
  secondary-container: '#9cf49c'
  on-secondary-container: '#19722b'
  tertiary: '#174321'
  on-tertiary: '#ffffff'
  tertiary-container: '#2f5b36'
  on-tertiary-container: '#a0d1a2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#acf4a4'
  primary-fixed-dim: '#91d78a'
  on-primary-fixed: '#002203'
  on-primary-fixed-variant: '#0c5216'
  secondary-fixed: '#9ff79f'
  secondary-fixed-dim: '#83da85'
  on-secondary-fixed: '#002105'
  on-secondary-fixed-variant: '#005318'
  tertiary-fixed: '#bdefbe'
  tertiary-fixed-dim: '#a2d3a4'
  on-tertiary-fixed: '#002109'
  on-tertiary-fixed-variant: '#24502c'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: 0em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
    lineHeight: 18px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system serves Indonesian civic neighborhood administration (Rukun Tetangga / Rukun Warga). The visual identity balances institutional authority, transparency, and grassroots community warmth. It replaces bureaucratic friction with approachable, structured clarity.

The visual direction follows **Modern Civic SaaS**: crisp information architecture, balanced density, and institutional trust accented by uplifting botanical greens. The atmosphere is reliable, accessible across age demographics, orderly, and calm. High-contrast typography paired with soft-tinted surfaces ensures rapid legibility under varied lighting conditions on mobile devices and desktop workstations alike.

## Colors

The palette establishes hierarchical clarity and communal trust through natural forest and mint tones grounded by slate neutrals:

- **Primary (`#1B5E20`)**: Deep Forest Green. Conveys institutional permanence, civic responsibility, and legal validity. Reserved for key actions, brand marks, primary buttons, and high-level navigation anchors.
- **Secondary (`#66BB6A`)**: Medium Vibrant Green. Represents positive status updates, successful dues verification, community health, and active badges.
- **Tertiary (`#A5D6A7`)**: Soft Sage Green. Applied to subtle structural borders, progress meter tracks, and hover-state focus indicators.
- **Neutral Base (`#1E293B`)**: Deep Slate. The primary text tone for optimal contrast ratio (passing WCAG AAA) against light surfaces.
- **Neutral Muted (`#64748B`)**: Slate Gray. Used for table headers, secondary meta descriptions, and non-active icons.
- **Canvas (`#F8FAFC`)**: Clean Slate Mist. Primary background to prevent eye strain during extensive data entry.
- **Surface Canvas Tint (`#E8F5E9`)**: Ultra Light Mint. Reserved for highlighted community announcements, dues receipts, active table row highlights, and verified citizen cards.

## Typography

The typography leverages **Plus Jakarta Sans** across all levels. It brings geometric stability with subtle humanist warmth, ensuring modern readability for numerical citizen identification (NIK/KK), census data, and long announcements.

- **Headlines**: Semi-bold to bold weights with tight letter-spacing for sharp, editorial authority.
- **Body**: Generous x-height for clear legibility on both desktop monitoring screens and low-resolution mobile devices.
- **Labels & Badges**: Micro typography employs bold weights and positive letter-spacing (`0.01em` to `0.04em`) to make uppercase status tags (e.g., `LUNAS`, `TERVERIFIKASI`, `PENDUDUK TETAP`) identifiable at a glance.

## Layout & Spacing

The layout adopts a **12-column responsive grid** engineered for data-heavy civic interfaces:

- **Desktop (>= 1024px)**: 12-column fluid grid, `2rem` outer margins, `1.5rem` gutters. Accommodates persistent left navigation, split-panel forms (e.g., citizen bio & document previews), and multi-column demographic dashboards.
- **Tablet (768px - 1023px)**: 8-column fluid grid, `1.5rem` margins, `1rem` gutters. Metric cards wrap into 2x2 grids; secondary sidebars collapse to slide-over trays.
- **Mobile (< 768px)**: 4-column fluid grid, `1rem` margins, `1rem` gutters. Stacked single-column layouts prioritize immediate citizen tasks (surat pengantar request, iuran payment proof upload).

Interior component spacing strictly scales on a base 4px system, ranging from compact `space-xs` (tight form metadata) to `space-xl` (section breaks between administrative modules).

## Elevation & Depth

Visual hierarchy uses **tonal layering and low-contrast borders** rather than pronounced shadows to maintain an uncluttered administrative feel:

- **Base Layer (Level 0)**: Background canvas (`#F8FAFC`).
- **Cards & Surfaces (Level 1)**: Flat white (`#FFFFFF`) with a structural 1px border of `#E2E8F0` or `#A5D6A7` on highlighted panels. Soft ambient elevation is introduced only for floating popovers, drawers, and modal sheets using a diffused, green-tinted shadow: `0 8px 24px -4px rgba(27, 94, 32, 0.08)`.
- **Interactive Elevated (Level 2)**: Actionable elements on hover elevate slightly using a subtle transform and ambient glow: `0 4px 12px -2px rgba(27, 94, 32, 0.12)`.
- **Tonal Contrast**: Subtle `#E8F5E9` pale mint fills serve as background layering for contextual callouts, pinned announcements, and verified verification badges without relying on z-index depth.

## Shapes

The interface implements **Roundedness Level 2** (0.5rem / 8px standard corner radius). 

- **Inputs, Buttons, and Cards**: Standard `0.5rem` (8px) radius balances modern software aesthetics with structural grid discipline.
- **Modals and Dashboard Panels**: `rounded-lg` (1rem / 16px) softens large overlay surfaces.
- **Status Tags, Filter Chips, and Avatars**: Fully rounded pills (`9999px`) to create an immediate optical distinction between structural containers and metadata tokens.

## Components

### Buttons
- **Primary**: Solid Deep Forest Green (`#1B5E20`) fill with white text. Hover transitions to `#144617`. Focus states show a 2px offset ring in `#66BB6A`.
- **Secondary**: Crisp white background with a 1px border of `#A5D6A7`, text in `#1B5E20`. Hover activates an `#E8F5E9` surface wash.
- **Subtle / Ghost**: Transparent background with `#1E293B` text, shifting to `#E8F5E9` on interaction for secondary table actions.

### Civic Badges & Chips
- **Status Badges**: Pill-shaped with a 6px vertical and 12px horizontal padding.
  - *Lunas / Disetujui (Paid / Approved)*: Background `#E8F5E9`, text `#1B5E20`, border `#A5D6A7`.
  - *Menunggu Verifikasi (Pending)*: Background `#FEF3C7`, text `#92400E`, border `#FCD34D`.
  - *Ditolak / Tunggakan (Rejected / Overdue)*: Background `#FEE2E2`, text `#991B1B`, border `#FCA5A5`.
- **Filter Chips**: Neutral slate border `#E2E8F0` on white; active state triggers `#1B5E20` fill with white text.

### Tables & Citizen Registries
- Clean, compact row heights (48px default). Table headers feature `#64748B` uppercase micro-text over an ultra-light tint background.
- Zebra-striping avoided; rows separated by 1px `#F1F5F9` lines, with hovered rows activating an `#E8F5E9` 50% opacity wash.
- Numerical fields (NIK, No. KK, Nominal Kas) render in tabular figures with right alignment.

### Form Inputs
- 40px default height, `#FFFFFF` background, `#CBD5E1` border, `0.5rem` radius.
- Active focus triggers a 1px `#1B5E20` border and a 3px outer glow ring in `rgba(102, 187, 106, 0.25)`.
- Helper text rests at `12px` in `#64748B`.

### Administrative Metric Cards
- White containers outlined with `#E2E8F0`. 
- Top-accented with a subtle 3px border line in `#66BB6A` for quick category recognition (e.g., Total Kas RT, Total Kepala Keluarga, Pengajuan Surat).