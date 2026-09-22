---
name: Portal UNH Institucional
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
  on-surface-variant: '#44474f'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#747781'
  outline-variant: '#c4c6d1'
  surface-tint: '#415e95'
  primary: '#001a42'
  on-primary: '#ffffff'
  primary-container: '#0b2f64'
  on-primary-container: '#7c98d4'
  inverse-primary: '#adc6ff'
  secondary: '#115cb9'
  on-secondary: '#ffffff'
  secondary-container: '#659dfe'
  on-secondary-container: '#003370'
  tertiary: '#301500'
  on-tertiary: '#ffffff'
  tertiary-container: '#4e2700'
  on-tertiary-container: '#e47f15'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a41'
  on-primary-fixed-variant: '#28467c'
  secondary-fixed: '#d7e2ff'
  secondary-fixed-dim: '#acc7ff'
  on-secondary-fixed: '#001a40'
  on-secondary-fixed-variant: '#004491'
  tertiary-fixed: '#ffdcc3'
  tertiary-fixed-dim: '#ffb77d'
  on-tertiary-fixed: '#2f1500'
  on-tertiary-fixed-variant: '#6e3900'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
  civic-red: '#C81E2F'
  accent-gold: '#F59E0B'
  sky-tint: '#EBF3FB'
  surface-bg: '#F8FAFC'
  neutral-border: '#E2E8F0'
typography:
  display-hero:
    fontFamily: Public Sans
    fontSize: 44px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Public Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Public Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Public Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Public Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Public Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Public Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Public Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Public Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Work Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
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

The design system projects academic prestige, administrative transparency, and civic trust for a major Peruvian state university. Serving students, faculty, researchers, administrative personnel, and citizens, the visual identity blends institutional gravitas with modern, frictionless public-sector service delivery.

The aesthetic follows a **Corporate / Modern Government & Academic** movement:
- **Clarity and order:** High information density structured logically through clear visual hierarchy, avoiding cognitive overload.
- **Accessible authority:** Official institutional blues combined with warm energetic accents (sun gold and civic red) that honor regional identity and national symbolism.
- **Service-driven simplicity:** Administrative procedures, student portals, and official announcements are elevated with distinct, clean card surfaces, predictable icon signifiers, and disciplined typographic rhythm.

## Colors

The palette is anchored in Peruvian public higher-education dignity and high-contrast digital accessibility (WCAG AA/AAA compliant):

- **Primary (`#0B2F64`):** Deep institutional navy representing rigor, stability, and historical weight. Applied to top headers, key callouts, authoritative headings, and primary buttons.
- **Secondary (`#0056B3`):** Royal blue providing interactive energy, focus rings, primary links, active tabs, and secondary buttons.
- **Tertiary (`#D97706` / `accent-gold: #F59E0B`):** Warm solar gold derived from the university seal. Reserved for urgent announcements, highlights, portal badges, and academic achievements.
- **Civic Red (`#C81E2F`):** National state signifier used for mandatory alerts, legal deadlines, emergency notifications, and formal convocation badges.
- **Neutral (`#1E293B`):** Slate dark tone ensuring high legibility for long-form reading across resolutions, paired with `#F8FAFC` base surface canvas to alleviate ocular strain.

## Typography

The design system selects **Public Sans** for display, headings, and continuous body text due to its institutional clarity, high neutrality, and strong optical legibility across multi-column civic portals. For precise utilitarian data, stamps, badges, and button labels, **Work Sans** provides geometric rhythm and unmistakable character differentiation.

- Section headers maintain strict hierarchy with subtle bottom decorative accents in primary navy or civic red.
- Long administrative transcripts and resolutive notifications adhere to `body-md` (14px) and `body-lg` (16px) with an open 1.55 to 1.62 line-height ratio to prevent fatigue.
- Acronyms (UNH, CEPRE, Siga Web, DBU) are kept legible with uppercase kerning enabled via `letterSpacing`.

## Layout & Spacing

A structured **12-column responsive fluid grid** with bounded container widths ensures order across complex university layouts:

- **Desktop (1200px+):** 12 columns, max container width 1280px, 24px (`1.5rem`) gutters, and 32px (`2rem`) page margin.
- **Tablet (768px - 1199px):** 8 columns, 20px gutters, and 24px margins. Direct-access icon clusters collapse from 6 columns to 3 or 4 columns.
- **Mobile (< 768px):** 4 columns, 16px (`1rem`) gutters, and 16px page margins. Digital service tiles convert to a 2-column or horizontal scrolling grid.
- **Rhythm:** An 8pt base spatial unit guides section separation. Major institutional thematic sections (Actualidad, Convocatorias, Trámites) maintain `2.5rem` (`space-xl`) internal padding.

## Elevation & Depth

Visual depth is achieved through **restrained tonal layers and subtle ambient shadows**, preserving an efficient, print-friendly academic document aesthetic:

- **Level 0 (Flat Surface):** `#F8FAFC` page background; cards and panels use pure `#FFFFFF` background with a crisp `1px solid #E2E8F0` border.
- **Level 1 (Interactive Base):** Service access cards and news items feature a delicate tinted shadow: `box-shadow: 0 1px 3px rgba(11, 47, 100, 0.05), 0 1px 2px rgba(11, 47, 100, 0.03)`.
- **Level 2 (Hover / Active):** On hover, interactive cards elevate with `box-shadow: 0 8px 20px rgba(11, 47, 100, 0.08)` and a subtle upward translate of `-2px`.
- **Level 3 (Modals, Overlays & Virtual Assistant):** Floating widgets (e.g., KawsayBot or modal alerts) use `box-shadow: 0 16px 36px rgba(11, 47, 100, 0.16)`. No heavy black drop shadows are permitted.

## Shapes

The system implements a **Soft (Level 1)** geometric standard to balance contemporary digital elegance with bureaucratic dependability:

- Standard cards, tables, announcement banners, and input fields adopt `4px` (`0.25rem`) corner radiuses.
- Modal dialogues, featured promotional carousels, and digital service hubs scale to `8px` (`0.5rem`).
- Strict circle profiles (`rounded-full`) are reserved exclusively for direct service icon badges, circular status avatars, and floating assistant action triggers.
- Sharp, clean corners ensure alignment with official state certifications (ISO 9001, ISO 14001, ISO 21001 badge enclosures).

## Components

### Buttons
- **Primary:** Solid `#0B2F64` background, `#FFFFFF` text, `4px` border radius, `0.75rem 1.5rem` padding. Subtle color transition to `#0056B3` on hover.
- **Secondary / Action:** Outlined with `1.5px solid #0056B3`, `#0056B3` text, transparent background. Active states fill with `#EBF3FB`.
- **Urgent / Convocatoria:** Solid `#C81E2F` background with white bold typography for immediate deadlines.
- **Access Quick-Action (Descubrir Más):** Compact pill-styled or soft-rectangle button using dark navy background with centered white label and arrow icon.

### Service & Tramite Cards
- Digital access items (Siga Web, Mesa de Partes, Biblioteca Virtual) utilize a modular vertical layout: white surface, subtle border `#E2E8F0`, centralized monochrome or duo-tone navy icon within an azure circular badge, followed by uppercase concise title, and a standardized action button at the base.

### Chips & Badges
- Institutional tags: `label-sm` font, `4px` radius, uppercase.
- Status Categories:
  - *Académico / Noticias:* Tinted blue background (`#EBF3FB`) with `#0B2F64` text.
  - *Convocatorias CAS / Docente:* Tinted gold background (`#FEF3C7`) with `#B45309` text.
  - *Vigente / Oficial:* Tinted green background (`#DCFCE7`) with `#15803D` text.
  - *Urgente / Importante:* Tinted red background (`#FEE2E2`) with `#B91C1C` text.

### News & Carousel Cards
- Split content architecture: upper 16:9 thumbnail photo container with a date stamp chip overlaid; lower section with `headline-sm` headline (2 lines clamped), short abstract, and an inline link (`Leer más →`).

### Input Fields & Search Bars
- Institutional search inputs use pure white background, `1px solid #CBD5E1` border, `8px 16px` padding, and a prominent navy magnifying icon button. Focused state invokes a crisp `2px solid #0056B3` ring with zero offset.

### Official Certifications Header
- Clean horizontal badge lockups showcasing university accreditation alongside ISO standards (9001, 14001, 21001) in soft gray bordered containers with Bureau Veritas seals.