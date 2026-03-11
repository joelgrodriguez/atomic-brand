# Atomic Ammunitions — Brand Manifesto & Design Specification

**Internal Brand Reference | Marketing Team**
Version 1.0 | March 2026

---

## 1. Brand Identity

Atomic Ammunitions is not a heritage sporting goods company. It operates with the precision, intensity, and visual language of a high-end ballistics R&D laboratory — think what would happen if Apple ran the Manhattan Project. Every touchpoint should feel engineered, issued, and classified rather than marketed.

**The vibe:** Space-industrial, hyper-tactical, utilitarian, engineered. Equal parts defense contractor and consumer tech. Clean like Cupertino, lethal like Los Alamos.

**The look:** Blueprint schematics, technical data sheets, high-contrast caution signals, and precision grid systems. Design elements should feel stamped, machined, or issued — never merely printed. Form follows function. Data is the decoration. If it doesn't communicate technical data or operational purpose, remove it.

**Reference points:** Anduril Industries, Skunkworks, Weyland-Yutani, Braun/Dieter Rams, Apple product packaging.

---

## 2. Typography System

Typography is clinical, highly legible, and structured like a military dossier. See `brand-typography.md` for the full type scale, weights, and implementation details.

| Role | Typeface | When |
|------|----------|------|
| Headings, numbers, data, accents | **Roboto Mono** | Calibers, lot numbers, specs, classifications, headings, buttons, tags, pricing |
| Body copy | **Roboto** | Paragraphs, descriptions, warning labels, dense readable text |

### Formatting Rules

- **Uppercase** for all headers and data points
- **Double tactical slashes** (`//`) as separators instead of commas or hyphens: `168GR // HP BT // 2600 FPS`
- Roboto Mono enforces the terminal/blueprint aesthetic — use it anywhere data needs to feel precise and engineered

---

## 3. Color System

The palette splits into two categories: Signal Colors for categorization and alerts, and the Tactical Grayscale for structural architecture. See `brand-colors.md` for full hex values, CSS classes, and pairing rules.

### Signal Colors (Categorization)

| Name | Hex | Role |
|------|-----|------|
| Nuclear | `#32CD32` | Duty classification. Synthetic, high-visibility green. Active deployment. |
| Signal | `#FFB000` | Hunting classification. Hazard amber. Field-ready payloads. |
| Tracer | `#ED1C24` | Match classification. Maximum precision, competition-grade. |

### Tactical Grayscale (Architecture)

| Name | Hex | Role |
|------|-----|------|
| Paper | `#FAFBFB` | Knockouts, barcodes, highest-contrast badges |
| Concrete | `#E5E5E5` | Standard background flood for civilian/standard-issue blueprint layouts |
| Washout | `#CCCCCC` | Background watermarks and architectural gridlines on Concrete |
| Steel | `#8E8E93` | Secondary accents, deactivated structural lines |
| Gunmetal | `#404040` | Muted text, stealth gridlines on dark packaging, secondary badges |
| Gunpowder | `#0D0D0D` | Anchor color. Primary typography, heavy borders, tactical packaging floods |

---

## 4. Divisions & Quadrant System

The brand is organized into two divisions, each containing two product quadrants. The quadrants are styled as **element symbols** — short abbreviations in a square or badge, reminiscent of the periodic table. This reinforces the scientific/lab identity of the brand.

### Division Structure

```
ATOMIC AMMUNITIONS
├── OPERATOR (Professional / Defense)
│   ├── Ta  — Tactical
│   └── Du  — Duty
└── MARKSMAN (Precision / Field)
    ├── Hu  — Hunting
    └── Ma  — Match
```

### The Quadrants

Each quadrant has its own element symbol, signature color, and persona.

---

#### `Ta` — Tactical

**Division:** Operator
**Color:** Gunpowder `#0D0D0D`
**Background:** Deep black flood
**Persona:** Stealth. Premium tactical performance. Specialized operations. Suppressed, nighttime, close-quarters.

The Tactical line uses the darkest end of the palette. Packaging is near-black with minimal contrast — information is revealed through subtle material changes, debossed marks, or low-contrast Gunmetal type. It should feel classified.

---

#### `Du` — Duty

**Division:** Operator
**Color:** Nuclear `#32CD32`
**Background:** Nuclear green flood or heavy green accents on Gunpowder
**Persona:** High-stakes, law-enforcement-grade, active deployment. The line that goes to work every day.

Duty is the most visible of the Operator lines. The Nuclear green is aggressive and synthetic — it signals readiness and lethality without subtlety. Think caution tape, reactor glow, night-vision phosphor.

---

#### `Hu` — Hunting

**Division:** Marksman
**Color:** Signal `#FFB000`
**Background:** Signal amber accents on Concrete or Gunpowder
**Persona:** Field-ready, high-yield, specialized ballistic payloads. Engineered for the wild, not the range.

The Hunting line uses amber as a wayfinding color — it cuts through visual noise the way blaze orange cuts through a tree line. Packaging leans on the blueprint/schematic aesthetic with Signal accents marking key data points.

---

#### `Ma` — Match

**Division:** Marksman
**Color:** Tracer `#ED1C24`
**Background:** Tracer red accents on Concrete or Paper
**Persona:** Competition-grade, exact-tolerance, engineered precision. Every grain measured, every lot verified.

Match is the prestige line. Red signals both danger and refinement — this is ammunition for shooters who care about sub-MOA groups and lot consistency. Packaging should feel like a technical data sheet from a metrology lab.

---

### Element Symbol Styling

The quadrant abbreviations (`Ta`, `Du`, `Hu`, `Ma`) are rendered as element-style badges:

```
┌──────┐
│  Ta  │
│      │
│TACTICAL│
└──────┘
```

- **Symbol text:** Roboto Mono, Bold, large (the two-letter abbreviation)
- **Label text:** Roboto Mono, Medium, small caps, below the symbol
- **Border:** 1–2px solid stroke in the quadrant's signature color
- **Background:** transparent or filled with the quadrant's signature color depending on context
- On dark backgrounds, the badge border and text use the signature color
- On light backgrounds, the badge may be filled with the signature color, text knocked out to white

These badges appear on packaging, product pages, marketing materials, and navigation as category identifiers.

---

## 5. Design Anatomy & Rules

Every asset produced for Atomic Ammunitions must follow these structural laws.

### The Grid

All packaging and digital assets sit on an architectural grid. Elements snap to sharp, mathematical alignments — flush left or flush right. No centered-and-floating layouts. The grid should be visible in the design DNA even when gridlines aren't literally shown.

### The Classification Block

Every product features a clear classification block (top-right or bottom-left) detailing the exact round purpose:

```
CUSTOM COMPETITION // CENTERFIRE
168GR // HP BT // 2600 FPS
LOT 2026-0312 // QTY 20
```

Always Roboto Mono. Always uppercase. Always separated with `//`.

### The Element Badge

Every product and product page must display the appropriate quadrant element badge (`Ta`, `Du`, `Hu`, `Ma`) as a primary categorization mark. It should be one of the first things the eye hits.

### No Frills

- No drop shadows
- No gradients
- No friendly marketing copy or lifestyle imagery
- No decorative elements that don't communicate data
- Information is king — if it doesn't serve a technical or operational purpose, cut it

---

## 6. Voice & Tone

The brand voice is clinical, confident, and sparse. It reads like a technical brief, not an ad.

**Do:** "168-grain hollow point boat tail. Match-grade brass. Lot-verified to ±0.3 grain."

**Don't:** "Our premium ammunition delivers incredible accuracy for the discerning shooter!"

- Use specifications as copy. The data sells itself.
- Use imperative statements when addressing the user: "Select your configuration." "Verify lot number."
- Avoid superlatives (best, ultimate, incredible). Let the numbers speak.
- When longer copy is required, keep sentences short and declarative. No fluff.

---

## 7. Document Index

All brand reference documents live in `logo/docs/`:

| File | Contents |
|------|----------|
| `brand-manifesto.md` | This document — identity, divisions, design rules |
| `brand-colors.md` | Full color palette, CSS classes, pairing rules, contrast notes |
| `brand-typography.md` | Type scale, weights, formatting rules, CSS/Tailwind implementation |
| `logo-usage-guidelines.md` | Logo hierarchy, background selection, channel usage, file reference |
| `aa-logo-usage-guidelines.docx` | Logo guidelines (Word format) |
| `packaging-spec.md` | Box layout anatomy, quadrant backgrounds, tag color logic, zone map |
