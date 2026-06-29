---
name: Kinetic Velocity
colors:
  surface: '#0c141b'
  surface-dim: '#0c141b'
  surface-bright: '#313a41'
  surface-container-lowest: '#070f15'
  surface-container-low: '#141d23'
  surface-container: '#182127'
  surface-container-high: '#222b32'
  surface-container-highest: '#2d363d'
  on-surface: '#dbe4ed'
  on-surface-variant: '#c5c5d5'
  inverse-surface: '#dbe4ed'
  inverse-on-surface: '#293138'
  outline: '#8f909e'
  outline-variant: '#444653'
  surface-tint: '#b9c3ff'
  primary: '#b9c3ff'
  on-primary: '#002388'
  primary-container: '#7189f6'
  on-primary-container: '#001e78'
  inverse-primary: '#3c55bf'
  secondary: '#dcb8ff'
  on-secondary: '#44176f'
  secondary-container: '#5c3187'
  on-secondary-container: '#d0a1ff'
  tertiary: '#c6c4df'
  on-tertiary: '#2f2e43'
  tertiary-container: '#908ea8'
  on-tertiary-container: '#28283c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b9c3ff'
  on-primary-fixed: '#001356'
  on-primary-fixed-variant: '#1f3ba6'
  secondary-fixed: '#f0dbff'
  secondary-fixed-dim: '#dcb8ff'
  on-secondary-fixed: '#2c0051'
  on-secondary-fixed-variant: '#5c3187'
  tertiary-fixed: '#e2e0fc'
  tertiary-fixed-dim: '#c6c4df'
  on-tertiary-fixed: '#1a1a2e'
  on-tertiary-fixed-variant: '#45455b'
  background: '#0c141b'
  on-background: '#dbe4ed'
  surface-variant: '#2d363d'
  electric-blue: '#00D4FF'
  energetic-orange: '#FF8C42'
  surface-dark: '#0F0F1A'
  glass-border: rgba(255, 255, 255, 0.1)
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: JetBrains Mono
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
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  container-max: 1440px
---

## Brand & Style
This design system centers on a "High-Tech Kinetic" aesthetic, tailored for a fast-paced vehicle inventory environment. It blends **Modern Corporate** structure with **Glassmorphism** and **Vibrant** accents to create a UI that feels both professional and "alive."

The brand personality is authoritative yet energetic, designed to give users a sense of total control over their data. The visual style utilizes deep atmospheric backgrounds contrasted with translucent, frosted-glass containers and high-energy focal points. Motion is a core tenet; interactions should feel fluid and snappy, mimicking the high-performance vehicles the system tracks.

## Colors
The palette is rooted in a deep "Midnight Tech" foundation (`#1A1A2E` and `#0F0F1A`) to establish a professional, high-end automotive feel. 

- **Primary & Secondary:** A vibrant gradient of `#667EEA` and `#764BA2` is used for high-level brand moments and active states.
- **Accents:** `Electric Blue` is reserved for data-points and system-status indicators, while `Energetic Orange` acts as the primary call-to-action color to ensure critical buttons (like "Sell" or "Add Inventory") are impossible to miss.
- **Neutral:** Sleek grays manage secondary information and metadata, ensuring the hierarchy remains clear in a data-heavy environment.

## Typography
The system uses **Inter** for its clean, Swiss-inspired legibility and modern proportions. Tight tracking and heavy weights are used for headlines to evoke a sense of power and precision.

To reinforce the high-tech, automotive nature of the product, **JetBrains Mono** is introduced for labels, vehicle specifications (VIN numbers, engine specs), and data visualizations. This monospaced contrast adds a "functional tool" feel to the interface, distinguishing raw data from editorial content.

## Layout & Spacing
The layout follows a **Fluid Grid** model with a 12-column structure on desktop. Spacing is based on an 8px rhythm to ensure perfect alignment of dense data tables and inventory cards.

On mobile, the grid collapses to 4 columns with 16px margins. Tablet (768px+) uses 8 columns. The "Inventory View" uses a dynamic masonry or grid layout that adapts based on screen width, prioritizing high-resolution vehicle imagery while maintaining clear technical specs in the sidebars or gutters.

## Elevation & Depth
Depth is created through **Glassmorphism** and tonal layering. Rather than traditional heavy shadows, this system uses:

1.  **Backdrop Blurs:** Secondary surfaces use a 12px blur with a semi-transparent dark tint (20-40% opacity).
2.  **Inner Glows:** To simulate high-tech screens, cards feature a 1px "glass border" on the top and left sides.
3.  **Luminous Depth:** Active elements emit a soft, colored glow (using the primary or accent color) instead of a black shadow, making the UI feel like it is emitting light rather than just reflecting it.

## Shapes
A **Rounded (0.5rem)** logic is applied throughout the system. This creates a balance between the precision of sharp corners and the approachability of circles. Inventory cards and primary action buttons utilize this standard. Pill shapes are reserved exclusively for status indicators (e.g., "In Stock," "Sold") and filter chips to provide high visual differentiation from functional buttons.

## Components
- **Buttons:** Primary buttons use the Energetic Orange with a slight "luminous" glow. Hover states should include a subtle scale increase (1.02x) and a shift in gradient intensity.
- **Inventory Cards:** These feature high-resolution imagery at the top, a "Glass" spec-sheet overlay at the bottom, and a subtle 1px border. 
- **Data Visualization:** Charts should use vibrant, glowing lines (Electric Blue) against the dark `surface-dark` background. Points on a graph should pulse when hovered.
- **Input Fields:** Semi-transparent backgrounds with a "glass-border." On focus, the border should glow with the Primary color.
- **Chips/Badges:** Small, high-contrast badges with monospaced text (JetBrains Mono) to show technical attributes like "AWD" or "EV."
- **Navigation:** A sleek, vertical sidebar on desktop with translucent backgrounds that expand on hover to reveal descriptive labels.