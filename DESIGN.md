---
name: Kinetic Elite
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
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
  on-tertiary: '#303030'
  tertiary-container: '#e4e2e1'
  on-tertiary-container: '#656464'
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
  tertiary-fixed: '#e4e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#474746'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Barlow Condensed
    fontSize: 80px
    fontWeight: '800'
    lineHeight: '1.0'
  display-lg-mobile:
    fontFamily: Barlow Condensed
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
  headline-lg:
    fontFamily: Barlow Condensed
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-sm:
    fontFamily: Barlow Condensed
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
spacing:
  base: 8px
  section-gap: 80px
  grid-margin: 24px
  grid-gutter: 16px
  container-max: 1280px
---

## Brand & Style

This design system is built on the pillars of **kinetic energy, industrial luxury, and disciplined strength**. It is designed for high-performance fitness environments where the digital experience must match the intensity of a physical workout. 

The aesthetic is a fusion of **High-Contrast Bold** and **Minimalist Glassmorphism**. By utilizing a dark-mode foundation, the system creates a focused, "in-the-zone" atmosphere. Large-scale typography and vibrant accent colors drive the user’s eye toward action, while subtle frosted glass textures provide the "high-end" polish expected by a premium clientele. The overall emotional response should be one of motivation, precision, and unwavering professional support.

## Colors

The palette is intentionally restricted to maximize visual impact.

- **Primary (Electric Lime):** This is the "energy" color. It is used exclusively for calls to action, progress indicators, and critical highlights. It should never be used for large surface areas to avoid visual fatigue.
- **Neutral (Deep Charcoal):** The foundation of the design system. It provides a sophisticated, low-distraction background that makes the Primary color pop.
- **Secondary (White):** Used for primary content, ensuring maximum legibility against the dark background.
- **Tertiary (Graphite):** A lighter charcoal used for surface layering, such as card backgrounds or input fields, to create subtle depth.

## Typography

The typography in the design system is designed to be loud and authoritative. 

- **Headlines:** Use **Barlow Condensed** in heavy weights. The condensed nature allows for massive font sizes that convey strength without crowding the horizontal space. Always use uppercase for Display and Headline levels to evoke a sense of "command."
- **Body:** **Inter** provides a clean, neutral balance to the aggressive headlines, ensuring that workout instructions and data remain highly readable.
- **Technical Labels:** **Space Grotesk** is used for data points (e.g., heart rate, weights, timer), providing a modern, technical edge that feels like a professional performance monitor.

## Layout & Spacing

The design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. 

The layout philosophy emphasizes **generous whitespace** (vertical "breathing room") to maintain a premium feel. Large section gaps (80px+) should be used to separate different training modules or content blocks, preventing the UI from feeling cluttered. 

Elements should be aligned to a strict 8px baseline grid to ensure mathematical precision, echoing the discipline of fitness training. On mobile, margins should remain tight (16px-24px) to maximize the "punchy" feel of the content.

## Elevation & Depth

Depth is achieved through **Glassmorphism** and **Tonal Layering** rather than traditional shadows.

1.  **The Base:** All content sits on the Deep Charcoal (#121212) floor.
2.  **Surface Layers:** Cards and containers use a semi-transparent version of the Tertiary color with a high-density background blur (20px-40px). 
3.  **Accents:** A 1px solid border (low-opacity White) is applied to glassmorphic cards to define their edges against the dark background.
4.  **Interaction:** When an element is focused or active, it should lose its transparency and gain a solid Electric Lime border, indicating a state of "high energy."

## Shapes

The shape language of the design system is **unapologetically sharp**. 

All corners for buttons, cards, input fields, and images must have a **0px radius**. Sharp corners communicate precision, aggression, and a modern architectural aesthetic. This "hard-edge" approach differentiates the system from the soft, rounded "friendly" UI of consumer social apps, positioning this as a tool for serious athletes.

## Components

- **Power Buttons:** Primary buttons are sharp-edged, filled with Electric Lime, and feature bold, uppercase black text. Secondary buttons are outlined in white with no fill.
- **Glass Cards:** Used for workout programs or class schedules. They feature a 1px border and background blur. On hover, the border transitions to Electric Lime.
- **Metric Chips:** Small, technical labels using Space Grotesk. These often feature a subtle Electric Lime glow when a personal record or goal is achieved.
- **Data Inputs:** Input fields are dark, sharp-edged boxes with a simple 1px white bottom border that transforms into a full Electric Lime frame upon focus.
- **Progress Bars:** Use a Deep Charcoal track with an Electric Lime fill. Avoid rounded caps; the progress bar should be a sharp rectangular block.
- **Community Lists:** Use high-contrast photography with a dark overlay, allowing white typography and lime accents to sit clearly on top of the imagery.