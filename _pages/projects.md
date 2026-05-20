---
permalink: /projects/
title: "Projects"
author_profile: true
---

## 📋 Bank Convertible Bond Research — Changjiang Securities
**Fixed Income | Macro & Credit | Internship Research Report · 2025.06–2025.09**

During my internship at Changjiang Securities, I independently authored a 
21-page institutional research report on China's bank convertible bond market 
(2015–2025) — the kind of report that goes out to real clients.

I tracked 26 bank CBs and over 1,000 individual securities across a full decade, 
mapping how valuation regimes shifted across four distinct macro environments: 
the 2015 bull market forced-redemption wave, the 2018 deleveraging shock, the 
2019 Baoshang Bank credit event, and the 2023–2025 supply-demand imbalance. 
The core finding: bank CB market dynamics are ultimately co-driven by regulatory 
cycles, banks' structural capital needs, and shifting capital market preferences 
— not just interest rates.

What I found most interesting was uncovering how "strategic conversion" (战略转股) 
emerged as a new exit mechanism — China Huarong's purchase of 40.56% of 
Everbright Bank's CBs in 2023 being a striking case study in creative capital 
structure management.

[📄 View Full Report (Chinese)](/files/convertible-bond-report.pdf)

---

## 🏆 Dynamic Portfolio Optimization — Kaggle S&P 500 Competition
**Published at ICLR 2026 · 2025.10–2025.12**

This project started as a Kaggle competition and ended up as a published paper 
at ICLR 2026. The task: predict S&P 500 excess returns from 98 high-dimensional 
time-series features, and generate daily portfolio weights (0–200%) to maximize 
a volatility-adjusted Sharpe ratio.

Our approach combined LightGBM and XGBoost in an ensemble, with careful feature 
engineering (110+ features including lagged returns, rolling Sharpe ratios, VIX 
interactions), 5-fold time-series cross-validation to prevent data leakage, and 
a custom PositionOptimizer that dynamically adjusts weights based on historical 
volatility regimes rather than blindly following model signals.

The result was a validation Sharpe of **0.714** with no volatility penalties — 
the strategy's annualized volatility stayed within 4.6% of the market benchmark. 
What I found most satisfying was the deliberate choice to submit Version 42 
(score: 0.655) over a higher-scoring overfit version, prioritizing robustness 
over leaderboard rank.

[📄 View Paper](/files/kaggle-sp500.pdf)

---

## 📊 Amazon–Whole Foods DCF Valuation & M&A Analysis
**FIN4210 Group Project · 2026.03–2026.04**

A full-stack valuation and M&A analysis of Amazon's $13.7B acquisition of Whole 
Foods — one of the most studied deals in modern tech-retail history.

We built a 5-step DCF model using 2012–2016 annual report data: revenue forecast 
via ratio regression (tapering from 4.0% to 2.5% growth), EBIT margin held at 
the 5-year average of 6.16%, NOPAT derived with a 38.73% effective tax rate, 
CAPEX at 4.03% of revenue, and terminal value via perpetuity growth model. 
Our estimated intrinsic value came out at **$11.1B** ($34.04/share) vs. the 
actual $13.7B acquisition price — a 23% premium.

The more interesting question was *why* the premium was rational. The gap between 
our DCF and the deal price reflects synergy value: supply chain integration, 
Prime ecosystem expansion, and Amazon gaining 460 physical stores overnight. 
Market validation was striking — Amazon's market cap rose $15.6B on announcement 
day, exceeding the acquisition cost itself.

We also identified three post-acquisition risks: cultural integration friction 
(Whole Foods employees unionized in 2018), brand dilution from Amazon's direct 
price cuts, and consumer resistance to palm-print payment technology rollout.

[📄 View Slides](/files/amazon-dcf.pdf)
