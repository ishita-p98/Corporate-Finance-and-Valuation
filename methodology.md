# Data, variables and empirical methodology

**Scope:** This document explains the methodology in Baker and Wurgler's paper as described by the group's presentation. The underlying Compustat and IPO datasets were **not** provided for this repository, and the regressions were **not** rerun.

## 1. Sample construction and data sources

The presentation identifies the following inputs:

| Source | Coverage stated in the slides | Role |
| --- | --- | --- |
| **Compustat** | Firm observations, **1968–1999** | Accounting and financing variables |
| **Jay Ritter's IPO database** | **1968–1995** | IPO dates |
| **Securities Data Company (SDC)** | **1970–1998** | Additional IPO information |

The slides describe excluding **financial firms (SIC 6000–6999)**, firms with assets below **$10 million**, and firm-years with extreme leverage or market-to-book values. The sample is organized by firm age relative to IPO (e.g., IPO+3).

These dates and exclusions reproduce the group's presentation framing; consult the original paper for precise sample definitions.

*Presentation: slide 8.*

## 2. Dependent variables: two views of leverage

**Book leverage**

\[
L^{book}=\frac{\text{Book debt}}{\text{Total assets}}
\]

**Market leverage**

\[
L^{market}=\frac{\text{Book debt}}{\text{Assets}-\text{Book equity}+\text{Market equity}}
\]

The distinction matters: changes in stock-market valuations can move market leverage mechanically even without new financing. Using both measures helps examine whether the result is limited to a particular leverage definition.

*Presentation: slide 9.*

## 3. Financing-channel decomposition

The slides identify three financing components, scaled by assets:

1. **Net equity issues**
2. **Net debt issues**
3. **Retained earnings**

The research asks whether a market-to-book relationship with leverage is associated primarily with firms issuing equity, changing debt financing, or accumulating retained earnings.

This is central to interpreting the short-run result. A correlation between valuations and leverage alone would not reveal the financing channel.

*Presentation: slides 9 and 12–13.*

## 4. The key explanatory variable: historical market-to-book

The paper introduces the **external-finance-weighted average market-to-book ratio**, often written \((M/B)_{efwa}\).

The group presentation gives the conceptual formula:

\[
(M/B)_{efwa}=\frac{\sum_t (M/B)_t\times EF_t}{\sum_t EF_t}
\]

where \(EF_t\) denotes the relevant external-financing weight. The slides explain that years with zero or negative external financing receive zero weight.

### Why this is different from current market-to-book

A firm's **current market-to-book ratio** describes its valuation today. The historical weighted measure instead summarizes the valuation environment **when the firm raised external financing**.

For intuition, imagine two firms with similar current financial characteristics. One raised substantial equity during a high-valuation period; the other raised capital during less favorable valuations. The historical measure distinguishes their financing paths.

This example is illustrative, not an additional observation from the paper.

*Presentation: slide 10.*

## 5. Main regression framework

The group summarizes a leverage specification of the form:

\[
Leverage_{i,t}=\alpha+\beta_1(M/B)_{efwa,i,t}
+\beta_2(M/B)_{i,t}+\gamma'Controls_{i,t}+\varepsilon_{i,t}.
\]

The controls highlighted in the slides are **asset tangibility, profitability and firm size**. The paper also considers book versus market leverage and different firm ages since IPO.

The presentation names **OLS, Fama–MacBeth, firm fixed effects and Tobit models** among the empirical approaches. These methods are not interchangeable; the slides provide a high-level summary rather than the complete estimating equations and tables.

## 6. Tests of persistence

The group explains that the paper examines:

- Current leverage against the historical weighted market-to-book measure.
- **Future leverage** at horizons after the historical financing window.
- Future leverage after accounting for subsequent fundamentals.
- **Cumulative leverage changes from before IPO**, to investigate whether results are explained by stable firm traits.

The central question is whether historical valuation conditions retain explanatory power as firms age.

## 7. What the design can and cannot show

Controlling for current market-to-book and observed fundamentals strengthens the interpretation that past financing conditions matter. But the slides' claim that historical weighted market-to-book *isolates* market timing should be read as the authors' identification argument, not an automatic proof of causation.

Unobserved financing needs, growth opportunities and adjustment costs may still be relevant when interpreting persistence.

*Presentation: slides 8–11 and 16–18.*

[Return to README](README.md)
