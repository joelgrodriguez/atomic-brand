# Atomic Ammunitions — Packaging Specification

**Internal Brand Reference | Marketing Team**
Version 1.0 | March 2026

---

## 1. Box Anatomy

Every box follows the same layout grid regardless of quadrant. The system is modular — what changes between quadrants is color, not structure.

```
┌─────────────────────────────────────────────────────────────┐
│▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓ TOP BAND (Gunpowder) ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓│
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  [LOGO]                              [DIVISION] [QUADRANT]  │
│  Atomic Ammunitions                                         │
│                                   CLASSIFICATION // LINE    │
│                                                             │
│  CALIBER NAME                          ┌─────────────────┐  │
│                                        │                 │  │
│  WEIGHT // TYPE // VELOCITY            │   AA MONOGRAM   │  │
│                                        │   WATERMARK     │  │
│  [TAG] [TAG] [TAG] [QTY]              │                 │  │
│                                        └─────────────────┘  │
│                                                             │
│  ┌──────────────────┐                                       │
│  │ Aa │ BALLISTICS   │                    ┌──────────┐      │
│  │    │ LAB //       │                    │ MADE IN  │      │
│  │    │ DEPT OF R&D  │                    │ USA      │      │
│  └──────────────────┘                    └──────────┘      │
│                                                             │
├─────────────────────────────────────────────────────────────┤
│▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓ BOTTOM BAND (Gunpowder) ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓│
└─────────────────────────────────────────────────────────────┘
```

---

## 2. Quadrant Backgrounds

The body panel between the top and bottom Gunpowder bands changes per quadrant. This is the primary visual differentiator on shelf.

| Quadrant | Body Background | Grid Lines | Logo Color | Text Color | Notes |
|----------|----------------|------------|------------|------------|-------|
| `Ta` Tactical | Gunpowder `#0D0D0D` | Gunmetal `#404040` (stealth) | White logo, green accents | White / Steel | Dark-on-dark. Grid barely visible. Classified feel. |
| `Du` Duty | Nuclear `#32CD32` | Darker green tint | White logo | White / Gunpowder | Full green flood. Most aggressive shelf presence. |
| `Hu` Hunting | Concrete `#E5E5E5` | Washout `#CCCCCC` | Dark logo, green accents | Gunpowder | Light blueprint. Signal amber accents on tags. |
| `Ma` Match | Concrete `#E5E5E5` | Washout `#CCCCCC` | Dark logo, green accents | Gunpowder | Light blueprint. Tracer red accents on tags. |

### Key Observations

- **Operator boxes (Ta, Du) are dark.** Ta is near-black, Du is saturated green. Both use white text and white logo.
- **Marksman boxes (Hu, Ma) are light.** Both use the Concrete/grid background with dark text. They differentiate through tag color — amber for Hu, red for Ma.
- The Gunpowder top and bottom bands are constant across all four quadrants — they frame every box identically.

---

## 3. Layout Zones

### Zone A — Top Left: Brand Logo

- Atomic Ammunitions primary logo (horizontal lockup or stacked)
- On dark boxes (Ta, Du): white logo with green atom accents
- On light boxes (Hu, Ma): dark logo with green atom accents
- Positioned flush left, below the top Gunpowder band

### Zone B — Top Right: Division + Quadrant Badge

- Division label: `OPERATOR` or `MARKSMAN` in a dark pill/badge
- Quadrant element badge immediately adjacent: `Ta`, `Du`, `Hu`, or `Ma`
- Element badge fill color matches the quadrant's signature color
- Below the badge: classification line in `//` format (e.g., `CUSTOM // COMPETITION // CENTERFIRE` or `BONDED // MATCH GRADE`)

### Zone C — Left Center: Hero Caliber

- **Largest text element on the box**
- Caliber name: Roboto Mono, Bold, uppercase
- Examples: `.223 REMINGTON`, `6.5 CREEDMOOR`, `7.62X39 TACTICAL`, `5.56 NATO MK262`
- Flush left alignment
- The caliber line may include a product descriptor (e.g., `TACTICAL` appended to the caliber on the Ta line)

### Zone D — Below Caliber: Spec Line

- `WEIGHT // TYPE // VELOCITY` format
- Roboto Mono, Medium, smaller than caliber
- Examples: `130GR // HP BT // 1050 FPS`, `77GR // JHP // 2750 FPS`
- Same flush left alignment as caliber

### Zone E — Below Specs: Tag Row

- Horizontal row of pill-shaped tags
- Each tag is a rectangular badge with filled background and white or dark text
- Tag types and their colors:

| Tag Purpose | Color | Examples |
|-------------|-------|---------|
| Quadrant line name | Quadrant signature color | `TACTICAL` (Nuclear), `DUTY` (Nuclear), `HUNTING` (Signal), `MATCH` (Tracer) |
| Product attribute | Nuclear green | `SUBSONIC`, `COMPETITION`, `CYCLING`, `BONDED` |
| Secondary category | Gunmetal `#404040` | `DEFENSE`, secondary descriptors |
| Quantity | Gunmetal `#404040` | `X20`, `X50` |

- Tags sit flush left, evenly spaced in a single row
- On dark boxes, tag text is white; on light boxes, tag text is white (tags are always filled)

### Zone F — Right Center: AA Monogram Watermark

- Large AA monogram + atom mark
- Low opacity — Washout on light boxes, Gunmetal on dark boxes
- Positioned right-center, partially bleeding off the right edge
- Decorative only — reinforces brand without competing with data

### Zone G — Bottom Left: Ballistics Lab Lockup

- `Aa` element badge (small, square) next to lab name
- `ATOMIC AMMUNITION BALLISTICS LAB //`
- `DEPARTMENT OF RESEARCH & DEVELOPMENT`
- Roboto Mono, small, subdued color (Steel or white depending on background)
- Consistent across all quadrants

### Zone H — Bottom Right: Made in USA

- Flag icon + `MADE IN USA`
- White on dark boxes, dark on light boxes
- Flush right, above bottom Gunpowder band

---

## 4. Tag Color Logic

Tags use a consistent color system across all quadrants. The tag's fill color communicates what kind of information it carries.

### Quadrant-Specific Tags

These identify which product line the round belongs to. They always use the quadrant's signature color:

| Tag | Fill | Used On |
|-----|------|---------|
| `TACTICAL` | Nuclear `#32CD32` | Ta boxes |
| `DUTY` | Nuclear `#32CD32` | Du boxes |
| `HUNTING` | Signal `#FFB000` | Hu boxes |
| `MATCH` | Tracer `#ED1C24` | Ma boxes |

### Attribute Tags

These describe round characteristics. Color coding:

| Tag | Fill | Meaning |
|-----|------|---------|
| `SUBSONIC` | Nuclear `#32CD32` | Velocity below speed of sound |
| `COMPETITION` | Nuclear `#32CD32` | Competition-rated |
| `CYCLING` | Nuclear `#32CD32` | Optimized for semi-auto cycling |
| `BONDED` | Nuclear `#32CD32` | Bonded core construction |
| `DEFENSE` | Gunmetal `#404040` | Self-defense application |

### Quantity Tag

| Tag | Fill | Meaning |
|-----|------|---------|
| `X20`, `X50`, etc. | Gunmetal `#404040` | Round count per box |

---

## 5. Element Badge Spec

The quadrant badges (`Ta`, `Du`, `Hu`, `Ma`) and the Ballistics Lab badge (`Aa`) follow the same construction:

```
┌────────┐
│   Ta   │
└────────┘
```

- **Shape:** Rounded rectangle or square
- **Symbol:** Roboto Mono, Bold, centered, 2-letter abbreviation
- **Fill:** Quadrant signature color (or Gunpowder for the `Aa` lab badge)
- **Text color:** White (always — on all fill colors)
- **Border:** None when filled; 1px stroke in signature color when on transparent background
- **Size on packaging:** Approximately matches the height of the division label text beside it

### Division Label + Badge Pairing

The division name and element badge sit together as a unit:

```
┌───────────┐ ┌────┐
│ MARKSMAN  │ │ Hu │
└───────────┘ └────┘
```

- Division label: Gunpowder fill (dark pill), white text, Roboto Mono Medium
- Element badge: Signature color fill, white text, Roboto Mono Bold
- The two badges are the same height, sitting flush next to each other

---

## 6. Grid System

### Light Boxes (Hu, Ma)

- Background: Concrete `#E5E5E5`
- Grid lines: Washout `#CCCCCC`, 1px, evenly spaced
- Grid is always visible — it's the "blueprint paper" of the brand
- Grid spacing is consistent and mathematical

### Dark Boxes (Ta)

- Background: Gunpowder `#0D0D0D`
- Grid lines: Gunmetal `#404040`, 1px
- Grid is subtle, nearly invisible — the "classified document" feel
- Same spacing as light boxes

### Green Boxes (Du)

- Background: Nuclear `#32CD32`
- Grid lines: Slightly darker green tint, 1px
- Grid maintains the architectural structure even on the boldest colorway

### Rule

The grid is never absent. Every box has it. It's as much a brand element as the logo.

---

## 7. Constant Elements (All Quadrants)

These elements appear on every box, same position, same treatment:

1. **Top and bottom Gunpowder bands** — structural frame
2. **Atomic Ammunitions logo** — top left (Zone A)
3. **Division + quadrant badge** — top right (Zone B)
4. **Caliber as hero** — largest text, left center (Zone C)
5. **Spec line with `//` separators** — below caliber (Zone D)
6. **Tag row** — below specs (Zone E)
7. **AA monogram watermark** — right center, low opacity (Zone F)
8. **Ballistics Lab lockup** — bottom left (Zone G)
9. **Made in USA** — bottom right (Zone H)
10. **Grid lines** — always present on the body panel
