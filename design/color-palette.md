# Color Palette

Visual color system for *Stocks vs. Real Estate: A Comprehensive Guide to Building Wealth Through the Two Most Popular Asset Classes.*

---

## Primary Colors

These two colors anchor the book's core identity. Every comparison-driven element is coded to one of these two hues so the reader instinctively knows which asset class is being discussed before reading a word.

### Deep Navy — Stocks
- **Hex:** `#1B2A4A`
- **RGB:** 27, 42, 74
- **CMYK:** 64, 43, 0, 71 (print reference)
- **Use:** All stocks-related column headers, stocks-side table cells, stocks-themed chapter accent bars, stocks icon backgrounds, stocks label badges.
- **Psychological intent:** Authority, precision, institutional trust. Blue is strongly associated with financial markets, brokerage interfaces, and analytical rigor.

### Warm Terracotta — Real Estate
- **Hex:** `#C4572A`
- **RGB:** 196, 87, 42
- **CMYK:** 0, 56, 79, 23 (print reference)
- **Use:** All real estate-related column headers, RE-side table cells, real estate chapter accent bars, RE icon backgrounds, RE label badges.
- **Psychological intent:** Warmth, tangibility, the physical world. Terracotta evokes bricks, land, and the built environment — grounded and material in contrast to the abstract nature of securities.

---

## Secondary Colors

Secondary colors mark specific types of content across both asset classes. They are not asset-class-specific; they convey meaning about the *nature* of the information, not its subject.

### Forest Green — Growth and Positive Indicators
- **Hex:** `#2E7D4F`
- **RGB:** 46, 125, 79
- **CMYK:** 63, 0, 37, 51 (print reference)
- **Use:** Positive return figures, "Reality" side of myth-busting callouts, upward trend indicators, favorable comparison cells, success markers in case studies.
- **Psychological intent:** Prosperity, forward momentum, optimism. Universally understood as the color of financial gain.

### Muted Purple — Myths and Misconceptions
- **Hex:** `#6B5B7B`
- **RGB:** 107, 91, 123
- **CMYK:** 13, 26, 0, 52 (print reference)
- **Use:** "Myth" side borders and labels in myth-busting callouts, misconception headers, belief-challenge sections, behavioral bias sidebars.
- **Psychological intent:** Caution, complexity, intellectual inquiry. Purple occupies an ambiguous space that signals "this requires re-examination" without the alarm of red.

---

## Accent Color

### Gold — Key Takeaways, Highlights, and Decorative Elements
- **Hex:** `#C9A84C`
- **RGB:** 201, 168, 76
- **CMYK:** 0, 16, 62, 21 (print reference)
- **Use:** Left border on Key Takeaway boxes, chapter number ornaments, pull-quote quotation marks, decorative dividers, star/highlight icons, cover foil accent.
- **Psychological intent:** Value, importance, premium quality. Gold draws the eye to the most important distillations of each chapter without shouting.

---

## Neutral Palette

Neutrals carry the majority of the page surface. They are chosen for warmth rather than coldness — this book is authoritative but not sterile.

### Warm White — Primary Background
- **Hex:** `#FAF8F5`
- **RGB:** 250, 248, 245
- **Use:** Page background, interior of callout boxes, table alternating-row fill (paired with white `#FFFFFF`), Key Takeaway box interior.
- **Note:** Slightly warm rather than pure white to reduce eye fatigue in long reading sessions and to complement the Terracotta and Gold accents.

### Charcoal — Primary Body Text
- **Hex:** `#2D2D2D`
- **RGB:** 45, 45, 45
- **Use:** All body copy, table cell text, caption text, definition text.
- **Note:** Near-black rather than pure black (`#000000`) softens the contrast against Warm White and reduces harshness on both print and screen.

### Slate Gray — Secondary Text
- **Hex:** `#6B7280`
- **RGB:** 107, 114, 128
- **Use:** Captions, attributions on quotes, footnote-style annotations, table sub-headers, secondary labels, placeholder and helper text.
- **Note:** Provides clear hierarchy below Charcoal without disappearing into the background.

---

## Color Pairing Rules

### Asset-Class Pairing
- Deep Navy and Warm Terracotta should **always appear together** in comparison contexts. Never use one without the other in a two-column comparison table — asymmetry breaks the visual logic.
- In single-asset-class discussions (a chapter section focusing only on stocks, for example), use only the relevant primary color with neutral support.

### Accent Restraint
- Gold should **never** be used as a large fill color. It is exclusively a border, rule line, ornament, or small icon color. Overuse degrades its "premium signal."
- Do not use Gold on text — it fails contrast thresholds on both Warm White and Charcoal backgrounds.

### Secondary Color Exclusivity
- Forest Green is reserved strictly for genuinely positive content. Do not apply it to neutral comparisons or data points that are positive in some scenarios and negative in others.
- Muted Purple is reserved for myth/misconception contexts. Do not use it as a general accent — its meaning must remain unambiguous throughout the book.

### Background Combinations
- Warm White background + Charcoal text: primary reading experience.
- Deep Navy background + white text: stocks column headers, chapter part openers for stock-focused sections.
- Warm Terracotta background + white text: real estate column headers, chapter part openers for RE-focused sections.
- Muted Purple background (10% tint) + Charcoal text: Myth callout box fill.
- Forest Green background (10% tint) + Charcoal text: Reality callout box fill.
- Gold border + Warm White fill + Charcoal text: Key Takeaway boxes.

---

## Accessibility Notes

All color combinations used for text must meet **WCAG 2.1 AA contrast standards** (minimum ratio of 4.5:1 for normal text, 3:1 for large text and UI components).

| Foreground | Background | Contrast Ratio | WCAG AA Status |
|------------|-----------|----------------|----------------|
| Charcoal `#2D2D2D` | Warm White `#FAF8F5` | ~14.5:1 | Pass |
| White `#FFFFFF` | Deep Navy `#1B2A4A` | ~12.1:1 | Pass |
| White `#FFFFFF` | Warm Terracotta `#C4572A` | ~4.6:1 | Pass (large text only recommended) |
| White `#FFFFFF` | Forest Green `#2E7D4F` | ~5.1:1 | Pass |
| White `#FFFFFF` | Muted Purple `#6B5B7B` | ~5.4:1 | Pass |
| Charcoal `#2D2D2D` | Forest Green tint 10% `#EBF4EF` | ~12.8:1 | Pass |
| Charcoal `#2D2D2D` | Muted Purple tint 10% `#F0EEF2` | ~13.9:1 | Pass |

**Important:** Do not place Charcoal text directly on Warm Terracotta — the contrast ratio (~3.2:1) does not meet AA for body-sized text. Use white text on Terracotta backgrounds only.

---

## Component–Color Usage Table

| Component | Primary Color | Secondary/Fill | Text Color | Border/Accent |
|-----------|--------------|----------------|------------|---------------|
| Stocks column header | Deep Navy `#1B2A4A` | — | White `#FFFFFF` | — |
| Real Estate column header | Warm Terracotta `#C4572A` | — | White `#FFFFFF` | — |
| Table alternating row (odd) | — | White `#FFFFFF` | Charcoal `#2D2D2D` | — |
| Table alternating row (even) | — | Warm White `#FAF8F5` | Charcoal `#2D2D2D` | — |
| Key Takeaway box | — | Warm White `#FAF8F5` | Charcoal `#2D2D2D` | Gold `#C9A84C` (left, 4px) |
| Myth callout | — | Muted Purple tint 10% | Charcoal `#2D2D2D` | Muted Purple `#6B5B7B` (left, 4px) |
| Reality callout | — | Forest Green tint 10% | Charcoal `#2D2D2D` | Forest Green `#2E7D4F` (left, 4px) |
| Persona/case study block | — | Warm White `#FAF8F5` | Charcoal `#2D2D2D` | Slate Gray `#6B7280` (dashed, 1px) |
| Opening quote block | — | — | Slate Gray `#6B7280` | — |
| Chapter number ornament | Gold `#C9A84C` | — | — | — |
| Pull-quote marks | Gold `#C9A84C` | — | — | — |
| Inline term (bold) | — | — | Charcoal `#2D2D2D` | — |
| Caption / attribution text | — | — | Slate Gray `#6B7280` | — |
| Positive data cell | — | Forest Green tint 10% | Charcoal `#2D2D2D` | — |
| Cover background (stocks side) | Deep Navy `#1B2A4A` | — | White `#FFFFFF` | — |
| Cover background (RE side) | Warm Terracotta `#C4572A` | — | White `#FFFFFF` | — |
| Cover title text | — | — | White `#FFFFFF` | Gold `#C9A84C` (decorative rule) |
