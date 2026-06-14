---
name: Tender Spark
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#504444'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#827473'
  outline-variant: '#d4c2c2'
  surface-tint: '#7b5455'
  primary: '#7b5455'
  on-primary: '#ffffff'
  primary-container: '#f4c2c2'
  on-primary-container: '#734e4e'
  inverse-primary: '#ecbaba'
  secondary: '#5c5d6e'
  on-secondary: '#ffffff'
  secondary-container: '#e1e1f5'
  on-secondary-container: '#626374'
  tertiary: '#74593f'
  on-tertiary: '#ffffff'
  tertiary-container: '#ecc8a8'
  on-tertiary-container: '#6d5239'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad9'
  primary-fixed-dim: '#ecbaba'
  on-primary-fixed: '#2f1314'
  on-primary-fixed-variant: '#613d3e'
  secondary-fixed: '#e1e1f5'
  secondary-fixed-dim: '#c5c5d8'
  on-secondary-fixed: '#191b29'
  on-secondary-fixed-variant: '#444655'
  tertiary-fixed: '#ffdcbe'
  tertiary-fixed-dim: '#e3c0a0'
  on-tertiary-fixed: '#2a1704'
  on-tertiary-fixed-variant: '#5a422a'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
---

## Brand & Style

The design system is centered on the "Tender Spark" narrative—a blend of modern romance and whimsical playfulness. It targets a demographic that appreciates thoughtful, intimate connections over generic romantic gestures. The aesthetic avoids heavy reds and hearts, opting instead for a soft-focus, dreamlike atmosphere that feels both premium and approachable.

The design style is **Modern Glassmorphism**. It utilizes multi-layered translucency to create a sense of depth and lightness, as if the interface is floating on a cloud of pastel gradients. The emotional response should be one of "gentle excitement"—a fluttery, magical feeling conveyed through soft edges, shimmering textures, and subtle bunny-themed motifs that serve as a quiet, playful mascot for the brand.

## Colors

This color palette is designed to evoke warmth and softness without being saccharine.
- **Primary (Blush Pink):** Used for key actions and focal points of affection.
- **Secondary (Lavender):** Used for secondary accents and to bring a "magical" evening quality to the palette.
- **Tertiary (Light Peach):** Used for highlights and micro-interactions to add warmth.
- **Neutral (Cream & Warm White):** The foundational canvas. Avoid pure #FFFFFF; use the warm white for surfaces to maintain a tender, organic feel.

Backgrounds should utilize soft, sweeping radial gradients blending these colors at low opacity (5-10%) to create a dynamic, "shimmering" canvas.

## Typography

The typography pairs the high-contrast elegance of a modern serif with the friendly, rounded legibility of a contemporary sans-serif. 

**Headlines** use a serif font to provide an editorial, romantic feel. Use "Headline-XL" for invitation titles and "Headline-LG" for section headers. **Body text** uses a sans-serif with generous line heights to ensure the content feels airy and easy to digest. **Labels** and small metadata should use slightly increased letter spacing and a semi-bold weight to maintain hierarchy against the soft color palette.

## Layout & Spacing

The layout philosophy follows a **Fluid Grid** with generous white space (negative space) to prevent the UI from feeling cluttered or transactional. 

- **Desktop:** 12-column grid with wide 64px side margins to center the invitation content as a focal point.
- **Mobile:** 4-column grid. The glass cards should stretch nearly edge-to-edge with 20px margins.
- **Rhythm:** Use an 8px base unit. Vertical spacing between sections should be aggressive (80px - 120px) to allow the "magical" background gradients to breathe. 
- **Alignment:** Central alignment is preferred for primary invitation flows to emphasize the personal, formal nature of a date request.

## Elevation & Depth

This design system eschews traditional shadows in favor of **Glassmorphism** and **Tonal Depth**. 

- **Surfaces:** Use semi-transparent white (#FFFFFF at 40-60% opacity) with a `backdrop-filter: blur(20px)`. 
- **Borders:** Apply a 1px solid border at 20% white opacity to define the edges of glass containers. This simulates the "sheen" of a glass edge.
- **Soft Shadows:** When depth is required (e.g., a primary button), use a "Glow Shadow"—a diffused shadow tinted with the primary Blush Pink color (`rgba(244, 194, 194, 0.3)`) rather than black or grey.
- **Layering:** Elements closer to the user should have higher opacity and a slightly more pronounced white border.

## Shapes

The shape language is consistently soft and organic. There are no sharp corners in this design system. 
- **Standard Cards:** Use `rounded-lg` (16px) for the main glassmorphic containers.
- **Buttons & Inputs:** Use `rounded-xl` (24px) or full pill-shaping to reinforce the friendly, safe nature of the experience.
- **Icon Enclosures:** Tiny stars or bunny motifs should be enclosed in circular or organic, "blob-like" shapes rather than squares.

## Components

### Buttons
Primary buttons are pill-shaped, using a Blush Pink to Light Peach gradient. On hover, they should grow slightly (1.05x) and increase their glow shadow. Secondary buttons are "ghost" glass style with a Lavender border.

### Glassmorphic Cards
These are the primary containers for invitation details (Date, Time, Location). They must feature the 20px backdrop blur and a thin, white inner stroke to catch the "light."

### Inputs
Text fields should be soft-tinted Lavender with 40% opacity. Upon focus, the border should transition to a solid Peach and the background blur should intensify.

### Chips/Tags
Used for "vibe" tags (e.g., "Casual," "Sunset," "Surprise"). These should be small, pill-shaped elements in Secondary Lavender with a tiny "sparkle" icon prepended to the text.

### Micro-interactions & Iconography
- **Bunnies:** Minimalist line-art bunnies should appear near "Accept" buttons or in empty states.
- **Stars/Sparkles:** Use CSS animations to make tiny 4-pointed stars slowly pulse or "twinkle" in the corners of glass cards.
- **Transitions:** Use "spring" physics for all modal appearances to give them a light, bouncy, playful quality.