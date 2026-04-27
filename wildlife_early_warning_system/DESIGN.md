---
name: Wildlife Early Warning System
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#40493d'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#707a6c'
  outline-variant: '#bfcaba'
  surface-tint: '#1b6d24'
  primary: '#0d631b'
  on-primary: '#ffffff'
  primary-container: '#2e7d32'
  on-primary-container: '#cbffc2'
  inverse-primary: '#88d982'
  secondary: '#2a6b2c'
  on-secondary: '#ffffff'
  secondary-container: '#acf4a4'
  on-secondary-container: '#307231'
  tertiary: '#7a4a00'
  on-tertiary: '#ffffff'
  tertiary-container: '#9c6000'
  on-tertiary-container: '#ffeee0'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a3f69c'
  primary-fixed-dim: '#88d982'
  on-primary-fixed: '#002204'
  on-primary-fixed-variant: '#005312'
  secondary-fixed: '#acf4a4'
  secondary-fixed-dim: '#91d78a'
  on-secondary-fixed: '#002203'
  on-secondary-fixed-variant: '#0c5216'
  tertiary-fixed: '#ffddba'
  tertiary-fixed-dim: '#ffb865'
  on-tertiary-fixed: '#2b1700'
  on-tertiary-fixed-variant: '#663d00'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  headline-xl:
    fontFamily: Epilogue
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Epilogue
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Epilogue
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Epilogue
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Epilogue
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Epilogue
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Epilogue
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 40px
  xl: 64px
  gutter: 24px
  margin: 32px
---

## Brand & Style

The design system is engineered to convey precision, environmental stewardship, and technological sophistication. It serves a dual purpose: providing high-stakes safety information while maintaining a serene, nature-focused aesthetic. 

The style is rooted in **Minimalism** with a high-tech edge. It prioritizes clarity through expansive white space, ensuring that critical alerts are never lost in visual noise. By utilizing a flat design language with structural borders rather than depth-based shadows, the interface feels lightweight and immediate. The aesthetic response should be one of "calm urgency"—professional enough for researchers and government officials, yet intuitive enough for local communities and travelers.

## Colors

The palette is anchored by **Refined Forest Green**, a color that symbolizes both the natural world and safety. This primary hue is used for brand presence and positive actions. To maintain a high-tech feel, the system leans heavily on a "Paper & Ink" philosophy: pure white backgrounds contrasted with high-legibility dark slate text.

- **Primary:** Forest Green (#2E7D32) for key interactions and brand identity.
- **Secondary:** Deep Moss (#1B5E20) for hover states and heavy-duty grounding.
- **Alert/Tertiary:** Amber (#FFA000) is used sparingly for "Warning" states to ensure it commands attention without causing panic.
- **Neutrals:** A range of soft grays is used for structural division and secondary information, keeping the interface feeling airy and "light."

## Typography

This design system uses **Epilogue** exclusively to achieve a bold, contemporary look that bridges the gap between editorial and technical. The typeface's geometric construction provides the "high-tech" feel required for a monitoring app.

Headlines should utilize heavy weights (700) with slight negative letter-spacing to create a sense of authority and impact. Body text remains at a generous 16px or 18px to ensure readability in outdoor or high-glare environments. Labels and small data points use a medium weight with increased letter-spacing to maintain a professional, systematic appearance.

## Layout & Spacing

The layout philosophy follows a **Fluid Grid** model with an emphasis on generous breathing room. A 12-column system is used for desktop, scaling down to 4 columns for mobile, with a consistent 24px gutter. 

To achieve the professional vibe, the design system utilizes "Generous Padding." Elements are never crowded; instead, they are grouped logically using whitespace as the primary separator. Margin sizes of 32px or 40px are common for container edges to push the content into a focused central area, reflecting a premium, curated experience.

## Elevation & Depth

This design system eschews heavy shadows in favor of **Low-Contrast Outlines** and **Tonal Layers**. 

Depth is communicated through 1px borders in soft neutral grays (#E0E0E0). When an element needs to stand out or appear "active," it should utilize a slightly darker background shade or a thicker (2px) primary-colored border rather than a drop shadow. For critical modals or overlays, a very soft, high-diffusion shadow (Opacity < 5%, Blur > 20px) may be used to provide a subtle lift from the background without breaking the flat aesthetic.

## Shapes

The shape language is defined by **Rounded Corners (Level 2)**, specifically targeting an 8px to 12px radius. This softening of the geometry makes the app feel approachable and modern, contrasting with the "hard" data often displayed.

- **Standard Buttons/Inputs:** 8px radius.
- **Cards/Containers:** 12px radius.
- **Status Pills:** Fully rounded (pill-shaped) to distinguish them from interactive buttons.

## Components

### Buttons
Primary buttons are solid Forest Green with white text, using 24px horizontal padding. Secondary buttons use a 1px border (#E0E0E0) with Forest Green text. Both utilize the 8px corner radius.

### Cards
Cards are the primary data containers. They feature a white background, a 1px soft gray border, and no shadow. Padding inside cards should be generous (24px) to keep the data points clear.

### Input Fields
Inputs are flat with a light gray background (#F8F9FA) and an 8px radius. On focus, the border transitions to a 2px Forest Green stroke.

### Chips & Status Indicators
Used for "Animal Type" or "Threat Level." These are small, pill-shaped elements. For threat levels, use high-contrast text on soft, tinted backgrounds (e.g., Amber text on a very light Amber background).

### Wildlife Map & Alerts
A custom map component should use a "Silver" or "Light" map style with Forest Green markers. Alert notifications appear as "Toasts" at the top of the screen, utilizing the full width of the container with a bold, flat background color to indicate urgency.

### Data Visualization
Charts and graphs should use a monochromatic green scale supplemented by neutral grays to maintain the high-tech, professional aesthetic without looking cluttered.