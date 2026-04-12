# Issue Template

## Purpose

Standard format for GitHub issues in the *Stocks vs. Real Estate* book project. Use this template when opening any issue to ensure consistent tracking of tasks, edits, reviews, and fixes across all contributors.

---

## Issue Title Format

```
[type] Chapter X — Short description of the task
```

### Type Tags

| Tag | Use When |
|-----|----------|
| `[draft]` | Writing a new chapter or section from scratch |
| `[edit]` | Revising or improving existing prose |
| `[fix]` | Correcting a specific error (factual, formatting, structural) |
| `[fact-check]` | Verifying a claim, statistic, or data point |
| `[legal-review]` | Flagging content that requires legal or disclaimer review |
| `[design]` | Tasks related to figures, tables, charts, or layout elements |

---

## Issue Body Template

```
## Description

[Describe the task clearly. What needs to be done and why?]

## Acceptance Criteria

- [ ] [What does "done" look like for this issue?]
- [ ] [Add as many criteria as needed]

## Related Files

- [List any files directly involved, e.g., `chapter-05.md`, `FACT_CHECK.md`]

## Data Sources Needed

- [List any data sources, reports, or references required to complete this task]
- [Leave blank if not applicable]

## Notes

[Any additional context, constraints, open questions, or links to related issues]
```

---

## Example Issue

**Title:** `[fact-check] Chapter 5 — Verify S&P 500 annualized return figure (1926–2023)`

**Body:**

```
## Description

The current draft of Chapter 5 cites a 10.0% nominal annualized return for the S&P 500
from 1926 to 2023. This figure needs to be verified against a primary source before the
chapter is marked ready for review.

## Acceptance Criteria

- [ ] Figure confirmed against a named primary source (e.g., Ibbotson, Damodaran, or SBBI)
- [ ] Source citation added inline in chapter-05.md
- [ ] Entry logged in FACT_CHECK.md with source URL and access date

## Related Files

- chapter-05.md
- FACT_CHECK.md
- DATA_SOURCES.md

## Data Sources Needed

- Damodaran Online historical return datasets (damodaran.com)
- SBBI Yearbook (Morningstar/Ibbotson)

## Notes

If the exact figure differs by more than 0.2 percentage points from what is cited,
open a follow-up [fix] issue to update the text.
```
