---
name: Structural Kinetic
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#44474d'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#75777e'
  outline-variant: '#c5c6cd'
  surface-tint: '#515f78'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#0d1c32'
  on-primary-container: '#76849f'
  inverse-primary: '#b9c7e4'
  secondary: '#a04100'
  on-secondary: '#ffffff'
  secondary-container: '#fe6b00'
  on-secondary-container: '#572000'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#101d25'
  on-tertiary-container: '#788690'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b9c7e4'
  on-primary-fixed: '#0d1c32'
  on-primary-fixed-variant: '#39475f'
  secondary-fixed: '#ffdbcc'
  secondary-fixed-dim: '#ffb693'
  on-secondary-fixed: '#351000'
  on-secondary-fixed-variant: '#7a3000'
  tertiary-fixed: '#d6e4f0'
  tertiary-fixed-dim: '#bbc8d3'
  on-tertiary-fixed: '#101d25'
  on-tertiary-fixed-variant: '#3b4851'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
  slate-blue: '#3A4750'
  surface-off-white: '#F8F9FA'
  deep-navy-dark: '#060D1A'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 80px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
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
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
  stats-number:
    fontFamily: Inter
    fontSize: 56px
    fontWeight: '800'
    lineHeight: '1'
    letterSpacing: -0.03em
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style
The design system is engineered for a high-end construction solutions firm, blending the unwavering stability of structural engineering with the forward momentum of innovative technology. The brand personality is authoritative yet visionary—evoking the feeling of a massive, well-oiled machine that operates with surgical precision.

The visual style is **Corporate Modern with Parametric influences**. It utilizes high-contrast layouts, heavy-weight typography, and technical grid structures to communicate industrial strength. Motion is a core tenet; containers should feel like they are part of an assembly, utilizing "Motion-ready" transitions where elements slide or scale along rigid axes. The aesthetic avoids unnecessary decoration, favoring functional aesthetics, clean lines, and an "industrial-premium" finish.

## Colors
The palette is anchored in **Deep Navy (#0A192F)**, providing a sense of depth and permanence. **Safety Orange (#FF6B00)** is used surgically for high-visibility actions, status indicators, and key structural accents, mirroring the visual language of a construction site.

**Slate Blue (#3A4750)** serves as a bridge between the primary navy and the light backgrounds, ideal for secondary structural elements or iconography. Backgrounds are primarily **Clean White (#FFFFFF)** to ensure maximum readability, with **Steel Gray (#E0E0E0)** and **Surface Off-White** utilized for section differentiation and "blueprint" style container backgrounds.

## Typography
The typography system uses **Inter** for its neutral, highly legible, and industrial-modern character. To emphasize engineering precision, **JetBrains Mono** is introduced for labels, metadata, and technical specifications, providing a "data-driven" aesthetic.

Headlines should be set with tight tracking (letter-spacing) to feel dense and structural. Large display styles should utilize the "Extra Bold" or "Black" weights to command attention, while body text remains clean and spacious for professional clarity.

## Layout & Spacing
The layout follows a **Parametric 12-column grid**. Instead of standard fluid containers, the design system encourages "asymmetric balance"—where content spans specific column ranges (e.g., columns 1-7 for imagery, 8-12 for text) to create a dynamic, engineered feel.

Margins and gutters are generous to provide an "architectural" sense of space. Spacing follows a strict 8px base unit. On mobile, the grid collapses to a single column with a 20px safety margin, but retains "bleeding" elements that extend to the edge of the screen to maintain the dynamic energy of the desktop experience.

## Elevation & Depth
Elevation is conveyed through **Tonal Layering** and **Subtle Direct Shadows**. Surfaces do not "float" high above the background; instead, they feel like stacked slabs or panels.

- **Level 1 (Base):** Clean White or Steel Gray background.
- **Level 2 (In-set):** Subtly darker gray areas that look recessed into the page.
- **Level 3 (Raised):** Deep Navy or White panels with a crisp 1px border (#E0E0E0) and a soft, tight shadow (0px 4px 12px rgba(10, 25, 47, 0.08)).
- **Interactive Depth:** On hover, service modules should "lift" by increasing shadow spread and shifting 4px upwards, simulating a mechanical engagement.

## Shapes
In alignment with the construction and engineering theme, the shape language is **Sharp (0px radius)**. This reinforces the concepts of precision, structural integrity, and industrial strength. Avoid any rounded corners on buttons, inputs, or cards. Diagonal chamfers (clipped corners) may be used on primary display elements to evoke a blueprint or heavy-machinery aesthetic.

## Components
- **Buttons:** Sharp-cornered, high-contrast blocks. Primary buttons use Deep Navy background with White text; CTAs use Safety Orange. Implement a "shutter" fill animation on hover where the color slides in from the left.
- **Service Modules (Cards):** Large, white containers with 1px Steel Gray borders. Use a JetBrains Mono label at the top right to indicate a category or "Module ID."
- **Input Fields:** Thick 2px bottom borders in Slate Blue, turning Safety Orange on focus. No top or side borders to keep the "technical drawing" feel.
- **Progress/Metric Bars:** Use Safety Orange for fill, with a Steel Gray track. The fill should have a subtle diagonal stripe pattern (hazard style) to indicate "work in progress" or active engineering.
- **Interactive Grids:** Use 1px lines to create a subtle background grid across the entire site, similar to graph paper or CAD software, helping align all components to a single source of truth.