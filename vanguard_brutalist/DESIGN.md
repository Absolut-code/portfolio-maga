---
name: Vanguard Brutalist
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c4c9ac'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8e9379'
  outline-variant: '#444933'
  surface-tint: '#abd600'
  primary: '#ffffff'
  on-primary: '#283500'
  primary-container: '#c3f400'
  on-primary-container: '#556d00'
  inverse-primary: '#506600'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#ffffff'
  on-tertiary: '#21323e'
  tertiary-container: '#d2e5f5'
  on-tertiary-container: '#556774'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c3f400'
  primary-fixed-dim: '#abd600'
  on-primary-fixed: '#161e00'
  on-primary-fixed-variant: '#3c4d00'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#d2e5f5'
  tertiary-fixed-dim: '#b6c9d8'
  on-tertiary-fixed: '#0b1d29'
  on-tertiary-fixed-variant: '#374956'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-xl:
    fontFamily: Syne
    fontSize: 120px
    fontWeight: '800'
    lineHeight: 110px
    letterSpacing: -0.04em
  display-lg:
    fontFamily: Syne
    fontSize: 80px
    fontWeight: '800'
    lineHeight: 80px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Syne
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 36px
  body-lg:
    fontFamily: Space Mono
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Space Mono
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-bold:
    fontFamily: Space Mono
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
  label-sm:
    fontFamily: Space Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
spacing:
  unit: 8px
  gutter: 0px
  margin-mobile: 24px
  margin-desktop: 48px
  border-width-thin: 1px
  border-width-thick: 4px
---

## Brand & Style

This design system is a provocative collision between high-fashion editorial aesthetics and digital Neo-Brutalism. It is designed for creators who want to command attention through unapologetic confidence and raw technicality. The personality is edgy, experimental, and high-impact.

The visual style rejects standard "soft" UI conventions in favor of stark contrasts, massive typography, and a "raw" construction feel. It leverages the precision of monospaced fonts against the expressive, avant-garde nature of experimental grotesques. The resulting interface feels like a digital gallery—one that is both structured and rebellious.

## Colors

The palette is restricted to three high-octane tones to maintain maximum visual tension. The default mode is **Dark**, utilizing "Deep Obsidian Black" (#0A0A0A) as the primary canvas to allow the other colors to vibrate with intensity.

- **Primary (Electric Neon Green):** Used exclusively for high-priority calls to action, active states, and critical highlights. It represents energy and the "future-forward" aspect of the brand.
- **Secondary (Stark White):** Used for primary content, large-scale typography, and borders to ensure absolute legibility and a clean, editorial finish.
- **Neutral (Obsidian Black):** The foundation of the design system, providing a void-like depth that forces the user's eye toward content and imagery.

## Typography

The typography strategy relies on extreme scale contrast. Headlines use **Syne**, an avant-garde grotesque that feels both architectural and artistic. At large scales, the letterforms function as graphic elements themselves. 

Body and technical text use **Space Mono**. This monospaced choice introduces a sense of "work-in-progress" and technical precision, grounding the expressive headlines in a structured, utilitarian reality. All labels and metadata should be set in uppercase Space Mono to reinforce the brutalist, document-style aesthetic.

## Layout & Spacing

This design system utilizes a **12-column fluid grid** with a twist: gutters are eliminated (0px) in favor of heavy borders as separators. This creates a "boxed" or "tabled" look characteristic of Brutalist layouts.

- **Asymmetry:** Content should rarely be centered. Align elements to the far left or far right of the grid to create dynamic tension.
- **Large-Scale Imagery:** Visuals should span at least 6 columns, often breaking the grid or extending to the edge of the viewport.
- **Section Breaks:** Use a 4px "Stark White" border to separate major vertical sections. Use 1px borders for internal component divisions.
- **Mobile Reflow:** On mobile, the 12-column grid collapses to a single column, but the heavy borders remain, creating a vertical "stack" of high-impact blocks.

## Elevation & Depth

Depth is conveyed through **High-Contrast Outlines** and **Tonal Layering** rather than shadows. This is a flat, "tactile-digital" environment.

- **No Shadows:** Shadows are strictly prohibited. They are too "soft" for this design system.
- **The Stacking Rule:** When an element (like a modal or menu) appears over another, it should be framed by a 4px Stark White border with a 100% opaque Obsidian Black background. 
- **Z-Index Contrast:** Depth is perceived by the thickness of the borders. Higher-level elements use thicker borders, while background divisions use thinner ones.
- **Active States:** Instead of elevation, active states are indicated by color inversion (e.g., a white background becomes neon green).

## Shapes

The shape language is defined by absolute **Sharpness (0px radius)**. Every element—buttons, cards, input fields, and image containers—must have 90-degree corners. This reinforces the architectural and rigid nature of the Brutalist style. 

Avoid circles or soft curves entirely. Even icon sets used within this system should favor angular, geometric forms over rounded ones.

## Components

### Buttons
Buttons are rectangular blocks with 2px or 4px borders.
- **Primary:** Neon Green background, Black text, no border. On hover, invert to White background.
- **Secondary:** Transparent background, White 2px border, White text. On hover, fill with White, Black text.

### Inputs & Forms
Form fields are defined by a bottom border only (4px) or a full 1px box. Labels sit directly above the input in uppercase Space Mono. The cursor/focus state should turn the entire input background to a low-opacity Neon Green or apply a 4px Neon Green border.

### Cards
Cards are not treated as "floating" objects. They are grid cells defined by 1px white borders. If a card is "featured," it receives a 4px border. Images within cards should be set to `grayscale(100%)` by default, bursting into full color only on hover.

### Lists
Lists should resemble a technical manifest. Each item is separated by a 1px white line. Use Space Mono for all list content to maintain the "raw data" aesthetic.

### Chips/Tags
Small, sharp-edged boxes with 1px white borders. For "active" filters, use a solid Neon Green fill with Black text.