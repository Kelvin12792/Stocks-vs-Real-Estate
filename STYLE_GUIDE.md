# Style Guide

## Writing Standards for *Stocks vs. Real Estate*

---

## Voice and Tone

### Core Voice
- **Objective third-person** throughout — no "I," "we," or "you should"
- Instead of "you should consider," use "investors may consider" or "one approach is to"
- The book observes, presents, and analyzes — it does not prescribe

### Blended Tone
The book combines four tonal registers. Each chapter will use all four, weighted by context:

| Register | When to Use | Example |
|----------|-------------|---------|
| **Academic/Analytical** | Presenting data, historical evidence, definitions | "Between 1926 and 2023, the S&P 500 delivered an annualized return of approximately 10.3% before inflation, according to data compiled by NYU Stern." |
| **Conversational/Approachable** | Explaining complex concepts simply | "Think of a cap rate like a stock's earnings yield — it tells an investor how much income a property generates relative to its price." |
| **Professional/Warm Advisor** | Guiding the reader through decisions | "The question is not whether stocks are better than real estate. The question is which combination of assets aligns with a given investor's timeline, risk tolerance, and life goals." |
| **Storytelling/Narrative** | Case studies, historical events, personas | "In March 2009, David Chen watched his brokerage account lose 40% of its value in five months. Three blocks from his apartment, a two-bedroom condo that had listed for $380,000 in 2007 was now asking $245,000." |

### Tone Don'ts
- Never condescending or preachy
- Never use hype language ("explosive returns," "guaranteed wealth," "secret strategy")
- Never use first person
- Never express a personal opinion as the author's stance
- Never use filler phrases ("it goes without saying," "needless to say," "at the end of the day")

### Punctuation Rules
- **No em dashes (—) anywhere in the manuscript.** This applies to prose, tables, captions, quotes, and metadata. Use commas, colons, parentheses, semicolons, or sentence breaks instead.
  - Instead of: "The cap rate, a widely used metric — expressed as a percentage — tells an investor how much income a property generates."
  - Write: "The cap rate, a widely used metric expressed as a percentage, tells an investor how much income a property generates."
- En dashes (–) are permitted only in numeric or date ranges (e.g., "1926–2023," "pp. 45–50").
- Hyphens (-) are used only in compound modifiers (e.g., "long-term," "inflation-adjusted").

---

## Formatting Conventions

### Headings
- **H1 (#):** Chapter title only — one per file
- **H2 (##):** Major sections within a chapter
- **H3 (###):** Subsections
- **H4 (####):** Sub-subsections (use sparingly)

### Chapter Opening Quote
Every chapter opens with a quote block:
```markdown
> "The stock market is a device for transferring money from the impatient to the patient."
> — Warren Buffett
```

### Inline Term Definitions
When introducing a technical term for the first time, define it inline using bold and parenthetical:
```markdown
The **cap rate** (capitalization rate — the ratio of a property's net operating income to its purchase price) is one of the most widely used metrics in real estate analysis.
```
The term should also be added to the glossary.

### Key Takeaways
Every chapter ends with a key takeaways section:
```markdown
---

## Key Takeaways

- Takeaway one in a complete sentence
- Takeaway two in a complete sentence
- Takeaway three in a complete sentence
```
Limit to 4–6 takeaways per chapter. Each must be a standalone, meaningful statement.

### Side-by-Side Comparisons
When comparing stocks and real estate on a specific dimension, use a table:
```markdown
| Dimension | Stocks | Real Estate |
|-----------|--------|-------------|
| Liquidity | High — shares can be sold in seconds during market hours | Low — transactions take 30–90 days on average |
```

### Case Studies and Personas
Introduce fictional personas in italic narrative blocks:
```markdown
*Maria Torres is a 42-year-old marketing director in Denver earning $135,000 annually. She has $80,000 in savings, a 401(k) with $210,000, and no real estate holdings. Her goal is to generate passive income within the next five years while keeping her day job.*
```
Always follow with analysis of how the chapter's concepts apply to this persona.

### Data and Statistics
- Always include the source and year inline
- Use tables for multi-point comparisons
- Round percentages to one decimal place unless precision matters
- Always specify whether returns are nominal or inflation-adjusted

```markdown
According to the Federal Reserve's Survey of Consumer Finances (2022), the median net worth of homeowning families was $396,200, compared to $10,400 for renting families.
```

### Citations
Use inline attribution for most data points and assertions (author, publication, and year in the sentence itself). In addition, every verified factual claim that cites a primary source should carry a numbered footnote so that readers, reviewers, and fact-checkers can trace it to a specific URL or document.

- Footnotes use the standard GitHub-flavored Markdown syntax: `[^1]` inline, with the matching `[^1]: ...` definitions collected in a "Sources" section at the end of the chapter.
- Each footnote must include the source name, the publication or access date, and a URL or document identifier where possible.
- Footnote numbering restarts at 1 within each chapter file.
- Endnotes and traditional academic bibliographies are still not used. The Sources section at the end of each chapter is the canonical reference list for that chapter.

```markdown
A 2023 study published in the *Journal of Financial Economics* found that...[^1]
According to IRS Publication 523 (2024)...[^2]
Data from the S&P Dow Jones Indices (2024) shows...[^3]
```

---

## Word Count Targets

| Section | Target Words |
|---------|-------------|
| Front matter (disclaimer, how-to, introduction) | 3,000–4,000 |
| Part I chapters (Ch. 1–4) | 2,500–3,500 each |
| Part II chapters (Ch. 5–12) | 3,000–4,000 each |
| Part III chapters (Ch. 13–14) | 3,000–3,500 each |
| Part IV chapters (Ch. 15–18) | 3,000–4,000 each |
| Back matter (glossary, appendices) | 4,000–6,000 total |
| **Total minimum** | **50,000** |

---

## Language Rules

### Terminology Consistency
Use these terms consistently throughout:

| Use This | Not This |
|----------|----------|
| Real estate | Real-estate, realty, property (when referring to the asset class) |
| Stocks | Equities (except when defining the term) |
| Investor | Trader (unless specifically discussing trading) |
| Returns | Gains (unless discussing capital gains specifically) |
| Portfolio | Holdings (unless in a specific financial context) |

### Numbers
- Spell out one through nine; use numerals for 10 and above
- Always use numerals for: percentages (5%), dollar amounts ($10,000), years (2008)
- Use commas in numbers over 999: $1,000 / $1,000,000
- For large round numbers, use words: "$2.3 million" not "$2,300,000"

### Abbreviations
- Define on first use: "net operating income (NOI)"
- After first use, abbreviation only is acceptable
- Common abbreviations that need no definition: IRS, S&P 500, GDP, SEC, FDIC

---

## File Naming Conventions

| Type | Format | Example |
|------|--------|---------|
| Chapters | `chapter-XX.md` | `chapter-05.md` |
| Front matter | `descriptive-name.md` | `how-to-use-this-book.md` |
| Appendices | `appendix-X-description.md` | `appendix-a-checklist.md` |
| Planning docs | `UPPERCASE.md` | `PERSONAS.md` |
| Tracking docs | `UPPERCASE.md` | `WORD_COUNT.md` |

---

## Review Checklist (Per Chapter)

Before marking a chapter as "Review Ready":

- [ ] Opens with a relevant, properly attributed quote
- [ ] All technical terms defined inline on first use
- [ ] At least one side-by-side comparison table
- [ ] At least one persona case study or real historical example
- [ ] All data points include source and year
- [ ] All tax/legal claims verified and logged in LEGAL_REVIEW.md
- [ ] All factual claims logged in FACT_CHECK.md
- [ ] Key takeaways section present (4–6 items)
- [ ] Word count meets target range
- [ ] No first-person language
- [ ] No prescriptive "you should" language
- [ ] No unsourced statistics or calculations
