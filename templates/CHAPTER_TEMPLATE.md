# Chapter Template

## Instructions

Copy this template when starting a new chapter. Replace every placeholder (shown in `ALL_CAPS` or inside `< >`) with the actual content. Do not delete section headings — if a section is not applicable, write a brief note explaining why rather than removing the heading. Remove these instructions before submitting a draft for review.

---
---

<!-- COPY BELOW THIS LINE -->

# <Chapter Title>

<!-- TARGET: ~<word count> words | PERSONA: <primary persona from PERSONAS.md> | DIMENSION: <comparison dimension, e.g., "Liquidity"> -->

> "<Quote text here.>"
>
> — <Attribution, *Source Title* (Year)>
>
> *(See QUOTES_BANK.md for pre-vetted options, or propose a new quote for approval.)*

---

## Introduction

<!-- 300–500 words. Set the stage for the comparison dimension this chapter covers. Establish why this dimension matters to the reader's financial life. Introduce the central tension between stocks and real estate on this topic. End with a one- or two-sentence preview of what the chapter will show. Do NOT make a conclusion here — the reader hasn't seen the evidence yet. -->

<Introduction content here.>

---

## The Stocks Perspective

<!-- Explain how stocks behave with respect to this chapter's comparison dimension. Use specific data, historical examples, and named sources. Cite figures that will be logged in FACT_CHECK.md. Be fair — acknowledge limitations as well as strengths. Approximate length: 400–600 words. -->

<Stocks perspective content here.>

---

## The Real Estate Perspective

<!-- Explain how real estate behaves with respect to this chapter's comparison dimension. Use specific data, historical examples, and named sources. Cite figures that will be logged in FACT_CHECK.md. Be fair — acknowledge limitations as well as strengths. Approximate length: 400–600 words. -->

<Real estate perspective content here.>

---

## Side-by-Side Comparison

<!-- This section MUST include at least one comparison table. The table should make the key differences visually immediate. Additional tables are encouraged where they add clarity. Follow with 2–3 paragraphs of prose interpreting the table(s) — do not let the table stand alone without narrative context. -->

| Factor | Stocks | Real Estate |
|--------|--------|-------------|
| <Factor 1> | <Stock value> | <RE value> |
| <Factor 2> | <Stock value> | <RE value> |
| <Factor 3> | <Stock value> | <RE value> |
| <Factor 4> | <Stock value> | <RE value> |
| <Factor 5> | <Stock value> | <RE value> |

<Interpretive prose here — 2–3 paragraphs explaining what the table shows, what nuances it cannot capture, and what the reader should take from the comparison.>

---

## Case Study / Persona Analysis

*<One-sentence italic introduction naming the persona and the specific scenario being analyzed. Example: "Meet Jordan, a 34-year-old software engineer deciding whether to invest a $60,000 windfall in an index fund or a down payment on a rental property."*>

<!-- Analyze the comparison dimension through the lens of the primary persona for this chapter. Show the math or reasoning step by step. Acknowledge what factors might shift the conclusion for other personas. Reference the relevant persona profile in PERSONAS.md. Approximate length: 400–600 words. -->

<Case study / persona analysis content here.>

---

## Key Takeaways

<!-- 4–6 bullet points. Each bullet must be a complete, standalone sentence — readable in isolation without needing the surrounding chapter context. Write these as durable, actionable insights, not summaries of what the chapter said. Avoid starting consecutive bullets with the same word. -->

- <Takeaway 1.>
- <Takeaway 2.>
- <Takeaway 3.>
- <Takeaway 4.>
- <Takeaway 5 (optional).>
- <Takeaway 6 (optional).>

---

---
<!-- COPY ABOVE THIS LINE -->

---

## Status Footer Reference

Paste this footer at the very bottom of each chapter file and update the fields as the draft progresses:

```
---

**Chapter Status**

| Field | Value |
|-------|-------|
| Draft version | v0.1 |
| Word count | 0 |
| Primary persona | <Persona name> |
| Comparison dimension | <Dimension> |
| Fact-check status | Not started |
| Last edited | YYYY-MM-DD |
| Reviewed by | — |
| Notes | — |
```

---

## Section Notes

### Opening Quote
- Pull from `QUOTES_BANK.md` whenever possible. Quotes there have already been verified for accuracy and cleared for fair use.
- If proposing a new quote, add it to `QUOTES_BANK.md` with a source citation before including it in the chapter.
- The quote should connect thematically to the chapter's comparison dimension — not just investing in general.

### Introduction
- Do not repeat the book's overall thesis here. Assume the reader has read the preceding chapters.
- Introduce the comparison dimension as if it is a fresh problem the reader needs to solve.
- The final sentence of the Introduction should serve as a natural handoff into "The Stocks Perspective."

### The Stocks Perspective / The Real Estate Perspective
- These sections should be roughly equal in length and tone. Neither asset class gets a home-field advantage.
- Every statistic must have an in-text attribution (e.g., "According to the Federal Reserve's 2023 Survey of Consumer Finances..."). Log each claim in `FACT_CHECK.md` at the time of drafting.
- Use subheadings (H3) freely within these sections if the content covers multiple sub-topics.

### Side-by-Side Comparison
- The table is mandatory. Minimum five rows.
- Column headers must always be "Stocks" and "Real Estate" (consistent across all chapters).
- Cells should use concise phrases, not full sentences. Save full sentences for the prose below the table.
- If a cell is genuinely inapplicable, write "N/A" with a note in the prose explaining why.

### Case Study / Persona Analysis
- Use only personas defined in `PERSONAS.md`. Do not invent new personas mid-chapter.
- The italic intro sentence is mandatory — it orients the reader before the analysis begins.
- Show the math. If comparing investment outcomes, include actual figures with clearly stated assumptions (e.g., assumed return rate, time horizon, tax bracket).
- End with a brief note on how the conclusion might differ for a different persona type.

### Key Takeaways
- Minimum 4 bullets, maximum 6.
- Every bullet is a full sentence ending with a period.
- Write at a level where the takeaway is useful to someone who has NOT read the chapter — these bullets will also appear in summary materials.
- Do not start with "In conclusion," "Overall," or "As we've seen."
