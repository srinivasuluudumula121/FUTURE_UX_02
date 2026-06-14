---
name: Premium Masculine Minimalist
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1b1b1c'
  on-surface-variant: '#524436'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0ef'
  outline: '#857464'
  outline-variant: '#d7c3b1'
  surface-tint: '#895100'
  primary: '#895100'
  on-primary: '#ffffff'
  primary-container: '#e89a3d'
  on-primary-container: '#5d3600'
  inverse-primary: '#ffb86b'
  secondary: '#605e5a'
  on-secondary: '#ffffff'
  secondary-container: '#e7e2dc'
  on-secondary-container: '#67645f'
  tertiary: '#8c5000'
  on-tertiary: '#ffffff'
  tertiary-container: '#ee9739'
  on-tertiary-container: '#5f3500'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcbc'
  primary-fixed-dim: '#ffb86b'
  on-primary-fixed: '#2c1700'
  on-primary-fixed-variant: '#683d00'
  secondary-fixed: '#e7e2dc'
  secondary-fixed-dim: '#cac6c0'
  on-secondary-fixed: '#1d1b18'
  on-secondary-fixed-variant: '#494642'
  tertiary-fixed: '#ffdcbf'
  tertiary-fixed-dim: '#ffb873'
  on-tertiary-fixed: '#2d1600'
  on-tertiary-fixed-variant: '#6a3b00'
  background: '#fcf9f8'
  on-background: '#1b1b1c'
  surface-variant: '#e5e2e1'
typography:
  display-hero:
    fontFamily: Manrope
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  heading-screen:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  heading-section:
    fontFamily: Manrope
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-card:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
  body-regular:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-small:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.01em
  button-primary:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  '4': 4px
  '8': 8px
  '12': 12px
  '16': 16px
  '24': 24px
  '32': 32px
  '40': 40px
  '48': 48px
---

## Brand & Style

This design system is built on a "Warm Minimalist" aesthetic tailored for a premium men's salon experience. It rejects the aggressive high-contrast "barber shop" tropes (black/gold/heavy chrome) in favor of a sophisticated, airy, and trustworthy atmosphere. 

The brand personality is **modern, refined, and approachable**. It evokes a sense of calm and precision. The visual language uses a foundation of organic, warm neutrals paired with a muted "Burnt Saffron" primary color that feels artisanal rather than synthetic. The goal is to make the user feel they are entering a high-end sanctuary where detail and comfort are prioritized. 

The style utilizes generous whitespace, soft tonal layering, and precise typography to guide the user through the booking and grooming journey without friction.

## Colors

The palette is anchored by a warm, off-white background (`#F3EEE8`) which provides a softer, more premium feel than pure white. This base is complemented by a primary brand color (`#E89A3D`) that acts as a focal point for actions and highlights.

- **Primary:** Use for main CTAs, active states, and brand-defining elements.
- **Surface:** The card color (`#FFFFFF`) should be used to lift content off the background.
- **Text:** Primary text uses a deep charcoal (`#1F1F1F`) to maintain high legibility without the harshness of true black. 
- **Borders:** The default border color is intentionally low-contrast to keep the UI looking clean and integrated.

## Typography

The design system exclusively uses **Manrope**, a modern geometric sans-serif that balances technical precision with warmth. 

- **Headlines:** Use SemiBold weights for clear hierarchy and a confident masculine tone.
- **Body:** Regular weight is used for all descriptive text to ensure maximum readability against the warm background.
- **Micro-copy:** Labels and captions use Medium weights at 12px to remain legible even at smaller scales.
- **Letter Spacing:** Headlines utilize slight negative tracking (-1% to -2%) to feel more compact and premium.

## Layout & Spacing

This design system follows a strict **8pt grid system** to ensure mathematical harmony across all screen sizes. 

- **Screen Padding:** A generous 24px horizontal padding is applied to all screens to prevent content from feeling crowded against the device edges.
- **Vertical Rhythm:** Use 16px or 24px spacing between cards and sections. Use 8px spacing for internal element groupings (e.g., a title and its subtitle).
- **Safe Areas:** Ensure all bottom-fixed elements (like the primary button or bottom nav) account for the device's home indicator zone.

## Elevation & Depth

The system uses **Tonal Layers** and **Subtle Shadows** to create a sense of organized depth. Avoid heavy, dark shadows.

- **Level 0 (Base):** The Background color (`#F3EEE8`).
- **Level 1 (Low):** Cards and surfaces. Use a subtle shadow: `0px 4px 12px rgba(31, 31, 31, 0.08)`.
- **Level 2 (Medium):** Hover states or focused cards. Use a slightly deeper shadow: `0px 8px 24px rgba(31, 31, 31, 0.12)`.
- **Level 3 (High):** Bottom sheets and floating action buttons. Use `0px 12px 32px rgba(31, 31, 31, 0.15)`.

All elevations should maintain the same light-source direction (top-down) for consistency.

## Shapes

The shape language is "Soft-Modern," using significant corner radii to feel approachable and high-end.

- **Small (12px):** Used for interior elements like Time Slot chips or small input groups.
- **Medium (16px):** The standard for Buttons and Input Fields.
- **Large (20px):** Exclusively for Service, Barber, and Appointment cards.
- **Full:** Used for profile avatars, status indicators, and pill-shaped badges.

## Components

### Buttons
- **Primary:** 56px height, `Brand Primary` background, White text, 16px radius. Center-aligned 16px SemiBold text.
- **Secondary:** 56px height, `Surface/Card` background, 1px `Border/Default`, 16px radius.
- **Text Button:** No background or border. Use `Brand Primary` text color for active actions or `Text Secondary` for neutral actions.

### Input Fields
- **Standard:** 56px height, 16px radius. Background: `Surface/Card`. Border: 1px `Border/Default`. 
- **Search:** Includes a 20px rounded outline search icon in the leading position.
- **OTP/Phone:** Use numeric keyboard triggers; consistent 56px height across all input types.

### Selection & Chips
- **Time Slot Chips:** 44px height, 12px radius. 
    - *Default:* White background, Default border.
    - *Selected:* Brand Primary background, Brand Primary text (or White).
    - *Unavailable:* Background `#F3EEE8`, Text `Disabled`.

### Cards
- **Dimensions:** Use 20px radius. 
- **Shadow:** Apply the Level 1 shadow (8% opacity).
- **Service Card:** Use a horizontal layout with a 64px square image (12px radius) on the left.
- **Barber/Appointment Card:** Use a vertical layout with high emphasis on the name and status label.

### Navigation
- **Top App Bar:** Transparent or matching Background color. Centered or Left-aligned title. Use 24px rounded outline icons.
- **Bottom Nav:** 84px height (including safe area), White background. Use a 1px top border (`Border/Default`). Icons should be 24px stroke-based, turning to `Brand Primary` when active.

### Icons
- Use **Rounded Outline Icons** with a consistent 1.5pt or 2pt stroke weight. Avoid filled icons unless used as an active state in the navigation bar.