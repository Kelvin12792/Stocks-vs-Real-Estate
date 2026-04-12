# Data Sources

## Purpose
Dedicated tracker for all datasets, government publications, and statistical sources used for numerical claims in the book. Separate from RESEARCH_SOURCES.md (which covers books, speeches, and articles).

---

## Stock Market Data

| Data Point | Source | URL | Frequency | Chapters |
|-----------|--------|-----|-----------|----------|
| S&P 500 historical annual returns (1926–present) | NYU Stern (Aswath Damodaran) | pages.stern.nyu.edu/~adamodar | Annual update | Ch. 1, 5 |
| S&P 500 total return with dividends reinvested | S&P Dow Jones Indices | spglobal.com/spdji | Monthly | Ch. 5 |
| Historical dividend yields (S&P 500) | multpl.com / S&P Global | multpl.com/s-p-500-dividend-yield | Monthly | Ch. 7 |
| Stock market volatility (VIX) | CBOE | cboe.com/vix | Daily | Ch. 6 |
| P/E ratio historical averages | multpl.com / Shiller | multpl.com/shiller-pe | Monthly | Ch. 2, 4 |
| Margin debt levels | FINRA | finra.org/investors/margin-statistics | Monthly | Ch. 11 |
| Investor behavior gap | Dalbar QAIB Report | dalbar.com | Annual | Ch. 14 |
| Market capitalization data | World Federation of Exchanges | world-exchanges.org | Annual | Ch. 2 |

## Real Estate Data

| Data Point | Source | URL | Frequency | Chapters |
|-----------|--------|-----|-----------|----------|
| Median home price (US) | National Association of Realtors (NAR) | nar.realtor | Monthly | Ch. 3, 5, 12 |
| Case-Shiller Home Price Index | S&P Dow Jones Indices | spglobal.com/spdji | Monthly | Ch. 1, 5, 6 |
| Homeownership rate | US Census Bureau | census.gov/housing | Quarterly | Ch. 1, 3, 12 |
| Rental vacancy rates | US Census Bureau | census.gov/housing/hvs | Quarterly | Ch. 6, 7 |
| Median gross rent | US Census Bureau (ACS) | census.gov | Annual | Ch. 7 |
| Housing starts and permits | US Census Bureau | census.gov/construction | Monthly | Ch. 3 |
| Average cap rates by market | CBRE, Real Capital Analytics | cbre.com | Quarterly | Ch. 3, 4, 5 |
| Commercial real estate vacancy rates | CBRE, CoStar | cbre.com / costar.com | Quarterly | Ch. 3, 6 |
| Average property management fees | Buildium/NARPM surveys | narpm.org | Annual | Ch. 8 |
| Closing cost averages | ClosingCorp, Bankrate | bankrate.com | Annual | Ch. 10, 12 |

## Macroeconomic Data

| Data Point | Source | URL | Frequency | Chapters |
|-----------|--------|-----|-----------|----------|
| Consumer Price Index (CPI) | Bureau of Labor Statistics (BLS) | bls.gov/cpi | Monthly | Ch. 1, 5 |
| Inflation rate (historical) | FRED (Federal Reserve Bank of St. Louis) | fred.stlouisfed.org | Monthly | Ch. 1, 5 |
| Federal Funds Rate (historical) | Federal Reserve | federalreserve.gov | Per meeting | Ch. 1, 11 |
| 30-year fixed mortgage rate | Freddie Mac PMMS | freddiemac.com/pmms | Weekly | Ch. 11, 12 |
| GDP growth rate | Bureau of Economic Analysis (BEA) | bea.gov | Quarterly | Ch. 1 |
| Unemployment rate | BLS | bls.gov | Monthly | Ch. 1, 6 |
| Recession dates | NBER | nber.org/research/data/us-business-cycle-expansions-and-contractions | As declared | Ch. 1, 6 |

## Wealth and Demographic Data

| Data Point | Source | URL | Frequency | Chapters |
|-----------|--------|-----|-----------|----------|
| Median net worth by homeowner vs. renter | Federal Reserve Survey of Consumer Finances (SCF) | federalreserve.gov/econres/scfindex.htm | Every 3 years | Ch. 1, 12 |
| Net worth by age group | Federal Reserve SCF | federalreserve.gov | Every 3 years | Ch. 1, 17 |
| Asset allocation by household wealth | Federal Reserve SCF | federalreserve.gov | Every 3 years | Ch. 15 |
| Stock market participation rate | Federal Reserve SCF / Gallup | gallup.com | Annual (Gallup) | Ch. 1, 2, 12 |
| Accredited investor thresholds | SEC Regulation D | sec.gov | As amended | Ch. 12 |

## Tax Data

| Data Point | Source | URL | Frequency | Chapters |
|-----------|--------|-----|-----------|----------|
| Federal capital gains tax rates | IRS | irs.gov | Annual (per tax year) | Ch. 9 |
| Federal income tax brackets | IRS | irs.gov | Annual | Ch. 9 |
| Property tax rates by state | Tax Foundation | taxfoundation.org | Annual | Ch. 9 |
| State income tax rates | Tax Foundation | taxfoundation.org | Annual | Ch. 9 |
| Estate tax exemption amounts | IRS | irs.gov | Annual | Ch. 9 |
| Depreciation schedules | IRS Publication 946 | irs.gov | Annual | Ch. 9 |

---

## Data Freshness Protocol

| Action | When |
|--------|------|
| Verify all annual data points are current year | Before each chapter finalization |
| Check for revisions to previously published data | During fact check phase |
| Log data vintage in FACT_CHECK.md | Per data point |
| Flag data older than 3 years for edition review | During EDITION_PLAN.md review |
| Re-pull all data for new editions | At start of each new edition cycle |
