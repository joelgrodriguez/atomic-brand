# Atomic Ammunitions — Brand Typography

**Internal Brand Reference | Marketing Team**
Version 1.0 | March 2026

---

## Typeface System

Atomic Ammunitions uses a two-font system built on the Roboto family for consistency and broad platform support.

| Role | Typeface | Weights | Google Fonts |
|------|----------|---------|--------------|
| Body / Copy | Roboto | Regular (400), Medium (500), Bold (700) | [Roboto](https://fonts.google.com/specimen/Roboto) |
| Headings / Numbers / Accents | Roboto Mono | Regular (400), Medium (500), Bold (700) | [Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono) |

---

## When to Use Each

### Roboto (Body)

The default for all running text. Use it anywhere the reader needs to absorb information comfortably.

- Paragraphs and body copy
- Descriptions and long-form content
- Navigation labels and menus
- Form labels and input text
- Tooltips and helper text
- Email body content

### Roboto Mono (Headings / Numbers / Accents)

The technical, precision feel of a monospace font reinforces the brand's ammunition and engineering identity. Use it for anything that should feel sharp and intentional.

- **Headings** — H1 through H4, page titles, section headers
- **Numbers** — pricing, stats, data callouts, countdowns, quantities, caliber specs
- **Accents** — tags, badges, labels, category names, nav highlights
- **Technical content** — product specs, SKUs, lot numbers, serial numbers
- **Code / data** — inline code, tables with numeric data, technical readouts
- **CTAs** — button text (uppercase, medium or bold weight)

---

## Type Scale

### Web / Digital

| Element | Typeface | Weight | Size | Line Height | Letter Spacing |
|---------|----------|--------|------|-------------|----------------|
| H1 | Roboto Mono | Bold (700) | 48px / 3rem | 1.1 | -0.02em |
| H2 | Roboto Mono | Bold (700) | 36px / 2.25rem | 1.15 | -0.01em |
| H3 | Roboto Mono | Medium (500) | 28px / 1.75rem | 1.2 | 0 |
| H4 | Roboto Mono | Medium (500) | 22px / 1.375rem | 1.3 | 0 |
| Body | Roboto | Regular (400) | 16px / 1rem | 1.6 | 0 |
| Body (small) | Roboto | Regular (400) | 14px / 0.875rem | 1.5 | 0 |
| Caption | Roboto | Regular (400) | 12px / 0.75rem | 1.4 | 0.01em |
| Button | Roboto Mono | Medium (500) | 14px / 0.875rem | 1 | 0.05em |
| Number callout | Roboto Mono | Bold (700) | 56px / 3.5rem | 1 | -0.02em |
| Tag / badge | Roboto Mono | Medium (500) | 11px / 0.6875rem | 1 | 0.08em |

### Print

Scale up by ~25% from digital sizes for comfortable reading at arm's length. Body copy should be no smaller than 10pt Roboto.

---

## Formatting Rules

### Headings

- Always Roboto Mono
- H1 and H2: Bold weight
- H3 and H4: Medium weight
- Color: Gunpowder `#0D0D0D` on light backgrounds, Paper `#FAFBFB` on dark backgrounds
- Nuclear `#32CD32` may be used for accent headings or subheadings sparingly

### Body Copy

- Always Roboto
- Regular weight for body text, Medium for emphasis, Bold for strong emphasis
- Color: Gunmetal `#404040` on light backgrounds, Paper `#FAFBFB` on dark backgrounds
- Max line width: 72 characters (approximately 720px at 16px body size)

### Numbers and Data

- Always Roboto Mono, regardless of surrounding text
- Use tabular figures (monospaced digits) for alignment in tables and columns
- Large stat callouts: Bold 700, Nuclear green `#32CD32` for emphasis or Gunpowder for neutral

### Buttons and CTAs

- Roboto Mono, Medium 500
- Uppercase with `letter-spacing: 0.05em`
- 14px minimum size for readability

### Tags, Badges, and Labels

- Roboto Mono, Medium 500
- Uppercase with `letter-spacing: 0.08em`
- 11px minimum, paired with appropriate padding

---

## CSS Implementation

```css
/* Import */
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&family=Roboto+Mono:wght@400;500;700&display=swap');

/* Base */
body {
  font-family: 'Roboto', sans-serif;
  font-size: 16px;
  line-height: 1.6;
  color: #404040;
}

/* Headings */
h1, h2, h3, h4 {
  font-family: 'Roboto Mono', monospace;
  color: #0D0D0D;
}

h1, h2 { font-weight: 700; }
h3, h4 { font-weight: 500; }

/* Numbers and data */
.stat, .price, .spec, .quantity {
  font-family: 'Roboto Mono', monospace;
}

/* Buttons */
.btn {
  font-family: 'Roboto Mono', monospace;
  font-weight: 500;
  font-size: 14px;
  text-transform: uppercase;
  letter-spacing: 0.05em;
}

/* Tags */
.tag, .badge {
  font-family: 'Roboto Mono', monospace;
  font-weight: 500;
  font-size: 11px;
  text-transform: uppercase;
  letter-spacing: 0.08em;
}
```

---

## Tailwind Config

```js
// tailwind.config.js
module.exports = {
  theme: {
    fontFamily: {
      sans: ['Roboto', 'sans-serif'],
      mono: ['Roboto Mono', 'monospace'],
    },
  },
}
```

Usage: `font-sans` for body, `font-mono` for headings/numbers/accents.

---

## Don'ts

- Don't use Roboto for headings — always Roboto Mono
- Don't use Roboto Mono for body paragraphs — it reduces readability at length
- Don't mix other typefaces into the system without brand approval
- Don't use light weights (300 or below) — they lack presence at the brand's scale
- Don't set body copy below 14px on web or 10pt in print
- Don't use italic Roboto Mono — it undermines the precision feel; use Regular or Medium instead
