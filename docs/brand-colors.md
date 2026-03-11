# Atomic Ammunitions — Brand Colors

**Internal Brand Reference | Marketing Team**
Version 1.0 | March 2026

---

## Primary Accents

| Swatch | Name | Hex | CSS Classes | Usage |
|--------|------|-----|-------------|-------|
| ![#32CD32](https://via.placeholder.com/16/32CD32/32CD32) | Nuclear | `#32CD32` | `bg-nuclear`, `text-nuclear` | Primary brand accent. Logo text, CTAs, links, active states. |
| ![#28A428](https://via.placeholder.com/16/28A428/28A428) | Nuclear Muted | `#28A428` | `bg-nuclear-muted` | Hover states, secondary green elements, pressed buttons. |
| ![#FFB000](https://via.placeholder.com/16/FFB000/FFB000) | Signal | `#FFB000` | `bg-signal`, `text-signal` | Warnings, highlights, promotional callouts, badges. |
| ![#CC8D00](https://via.placeholder.com/16/CC8D00/CC8D00) | Signal Muted | `#CC8D00` | `bg-signal-muted` | Hover/pressed states for signal elements. |
| ![#ED1C24](https://via.placeholder.com/16/ED1C24/ED1C24) | Tracer | `#ED1C24` | `bg-tracer`, `text-tracer` | Errors, alerts, urgency, sale tags, destructive actions. |
| ![#BE1620](https://via.placeholder.com/16/BE1620/BE1620) | Tracer Muted | `#BE1620` | `bg-tracer-muted` | Hover/pressed states for tracer elements. |

---

## Neutrals (Light → Dark)

| Swatch | Name | Hex | CSS Classes | Usage |
|--------|------|-----|-------------|-------|
| ![#FAFBFB](https://via.placeholder.com/16/FAFBFB/FAFBFB) | Paper | `#FAFBFB` | `bg-paper` | Light backgrounds, cards, content areas, page body. |
| ![#E5E5E5](https://via.placeholder.com/16/E5E5E5/E5E5E5) | Concrete | `#E5E5E5` | `bg-concrete`, `text-concrete` | Borders, dividers, subtle backgrounds, input borders. |
| ![#CCCCCC](https://via.placeholder.com/16/CCCCCC/CCCCCC) | Washout | `#CCCCCC` | `text-washout` | Disabled text, placeholder text, inactive icons. |
| ![#8E8E93](https://via.placeholder.com/16/8E8E93/8E8E93) | Steel | `#8E8E93` | `text-steel` | Secondary text, captions, metadata, timestamps. |
| ![#6B6B70](https://via.placeholder.com/16/6B6B70/6B6B70) | Slate | `#6B6B70` | `text-slate` | Body text alternative, labels, subheadings. |
| ![#404040](https://via.placeholder.com/16/404040/404040) | Gunmetal | `#404040` | `border-gunmetal` | Primary body text, borders, icons. |
| ![#0D0D0D](https://via.placeholder.com/16/0D0D0D/0D0D0D) | Gunpowder | `#0D0D0D` | `bg-gunpowder` | Dark backgrounds, headers, footers, hero sections. |

---

## Color Pairing Rules

### Dark Mode (Gunpowder backgrounds)

- **Primary text:** Paper `#FAFBFB`
- **Secondary text:** Steel `#8E8E93`
- **Accents:** Nuclear `#32CD32` for links/CTAs, Signal for warnings, Tracer for errors
- **Borders/dividers:** Gunmetal `#404040`

### Light Mode (Paper backgrounds)

- **Primary text:** Gunmetal `#404040`
- **Secondary text:** Slate `#6B6B70`
- **Accents:** Nuclear `#32CD32` for links/CTAs, Signal for warnings, Tracer for errors
- **Borders/dividers:** Concrete `#E5E5E5`

### Accent Usage Hierarchy

1. **Nuclear** — default accent for all interactive elements (buttons, links, toggles)
2. **Signal** — informational emphasis (warnings, promotions, highlights)
3. **Tracer** — reserved for errors, destructive actions, and urgency only

Never use Signal or Tracer as decorative colors. They carry meaning.

---

## Contrast Notes

| Text Color | On Background | WCAG Rating |
|------------|---------------|-------------|
| Paper on Gunpowder | `#FAFBFB` on `#0D0D0D` | AAA |
| Gunmetal on Paper | `#404040` on `#FAFBFB` | AAA |
| Nuclear on Gunpowder | `#32CD32` on `#0D0D0D` | AA (large text only) |
| Nuclear on Paper | `#32CD32` on `#FAFBFB` | Fails — use for large text/icons only, not body copy |

When using Nuclear green as text on light backgrounds, keep it to headings, labels, or UI elements — never body copy. For small body text on light backgrounds, use Gunmetal or Slate.
