# Appendix B — ROI and Cash Flow Calculators

<!-- DRAFT PLACEHOLDER — Target: ~1,500 words -->

*This appendix provides step-by-step calculators for comparing returns on stocks and real estate investments. All formulas are shown with worked examples so that every calculation is transparent and reproducible.*

---

## Calculator 1: Stock Portfolio Growth

### Formula

```
Future Value = P × (1 + r)^n + C × [((1 + r)^n - 1) / r]
```

Where:
- **P** = Initial investment (lump sum)
- **r** = Expected annual return (decimal)
- **n** = Number of years
- **C** = Annual contribution

### Worked Example

| Input | Value |
|-------|-------|
| Initial investment (P) | $50,000 |
| Annual contribution (C) | $6,000 |
| Expected annual return (r) | 8% (0.08) — conservative estimate for diversified index fund |
| Time horizon (n) | 20 years |

**Step 1:** Growth of initial investment
$50,000 × (1.08)^20 = $50,000 × 4.661 = **$233,048**

**Step 2:** Growth of annual contributions
$6,000 × [((1.08)^20 - 1) / 0.08] = $6,000 × 45.762 = **$274,572**

**Step 3:** Total future value
$233,048 + $274,572 = **$507,620**

**Total invested:** $50,000 + ($6,000 × 20) = $170,000
**Total growth:** $507,620 - $170,000 = **$337,620**

### Adjustments
- For **inflation-adjusted (real) returns**, use ~5–6% instead of 8%
- For **after-tax returns** in a taxable account, reduce by estimated tax drag (~0.5–1.5% depending on turnover and dividends)
- Returns in **tax-advantaged accounts** (401k, Roth IRA) grow tax-deferred or tax-free

---

## Calculator 2: Real Estate Cash Flow (Annual)

### Formula

```
Annual Net Cash Flow = Gross Rental Income - Operating Expenses - Debt Service
```

```
Cash-on-Cash Return = Annual Net Cash Flow / Total Cash Invested × 100
```

### Worked Example

| Input | Value |
|-------|-------|
| Purchase price | $300,000 |
| Down payment (20%) | $60,000 |
| Closing costs | $8,000 |
| **Total cash invested** | **$68,000** |
| Mortgage amount | $240,000 |
| Mortgage rate | 6.5% (30-year fixed) |
| Monthly mortgage payment (P&I) | $1,517 |

| Income | Monthly | Annual |
|--------|---------|--------|
| Gross rent | $2,200 | $26,400 |

| Operating Expenses | Monthly | Annual |
|-------------------|---------|--------|
| Property taxes | $250 | $3,000 |
| Insurance | $125 | $1,500 |
| Maintenance reserve (10% of rent) | $220 | $2,640 |
| Vacancy reserve (8% of rent) | $176 | $2,112 |
| Property management (10% of rent) | $220 | $2,640 |
| **Total operating expenses** | **$991** | **$11,892** |

| Cash Flow Calculation | Annual |
|----------------------|--------|
| Gross rental income | $26,400 |
| Minus operating expenses | -$11,892 |
| **Net Operating Income (NOI)** | **$14,508** |
| Minus debt service ($1,517 × 12) | -$18,204 |
| **Annual net cash flow** | **-$3,696** |

**Cash-on-Cash Return:** -$3,696 / $68,000 × 100 = **-5.4%**

### Important Notes on This Example
- This example shows a **negative cash flow** scenario — common in higher-priced markets at current interest rates
- **Total return** includes appreciation + mortgage paydown + tax benefits, not just cash flow
- At 3% annual appreciation: property value grows ~$9,000/year
- Annual mortgage principal paydown: ~$3,600 in year 1
- Depreciation tax benefit (assuming 25% bracket): ~$2,727/year deduction value
- **Total return picture** is more favorable than cash flow alone suggests

---

## Calculator 3: Real Estate Total Return (Annual)

### Formula

```
Total Return = Cash Flow + Appreciation + Principal Paydown + Tax Benefit
ROI = Total Return / Total Cash Invested × 100
```

### Worked Example (Using Calculator 2 inputs)

| Return Component | Annual Value |
|-----------------|-------------|
| Net cash flow | -$3,696 |
| Appreciation (3% of $300,000) | +$9,000 |
| Mortgage principal paydown (year 1) | +$3,600 |
| Tax benefit of depreciation (est.) | +$2,727 |
| **Total return** | **$11,631** |

**Total ROI on cash invested:** $11,631 / $68,000 × 100 = **17.1%**

*Note: Appreciation is unrealized until the property is sold or refinanced. This is a paper return, not cash in hand.*

---

## Calculator 4: Side-by-Side Comparison

### Scenario: $68,000 available to invest

| Metric | Stocks (Index Fund) | Real Estate (Rental Property) |
|--------|-------------------|-------------------------------|
| Initial investment | $68,000 | $68,000 (down payment + closing) |
| Asset controlled | $68,000 | $300,000 (4.4:1 leverage) |
| Year 1 income | ~$1,360 (2% div yield) | -$3,696 (net cash flow) |
| Year 1 appreciation (est.) | ~$5,440 (8% return) | ~$9,000 (3% on $300K) |
| Year 1 total return | ~$6,800 | ~$11,631 |
| Year 1 ROI on cash | ~10% | ~17.1% |
| Liquidity | High — sell in seconds | Low — 30–90 day sale process |
| Time commitment | 1–2 hours/month | 5–15 hours/month (or pay manager) |
| Risk profile | Market volatility | Concentration + leverage + tenant risk |

### 10-Year Projection (Simplified)

| Year | Stock Portfolio Value | RE Equity (est.) |
|------|---------------------|------------------|
| 0 | $68,000 | $68,000 |
| 5 | $99,932 (8% annual) | $127,764 (appreciation + paydown) |
| 10 | $146,826 (8% annual) | $201,450 (appreciation + paydown) |

*Assumptions: Stock returns at 8% nominal annually, no additional contributions. Real estate at 3% annual appreciation, mortgage paydown per amortization schedule. Simplified — does not account for taxes, inflation, maintenance capex, or rental income reinvestment.*

---

## Disclaimer

These calculators are educational tools for illustrative purposes. Actual returns will vary based on market conditions, property specifics, tax situation, and other factors. Past performance does not guarantee future results. Consult a qualified financial advisor before making investment decisions.

---

*Printable worksheet versions of these calculators are available in Appendix C.*
