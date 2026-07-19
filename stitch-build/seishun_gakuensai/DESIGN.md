---
name: Seishun Gakuensai
colors:
  surface: '#fbfaee'
  surface-dim: '#dbdbcf'
  surface-bright: '#fbfaee'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f4e8'
  surface-container: '#efeee3'
  surface-container-high: '#e9e9dd'
  surface-container-highest: '#e4e3d7'
  on-surface: '#1b1c15'
  on-surface-variant: '#5c403a'
  inverse-surface: '#303129'
  inverse-on-surface: '#f2f1e5'
  outline: '#916f69'
  outline-variant: '#e5bdb6'
  surface-tint: '#ba1c00'
  primary: '#b51c00'
  on-primary: '#ffffff'
  primary-container: '#dc3214'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb4a5'
  secondary: '#4e5d8c'
  on-secondary: '#ffffff'
  secondary-container: '#b9c7fd'
  on-secondary-container: '#445281'
  tertiary: '#755700'
  on-tertiary: '#ffffff'
  tertiary-container: '#936f03'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad3'
  primary-fixed-dim: '#ffb4a5'
  on-primary-fixed: '#3e0400'
  on-primary-fixed-variant: '#8e1300'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b6c5fb'
  on-secondary-fixed: '#061845'
  on-secondary-fixed-variant: '#364572'
  tertiary-fixed: '#ffdf9b'
  tertiary-fixed-dim: '#edc157'
  on-tertiary-fixed: '#251a00'
  on-tertiary-fixed-variant: '#5b4300'
  background: '#fbfaee'
  on-background: '#1b1c15'
  surface-variant: '#e4e3d7'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 40px
  xl: 64px
  gutter: 20px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style
This design system captures the fleeting, high-energy atmosphere of a Japanese high school cultural festival (*Bunkasai*). The brand personality is "Seishun" (youthful), energetic, and collaborative. It targets a Gen-Z and millennial audience, evoking the nostalgia of student-run booths and the excitement of a school campus transformed for a weekend.

The design style is **Modern-Tactile**. It blends clean, systematic UI containers with expressive, hand-drawn elements reminiscent of chalkboards and DIY club banners. The aesthetic avoids traditional "New Year" tropes in favor of a contemporary "School Life" motif—incorporating subtle paper textures, tape-stuck notes, and vibrant accent colors that represent different student clubs (Sports, Arts, Science).

## Colors
The palette is built on the friction between institutional structure and student creativity. 

- **Seishun Red (#FF4B2B):** The primary driver of energy, used for key actions and "Festival Spirit."
- **Academy Navy (#2B3A67):** Provides the grounding, "uniform-like" professional base for the UI.
- **Festival Cream (#FDFCF0):** The background color, mimicking high-quality cardstock or slightly aged campus flyers, providing a warmer feel than pure white.
- **Club Yellow (#FFD166):** An accent for highlights, alerts, and "New" badges, inspired by caution tape and optimistic banners.

## Typography
The typography balances the cleanliness of modern sans-serifs with the technical edge of school science labs. 

- **Headlines:** Use **Plus Jakarta Sans** with tight tracking and heavy weights to mimic bold, hand-painted festival signs.
- **Body:** **Plus Jakarta Sans** provides a friendly, readable experience for long-form content.
- **Data & Labels:** **Space Grotesk** is introduced for mono-styled labels, providing a "technical/club-ledger" feel that differentiates meta-data from content.

## Layout & Spacing
The layout follows a **structured but asymmetrical** philosophy. While the underlying grid is a standard 12-column system, elements are often offset or "taped" to the layout to break the corporate feel.

- **Grid:** 12-column fluid grid on desktop; 4-column on mobile.
- **Margins:** Generous outer margins to create a "canvas" feel rather than an edge-to-edge app.
- **Rhythm:** Use an 8px base unit for most spacing, but 4px for tight internal component relationships (like labels to inputs).

## Elevation & Depth
This system eschews traditional soft shadows for **Tonal Layers and Physical Overlays.**

- **The Layering Model:** Use "Academy Navy" surfaces for persistent navigation and "Festival Cream" for the main content area. 
- **Hard Shadows:** Instead of blurs, use 100% opacity offset "block shadows" (2px or 4px) in Navy to give elements a sticker-like or paper-cutout appearance.
- **Z-Axis:** Components like Modals should feel like "Banners" (Nobori) dropped over the interface, using a subtle vertical paper texture.

## Shapes
Shapes are intentionally **Soft (0.25rem)** to mimic the corners of printed flyers and classroom posters. 

- **Primary Radius:** 4px (Soft) for most buttons and inputs.
- **Large Containers:** 8px (Rounded-lg) for cards and sections.
- **Organic Accents:** Use "hand-drawn" SVG masks for specific decorative elements like text-highlights or club badges to contrast against the geometric UI.

## Components
Consistent component styling reinforces the "Festival Booth" aesthetic.

- **Buttons:** High-contrast Seishun Red with a 2px Navy bottom-right block shadow. On hover, the shadow disappears as if the button is being "pressed" into the paper.
- **Cards:** Use a thin 1px Navy border. Headers should have a subtle "washi tape" texture accent in the top corner to suggest they’ve been stuck onto the board.
- **Inputs:** Clean "Chalkboard" style for focus states—using a high-contrast yellow underline or border to indicate activity.
- **Chips/Badges:** Styled as "entry stamps" or "club ribbons," using vibrant colors from the tertiary palette.
- **Blackboard Elements:** Use a dark-slate background with white "chalk" stroke icons for specialized sections like "Rules" or "Live Schedules."
- **Banners (Nobori):** Vertical side-tags for categories, mimicking the long flags found at school festival entrances.