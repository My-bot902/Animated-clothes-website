---
name: Linen & Loom
colors:
  surface: '#fbf9f9'
  surface-dim: '#dbdad9'
  surface-bright: '#fbf9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#e9e8e7'
  surface-container-highest: '#e3e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#444748'
  inverse-surface: '#303031'
  inverse-on-surface: '#f2f0f0'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#0a0a0a'
  on-primary: '#ffffff'
  primary-container: '#212121'
  on-primary-container: '#898888'
  inverse-primary: '#c8c6c5'
  secondary: '#695d4a'
  on-secondary: '#ffffff'
  secondary-container: '#f2e0c8'
  on-secondary-container: '#6f6350'
  tertiary: '#0b0a09'
  on-tertiary: '#ffffff'
  tertiary-container: '#222120'
  on-tertiary-container: '#8b8886'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1b1c1c'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#f2e0c8'
  secondary-fixed-dim: '#d5c4ad'
  on-secondary-fixed: '#231a0c'
  on-secondary-fixed-variant: '#504534'
  tertiary-fixed: '#e6e2e0'
  tertiary-fixed-dim: '#c9c6c4'
  on-tertiary-fixed: '#1c1b1a'
  on-tertiary-fixed-variant: '#484645'
  background: '#fbf9f9'
  on-background: '#1b1c1c'
  surface-variant: '#e3e2e2'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '600'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 48px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
  price-tag:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 24px
spacing:
  base: 8px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 80px
  container-max: 1440px
---

## Brand & Style

The design system is rooted in the philosophy of **Modern Minimalism** with a focus on editorial elegance. It is designed for a discerning male clientele who appreciates the heritage of unstitched fabric but seeks a contemporary shopping experience. The visual language evokes a sense of "quiet luxury"—calm, confident, and meticulously curated.

Key stylistic pillars include:
- **Breathable Whitespace:** Generous margins and padding that allow the fabric textures and photography to breathe.
- **Editorial Typography:** High-contrast serif headings that mirror luxury tailoring and heritage brand marks.
- **Subtle Tactility:** Low-contrast borders and tonal shifts that suggest a physical, paper-like quality rather than a digital interface.
- **Non-Corporate Professionalism:** Avoiding generic SaaS-like patterns in favor of boutique, gallery-inspired layouts.

## Colors

The palette is intentionally restrained to keep the focus on product photography. 

- **Primary (Dark Charcoal - #212121):** Used for all primary text, icons, and high-emphasis interactive elements.
- **Secondary (Twill - #8C7E6A):** A muted, warm earthy tone used for subtle accents, success states, or active indicators that require a softer touch than black.
- **Background (Parchment - #F9F6F0):** A warm off-white that reduces eye strain and provides a premium, "gallery" feel compared to stark pure white.
- **Neutral (Slate Grey - #757575):** Used for secondary information, meta-data, and placeholder text to maintain a clear hierarchy.
- **Surface (Ghost - #EBE7DF):** Used for very subtle section dividers and input field backgrounds.

## Typography

The typography strategy relies on the tension between the classic, high-contrast **Playfair Display** (Serif) and the precision-engineered **Hanken Grotesk** (Sans-Serif).

- **Headlines:** Always use Playfair Display. Display sizes should utilize tighter letter spacing to create a sense of bespoke craftsmanship.
- **Body:** Hanken Grotesk provides a clean, neutral base. Maintain generous line height (1.5x minimum) to ensure long descriptions of fabric weave and weight remain legible.
- **Labels:** Use uppercase Hanken Grotesk with 10% letter spacing for small UI elements like category labels, badges, and the 3-step guide icons to create an organized, architectural feel.

## Layout & Spacing

This design system utilizes a **12-column fixed grid** for desktop and a **fluid 4-column grid** for mobile.

- **The "Breathe" Principle:** Vertical spacing between sections should be aggressive (80px to 120px) to maintain the premium, minimalist aesthetic.
- **Product Grids:** On desktop, use a 3-column layout to allow product cards to be large enough to showcase fabric texture. On mobile, transition to a single-column view to maximize image size.
- **Safe Zones:** Content containers should never exceed 1440px to ensure line lengths for body text remain optimal for readability.

## Elevation & Depth

This design system avoids traditional shadows in favor of **Tonal Layering** and **Ghost Outlines**.

- **Surfaces:** Depth is created by placing #F9F6F0 cards on top of #EBE7DF sections. 
- **Borders:** Use very thin (1px) borders in a slightly darker shade than the background (#DED9CE) to define cards.
- **Interaction:** Upon hover, product cards should not "lift" with a shadow. Instead, the border should darken to Primary Charcoal or the image should subtly scale (1.02x) within its frame to signal interactivity.

## Shapes

The design system adopts a **Sharp (0px)** roundedness profile. This "hard edge" approach reinforces the professional, architectural nature of men's tailoring and premium fashion.

- **Buttons & Inputs:** Strictly rectangular with no corner radius.
- **Product Images:** Sharp edges to mimic the look of fabric swatches and editorial magazine layouts.
- **Color Dots:** The only exception to the sharp rule are the product color selection dots, which should be perfect circles to differentiate them as interactive color swatches.

## Components

### Sticky Navigation
The header is a slim, #F9F6F0 semi-transparent bar with a `backdrop-filter: blur(10px)`. It features a centered logo in Playfair Display and minimalist text links in Hanken Grotesk.

### Product Cards
Large-scale cards where the image occupies 85% of the card area.
- **Price Tag:** Positioned bottom-left in `price-tag` style.
- **Color Swatches:** Small circles (16px) positioned bottom-right, with a 1px border when selected.
- **Interaction:** Hovering reveals a "Quick View" button in a solid Primary Charcoal block.

### 3-Step Guide Icons
Icons should be thin-stroke (1px) monolinear illustrations. They are paired with `label-caps` titles and `body-md` descriptions. These are placed in a horizontal row with centered alignment to explain the "Choose, Customize, Receive" process.

### Buttons
- **Primary:** Solid Primary Charcoal background with Parchment text. No border.
- **Secondary:** Transparent background with a 1px Primary Charcoal border. 
- **Action:** All buttons are full-width on mobile to improve ergonomics.

### Input Fields
Inputs use a "bottom-border only" style to maintain the clean, minimalist look. Labels should float above the line in `label-caps`.