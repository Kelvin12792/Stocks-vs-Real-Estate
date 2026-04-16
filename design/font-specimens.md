# Font Specimens

Typography system for *Stocks vs. Real Estate: A Comprehensive Guide to Building Wealth Through the Two Most Popular Asset Classes.*

---

## Font Stack Overview

| Role | Typeface | Classification | Source |
|------|----------|---------------|--------|
| Heading | Playfair Display | Serif (transitional) | Google Fonts |
| Body | Source Sans 3 | Humanist sans-serif | Google Fonts / Adobe Fonts |
| Accent / Mono | Source Code Pro | Monospaced slab-serif | Google Fonts / Adobe Fonts |

---

## Heading Font: Playfair Display

**Classification:** Transitional serif
**Designer:** Claus Eggers Sørensen
**License:** SIL Open Font License
**Primary Use:** Chapter titles, part openers, major section headings (H1, H2), cover title, pull quotes

### Rationale

Playfair Display carries the authority of classic financial and legal publishing — its high-contrast strokes and refined serifs recall the masthead typography of the *Financial Times* and century-old investment prospectuses — while remaining contemporary enough to feel current rather than archaic. Its strong vertical stress and ink-trap details reproduce well in both print and high-resolution digital formats. The contrast between Playfair's thick-and-thin strokes and Source Sans 3's uniform weight creates immediate visual hierarchy without requiring size alone to do the work. For a book that asks readers to take its analysis seriously, Playfair Display signals that intent from the first page.

### Weights in Use

| Weight | Use Case |
|--------|----------|
| Bold (700) | H1 chapter titles, H2 major section headings, cover title |
| Regular (400) | H3 subsection headings, part opener subtitles |
| Italic Regular (400i) | Opening chapter quotes, persona narrative introductions |
| Bold Italic (700i) | Rare emphasis within headings; use sparingly |

### Do Not Use
- Playfair Display for body text — its high contrast is fatiguing at small sizes.
- Playfair Display for table content — its letterforms are too wide and decorative for data-dense contexts.
- Light (300) weight — it prints poorly at small sizes and lacks sufficient contrast.

---

## Body Font: Source Sans 3

**Classification:** Humanist sans-serif
**Designer:** Paul D. Hunt
**License:** SIL Open Font License
**Primary Use:** All body copy, table content, captions, callout box text, inline term definitions, list items

### Rationale

Source Sans was designed specifically for interfaces and documents where reading comfort across extended passages is paramount. Its humanist construction — drawn from calligraphic origins — gives it warmth that purely geometric or grotesque sans-serifs lack, making it appropriate for a book that aims to feel like a trusted advisor rather than a software manual. Source Sans 3 (the updated variable-font version) offers a full weight range with superior screen rendering hinting, ensuring consistent appearance whether the book is printed or read in a digital viewer. Its open apertures and generous x-height maintain legibility at the 10–11pt sizes used for body text and at the 8pt sizes used for table cells and captions.

### Weights in Use

| Weight | Use Case |
|--------|----------|
| Bold (700) | Inline term introductions (the term itself), table column headers, Key Takeaway labels, callout box labels ("Key Takeaways," "Myth," "Reality") |
| SemiBold (600) | Table row headers, H4 sub-subsection headings, persona name labels |
| Regular (400) | All body prose, table cell text, captions, quote attributions, list items |
| Light (300) | H2 subtitle/descriptor line (the short descriptive phrase beneath a major section heading), chapter subtitle on cover |
| Italic Regular (400i) | Persona narrative blocks, inline emphasis within body text (sparingly) |

### Do Not Use
- Source Sans 3 for chapter-level titles — at large display sizes it lacks the visual authority Playfair provides.
- Black (900) weight — too heavy for this book's tone; reserved for marketing materials only.

---

## Accent / Monospaced Font: Source Code Pro

**Classification:** Monospaced slab-serif
**Designer:** Paul D. Hunt
**License:** SIL Open Font License
**Primary Use:** Calculations, formulas, numerical examples formatted as code, spreadsheet-style data blocks, hex color values in technical references

### Rationale

Source Code Pro shares its design DNA with Source Sans 3 — both are Paul D. Hunt designs from Adobe's Source family — which creates a natural, harmonious pairing while clearly distinguishing formulaic or structured content from flowing prose. The monospaced grid makes multi-line calculations align cleanly without tables, and the slab-serif construction at monospaced widths produces a slightly mechanical, precise feeling that reinforces the quantitative nature of the content it presents. Using Source Code Pro for calculations rather than an italic or bold variant of the body font gives readers a visual shortcut: "this is a number to examine carefully."

### Weights in Use

| Weight | Use Case |
|--------|----------|
| Regular (400) | All inline calculations, formulas, code-style data blocks |
| Bold (700) | Key output values within a calculation (the final answer or result line) |

### Typical Applications

```
Cap Rate = NOI / Property Value
Cap Rate = $18,000 / $300,000 = 6.0%

CAGR = (Ending Value / Beginning Value)^(1/n) - 1
CAGR = ($215,000 / $100,000)^(1/20) - 1 = 3.88%
```

---

## Type Scale

All sizes are given in points (pt) for print. For digital/web rendering, multiply by 1.333 to convert to pixels (px).

### Display and Heading Scale

| Level | Element | Typeface | Weight | Size | Leading | Tracking |
|-------|---------|----------|--------|------|---------|----------|
| H1 | Chapter title | Playfair Display | Bold 700 | 32pt | 38pt | -10 |
| H1 sub | Chapter subtitle / descriptor | Source Sans 3 | Light 300 | 14pt | 20pt | 20 |
| Part opener | Part number + title | Playfair Display | Bold 700 | 40pt | 48pt | -15 |
| H2 | Major section heading | Playfair Display | Bold 700 | 22pt | 28pt | -5 |
| H2 sub | Section sub-descriptor | Source Sans 3 | Light 300 | 11pt | 16pt | 10 |
| H3 | Subsection heading | Playfair Display | Regular 400 | 16pt | 22pt | 0 |
| H4 | Sub-subsection heading | Source Sans 3 | SemiBold 600 | 12pt | 18pt | 5 |

### Body and Supporting Scale

| Level | Element | Typeface | Weight | Size | Leading | Tracking |
|-------|---------|----------|--------|------|---------|----------|
| Body | Running prose | Source Sans 3 | Regular 400 | 10.5pt | 16pt | 0 |
| Body emphasis | Inline bold term | Source Sans 3 | Bold 700 | 10.5pt | 16pt | 0 |
| Body italic | Persona narrative, light emphasis | Source Sans 3 | Italic 400i | 10.5pt | 16pt | 0 |
| Table header | Column and row headers | Source Sans 3 | Bold 700 | 9pt | 13pt | 10 |
| Table cell | Cell body text | Source Sans 3 | Regular 400 | 9pt | 13pt | 0 |
| Caption | Figure and table captions | Source Sans 3 | Regular 400 | 8.5pt | 13pt | 5 |
| Attribution | Quote attribution line | Source Sans 3 | Regular 400 | 8.5pt | 13pt | 15 |
| Callout label | "Key Takeaways," "Myth," "Reality" box labels | Source Sans 3 | Bold 700 | 9pt | — | 30 |
| Callout body | Text inside callout boxes | Source Sans 3 | Regular 400 | 10pt | 15pt | 0 |
| Formula | Calculation / formula blocks | Source Code Pro | Regular 400 | 9.5pt | 15pt | 0 |
| Formula result | Output line of a calculation | Source Code Pro | Bold 700 | 9.5pt | 15pt | 0 |
| Pull quote | Large in-text quote | Playfair Display | Italic 400i | 18pt | 26pt | 0 |

---

## Weight Usage Summary

| Weight Level | Typeface | Signal |
|-------------|----------|--------|
| Bold | Playfair Display | Headline authority — chapter and section identity |
| Regular | Playfair Display | Softer heading authority — subsections, quotes |
| Italic | Playfair Display | Narrative distance — pull quotes, persona intros |
| Bold | Source Sans 3 | Attention and terminology — terms, labels, table headers |
| SemiBold | Source Sans 3 | Secondary structure — row headers, H4, names |
| Regular | Source Sans 3 | The reading voice — all sustained body content |
| Light | Source Sans 3 | Recede and support — subtitles, descriptors |
| Italic | Source Sans 3 | Human element — persona voice, light emphasis |
| Bold | Source Code Pro | Answer / result — the final computed value |
| Regular | Source Code Pro | Process / formula — the working calculation |

---

## Pairing Logic

The three-font system is built on two principles:

**1. Contrast by function, not decoration.** Playfair Display and Source Sans 3 are structurally opposite — high-contrast serif vs. low-contrast sans — so every shift between them communicates a functional change (structure-to-reading, heading-to-body) rather than a decorative one. Source Code Pro enters only for calculable content, which means its appearance alone signals "here is a number to work through."

**2. Family cohesion.** Source Sans 3 and Source Code Pro are both part of Adobe's Source type family, designed by the same hand to work together. This ensures that switching between body prose and formula notation feels intentional and disciplined rather than jarring.

---

## Font Loading and Fallback Stack

For digital editions and any CSS-rendered output:

```css
/* Heading */
font-family: 'Playfair Display', 'Georgia', 'Times New Roman', serif;

/* Body */
font-family: 'Source Sans 3', 'Source Sans Pro', 'Helvetica Neue', 'Arial', sans-serif;

/* Mono / Formula */
font-family: 'Source Code Pro', 'Consolas', 'Courier New', monospace;
```
