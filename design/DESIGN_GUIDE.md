# Design Guide

*The master visual design system for* **Stocks vs. Real Estate: A Comprehensive Guide to Building Wealth Through the Two Most Popular Asset Classes.**

---

## Purpose

This guide defines the complete visual language for the book — color, typography, layout, component styling, chart conventions, and cover design. It exists so that every chapter, table, callout, figure, and cover element feels like part of the same disciplined publication, whether a reader encounters it in print, in an e-reader, or on the web.

Two companion files carry the low-level specifications:

- `color-palette.md` — full hex values, pairing rules, and accessibility notes
- `font-specimens.md` — complete type scale, weights, and pairing logic

This document assumes both are present and references them where relevant. When the two conflict with this guide, this guide is the source of truth.

---

## Design Principles

1. **Neutrality through symmetry.** Stocks and real estate are given equal visual weight in every layout. Neither side is styled to feel dominant, more modern, or more authoritative than the other.
2. **Contrast by function, not decoration.** Every font shift, color shift, or weight shift communicates a structural change (heading → body, prose → calculation, stock content → real estate content). Decoration for its own sake is avoided.
3. **Clarity over ornament.** The book carries quantitative claims. The visual system must never make numbers harder to read or comparisons harder to see.
4. **Reproducibility.** Every color has a hex code. Every type choice has a specified weight and size. A future editor or designer should be able to rebuild the book from the specifications in this guide.

---

## Color System

Full specifications live in `color-palette.md`. The essentials:

| Role | Name | Hex | Primary Use |
|------|------|-----|-------------|
| Primary A | Deep Navy | `#1B2A4A` | Stocks-related content, primary headings, spine |
| Primary B | Warm Terracotta | `#C4572A` | Real estate–related content, secondary headings |
| Secondary | Forest Green | `#2E7D4F` | Positive/growth indicators, green callouts |
| Secondary | Muted Purple | `#6B5B7B` | Myth labels, behavioral/psychology content |
| Accent | Gold | `#C9A84C` | Key takeaway labels, decorative rules, cover accent |
| Neutral | Warm White | `#FAF8F5` | Page background |
| Neutral | Charcoal | `#2D2D2D` | Body text |
| Neutral | Slate Gray | `#6B7280` | Captions, secondary text, rule lines |

### Color Pairing Rules

- **Navy and Terracotta never appear in the same decorative block** except when the block's explicit purpose is to compare stocks and real estate side by side. This preserves the symbolism of each color.
- **Forest Green and Muted Purple are supporting colors, not substitutes** for the two primaries. They are used for signal (positive/negative, myth/reality) inside comparison layouts, not as a third or fourth "asset class" color.
- **Gold is used sparingly** — typically once per spread at most. Overuse erodes its signal as the highest-attention color.
- **Charcoal is the only approved body-text color.** Pure black (`#000000`) is not used anywhere in the book; it reads as harsh against Warm White.

See `color-palette.md` for WCAG contrast ratios and accessibility notes.

---

## Typography System

Full specifications live in `font-specimens.md`. The essentials:

| Role | Typeface | Where Used |
|------|----------|------------|
| Heading | Playfair Display | Chapter titles, part openers, H1/H2, cover title, pull quotes |
| Body | Source Sans 3 | All running prose, tables, captions, callouts |
| Formula | Source Code Pro | Calculations, formulas, numerical examples |

The type scale (H1 32pt → body 10.5pt → caption 8.5pt) is specified in full in `font-specimens.md § Type Scale`.

**Fallback stacks** for CSS-rendered editions are documented in `font-specimens.md § Font Loading and Fallback Stack`.

---

## Page Layout

### Trim and Margins

| Specification | Value |
|--------------|-------|
| Trim size (print) | 6" × 9" (152mm × 229mm) |
| Inside margin | 0.875" |
| Outside margin | 0.625" |
| Top margin | 0.75" |
| Bottom margin | 0.875" |
| Running head | 0.4" from top |
| Folio (page number) | 0.5" from bottom, outside corner |

### Baseline Grid

All body text aligns to a 16pt baseline grid, matching body leading. Callouts, captions, and tables reset to their own leading but begin and end on grid lines so the facing page maintains visual alignment.

### Running Heads

- **Verso (left page):** Book title, Source Sans 3 Regular, 9pt, Slate Gray, small caps, tracking +30
- **Recto (right page):** Chapter number and title, Source Sans 3 Regular, 9pt, Slate Gray, small caps, tracking +30
- Part-opener pages and chapter-opener pages carry no running head.

### Folios

Page numbers appear in the outside bottom corner, Source Sans 3 Regular, 9pt, Slate Gray. Front matter uses lowercase Roman numerals; body matter uses Arabic numerals starting at 1 on the first page of the Introduction.

---

## Component Styling

### Chapter Opener

- Chapter number in Playfair Display Regular 14pt, Gold, tracking +40, small caps ("CHAPTER FIVE")
- 0.5pt Gold horizontal rule, 1" wide, below the number
- Chapter title in Playfair Display Bold 32pt, Charcoal, left-aligned
- Chapter subtitle in Source Sans 3 Light 14pt, Slate Gray, left-aligned, below title
- Opening epigraph in Playfair Display Italic 13pt, indented 0.5" from left margin, with attribution in Source Sans 3 Regular 10pt, Slate Gray
- First paragraph uses no drop cap (drop caps would clash with the book's analytical tone)

### Part Openers

- Full-page design on a recto page
- Part number ("PART II") in Playfair Display Regular 18pt, Gold, small caps, centered
- Part title in Playfair Display Bold 40pt, Charcoal, centered
- Short part description in Source Sans 3 Light 13pt, Slate Gray, centered, max 3 lines
- Verso page facing part opener is intentionally blank

### Callout Boxes

Callouts are used for Key Takeaways, Myth/Reality, Warning, and Formula blocks.

| Callout | Border | Fill | Label Color | Label Text |
|---------|--------|------|-------------|------------|
| Key Takeaways | 0.5pt Gold | Warm White | Gold | "KEY TAKEAWAYS" |
| Myth / Reality | 0.5pt Muted Purple | Warm White | Muted Purple | "MYTH" / "REALITY" |
| Warning | 0.5pt Terracotta | Warm White | Terracotta | "A NOTE OF CAUTION" |
| Formula | None | `#F4F1EC` (5% Charcoal on Warm White) | Charcoal | "CALCULATION" |
| Persona Profile | 0.5pt Slate Gray | Warm White | Slate Gray | "PERSONA" |

Labels use Source Sans 3 Bold 9pt, tracking +30, small caps. Callout body uses Source Sans 3 Regular 10pt on 15pt leading. Internal padding: 12pt all sides.

### Comparison Tables (Part II)

Part II presents head-to-head comparisons across eight dimensions. These tables follow a strict pattern:

- Header row: Source Sans 3 Bold 9pt, Warm White text
- Stocks header cell: Navy fill
- Real Estate header cell: Terracotta fill
- Dimension (row label) header: Charcoal fill
- Data cells: Warm White fill, Charcoal text
- Row separators: 0.25pt Slate Gray rules
- No vertical rules between columns (whitespace carries the structure)
- Alternating row banding is not used — it fights the color-coded columns

### Persona Sidebars

Eight fictional personas appear in boxed sidebars with:
- Persona name in Source Sans 3 SemiBold 11pt, Charcoal
- Age, occupation, capital, and primary goal in a 4-cell micro-table, Source Sans 3 Regular 9pt
- Narrative block in Source Sans 3 Italic 10pt, indented 0.25"

Personas are analytical tools, never presented as recommendations. A repeated footer line (Source Sans 3 Regular 8pt, Slate Gray) reads: *"Fictional profile for illustration."*

### Inline Term Definitions

When a term first appears in the text, it is set in Source Sans 3 Bold 10.5pt, Charcoal, immediately followed by an inline parenthetical definition in Source Sans 3 Regular. The same term is also listed in the glossary with the chapter of first use cited.

---

## Charts and Figures

### Chart Conventions

- Stocks data uses Deep Navy (`#1B2A4A`)
- Real estate data uses Warm Terracotta (`#C4572A`)
- Positive reference lines (inflation, risk-free rate, target) use Forest Green (`#2E7D4F`) dashed
- Gridlines: 0.25pt Slate Gray at 25% opacity
- Axis labels: Source Sans 3 Regular 8pt, Charcoal
- Chart titles: Source Sans 3 SemiBold 10pt, Charcoal, left-aligned above the chart
- Chart captions: Source Sans 3 Regular 8.5pt, Slate Gray, left-aligned below the chart
- Every chart carries a source line in Source Sans 3 Regular 7.5pt, Slate Gray, italic: *"Source: [dataset], [date range]."*

### Figure Numbering

Figures are numbered `[Chapter].[Sequence]` (e.g., Figure 5.3 is the third figure in Chapter 5). The same convention applies to tables, numbered `Table 5.3`.

### Do Not Use

- 3D charts (distort comparison)
- Dual y-axes (misleading when the two sides are the book's central comparison)
- Pie charts for anything other than portfolio allocation breakdowns
- Chartjunk: drop shadows, gradients, textured fills, skeuomorphic effects

---

## Cover Design Brief

### Front Cover

- **Composition:** Vertical split — left half Deep Navy, right half Warm Terracotta, with a thin Gold rule dividing them
- **Title:** *Stocks vs. Real Estate* in Playfair Display Bold, Warm White, centered across the split, with "vs." set slightly smaller and italic
- **Subtitle:** *A Comprehensive Guide to Building Wealth Through the Two Most Popular Asset Classes* in Source Sans 3 Light, Warm White, centered below the title
- **Author name:** Source Sans 3 Regular, Warm White, bottom-centered
- **Accent:** A single Gold horizontal rule beneath the title, approximately 1.25" wide
- **Imagery:** None. The split-color composition is the design. Illustrative imagery would weaken the neutrality the book depends on.

### Spine

- Background: Deep Navy
- Title: Playfair Display Bold, Warm White, reading bottom-to-top
- Author: Source Sans 3 Regular, Warm White
- Publisher mark: Bottom, Warm White

### Back Cover

- Background: Warm White
- Blurb: Source Sans 3 Regular 11pt, Charcoal
- "What Readers Will Learn" bulleted list: Source Sans 3 Regular 10pt, Charcoal
- Author bio: Source Sans 3 Regular 9.5pt, Charcoal
- ISBN/barcode: bottom-right, standard EAN-13 format
- Thin Gold rule separating blurb from author bio

Full cover specifications, ISBN slot, and edition marking conventions live in `cover.md`.

---

## Digital and Web Rendering

For any HTML/CSS rendering of the book (web preview, blog excerpts, marketing pages):

- Use the CSS fallback stacks specified in `font-specimens.md § Font Loading and Fallback Stack`
- Convert point sizes to pixels by multiplying by 1.333
- Maintain the 16pt → 21.3px baseline leading on body copy
- Backgrounds use Warm White; body text uses Charcoal — do not invert for "dark mode" without a full dark-mode palette (not yet defined)
- Hyperlinks use Deep Navy, underlined; visited links use Muted Purple

---

## Accessibility

- All primary and secondary color pairings against Warm White meet WCAG AA contrast (≥ 4.5:1) for body text. See `color-palette.md` for specific ratios.
- Charts never rely on color alone to distinguish series — line style, marker shape, or direct labeling is always added so the chart remains readable in grayscale.
- Minimum body text size in print is 10pt; in digital editions, 13.3px.
- Figure and table captions always include enough descriptive text to convey the point of the figure to a reader who cannot see it.

---

## Revision Discipline

Any change to color values, type specifications, layout grid, or component styling must be made in this file first, then propagated to `color-palette.md` or `font-specimens.md` as appropriate, and logged in `CHANGELOG.md` under a `[design]` tag. Never change a visual specification in one file without updating the others.

---

*Status: Draft — specifications are complete; refinements expected once chapter drafts expose edge cases.*
