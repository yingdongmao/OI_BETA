# Option-Implied Betas under a Common Lens

Public companion to the working paper

> **Mao, Y. and Gao, C.** *Option-Implied Betas under a Common Lens: Buss-Vilkov versus Kempf-Korn-Sassning, with an Emphasis on the Term Structure.*  Working paper.
>
> *Authors:* Yingdong Mao (University of Sydney) and Chao Gao (Australian National University).

## What the paper does

We place the option-implied beta estimators of **Buss & Vilkov (2012)** (BV) and **Kempf, Korn & Sassning (2015)** (KKS) inside a single beta-decomposition framework,

$$\beta_i(\tau) = \rho_{iM}(\tau)\,\frac{\sigma_i(\tau)}{\sigma_M(\tau)}.$$

Within this language the two methods differ in *exactly one object*: the stock-specific implied correlation with the market. BV supplies it via a one-parameter affine transform of historical pairwise correlations; KKS replaces it with a market-wide constant.

We make three points:

1. **Nesting.** KKS is the constant-correlation special case of BV in the large-diversification limit. The whole gap between the two reduces to the cross-sectional heterogeneity of implied market correlations.
2. **Term structure.** Applied to $\Delta\beta_i = \beta_i(\tau_L) - \beta_i(\tau_S)$, BV carries a name-specific correlation term structure whereas KKS carries only a market-wide one. BV is therefore more accurate when the signal lives in correlations, but KKS degrades much more gracefully when long-horizon pairwise-correlation data are unreliable.
3. **Attribution.** Decomposing implied volatility additively, $\sigma^{IV} = \sigma^{ERV} + \sigma^{VRP}$, the KKS beta admits a clean additive split into ERV and VRP components sharing the same denominator; BV does not, because both its index volatility and its risk-neutral correlation carry their own variance- and correlation-risk premia. KKS therefore offers a cleaner per-stock attribution of the beta slope.

## Code & data

🔒 The full code repository and replication scripts are **private at this stage**. They will be released publicly once the paper is accepted for publication.

In the meantime, please direct enquiries to [Yingdong Mao](https://github.com/yingdongmao).
