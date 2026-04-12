# Contributing Guidelines

## Welcome

Thank you for your interest in contributing to *Stocks vs. Real Estate*. This document outlines the standards and processes for contributing to this book project.

---

## How to Contribute

### 1. Reporting Errors
If you find a factual error, outdated statistic, or incorrect legal/tax information:
- Open a GitHub Issue using the **Fact Check** label
- Include: the chapter number, the specific claim, the correct information, and a verifiable source
- All corrections will be logged in `tracking/FACT_CHECK.md` and `editions/ERRATA.md`

### 2. Suggesting Content
- Open an Issue with the **Content Suggestion** label
- Describe the topic, why it belongs in the book, and which chapter it relates to
- Include supporting sources where possible

### 3. Reviewing Drafts
- Draft chapters will be submitted as Pull Requests
- Reviewers should check for: factual accuracy, tone consistency, clarity, and adherence to the [Style Guide](STYLE_GUIDE.md)
- Use inline comments on the PR for specific feedback

### 4. Submitting Edits
- Fork the repository
- Create a branch named: `edit/chapter-XX-description`
- Make changes and submit a Pull Request with a clear description of what was changed and why

---

## Standards

All contributions must adhere to:

| Standard | Document |
|----------|----------|
| Writing tone and formatting | [STYLE_GUIDE.md](STYLE_GUIDE.md) |
| Visual design and layout | [design/DESIGN_GUIDE.md](design/DESIGN_GUIDE.md) |
| Chapter structure | [templates/CHAPTER_TEMPLATE.md](templates/CHAPTER_TEMPLATE.md) |
| Research integrity | See README.md — Research Integrity section |

---

## Branch Naming Conventions

| Purpose | Format | Example |
|---------|--------|---------|
| New chapter draft | `draft/chapter-XX` | `draft/chapter-05` |
| Chapter edit | `edit/chapter-XX-description` | `edit/chapter-05-fix-roi-calc` |
| Planning docs | `planning/description` | `planning/add-persona` |
| Design changes | `design/description` | `design/update-color-palette` |
| Bug/error fix | `fix/description` | `fix/chapter-09-tax-rate` |

---

## Commit Message Format

```
[type] Short description

- Detail 1
- Detail 2

Refs: #issue-number (if applicable)
```

**Types:** `[draft]` `[edit]` `[fix]` `[plan]` `[design]` `[track]` `[meta]`

**Examples:**
```
[draft] Complete first draft of Chapter 5 — Returns and Growth Potential

- Added historical S&P 500 return data (1926–2024)
- Added Case-Shiller home price index comparison
- Included persona case study: David, 38, software engineer
- Word count: 3,200

Refs: #12
```

---

## Code of Conduct

- Be respectful and constructive in all feedback
- Prioritize factual accuracy over opinion
- Cite sources for any factual claims added
- Maintain the neutral, objective tone of the book
