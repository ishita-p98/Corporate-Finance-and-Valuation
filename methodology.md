# Data and methodology

*The methods below describe the published study as summarized in the course presentation; no Compustat dataset or regressions were reproduced for this repository.*

## Sample

The slides describe **Compustat firms from 1968–1999**, combined with IPO dates from Jay Ritter's IPO database (1968–1995) and Securities Data Company (1970–1998). Financial firms (SIC 6000–6999), very small firms and observations with extreme leverage or market-to-book ratios are excluded. Firms are followed by years since IPO.

## Leverage measures

- **Book leverage:** book debt divided by total assets.
- **Market leverage:** book debt divided by assets minus book equity plus market equity.

The presentation also describes net equity issues, net debt issues and retained earnings scaled by assets to separate financing channels.

## Historical market-to-book measure

A central variable is the **external-finance-weighted average market-to-book ratio**, commonly written \(M/B_{efwa}\). It summarizes valuations at the times firms raised external financing:

\[
(M/B)_{efwa}=\frac{\sum_t (M/B)_t\times EF_t}{\sum_t EF_t}
\]

where \(EF_t\) denotes the external-financing weight in the simplified expression shown in the presentation. The slides state that years with zero or negative external financing receive zero weight.

The measure aims to capture **financing history**, rather than simply the firm's current valuation.

## Regression design

The presentation summarizes leverage regressions using historical weighted market-to-book, current market-to-book and controls including asset tangibility, profitability and firm size. It also mentions OLS, Fama–MacBeth, firm fixed effects and Tobit models, alongside a decomposition of leverage changes into equity issuance, debt issuance and retained earnings.

**Interpretation caution:** Controlling for observable fundamentals does not by itself establish that the estimated historical-valuation relationship is causal. The slide deck describes an identification argument; the full paper should be consulted for exact specifications.

**Source:** Group presentation, slides 8–11.

[Back to project overview](README.md)
