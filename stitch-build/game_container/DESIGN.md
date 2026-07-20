---
name: Seishun Gakuensai Mobile
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
  on-surface-variant: '#5b403e'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#8f6f6d'
  outline-variant: '#e4bebb'
  surface-tint: '#ba1826'
  primary: '#b61524'
  on-primary: '#ffffff'
  primary-container: '#da3339'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb3ae'
  secondary: '#4e5d8c'
  on-secondary: '#ffffff'
  secondary-container: '#b9c7fd'
  on-secondary-container: '#445281'
  tertiary: '#595d5c'
  on-tertiary: '#ffffff'
  tertiary-container: '#717574'
  on-tertiary-container: '#fafdfb'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad7'
  primary-fixed-dim: '#ffb3ae'
  on-primary-fixed: '#410005'
  on-primary-fixed-variant: '#930016'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b6c5fb'
  on-secondary-fixed: '#061845'
  on-secondary-fixed-variant: '#364572'
  tertiary-fixed: '#e0e3e1'
  tertiary-fixed-dim: '#c4c7c5'
  on-tertiary-fixed: '#181c1c'
  on-tertiary-fixed-variant: '#434846'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  headline-xl:
    fontFamily: Anybody
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Anybody
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Anybody
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 14px
spacing:
  margin-mobile: 20px
  gutter-mobile: 12px
  stack-xs: 4px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  stack-xl: 48px
---

## Brand & Style

The design system captures the fleeting, energetic essence of a Japanese school festival—vibrant, youthful, and slightly nostalgic. It targets a Gen-Z and Millennial audience looking for community engagement and event discovery.

The design style is **Expressive Minimalism with Brutalist accents**. It uses high-contrast typography and a paper-like texture to mimic physical flyers and posters. For mobile, the brand shifts toward a "stacked flyer" aesthetic, prioritizing vertical scanning and high-energy interactions. The UI should feel immediate and tactile, like a program booklet held in hand.

## Colors

The palette is driven by "Youthful Red" (#FF4E50) for high-action areas and "Deep Midnight" (#2B3A67) for grounding elements.

- **Primary:** Used for main calls to action, active states, and critical highlights.
- **Secondary:** Used for headers, navigation backgrounds, and structural contrast.
- **Tertiary/Surface:** A warm, off-white (#FCFFFD) used as the "Paper" background to reduce eye strain and provide a nostalgic feel.
- **Neutral:** Pure blacks are avoided in favor of "Off-Black" (#1A1A1A) for all typography to maintain a premium editorial look.

## Typography

Typography is the primary driver of the brand's energy. **Anybody** provides a variable, high-impact presence for headings, while **Plus Jakarta Sans** ensures legible, friendly body text.

On mobile, headlines utilize tight line-heights and negative letter-spacing to maximize screen real estate and create a "loud" visual hierarchy. **Space Grotesk** is used for technical data, time-stamps, and labels to introduce a slight technical/functional contrast to the organic body text. Use `headline-xl` sparingly for screen entry points; `headline-lg` is the standard for in-page section headers.

## Layout & Spacing

The layout follows a **Fluid Vertical Stack** model optimized for one-handed thumb use. 

- **Grid:** A 4-column fluid grid for mobile.
- **Margins:** A consistent 20px outer margin ensures content doesn't feel cramped against the bezel.
- **Vertical Flow:** Elements are grouped in logical "blocks" with 16px (stack-md) internal spacing and 32px (stack-lg) between distinct sections.
- **Safe Areas:** Navigation is anchored to the bottom of the screen (Bottom Bar) to account for reachability on large mobile devices.

## Elevation & Depth

This design system rejects traditional shadows in favor of **Bold Outlines** and **Tonal Layering**.

Depth is created through:
- **Hard Offsets:** Instead of soft shadows, use a 2px or 4px solid black offset border to make elements "pop" from the background.
- **High-Contrast Strokes:** Every card and button features a 1.5pt solid stroke (#1A1A1A).
- **Z-axis:** Overlapping elements (like a floating action button over a list) use a solid primary color background to assert dominance rather than a blur or shadow.

## Shapes

The shape language is strictly **Sharp (0)**. 

To evoke the "cut-paper" aesthetic of school festival posters, all containers, buttons, and input fields utilize 90-degree corners. This sharp geometry provides a modern, structured contrast to the friendly typography. For circular elements (like profile avatars), use a square frame with a thick interior border to maintain the system's geometric consistency.

## Components

- **Buttons:** Rectangular with a 2px black border. Primary buttons use a solid Red fill with white text. Secondary buttons are transparent with a black border and text. On press, buttons shift 2px down and right to simulate a physical "click."
- **Cards:** White or Cream background with a 1.5pt black border. Content inside cards follows the 12px gutter. Use "header-md" for card titles.
- **Lists:** Separated by 1.5pt horizontal strokes. List items should have a minimum height of 56px to ensure a comfortable touch target.
- **Input Fields:** Sharp-edged boxes with a 1pt border that thickens to 2.5pt on focus. Labels use "label-md" and are placed strictly above the field.
- **Chips/Tags:** Small rectangular boxes with "label-sm" text. Use the secondary color (#2B3A67) for category tags to distinguish them from action buttons.
- **Bottom Navigation:** A solid black bar with white icons. Active states are indicated by a Red (#FF4E50) block behind the icon.