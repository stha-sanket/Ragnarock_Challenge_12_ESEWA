---
name: WildGuard AI
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#40493d'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0ef'
  outline: '#707a6c'
  outline-variant: '#bfcaba'
  surface-tint: '#1b6d24'
  primary: '#0d631b'
  on-primary: '#ffffff'
  primary-container: '#2e7d32'
  on-primary-container: '#cbffc2'
  inverse-primary: '#88d982'
  secondary: '#7a5649'
  on-secondary: '#ffffff'
  secondary-container: '#fdcdbc'
  on-secondary-container: '#795548'
  tertiary: '#ac0c18'
  on-tertiary: '#ffffff'
  tertiary-container: '#d02d2d'
  on-tertiary-container: '#ffedeb'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a3f69c'
  primary-fixed-dim: '#88d982'
  on-primary-fixed: '#002204'
  on-primary-fixed-variant: '#005312'
  secondary-fixed: '#ffdbcf'
  secondary-fixed-dim: '#ebbcac'
  on-secondary-fixed: '#2e150b'
  on-secondary-fixed-variant: '#603f33'
  tertiary-fixed: '#ffdad6'
  tertiary-fixed-dim: '#ffb3ac'
  on-tertiary-fixed: '#410003'
  on-tertiary-fixed-variant: '#930010'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e5e2e1'
typography:
  h1:
    fontFamily: Epilogue
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Epilogue
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  h3:
    fontFamily: Epilogue
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.2'
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 48px
  gutter: 16px
  margin: 24px
---

## Brand & Style
This design system is engineered for high-stakes environmental monitoring and rapid response. The brand personality is **rugged, authoritative, and utilitarian**, mirroring the physical equipment used by forest rangers in the field. It prioritizes clarity over decoration, ensuring that critical data is legible under varying light conditions—from the glare of direct sunlight to the low-light environments of a command center.

The aesthetic follows a **Functional-Modern** approach with subtle **Tactile** influences. It avoids delicate gradients or "glass" effects in favor of solid containers, heavy strokes, and high-contrast surfaces. The goal is to evoke the reliability of a high-end GPS unit or a piece of tactical gear, providing users with a sense of stability and precision when managing wildlife threats.

## Colors
The color palette is grounded in the natural environment while maintaining strict accessibility standards. 

- **Primary Forest Green**: Used for primary actions, navigation headers, and active states. It reinforces the connection to the forest while providing a professional, "official" tone.
- **Secondary Earth Brown**: Utilized for structural elements, secondary buttons, and grouping containers. It provides a warm, grounded contrast to the green.
- **Alert Tiers**: A strict hierarchy of alert colors is enforced. **Critical Red** is reserved exclusively for immediate wildlife threats or system failures. **Warning Orange** denotes potential activity or cautionary status, and **Success Green** indicates secure perimeters or completed tasks.
- **Neutrals**: The system uses a deep charcoal (#212121) for text to maintain maximum contrast against off-white or light-grey backgrounds, reducing eye strain during long shifts.

## Typography
The typography strategy focuses on "glanceability." **Epilogue** (serving as a rugged, geometric alternative to Poppins) is used for headings to provide a distinctive, modern character that feels structured and bold. 

**Inter** is the workhorse for all body copy and data displays. Chosen for its exceptional legibility on digital screens, it ensures that long reports and technical coordinates remain readable. Labels are often set in uppercase with slightly increased letter spacing to differentiate them from interactive text, facilitating quick scanning of field data and sensor readings.

## Layout & Spacing
This design system employs a **Fixed Grid** model for administrative dashboards to maintain high-density data visualization, transitioning to a **Fluid Grid** for field-based mobile views. 

The layout relies on a 12-column grid with a baseline unit of 4px. This tight rhythm allows for dense information displays without clutter. Gutters are kept at 16px to maximize screen real estate for maps and camera feeds, while outer margins are a generous 24px to ensure tap targets are safely away from the edges of ruggedized hardware bezels.

## Elevation & Depth
In line with the rugged, functional aesthetic, this design system avoids soft, atmospheric shadows. Instead, it uses **Bold Borders** and **Tonal Layers** to define hierarchy.

Depth is communicated through:
1.  **Strokes**: All cards and input fields use a 1px or 2px solid border (#E0E0E0 or Secondary Brown) to define their boundaries.
2.  **Surface Tiers**: High-priority information is placed on pure white surfaces, while background data and sidebars sit on light grey or low-saturation earth-toned "trench" layers.
3.  **Active Elevation**: When an element is interacted with, it does not "glow"; rather, it uses a high-contrast offset stroke or a saturated fill color change to indicate state change.

## Shapes
The shape language is primarily **Soft-Cornered (0.25rem)**. This provides a balance between the precision of a sharp-edged industrial tool and the approachability of a modern software interface. Large radius curves (pills) are avoided as they waste space and feel too consumer-oriented. Buttons and containers feature consistent 4px corners to maintain a cohesive, "machined" look across the interface.

## Components
- **Buttons**: Designed as "tactile slabs." Primary buttons use a solid Forest Green fill with white text. Secondary buttons use a thick 2px Earth Brown border. All buttons must have a minimum height of 48px to accommodate gloved hands in the field.
- **Alert Cards**: Use a high-contrast left-border accent (4px width) in Critical Red or Warning Orange. Icons within these cards must be 24px minimum and use solid, heavy weights.
- **Input Fields**: Feature a light grey background with a clear, dark charcoal bottom-border. On focus, the border transitions to Forest Green with a 2px thickness.
- **Status Chips**: Use solid fills for critical states and outlined styles for informational states. The contrast ratio between text and chip background must always exceed 4.5:1.
- **Map Overlays**: Use a semi-opaque dark charcoal background (85% opacity) to ensure that white text and iconography remain legible over complex topographic satellite imagery.
- **Data Lists**: High-density lists utilize zebra-striping in very light neutrals to help the eye track coordinates and timestamps across wide screen widths.