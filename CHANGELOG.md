# Changelog

This file records meaningful changes to the *Stocks vs. Real Estate* book repository over time. It is not auto-generated — entries are written by hand to capture intent, not just file diffs. Use it to understand what changed, when, and why.

---

## Format

Each entry follows this structure:

```
YYYY-MM-DD [tag] Brief description of the change.
```

**Type tags:**

| Tag | Use for |
|-----|---------|
| `[draft]` | New prose written or a chapter section completed |
| `[edit]` | Revisions, rewrites, or cuts to existing prose |
| `[fix]` | Corrections to facts, figures, citations, or errors |
| `[plan]` | Changes to structure, outline, scope, or schedule |
| `[design]` | Updates to style guide, layout decisions, or visual assets |
| `[track]` | Progress tracker, word count, or status updates |
| `[meta]` | Repository files, tooling, templates, or housekeeping |

Multiple tags may be used on a single entry when appropriate, e.g. `[plan][meta]`.

---

## Entries

2026-04-12 [meta][plan] Initial repository setup. Created full project scaffold including OUTLINE.md (18 chapters across four parts plus front and back matter), BOOK_BLUEPRINT.md, STYLE_GUIDE.md, CHAPTER_TEMPLATE.md, PROGRESS.md, WORD_COUNT.md, DATA_SOURCES.md, RESEARCH_SOURCES.md, FACT_CHECK.md, FIGURES_AND_TABLES.md, MYTHS_LIST.md, PERSONAS.md, QUOTES_BANK.md, REVIEW_NOTES.md, LEGAL_REVIEW.md, EDITION_PLAN.md, EDITION_LOG.md, ERRATA.md, CONTRIBUTING.md, ISSUE_TEMPLATE.md, and LICENSE.md. Added placeholder files for all 18 chapters (chapter-01.md through chapter-18.md), four appendices, and front-matter pages (cover, disclaimer, how-to-use-this-book, introduction, glossary). No prose drafted yet — all chapter files are stubs pending the drafting phase.

2026-04-12 [meta] Fixed file-to-content mismatches across all 45 original files; created 11 additional files (CHAPTER_TRACKER, DESIGN_GUIDE, EDITION_LOG, ERRATA, QUOTES_BANK, appendix-b, appendix-d, chapter-09, chapter-13, chapter-17, chapter-18). Repository now contains 53 correctly named files.

2026-04-12 [meta] Nested the flat repository into manuscript/ (with part-01-foundations, part-02-comparison, part-03-mind-game, part-04-putting-it-together, 00-front-matter, and back-matter), planning/, tracking/, design/, and templates/ folders. All 49 moves preserved git history via git mv.

2026-04-12 [draft][track] First draft of Chapter 1, The Wealth-Building Landscape. ~3,050 words. Covers the Buttonwood Agreement through commission-free trading for stocks; the Homestead Act through REITs and FIRREA for real estate; a Century of Returns comparison table drawing on Jordà et al. (2019) and Damodaran; historical inflection points from 1929 through COVID; and a detailed 2008 financial crisis case study comparing S&P 500 and Case-Shiller peak-to-trough and recovery paths. 12 [VERIFY] / [LEGAL CHECK] flags logged to FACT_CHECK.md (claims 1.01–1.25) and LEGAL_REVIEW.md (L.06–L.11). Six new glossary entries added: Bucket Shop, Buttonwood Agreement, Correlation, Homestead Act, Index Fund, Survey of Consumer Finances, Survivorship Bias. Table T1.1 logged in FIGURES_AND_TABLES.md.

2026-04-13 [edit][fix][meta] Chapter 1 second pass. (1) STYLE_GUIDE.md updated with a new Punctuation Rules section forbidding em dashes anywhere in the manuscript going forward (en dashes permitted only in numeric/date ranges); Citations rule rewritten to permit numbered Markdown footnotes (`[^n]`) for primary-source attribution, with a chapter-level Sources section replacing the old "inline only, no footnotes" rule. (2) Chapter 1 prose fully edited to remove all em dashes, replaced with commas, colons, parentheses, semicolons, or sentence breaks; title and quote attribution also de-dashed. (3) Every [VERIFY] and [LEGAL CHECK] flag in Chapter 1 replaced with a verified numbered footnote (22 total) pointing to primary sources (govinfo.gov Public Laws, U.S. National Archives Milestone Documents, FRASER / St. Louis Fed, SEC Historical Society, Vanguard corporate history, State Street SPDR anniversary release, Nareit, Federal Reserve SCF 2022, Jordà et al. QJE 2019, NYU Stern / Damodaran historical returns dataset, FRED CSUSHPINSA) and authoritative secondary sources where needed. (4) FACT_CHECK.md rows 1.01–1.25 updated from 🟡 to 🟢 with Verified Date 2026-04-13 and expanded source citations. (5) LEGAL_REVIEW.md rows L.06–L.11 updated from 🟡 to 🟢 with full statute citations (public law numbers and Stat. references). Chapter 1 draft version bumped to v0.2.
