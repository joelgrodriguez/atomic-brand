# Atomic Ammunitions — Logo Usage Guidelines

**Internal Brand Reference | Marketing Team**
Version 1.0 | March 2026

---

## 1. Logo Hierarchy

Always start at Tier 1 and only move down when the context demands it.

1. **Primary Logo** (full wordmark + atom) — default for everything. If it fits, use it.
2. **Horizontal Logo** — when vertical space is limited (nav bars, banners, headers).
3. **Monogram (AA)** — when space is tight or the brand is already established in context (social avatars, favicons, app icons, watermarks).
4. **Atom Icon** — decorative or secondary use only (patterns, loading animations, accent marks). Never as the sole brand identifier.
5. **Labs Sub-brand** — R&D / Ballistics Lab content only. Never mix with the primary brand in the same layout.

---

## 2. Background + Color Variant Selection

Choose the logo color variant based on the background it sits on. Maximize contrast and lead with brand green where possible.

### On Gunpowder / Dark Backgrounds

| File | Use When | Background | Notes |
|------|----------|------------|-------|
| `aa-logo-primary` | Default on dark | Gunpowder | First choice always |
| `aa-logo-inverse` | Alternate dark | Dark grays | Subtle tonal variant |
| `aa-monogram-primary` | Small placements | Gunpowder | Blk letters, green atom |
| `aa-atom-green` | Decorative only | Dark | Accent, not identifier |

### On Paper / Light Backgrounds

| File | Use When | Background | Notes |
|------|----------|------------|-------|
| `aa-logo-blk` | Default on light | Paper/White | Full black wordmark |
| `aa-logo-wht-green-text` | Brand emphasis | Paper | Green ATOMIC word pops |
| `aa-monogram-green-wht-atom` | Icons on light | Paper | Green letters, wht atom |
| `aa-atom-blk` | Decorative only | Light | Accent use |

### On Green / Colored Backgrounds

| File | Use When | Background | Notes |
|------|----------|------------|-------|
| `aa-logo-wht` | On Nuclear green | Nuclear | All white for contrast |
| `aa-monogram-wht` | Small on green | Nuclear | All white monogram |
| `aa-logo-blk` | On Concrete gray | Concrete | Dark on mid-tone |

### On Photography / Busy Backgrounds

Use the all-white or all-black variants depending on image darkness. Place a semi-transparent overlay or solid container behind the logo if contrast is insufficient. Never let the logo compete with a busy image.

---

## 3. Usage by Channel

### Website

| Placement | Logo | Details |
|-----------|------|---------|
| Navigation bar | `aa-logo-horizontal` | Horizontal fits nav height. Color per bg. |
| Hero / splash | `aa-logo-primary` | Full primary logo. Centered or left-aligned. |
| Favicon / tab | `aa-monogram-primary` | Monogram at 32x32 or 16x16. |
| Footer | `aa-logo-wht` or `aa-logo-gry` | Subdued on dark footer bg. |

### Social Media

| Placement | Logo | Details |
|-----------|------|---------|
| Profile avatar | `aa-monogram-primary` | Circular crop safe. Green atom reads well small. |
| Cover / banner | `aa-logo-horizontal` | Wide format fits banner aspect ratios. |
| Post watermark | `aa-monogram-wht` (30% opacity) | Subtle brand mark on photos/graphics. |

### Email Signatures & Documents

Use the horizontal logo variant at a max height of 48px. On light email backgrounds, use `aa-logo-horizontal` (dark version). On dark templates, use the white variant. Keep it left-aligned.

### Presentations & Decks

Title slide: primary logo, centered. Interior slides: monogram or horizontal logo in the corner. Dark slides (Gunpowder bg) get primary or white variants. Light slides (Paper bg) get the black variant.

---

## 4. Labs Sub-brand Usage

The Atomic Ammunitions Ballistics Lab is the R&D studio arm of the brand. It has its own logo set and should be treated as a distinct identity that lives under the parent brand.

### When to Use Labs Logos

- R&D publications, white papers, and technical reports
- Lab testing documentation and certifications
- Internal R&D tools, dashboards, or portals
- Experimental product lines or prototypes

### When NOT to Use Labs Logos

- Consumer-facing marketing (use primary brand)
- Social media profiles (use primary brand)
- Never combine Labs and primary logos in the same layout or lockup

### Labs Logo Variants

| File | Background | Notes |
|------|------------|-------|
| `aa-lab-ballistics` | With background | Self-contained badge with built-in bg |
| `aa-lab-ballistics-nobg` | Light backgrounds | Transparent, dark elements |
| `aa-lab-ballistics-nobg-wht` | Dark backgrounds | Transparent, white elements |
| `aa-lab-logo` / `aa-lab-logo-wht` | Light / Dark | Alternate lab wordmark style |

---

## 5. Brand Color Reference

### Primary Accents

| Swatch | Name | Hex | Usage |
|--------|------|-----|-------|
| ![#32CD32](https://via.placeholder.com/16/32CD32/32CD32) | Nuclear | `#32CD32` | Primary brand accent. Logo text, CTAs, links. |
| ![#28A428](https://via.placeholder.com/16/28A428/28A428) | Nuclear Muted | `#28A428` | Hover states, secondary green elements. |
| ![#FFB000](https://via.placeholder.com/16/FFB000/FFB000) | Signal | `#FFB000` | Warnings, highlights, promotional callouts. |
| ![#CC8D00](https://via.placeholder.com/16/CC8D00/CC8D00) | Signal Muted | `#CC8D00` | Hover states for signal elements. |
| ![#ED1C24](https://via.placeholder.com/16/ED1C24/ED1C24) | Tracer | `#ED1C24` | Errors, alerts, urgency, sale tags. |
| ![#BE1620](https://via.placeholder.com/16/BE1620/BE1620) | Tracer Muted | `#BE1620` | Hover states for tracer elements. |

### Neutrals (Light to Dark)

| Swatch | Name | Hex | Usage |
|--------|------|-----|-------|
| ![#FAFBFB](https://via.placeholder.com/16/FAFBFB/FAFBFB) | Paper | `#FAFBFB` | Light backgrounds, cards, content areas. |
| ![#E5E5E5](https://via.placeholder.com/16/E5E5E5/E5E5E5) | Concrete | `#E5E5E5` | Borders, dividers, subtle backgrounds. |
| ![#CCCCCC](https://via.placeholder.com/16/CCCCCC/CCCCCC) | Washout | `#CCCCCC` | Disabled text, placeholder text. |
| ![#8E8E93](https://via.placeholder.com/16/8E8E93/8E8E93) | Steel | `#8E8E93` | Secondary text, captions, metadata. |
| ![#6B6B70](https://via.placeholder.com/16/6B6B70/6B6B70) | Slate | `#6B6B70` | Body text alternative, labels. |
| ![#404040](https://via.placeholder.com/16/404040/404040) | Gunmetal | `#404040` | Primary body text, borders. |
| ![#0D0D0D](https://via.placeholder.com/16/0D0D0D/0D0D0D) | Gunpowder | `#0D0D0D` | Dark backgrounds, headers, footers. |

---

## 6. Clear Space & Minimum Size

Maintain clear space equal to the height of the atom icon on all sides of any logo variant. No other graphic elements, text, or edges should encroach on this space.

### Minimum Sizes (Digital)

| Logo Type | Min Width | Notes |
|-----------|-----------|-------|
| Primary | 200px | Below this, AMMUNITIONS is illegible |
| Horizontal | 180px | Good for navs at 36-48px height |
| Monogram | 32px | Favicon-safe at 16px |
| Atom Icon | 24px | Decorative only at this size |

---

## 7. Do / Don't

### Do

- Use SVG for all digital placements (scales without quality loss)
- Match the color variant to the background (see Section 2)
- Maintain clear space on all sides
- Start with the primary logo and only move down the hierarchy when needed
- Keep the Labs brand separate from the main brand

### Don't

- Rotate, skew, stretch, or distort any logo
- Change the logo colors outside of the provided variants
- Place the logo on low-contrast backgrounds without an overlay
- Use the atom icon alone as the brand identifier
- Add drop shadows, outlines, or effects to the logo
- Place the logo smaller than minimum size
- Mix Labs logos with primary brand logos in the same layout

---

## 8. Complete File Reference

All files are SVG format. Print-ready formats (EPS, PDF, high-res PNG) will be added in a future version.

### `primary/`

- `aa-logo-primary.svg` — Standard (green ATOMIC, dark elements)
- `aa-logo-inverse.svg` — Tonal dark variant
- `aa-logo-blk.svg` — All black
- `aa-logo-wht.svg` — All white
- `aa-logo-wht-green-text.svg` — Green ATOMIC word, white everything else
- `aa-logo-wht-green-atom.svg` — Green atom symbol, white everything else

### `horizontal/`

- `aa-logo-horizontal.svg` — Standard 2-color horizontal lockup
- `aa-logo-horizontal-alt.svg` — 3-color variant (two greens)

### `monogram/`

- `aa-monogram-primary.svg` — Black letters/bullet, green atom
- `aa-monogram-green-wht-atom.svg` — Green letters/bullet, white atom
- `aa-monogram-wht-green-atom.svg` — White letters/bullet, green atom
- `aa-monogram-blk.svg` — All black
- `aa-monogram-gry.svg` — All grey
- `aa-monogram-wht.svg` — All white

### `atom/`

- `aa-atom-green.svg` — Green atom symbol
- `aa-atom-blk.svg` — Black atom symbol
- `aa-atom-gry.svg` — Grey atom symbol
- `aa-atom-wash.svg` — Wash/faded variant
- `aa-atom-design.svg` / `.png` — Full design reference file

### `labs/`

- `aa-lab-ballistics.svg` — With built-in background
- `aa-lab-ballistics-nobg.svg` — Transparent, dark elements
- `aa-lab-ballistics-nobg-wht.svg` — Transparent, white elements
- `aa-lab-logo.svg` — Alternate lab wordmark, dark
- `aa-lab-logo-wht.svg` — Alternate lab wordmark, white
