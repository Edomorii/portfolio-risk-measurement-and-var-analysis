# Portfolio Risk Measurement and VaR Analysis

Quantitative portfolio risk analytics project focused on Value-at-Risk modeling, volatility forecasting and systematic market risk estimation using Swiss equity market data.

---

## Project Overview

This project presents a comprehensive quantitative risk analysis of a Swiss equity portfolio using advanced Value-at-Risk (VaR) methodologies, portfolio risk decomposition techniques and volatility forecasting models.

The analysis evaluates how different quantitative frameworks capture:
- Portfolio exposure
- Diversification effects
- Systematic market risk
- Volatility clustering
- Downside tail-risk behavior under changing market conditions

The project combines statistical risk modeling, market factor analysis and volatility forecasting techniques to assess the strengths and limitations of different portfolio risk management methodologies in a realistic investment management environment.

---

## Key Areas Covered

- Parametric Value-at-Risk (VaR)
- Asset-Normal Portfolio VaR
- VaR Backtesting
- Component and Relative VaR Analysis
- Incremental VaR
- Market Beta Estimation
- EWMA Volatility Forecasting
- GARCH(1,1) Volatility Modeling
- Sharpe Diagonal VaR
- Portfolio Diversification Analysis

---

## Portfolio Composition

The portfolio analyzed between November 21, 2022 and March 13, 2025 consisted of the following Swiss equity positions:

| Asset | Position |
|---|---|
| Nestlé (NESN) | -30,000 shares (short) |
| Swiss Re (SREN) | +70,000 shares |
| Novartis (NOVN) | +80,000 shares |

The portfolio follows a buy-and-hold strategy where the number of shares remains constant throughout the investment horizon.

---

## Methodological Approach

The project combines:
- Historical volatility estimation
- Covariance-based portfolio modeling
- Statistical backtesting procedures
- Systematic risk estimation
- Dynamic volatility forecasting models

Particular attention is given to:
- Portfolio diversification effects
- Volatility persistence
- Market correlation structures
- Downside tail-risk estimation
- Model robustness under stressed market conditions

The analysis also evaluates how different volatility assumptions materially impact portfolio risk estimation and Value-at-Risk forecasts.

---

## Key Results

- Portfolio diversification reduced aggregate portfolio risk by approximately 36% relative to the undiversified sum of standalone asset VaRs
- Historical backtesting revealed exceedance rates slightly above theoretical expectations during periods of elevated market volatility
- Market beta estimation highlighted significant differences in systematic exposure across the portfolio constituents
- GARCH volatility forecasts produced VaR estimates materially closer to the Asset-Normal framework than EWMA-based estimates
- Incremental VaR analysis showed that portfolio rebalancing generated only a moderate increase in aggregate downside exposure due to diversification effects

---

## Real-World Applications

The methodologies implemented in this project are widely used across:
- Portfolio management teams
- Market risk divisions
- Investment banks
- Hedge funds
- Trading desks

to estimate downside exposure, evaluate diversification benefits, forecast volatility regimes and support portfolio allocation and risk management decisions.

---

## Repository Structure

```text
portfolio-risk-measurement-and-var-analysis/
│
├── data/                # Historical market datasets
├── excel-model/         # Portfolio risk modeling framework
├── outputs/             # Charts and analytical outputs
├── presentation/        # Project presentation materials
├── report/              # Full quantitative risk analysis report
└── README.md
```

---

## Technologies Used

- Microsoft Excel
- Quantitative Risk Modeling
- Statistical Portfolio Analysis
- EWMA Volatility Modeling
- GARCH(1,1) Modeling
- Covariance Matrix Analysis
- Market Beta Estimation
- Value-at-Risk Methodologies

---

## Risk Methodologies Implemented

| Methodology | Objective |
|---|---|
| Parametric VaR | Estimation of downside risk under normality assumptions |
| Asset-Normal VaR | Portfolio-level risk estimation using covariance structures |
| Backtesting | Validation of VaR model accuracy |
| Component VaR | Risk contribution decomposition |
| Incremental VaR | Portfolio rebalancing impact analysis |
| EWMA | Dynamic volatility forecasting |
| GARCH(1,1) | Volatility clustering and persistence modeling |
| Sharpe Diagonal VaR | Factor-based portfolio risk estimation |

---

## Objective

The project aims to demonstrate how quantitative risk management methodologies can be used to:
- Estimate portfolio downside exposure
- Evaluate diversification benefits
- Forecast market volatility
- Validate model robustness
- Support more informed portfolio management and risk control decisions
