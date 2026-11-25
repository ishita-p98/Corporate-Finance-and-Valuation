# Market Timing and Capital Structure

### Can decisions made during equity-market booms shape a company's leverage for decades?

**Corporate Finance & Valuation | Collaborative research project | Capital structure, equity issuance and empirical corporate finance**

This case study examines **Malcolm Baker and Jeffrey Wurgler's _Market Timing and Capital Structure_** through the lens of our university group presentation. It explores why companies tend to raise equity when valuations are high, how those choices affect leverage, and why the resulting financing history may persist long after the original issuance.

The central idea is straightforward: **a company's debt-to-equity mix may reflect the market conditions it encountered in the past, not simply an optimal capital structure chosen today.**

> **Research attribution:** The data, empirical models and reported findings discussed here come from Baker and Wurgler's research, as summarized in our presentation. This is a collaborative academic literature analysis, **not** an independent econometric replication.

## Executive summary

| Question | What the paper finds, as presented by our group |
| --- | --- |
| Do firms time equity issuance? | Higher market-to-book ratios are associated with more net equity issuance and lower leverage. |
| Which financing channel matters? | Net equity issuance is the main channel in the presented decomposition; debt issuance and retained earnings do not explain the result in the same way. |
| Do past valuations matter years later? | The external-finance-weighted historical market-to-book ratio is negatively related to current leverage. |
| Do firms quickly reverse timing-driven leverage changes? | The slides report that 73% of the book-leverage effect remains after ten years, with approximately full persistence for market leverage. |
| What does this mean for corporate finance? | Financing history may matter alongside current profitability, asset tangibility, firm size and investment opportunities. |

## The research in five steps

```mermaid
flowchart LR
  A[High market valuation] --> B[Greater equity issuance]
  B --> C[Lower leverage]
  C --> D[Financing history accumulates]
  D --> E[Persistent capital structure effects]
```

*Conceptual interpretation of the paper's argument, not a causal mechanism independently tested in this repository.*

## Explore the full analysis

1. **[Research context and competing theories](research-overview.md)** — why market timing matters and how it differs from trade-off and pecking-order theories.
2. **[Data, variables and empirical design](methodology.md)** — Compustat and IPO samples, leverage definitions, the external-finance-weighted market-to-book measure, regression specifications and financing-channel decomposition.
3. **[Findings and persistence evidence](empirical-findings.md)** — short-run issuance, historical valuations, long-run leverage, cumulative changes and robustness checks.
4. **[Critical evaluation and extensions](critical-discussion.md)** — how to interpret the evidence, alternative explanations, and applications to contemporary financing markets.
5. **[Conclusions and classical finance theory](theoretical-implications-and-conclusions.md)** — what the findings mean for Modigliani–Miller, trade-off and pecking-order theory, and where the evidence stops short.
6. **[Sources and acknowledgements](references.md)** — paper attribution, slide-to-section mapping and group credit.

## Three findings worth remembering

**1. Equity issuance links valuations to leverage.** The presentation reports a **1.14 percentage-point decrease in leverage** associated with a one-standard-deviation increase in market-to-book for the IPO+3 illustration.

**2. History remains visible in capital structure.** The paper's external-finance-weighted market-to-book variable summarizes valuations when a firm accessed external capital, rather than relying only on today's market-to-book ratio.

**3. Adjustment appears slow.** The presentation reports **73% persistence in the book-leverage effect after ten years**, challenging a simple story of rapid rebalancing toward fixed leverage targets.

These are paper-specific reported results; they are not universal forecasts or estimates reproduced here.

## What this project demonstrates

- Understanding of **capital structure and corporate financing theories**
- Ability to explain **regression-based empirical research**
- Interpretation of **market-to-book ratios, leverage and financing flows**
- Critical assessment of **identification, persistence and robustness**
- Communication of academic findings in a **collaborative research presentation**

## Acknowledgements

This project was developed collaboratively as part of the *Corporate Finance & Valuation* course. Thanks to **Linus Höller, Rehaan Joseph, Gunjan Kapoor and Yigit Yüceer** for their contributions.

The original presentation is not uploaded because it contains student identifiers. This repository is a newly written research case study, not a reproduction of the presentation or the authors' dataset. **Educational use only.**
