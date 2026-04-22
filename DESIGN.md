---
name: Professional Logic
colors:
  surface: '#fbf9f8'
  surface-dim: '#dadada'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#e9e8e8'
  surface-container-highest: '#e3e2e2'
  on-surface: '#313333'
  on-surface-variant: '#5e5f5f'
  inverse-surface: '#0e0e0e'
  inverse-on-surface: '#9e9d9c'
  outline: '#7a7b7b'
  outline-variant: '#b2b2b2'
  surface-tint: '#0053de'
  primary: '#0053de'
  on-primary: '#faf8ff'
  primary-container: '#0f62fe'
  on-primary-container: '#ffffff'
  inverse-primary: '#628aff'
  secondary: '#5f5f5f'
  on-secondary: '#faf8f8'
  secondary-container: '#e4e2e2'
  on-secondary-container: '#515252'
  tertiary: '#006e2b'
  on-tertiary: '#e9ffe5'
  tertiary-container: '#93f59e'
  on-tertiary-container: '#005d23'
  error: '#a83836'
  on-error: '#fff7f6'
  error-container: '#fa746f'
  on-error-container: '#6e0a12'
  primary-fixed: '#0f62fe'
  primary-fixed-dim: '#0056e7'
  on-primary-fixed: '#ffffff'
  on-primary-fixed-variant: '#d8dfff'
  secondary-fixed: '#e4e2e2'
  secondary-fixed-dim: '#d5d4d4'
  on-secondary-fixed: '#3f3f3f'
  on-secondary-fixed-variant: '#5b5b5b'
  tertiary-fixed: '#93f59e'
  tertiary-fixed-dim: '#86e791'
  on-tertiary-fixed: '#00481a'
  on-tertiary-fixed-variant: '#006828'
  primary-dim: '#0048c4'
  secondary-dim: '#535353'
  tertiary-dim: '#006125'
  error-dim: '#67040d'
  background: '#fbf9f8'
  on-background: '#313333'
  surface-variant: '#e3e2e2'
typography:
  headline-lg:
    fontFamily: Public Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Public Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Public Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Public Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Public Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.5px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
---

# Design System: Professional Logic

## Brand & Style
The brand personality has shifted from an energetic, sharp aesthetic to one of professional reliability and modern efficiency. The target audience includes enterprise users and developers who require a stable, trustworthy interface. The UI evokes a sense of logic, clarity, and precision.

The design style is **Corporate / Modern**, heavily influenced by functional systems like IBM Plex or Material 3. It prioritizes readability and accessibility, moving away from aggressive sharp corners to a more approachable, softened professional look.

## Colors
The palette is anchored by a vibrant, high-contrast **Electric Blue** (#0f62fe) as the primary color, signaling action and intelligence. The secondary palette uses a balanced **Mid-Gray** (#6f6f6f) to maintain a professional tone without competing with primary actions.

A new **Forest Green** (#198038) tertiary color is introduced to handle success states, positive growth indicators, or secondary accents. The neutral palette is a sophisticated **Carbon Gray** (#525252), providing high-contrast text and structural elements against the light background mode.

## Typography
We utilize **Public Sans** across all levels—a neutral, friendly, yet high-performance sans-serif font. Headlines use semi-bold weights for clear information hierarchy. Body text is optimized for long-form reading with generous line heights. Labels are slightly tighter and use medium weights to distinguish them from standard body copy.

- **Headlines**: Public Sans, Semi-Bold (600).
- **Body**: Public Sans, Regular (400).
- **Labels**: Public Sans, Medium (500), tracking slightly increased for readability.

## Layout & Spacing
The layout follows a **fluid grid** model with a consistent 4px baseline. Standard gutters are set at 16px (md) to provide adequate breathing room between components. Margins for page containers should scale from 16px on mobile to 32px on desktop. The rhythm is mathematical, ensuring all components align to the 4px increments for a crisp, organized appearance.

## Elevation & Depth
Hierarchy is primarily conveyed through **tonal layers**. Instead of heavy drop shadows, we use subtle surface-container variations (light grays against white backgrounds) to signify depth. When elevation is required for floating elements like menus or modals, use an ambient, low-opacity shadow with a slight neutral tint to maintain the clean, modern aesthetic.

## Shapes
The design has moved away from sharp 0px corners to a **Soft** (Level 1) rounding system. Standard components like buttons and input fields utilize a 4px (0.25rem) corner radius. Larger containers or cards can scale up to 8px or 12px to maintain visual softness without becoming overly "bubbly."

## Components
- **Buttons**: Primary buttons use the Electric Blue background with white text and 4px rounded corners. Secondary buttons use a neutral outline.
- **Input Fields**: Borders use the Neutral #525252 color at low opacity, thickening and changing to Primary Blue on focus.
- **Cards**: Use tonal layering—backgrounds are slightly off-white or have a very subtle 1px border to define boundaries.
- **Chips**: Use the Tertiary Green for success indicators or Secondary Gray for categorical metadata.
- **Checkboxes & Radios**: Utilize the 4px rounding for checkboxes to match the overall "Soft" shape language.