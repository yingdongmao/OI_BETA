# The Term Structure of Beta

Public companion to the working paper

> **Gao, C. and Mao, Y.** *The Term Structure of Beta.*  Working paper.
>
> *Authors:* Chao Gao (Australian National University) and Yingdong Mao (University of Sydney).

*(Previously circulated as "Option-Implied Betas under a Common Lens: Buss–Vilkov versus Kempf–Korn–Saßning, with an Emphasis on the Term Structure".)*

## What the paper does

We estimate the **term structure of option-implied beta** for S&P 500 stocks using four estimators that rest on deliberately different identifying restrictions:

1. **Kempf–Korn–Saßning (KKS)** — a market-wide implied correlation.
2. **Buss–Vilkov (BV)** — a stock-specific implied correlation from a one-parameter affine transform of historical pairwise correlations.
3. A **premium-ratio beta** that removes announcement and idiosyncratic variance from implied variance.
4. A **regression-based beta** identified from the co-movement of stock and index implied variances.

All four sit inside the same decomposition,

$$\beta_i(\tau) = \rho_{iM}(\tau)\,\frac{\sigma_i(\tau)}{\sigma_M(\tau)},$$

so they differ only in how the risk-neutral correlation with the market is pinned down.

## Main findings

1. **The slope is priced.** For all four estimators the slope of the term structure — the 91-day minus the 30-day beta — predicts *lower* returns over the next month. A one-standard-deviation higher slope lowers the next month's return by **19 to 30 basis points**.
2. **It is not a repackaged anomaly.** For the two new estimators the slope premium survives the stock's own implied-volatility slope and its earnings-announcement component, and it is not explained by idiosyncratic volatility, by co-movement with common idiosyncratic variance, by horizon bias, or by mutual-fund demand.
3. **Term-structure economics.** The implied *systematic*-variance term structure departs from the expectations hypothesis by more than total implied variance does, and the premium is larger in recessions — consistent with prices of market risk that decline with horizon.

## Code & data

🔒 The full code repository and replication scripts are **private at this stage**. They will be released publicly once the paper is accepted for publication.

In the meantime, please direct enquiries to [Yingdong Mao](https://github.com/yingdongmao).
