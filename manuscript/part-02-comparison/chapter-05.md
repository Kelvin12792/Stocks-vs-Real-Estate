# Chapter 5. Returns and Growth Potential: Where Does Your Money Grow Faster?

<!--
Chapter: 5
Part: II. Head-to-Head Comparison
Draft version: v0.1
Word count target: 3,500
Last edited: 2026-04-13
Persona: David Chen, 38, software engineer, Austin TX
Comparison dimension: Returns and growth potential
-->

> "The stock market is a device for transferring money from the impatient to the patient."
> Widely attributed to Warren Buffett

---

## Introduction

Part I built two self-contained portraits of two asset classes and a metric dictionary for translating between them. Part II begins the comparison in earnest, and it begins with the question most readers want answered first: where does money actually grow faster? The question is natural, but as the previous chapters warned, the headline numbers hide more than they reveal. A stock return of 10 percent and a real estate return of 10 percent describe different economic events, are produced by different mixes of income and appreciation, come with different levels of risk, and, crucially, rest on very different assumptions about leverage.

This chapter takes the question seriously on its own terms. It begins with the long-run historical record for each asset class, unleveraged and before taxes, drawing on the primary-source datasets introduced in Chapter 1. It then decomposes total return into its two components, income and appreciation, and shows how the mix differs between stocks and real estate. It walks through the arithmetic by which mortgage leverage transforms a modest unlevered real estate return into a larger return on invested equity, and it shows what happens to that arithmetic in a down year. It compares the two asset classes on a risk-adjusted basis using the Sharpe ratio. It explores how the answer changes across different holding periods. And it closes with a single worked example, tracing $100,000 invested in each asset class over 10, 20, and 30 years under clearly stated assumptions, followed by a persona chapter that puts a real investor's face on the same arithmetic.

The honest summary of the chapter is this: over long horizons, unleveraged stocks have historically produced higher total returns than unleveraged real estate; leveraged real estate has historically produced returns competitive with or exceeding those of stocks, but with meaningfully different risk; and the right answer for any individual investor depends on which of those two regimes, leveraged or unleveraged, they actually have access to.

## Historical Average Returns

The most carefully constructed long-run comparison of stock and housing returns is Jordà, Knoll, Kuvshinov, Schularick, and Taylor, "The Rate of Return on Everything, 1870 to 2015," published in the Quarterly Journal of Economics in 2019. Using nearly 150 years of annual data from 16 advanced economies, the authors assemble total-return series for equities and for residential real estate that are, for the first time, directly comparable on a like-for-like basis. Their headline finding is that the unweighted average real (inflation-adjusted) total return to residential housing across these economies over 1870 to 2015 was approximately 7.1 percent per year, while the unweighted average real total return to equities over the same period was approximately 6.9 percent per year.[^1] On that long-run, cross-country, unleveraged basis, housing and equities produced roughly comparable total returns, with housing a hair ahead and equities exhibiting considerably higher volatility.

The U.S.-specific picture is different. Damodaran's historical returns dataset at NYU Stern, the standard reference used throughout Chapter 1, reports annualized total returns for the S&P 500 of approximately 10.0 to 10.3 percent in nominal terms and approximately 6.8 to 7.0 percent in real terms over the period 1928 to the most recent year, depending on the end date chosen and whether dividends are reinvested.[^2] Over the same window, the S&P/Case-Shiller U.S. National Home Price Index, the best available long-run series for U.S. residential price appreciation, shows a nominal annualized price appreciation of roughly 3.5 to 4.0 percent and a real price appreciation very close to zero, a result originally documented by Robert Shiller and since confirmed in the Case-Shiller data maintained by S&P Dow Jones Indices and archived at the Federal Reserve Bank of St. Louis.[^3]

The apparent contradiction between Jordà et al. (housing ≈ equities) and the U.S. price series (equities ≫ housing price appreciation) is resolved by one word: income. The Case-Shiller index tracks prices only; it does not include the imputed rental value that a homeowner receives or the net rental income that a landlord collects. Jordà et al.'s housing total-return series adds rental yield net of maintenance, property tax, and vacancy costs to price appreciation, and it is the rental component, not the price appreciation component, that closes most of the gap with equities. Over the long U.S. record, a reasonable, widely cited decomposition is that residential real estate delivers a real total return of perhaps 4 to 5 percent per year unleveraged, of which about three-quarters comes from net rental income and only about one-quarter comes from real price appreciation. The stock figure, by contrast, is split closer to half and half between real earnings growth plus valuation change on the one hand and reinvested dividends on the other.

The practical lesson is that any comparison that looks only at price charts understates the real estate return and, by extension, overstates the gap between stocks and real estate. Chapter 5 will keep returning to this point. The right comparison is between total return and total return, and the right total return for real estate is one that includes rent net of costs. Even so, on an unleveraged basis, the long-run U.S. record is that stocks have delivered a total return of roughly 10 percent nominal per year while housing has delivered roughly 5 to 7 percent, depending on the sample period and the assumptions made about rental yield net of costs, with stocks ahead but by a smaller margin than the price-only comparison suggests.

## Total Return: Appreciation Plus Income

Chapter 4 drew the distinction between production metrics and distribution metrics. The historical record in the previous section pushes the same distinction a step further. For both asset classes, total return is the sum of two streams: the change in the asset's price and the cash income the asset produces along the way. The relative size of those two streams is the single most important shape parameter in any long-run return comparison, and it differs sharply between stocks and real estate.

For U.S. equities, the historical split is roughly balanced. Damodaran's dataset and the standard academic decomposition both suggest that, over the long run, something close to half of the real total return to U.S. stocks has come from reinvested dividends and something close to half has come from real earnings growth and valuation change combined.[^2] The dividend yield on the S&P 500 has ranged from under 2 percent in the late 1990s and since the mid-2010s to well above 5 percent in the 1930s and early 1980s, and the exact split between income and appreciation depends heavily on the sample window. What is stable is the principle that dividends reinvested back into additional shares are not a side dish. They are a large share of the meal, and any investor who mentally treats dividends as pocket money rather than as reinvestment capital has, over a multi-decade horizon, forgone roughly half of the asset class's total return.

For U.S. residential real estate, the split is tilted the other way. Net rental income has historically contributed the majority of the real total return; real price appreciation has contributed a minority. The Jordà et al. dataset is the strongest published evidence for this claim, and it is corroborated by the Case-Shiller price series showing that real price appreciation on U.S. housing has been close to zero over the twentieth century.[^1][^3] The implication is that a real estate investor whose analysis stops at "what will this house sell for in ten years?" is missing the larger component of the asset's return. The smaller component is the one most visible to the general public, because house prices are quoted and discussed in a way that net rents never are.

The asymmetry matters for comparison because the two income streams are taxed differently, reinvested differently, and scaled differently. A stock dividend can be reinvested in a single click and compounds seamlessly inside a brokerage account. A rental cash flow has to be withdrawn, banked, and in most cases paired with fresh capital and a new transaction before it can be redeployed into another property. The stock investor's compounding is frictionless; the real estate investor's compounding is lumpy, deliberate, and subject to the same 7 to 11 percent round-trip cost flagged in Chapter 3. Over a lifetime, the difference between frictionless compounding and lumpy compounding is larger than many comparisons allow for, and Chapter 7 returns to it in its discussion of cash flow and passive income.

---

## Sources

[^1]: Òscar Jordà, Katharina Knoll, Dmitry Kuvshinov, Moritz Schularick, and Alan M. Taylor, "The Rate of Return on Everything, 1870 to 2015," *Quarterly Journal of Economics* 134, no. 3 (August 2019): 1225 to 1298, https://doi.org/10.1093/qje/qjz012. Headline real total-return figures are from Table I. This is the same primary source cited in Chapter 1 footnote 21.

[^2]: Aswath Damodaran, "Historical Returns on Stocks, Bonds and Bills: 1928 to Current," NYU Stern School of Business, https://pages.stern.nyu.edu/~adamodar/New_Home_Page/datafile/histretSP.html. Accessed 2026-04-13. This is the same primary source cited in Chapter 1 footnote 20.

[^3]: S&P Dow Jones Indices, S&P/Case-Shiller U.S. National Home Price Index, series CSUSHPINSA, Federal Reserve Bank of St. Louis (FRED), https://fred.stlouisfed.org/series/CSUSHPINSA. Accessed 2026-04-13. See also Robert J. Shiller, *Irrational Exuberance*, 3rd ed. (Princeton University Press, 2015), chapter on long-run home prices. This is the same primary source cited in Chapter 1 footnote 22.

---

*Status: First draft in progress. Draft version v0.1 partial. Sections complete: Introduction, Historical Average Returns, Total Return (Appreciation Plus Income). Sections pending: The Leverage Effect, Risk-Adjusted Returns, Time Horizon, $100K Side-by-Side Table, Persona (David Chen), Key Takeaways. Target word count 3,500; current partial word count approximately 1,250 excluding footnotes and metadata. Last edited 2026-04-13. Reviewed by: (pending).*
