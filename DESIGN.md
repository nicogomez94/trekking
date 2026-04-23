---
name: Sierras Rugged
colors:
  surface: '#161311'
  surface-dim: '#161311'
  surface-bright: '#3c3836'
  surface-container-lowest: '#100e0c'
  surface-container-low: '#1e1b19'
  surface-container: '#221f1d'
  surface-container-high: '#2d2927'
  surface-container-highest: '#383432'
  on-surface: '#e9e1dd'
  on-surface-variant: '#c3c8c2'
  inverse-surface: '#e9e1dd'
  inverse-on-surface: '#33302d'
  outline: '#8d928d'
  outline-variant: '#434844'
  surface-tint: '#bbcabe'
  primary: '#bbcabe'
  on-primary: '#26332b'
  primary-container: '#2d3a31'
  on-primary-container: '#95a498'
  inverse-primary: '#546257'
  secondary: '#ffb77d'
  on-secondary: '#4d2600'
  secondary-container: '#d97707'
  on-secondary-container: '#432100'
  tertiary: '#89ceff'
  on-tertiary: '#00344d'
  tertiary-container: '#003b57'
  on-tertiary-container: '#1eaaee'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d7e6d9'
  primary-fixed-dim: '#bbcabe'
  on-primary-fixed: '#121e16'
  on-primary-fixed-variant: '#3d4a40'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#c9e6ff'
  tertiary-fixed-dim: '#89ceff'
  on-tertiary-fixed: '#001e2f'
  on-tertiary-fixed-variant: '#004c6e'
  background: '#161311'
  on-background: '#e9e1dd'
  surface-variant: '#383432'
typography:
  display-lg:
    fontFamily: Epilogue
    fontSize: 72px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Epilogue
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Epilogue
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Work Sans
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
  unit: 4px
  gutter: 24px
  margin: 32px
  container-max: 1280px
---

## Brand & Style

This design system is built for the rugged terrains of Córdoba, capturing the raw spirit of mountain expeditions. The visual language balances high-end editorial aesthetics with the utilitarian reliability of outdoor gear. It aims to evoke a sense of "civilized adventure"—where professional safety meets wild exploration.

The design style is **Modern Expeditionary**. It leverages high-contrast typography and a structured grid reminiscent of premium outdoor journals, combined with tactile elements that ground the digital experience in the physical world. The user interface acts as a quiet frame for immersive, full-bleed photography, ensuring the landscape of the Sierras remains the protagonist of the narrative.

## Colors

The palette is rooted in the natural minerals and flora of Argentina.
*   **Primary (Forest Depth):** A deep, desaturated green used for backgrounds and primary structural elements, providing a grounded, calm foundation.
*   **Secondary (Sunset Glow):** An energetic orange used exclusively for calls to action, highlights, and critical expedition markers. It provides high visibility against the earthy backdrop.
*   **Tertiary (Alpine Sky):** A crisp blue for technical data points (e.g., weather, altitude, water sources) and secondary interactive elements.
*   **Neutrals (Slate & Bone):** We use "Stone" (#1C1917) for the deepest backgrounds and "Bone" (#F5F5F4) for typography to maintain high readability without the harshness of pure white.

The default mode is **Dark**, mimicking the experience of a campfire or a mountain shelter, which allows vibrant landscape photography to glow on the screen.

## Typography

The typography strategy focuses on a hierarchy that feels both technical and literary. 

*   **Epilogue** is utilized for headlines to provide a bold, geometric presence that feels carved and intentional. 
*   **Work Sans** serves as the primary body face, chosen for its exceptional legibility and neutral, reliable character during long-form storytelling. 
*   **Space Grotesk** is reserved for metadata, technical specs (elevation, coordinates), and navigation labels, lending a modern, "altimeter-inspired" feel to the expedition data. 

All headings should favor tight tracking and significant weight to maintain the "rugged" look, while body text requires generous line heights for readability.

## Layout & Spacing

The design system utilizes a **12-column fixed grid** for desktop and a **4-column fluid grid** for mobile. The spacing rhythm is based on a 4px baseline unit to ensure mathematical precision in technical UI components.

We employ "Expansive Margins"—generous white space (or dark space in this case) around text blocks to create an editorial, premium feel. Content should be grouped in distinct "slabs" or vertical sections that alternate between full-bleed imagery and inset text columns. This creates a rhythmic pacing that mimics the stages of a mountain trek.

## Elevation & Depth

To maintain the rugged aesthetic, we avoid soft, ambient shadows. Instead, we use **Tonal Layers** and **Crisp Borders**:

1.  **Level 0 (Base):** The Stone (#1C1917) background.
2.  **Level 1 (Cards):** Surface colors created by adding a 4% white overlay to the base, creating a subtle "Slate" elevation.
3.  **Level 2 (Interactive):** Elements are defined by 1px solid borders in a muted Slate Grey rather than shadows.
4.  **Immersive Depth:** High-quality photography uses a subtle "top-down" vignette to ensure typography remains legible while creating a sense of atmospheric perspective. 

Glassmorphism is used sparingly—only for navigation bars and overlays on top of images—using a high-density blur (20px) to simulate frosted ice or mountain mist.

## Shapes

The shape language is **Soft (0.25rem)**. We intentionally avoid hyper-rounded corners or pill shapes to maintain a serious, functional atmosphere. 

*   **Standard Corners:** 4px radius for buttons, input fields, and small cards.
*   **Large Containers:** 8px radius for main content cards or image containers.
*   **Hard Edges:** Internal elements like progress bars or technical charts should use 0px radius (sharp) to emphasize the "equipment" feel.

Buttons should be rectangular with the minimal 4px radius to feel like solid blocks of gear.

## Components

### Buttons
Primary buttons use the **Sunset Glow** background with **Stone** text, utilizing the bold Epilogue font. Secondary buttons use a transparent background with a 1px Stone-light border. The hover state should involve a slight color shift to a more saturated orange, suggesting "activation."

### Chips & Tags
Used for trail difficulty (e.g., "Hard," "Intermediate") and duration. These should use the **Space Grotesk** font in all caps. Use background tints: Green for easy, Blue for moderate, and Orange for difficult.

### Input Fields
Fields should be dark with a 1px border. When focused, the border transitions to **Sunset Glow**. Labels always sit above the field in **Space Grotesk** all-caps for a technical appearance.

### Expedition Cards
Cards feature a large image header with a "scrim" (gradient overlay) at the bottom to house the title. Metadata like "Days" and "Max Elevation" should be displayed in a horizontal row of icon-label pairs using the tertiary Blue.

### Immersive Storytelling Elements
Include "Elevation Profiles" (line charts showing trek gradients) and "Gear Lists" (checklists with rugged, custom-styled checkboxes that use a 'tick' mark resembling a mountain peak).