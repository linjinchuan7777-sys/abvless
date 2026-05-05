---
name: Echoes of Abvless
colors:
  surface: '#141312'
  surface-dim: '#141312'
  surface-bright: '#3a3938'
  surface-container-lowest: '#0f0e0d'
  surface-container-low: '#1c1b1a'
  surface-container: '#201f1e'
  surface-container-high: '#2b2a29'
  surface-container-highest: '#363433'
  on-surface: '#e6e2df'
  on-surface-variant: '#cdc5bd'
  inverse-surface: '#e6e2df'
  inverse-on-surface: '#31302f'
  outline: '#969088'
  outline-variant: '#4b4640'
  surface-tint: '#cac5c2'
  primary: '#cac5c2'
  on-primary: '#32302e'
  primary-container: '#2c2a28'
  on-primary-container: '#95918e'
  inverse-primary: '#615e5b'
  secondary: '#e0c29f'
  on-secondary: '#3f2d14'
  secondary-container: '#5a452b'
  on-secondary-container: '#d1b492'
  tertiary: '#ccc6be'
  on-tertiary: '#33302b'
  tertiary-container: '#2d2a25'
  on-tertiary-container: '#96918a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e7e1de'
  primary-fixed-dim: '#cac5c2'
  on-primary-fixed: '#1d1b19'
  on-primary-fixed-variant: '#494644'
  secondary-fixed: '#fdddb9'
  secondary-fixed-dim: '#e0c29f'
  on-secondary-fixed: '#281803'
  on-secondary-fixed-variant: '#584329'
  tertiary-fixed: '#e8e1da'
  tertiary-fixed-dim: '#ccc6be'
  on-tertiary-fixed: '#1e1b17'
  on-tertiary-fixed-variant: '#4a4641'
  background: '#141312'
  on-background: '#e6e2df'
  surface-variant: '#363433'
typography:
  headline-display:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '300'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.4'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.8'
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.1em
spacing:
  unit: 8px
  gutter: 24px
  margin-edge: 64px
  section-gap: 160px
---

## Brand & Style
This design system is anchored in the concept of **Wabi-sabi (侘寂)**—finding beauty in imperfection, transience, and the passage of time. It serves as a digital archive for a space that no longer physically exists, functioning more as a silent documentary than a commercial platform.

The aesthetic follows a **Minimalist-Tactile** movement. It prioritizes vast, quiet negative space (Ma) punctuated by high-fidelity textures: weathered timber grains, crumbling plaster, and the soft diffusion of light through shoji paper. The emotional response is one of "Mono no aware"—a gentle sadness at the passing of things, paired with a deep respect for the architectural history of Taipei’s Zhongshan District.

## Colors
The palette is drawn directly from the materials of the historic Japanese structure. 

- **Primary (Deep Charcoal):** Represents the shadows within the wooden rafters and the "black" of calligraphy ink.
- **Secondary (Weathered Wood):** A desaturated, earthy brown used for structural accents and interactive states.
- **Tertiary (Warm Cream):** Evokes aged washi paper and the original plaster walls of the building.
- **Neutral (Obsidian):** Used for the deepest background layers to provide a sense of infinite, quiet space.

The interface primarily operates in a dark mode to mimic the dim, atmospheric lighting of the bar’s interior, using high-contrast white text only for essential legibility.

## Typography
The typography system relies on the tension between the editorial elegance of **Noto Serif** and the functional clarity of **Work Sans**. 

Headlines should be treated with generous leading and occasional vertical orientation (evoking Japanese tategaki) to emphasize the "historic archive" feel. Body text utilizes a wide line height (1.6 - 1.8) to ensure the reading experience feels unhurried and spacious. Labels are always set in uppercase with increased letter spacing to serve as subtle, architectural markers within the layout.

## Layout & Spacing
The layout employs a **Fixed Grid** model inspired by the structural beams of a Japanese house. On desktop, a 12-column grid is used, but content is often intentionally "broken" or offset to mimic the organic growth of the tree structure seen in the reference image.

Whitespace is the primary design tool. Section gaps are intentionally large to force the user to slow down their scroll speed. Margins are wide, pushing content toward the center to create a focused, "gallery" viewing experience.

## Elevation & Depth
Depth is conveyed through **Tonal Layers** rather than shadows. 
- **Base Layer:** The deepest neutral charcoal (#1A1918).
- **Interactive Layer:** Subtle shifts to weathered wood brown (#8C7355) upon engagement.
- **Overlay Layer:** Semi-transparent "Shoji" panels (Cream at 10% opacity) with a heavy background blur (20px) to simulate light passing through frosted glass or paper.

Physicality is added via **Grain Overlays**. A subtle, persistent noise filter should be applied to the entire UI to simulate the texture of old film or dusty wood.

## Shapes
In keeping with the "Ruins" (廃墟) aesthetic and the rigid timber framing of the building, the shape language is strictly **Sharp (0)**. 

Every container, button, and image frame uses 90-degree corners. This reflects the precision of Japanese architecture. Softness is introduced not through corner radii, but through the use of natural, deckled edges on image assets or organic masks that follow the silhouette of the wooden structures.

## Components
- **Buttons:** Ghost-style with a thin 1px border. On hover, the border dissolves and the background fills with a low-opacity wood brown tint. Text is always centered and tracked out.
- **Cards:** Borderless. Content is separated by wide gutters or thin, "needle-like" horizontal rules that evoke the thin branches in the space.
- **Image Archive:** Images should feature a desaturated filter. When hovered, they may slightly regain warmth or color.
- **Navigation:** A minimal, fixed header. Navigation items should appear as simple text strings without icons, using a "fade-in" transition to appear and disappear.
- **Scroll Indicator:** A vertical line at the bottom of the hero section that slowly grows and shrinks, mimicking a slow breath.
- **Dividers:** Use a 1px solid line in the Secondary color, but interrupt the line occasionally to signify "decay" or age.