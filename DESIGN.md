---
name: SacroGems Vintage Pop
colors:
  surface: '#fff8f2'
  surface-dim: '#e0d9d1'
  surface-bright: '#fff8f2'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#faf2ea'
  surface-container: '#f4ede5'
  surface-container-high: '#efe7df'
  surface-container-highest: '#e9e1d9'
  on-surface: '#1e1b17'
  on-surface-variant: '#5e3f3b'
  inverse-surface: '#33302b'
  inverse-on-surface: '#f7efe8'
  outline: '#936e69'
  outline-variant: '#e9bcb7'
  surface-tint: '#c00010'
  primary: '#bb000f'
  on-primary: '#ffffff'
  primary-container: '#e80e19'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb4aa'
  secondary: '#8b4b5b'
  on-secondary: '#ffffff'
  secondary-container: '#ffadbf'
  on-secondary-container: '#7b3d4d'
  tertiary: '#b80f18'
  on-tertiary: '#ffffff'
  tertiary-container: '#dd302e'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad5'
  primary-fixed-dim: '#ffb4aa'
  on-primary-fixed: '#410002'
  on-primary-fixed-variant: '#930009'
  secondary-fixed: '#ffd9e0'
  secondary-fixed-dim: '#ffb1c2'
  on-secondary-fixed: '#390819'
  on-secondary-fixed-variant: '#6f3444'
  tertiary-fixed: '#ffdad6'
  tertiary-fixed-dim: '#ffb4ab'
  on-tertiary-fixed: '#410002'
  on-tertiary-fixed-variant: '#93000d'
  background: '#fff8f2'
  on-background: '#1e1b17'
  surface-variant: '#e9e1d9'
typography:
  display-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 56px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Bricolage Grotesque
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Bricolage Grotesque
    fontSize: 22px
    fontWeight: '700'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '500'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.05em
  display-lg-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 36px
    fontWeight: '800'
    lineHeight: '1.1'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin: 32px
  container-max: 1200px
---

## Brand & Style

The design system is a vibrant fusion of **Retro Cartoon** and **Pop-Art Boutique** aesthetics. It is designed to evoke a playful, feminine, and high-energy atmosphere—reminiscent of 1970s vinyl stickers and vintage beauty parlors. The personality is "polished but hand-drawn," balancing thick, rhythmic outlines with a sophisticated color palette.

The visual language focuses on "the sticker effect"—where every UI element feels like a physical object placed on a cream-colored canvas. High-contrast outlines provide structure, while soft-pink offset shadows provide a sense of depth that feels nostalgic and tactile. This is a system built for a youthful, fashion-forward audience that values individual expression and boutique craftsmanship.

## Colors

This palette is anchored in a high-contrast relationship between **Primary Red** and a warm, dairy **Cream Background**. 

- **Primary Red (#F0181E)**: Used for key calls to action, logos, and high-impact accents.
- **Soft Pink & Light Blush**: Used for secondary surfaces, chip backgrounds, and tonal variations to maintain a feminine boutique vibe.
- **Cream & Beige**: These provide the warmth that separates this system from modern, sterile UI. The background should never be pure white.
- **Black Outline (#111111)**: Crucial for the pop-art look. Every interactive component or card must use this for its 2px-3px stroke.
- **Deep Red (#B80F18)**: Reserved for hard shadows on red elements or hover states for buttons.

## Typography

The typography strategy pairs a "character-heavy" display face with a clean, modern geometric sans-serif to ensure legibility is never sacrificed for style.

- **Headlines**: Use **Bricolage Grotesque**. Its idiosyncratic, rounded ink-traps and vintage curves perfectly mirror the hand-drawn nature of the brand.
- **Body & Labels**: Use **Plus Jakarta Sans**. It provides a soft, approachable, and highly readable foundation for service descriptions, booking forms, and pricing.
- **Stylistic Rule**: Headlines should occasionally utilize a slight "wave" or "arc" transformation for hero sections to lean into the vintage sticker aesthetic.

## Layout & Spacing

The layout follows a **Fixed-Grid** philosophy within a 12-column system, but with a "loose" feel created by intentional asymmetry and overlapping elements.

- **The Sticker Grid**: Content is often housed in cards that do not necessarily align perfectly with the vertical rhythm, mimicking stickers tossed on a table.
- **Gutters**: A consistent 24px gutter ensures that despite the bold outlines, the UI has room to breathe.
- **Mobile Reflow**: On mobile, margins reduce to 16px, and the multi-column cards stack vertically. Ensure that the "sparkle" decorative icons reflow to sit between sections as dividers.

## Elevation & Depth

This system rejects ambient, realistic shadows in favor of **Graphic Hard Shadows**.

- **Shadow Style**: 100% opaque shadows offset by 4px to 8px. Use **Soft Pink (#F7A6B8)** for most elements and **Deep Red (#B80F18)** for primary red elements.
- **Sticker Borders**: Every surface (cards, buttons, inputs) must have a **3px solid Black (#111111)** border.
- **Layering**: Higher z-index elements should have a larger shadow offset (e.g., a modal has an 8px offset, while a button has a 4px offset).

## Shapes

The shape language is dominated by **Exaggerated Roundness**. 

- **Primary Radius**: 1rem (16px) is the standard for cards and larger containers.
- **Secondary Radius**: 0.5rem (8px) for input fields and small chips.
- **Iconography**: Icons should be enclosed in circles or "blob" shapes with the same 2px-3px black outline. Use starbursts and 4-point sparkles as recurring decorative motifs to denote "shine" and "gems."

## Components

### Buttons
Buttons are the quintessential "sticker" component. They feature a 3px black border and a 4px hard pink shadow. On hover, the button moves 2px down and right, and the shadow shrinks, creating a tactile "press" effect.

### Input Fields
Inputs use the **Warm Beige (#E8C9B8)** or **White** background with a 2px black border. Focused states change the border color to Primary Red.

### Cards
Cards are the primary container. They should use the **Soft Pink** or **Light Blush** backgrounds. Every card must have a "sparkle" icon positioned in the top-right or bottom-left corner, slightly overlapping the border.

### Chips & Tags
Used for service categories (e.g., "Tooth Gems," "Gold Charms"). These are pill-shaped with a 2px border and no shadow, using the Cream or Beige backgrounds to remain secondary to buttons.

### Sparkle Dividers
Instead of standard horizontal lines, use a row of alternating 4-point stars and small circles in Primary Red to separate sections of content.