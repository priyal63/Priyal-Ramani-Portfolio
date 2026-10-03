---
name: Modern Editorial Portfolio
colors:
  surface: '#fff9f0'
  surface-dim: '#dfd9d1'
  surface-bright: '#fff9f0'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f9f3ea'
  surface-container: '#f3ede4'
  surface-container-high: '#ede7df'
  surface-container-highest: '#e7e2d9'
  on-surface: '#1d1b16'
  on-surface-variant: '#45474c'
  inverse-surface: '#32302a'
  inverse-on-surface: '#f6f0e7'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#555e74'
  primary: '#01081a'
  on-primary: '#ffffff'
  primary-container: '#172033'
  on-primary-container: '#7f879f'
  inverse-primary: '#bdc6e0'
  secondary: '#7e553c'
  on-secondary: '#ffffff'
  secondary-container: '#fec6a7'
  on-secondary-container: '#795038'
  tertiary: '#000b06'
  on-tertiary: '#ffffff'
  tertiary-container: '#00261b'
  on-tertiary-container: '#6a907f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d9e2fc'
  primary-fixed-dim: '#bdc6e0'
  on-primary-fixed: '#121b2e'
  on-primary-fixed-variant: '#3e475b'
  secondary-fixed: '#ffdbc9'
  secondary-fixed-dim: '#f2bb9c'
  on-secondary-fixed: '#301402'
  on-secondary-fixed-variant: '#633e27'
  tertiary-fixed: '#c3ecd9'
  tertiary-fixed-dim: '#a7cfbd'
  on-tertiary-fixed: '#002116'
  on-tertiary-fixed-variant: '#294e40'
  background: '#fff9f0'
  on-background: '#1d1b16'
  surface-variant: '#e7e2d9'
typography:
  display-hero:
    fontFamily: Manrope
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 72px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Manrope
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 44px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Manrope
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Manrope
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.005em
  label-md:
    fontFamily: Manrope
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Manrope
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.06em
  code-snippet:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  gutter-lg: 2.5rem
  margin: 1.5rem
  margin-sm: 1rem
  margin-lg: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style

This design system establishes an editorial, tactile, and expressive identity for a high-caliber creative developer portfolio. The visual direction balances the crisp structure of a premium literary journal with the warmth, playfulness, and tactile intimacy of a boutique design studio. 

The aesthetic is anchored by an organic canvas, structured typography, and an intentional, low-saturation pastel palette. Rather than treating pastel accents as decorative novelties or toy-like flourishes, they serve an architectural role: categorizing technical stacks, distinguishing case study disciplines, and establishing focal points. 

The emotional response should evoke:
- **Quiet Mastery:** High visual restraint, precise line work, and generous negative space that signal technical authority without corporate sterility.
- **Warm Approachability:** A creamy ivory foundation that reduces ocular fatigue and feels organic, tactile, and human.
- **Curated Craft:** An editorial layout rhythm reminiscent of print publications, emphasizing projects as polished stories rather than static cards.

## Colors

The palette operates on a strict distribution model:
- **60% Base Canvas:** Warm Ivory (`#FFF9F0`) serves as the foundational light surface. Sub-surfaces use subtle shifts into pure white (`#FFFFFF`) for elevated cards or `#F7F0E4` for inset code blocks and recessed states.
- **20% Structure & Text:** Deep Navy (`#172033`) drives all primary headlines, dense structural borders, body copy, and iconography. Secondary metadata utilizes Navy at 70% opacity (`rgba(23, 32, 51, 0.70)`), with structural hairpins rendered at 12% opacity (`rgba(23, 32, 51, 0.12)`).
- **20% Contextual Accents:** Deliberate pastel tonalities mapped to project domains, domains of knowledge, and technical taxonomies:
  - **Soft Mint (`#BFE8D5`):** Databases, infrastructure, and technical skill matrices.
  - **Peach (`#FFC7A8`):** Primary interactions, CTAs, interactive hover reveals, and language proficiencies.
  - **Lavender (`#D8CCF5`):** Backend engineering, architecture, and conceptual exploration.
  - **Butter Yellow (`#F6D97A`):** Badges, verification, experimental artifacts, and live markers.
  - **Powder Blue (`#B9D9F5`):** Frontend architecture, client frameworks, and foundational web APIs.
  - **Soft Rose (`#F2C6D4`):** Developer tools, internal libraries, and editorial sidebars.

Accents are never deployed concurrently in dense groupings. Instead, they pair against Warm Ivory and Deep Navy to anchor individual components without creating visual noise.

## Typography

Typography drives the editorial tension within the system. **Manrope** is designated for high-impact structural communication: headlines, titles, navigation items, metrics, and interactive triggers. Its geometric precision and expressive terminal cuts create modern presence and graphic authority.

**Inter** handles all running paragraphs, project summaries, and process documentation. Its neutral, highly legible rhythm balances Manrope's expressive geometry, guaranteeing readability over extended text blocks.

Editorial typographic rules:
- Pair oversized `display-hero` headers directly with subdued, low-opacity `body-lg` introductory paragraphs to establish immediate hierarchy.
- Section tags, category descriptors, and metadata use `label-sm` with explicit tracking and uppercase casing to emulate classic architectural and editorial layout stamps.
- Avoid hyphenation in headlines; maintain tight negative tracking on display sizes to preserve visual cohesion.

## Layout & Spacing

The layout model is built on an asymmetric 12-column editorial grid configured within a maximum container width of `1280px`. 

### Breakpoints & Adaptive Rhythm
- **Mobile (< 768px):** 4 columns, `margin-sm` (1rem / 16px), `gutter-sm` (1rem / 16px). All asymmetric editorial sidebars collapse into vertically stacked sequences. Cards and showcase modules expand to full width.
- **Tablet (768px - 1024px):** 8 columns, `margin` (1.5rem / 24px), `gutter` (1.5rem / 24px). Dual-column arrangements for project lists; metadata appears inline or as top caps above project visuals.
- **Desktop (> 1024px):** 12 columns, `margin-lg` (4rem / 64px), `gutter-lg` (2.5rem / 40px). Enables broad multi-column editorial spreads: 8-column primary project narrative paired with a 4-column sticky metadata anchor (technologies, roles, timeline).

Rhythm guidelines:
- Use generous vertical gaps (`space-2xl` to `space-3xl`) between major portfolio chapters to replicate print spreads and prevent visual fatigue.
- Component-level spacing follows an internal 8px rhythm, using `space-xs` and `space-sm` for badge interiors, and `space-md` through `space-xl` for card paddings.

## Elevation & Depth

Visual depth is communicated primarily through structural framing and soft, tinted ambient diffusion rather than artificial 3D lighting or stark drop shadows.

- **Outlines as Boundaries:** Elevated components (such as project cards, modal drawers, and popovers) use crisp `1px` borders tinted with the core ink color: `rgba(23, 32, 51, 0.12)`. This provides architectural framing over the warm ivory substrate.
- **Ambient Tinted Shadows:** Shadows utilize Deep Navy rather than neutral pitch black, blending softly into the warm base:
  - *Resting Card Elevation:* `0 4px 20px -2px rgba(23, 32, 51, 0.06), 0 1px 4px 0 rgba(23, 32, 51, 0.04)`.
  - *Floating / Hover Elevation:* `0 12px 32px -4px rgba(23, 32, 51, 0.08), 0 2px 8px -1px rgba(23, 32, 51, 0.04)`.
- **Tonal Layers:** Elevation shifts are accompanied by background alterations. While the base canvas sits at `#FFF9F0`, floating cards utilize crisp white (`#FFFFFF`) with accent-tinted interiors or soft pastel fills (e.g., `#BFE8D5` for selected states).
- **Physical Offset Rule:** Interactive cards subtly displace by `-2px` along the Y-axis on hover to create tactile feedback without aggressive scale transforms.

## Shapes

The design system employs a calibrated `roundedness: 2` scale, enforcing specific radii between 12px and 14px for primary surfaces:
- **Base Components & Cards (`rounded-lg`):** Fixed at `14px` (`0.875rem`). This radius softens structural elements without appearing overly bubbly, matching the editorial tone.
- **Inner Sub-elements & Inputs (`rounded`):** Fixed at `10px` (`0.625rem`) to maintain nested geometric harmony inside parent cards.
- **Interactive Badges & Chips (`rounded-full`):** Pill-shaped surfaces (`9999px`) reserved strictly for status chips, technical skill badges, and micro-labels.
- **Buttons:** Unified at `12px` (`0.75rem`), bridging the gap between cards and circular badges to retain clear touch affordances.

## Components

### Buttons
- **Primary:** Deep Navy (`#172033`) background, Warm Ivory (`#FFF9F0`) text, `12px` border radius, font `label-md`. On hover: shifts background to Peach (`#FFC7A8`) with Deep Navy text, supported by a slight `-1px` vertical offset.
- **Secondary / Ghost:** Transparent background, `1px solid rgba(23, 32, 51, 0.12)`, Deep Navy text. On hover: background fills with `rgba(23, 32, 51, 0.04)` and border darkens to `rgba(23, 32, 51, 0.24)`.
- **Accent Action:** Background tinted with contextual category color (e.g., Lavender `#D8CCF5`), Deep Navy text, `1px solid rgba(23, 32, 51, 0.12)`.

### Chips & Badges
- Constructed as pill-shaped items (`rounded-full`) with `4px 12px` padding.
- Text set in `label-sm`.
- Accent variations map directly to role:
  - *Database / Skills:* Soft Mint (`#BFE8D5`) background with `#172033` text.
  - *Engineering / Logic:* Lavender (`#D8CCF5`) background with `#172033` text.
  - *Frontend / UI:* Powder Blue (`#B9D9F5`) background with `#172033` text.
  - *Status / Verification:* Butter Yellow (`#F6D97A`) background with `#172033` text, optional 6px pulsing indicator dot.

### Cards & Project Showcases
- **Container:** Pure white (`#FFFFFF`) or Warm Ivory surface, wrapped in a `1px` border (`rgba(23, 32, 51, 0.12)`), `14px` border radius, and resting elevation shadow.
- **Header:** Features a top row with uppercase category label (`label-sm`), date, and right-aligned accent badge.
- **Content:** Headline (`headline-sm`), followed by 2-line Inter summary (`body-md`).
- **Footer Strip:** Pinned technical stack chips with subtle top divider (`1px solid rgba(23, 32, 51, 0.06)`).

### Input Fields & Controls
- **Inputs:** Clean white interior, `10px` radius, `1px solid rgba(23, 32, 51, 0.12)`. Placeholder text set in Navy at 40% opacity. Focused state triggers a `2px` border highlight in Deep Navy with an ambient outer glow tinted in Powder Blue (`0 0 0 3px rgba(185, 217, 245, 0.45)`).
- **Checkboxes & Radios:** Deep Navy borders (`1.5px`), `4px` radius for checkboxes, circular for radios. When checked, background fills with Deep Navy and displays Warm Ivory glyphs.

### Lists & Index Views
- Editorial index rows: divided by thin horizontal rules (`1px solid rgba(23, 32, 51, 0.12)`).
- Layout: Monospaced numeric index (`01`, `02`), followed by headline (`headline-sm`), client domain, and right-aligned year. Hovering over a row triggers a subtle Peach (`#FFC7A8`) background tint across the row with an instant preview cursor thumbnail.

### Code Snippets & Architecture Blocks
- Recessed `#F7F0E4` background, `10px` radius, `1px solid rgba(23, 32, 51, 0.08)`.
- Syntax tokens rendered exclusively through deep, legible shades of Deep Navy, muted Teal, and Plum, preserving editorial restraint.