# COVID-19 Statistical Arbitrage Strategy

A pairs trading framework that analyzes market relationships during COVID-19 volatility periods using adaptive hedge ratios and mean reversion modeling.

## Overview

This project implements a statistical arbitrage strategy that identifies when stock relationships break down during market stress periods, specifically analyzing the COVID-19 era (2020-2024). The strategy uses dynamic modeling to replace static relationships with adaptive systems that adjust to changing market conditions.

## Research Foundation

### Core Methodology
- **Ornstein-Uhlenbeck Process**: Uhlenbeck & Ornstein (1930) "On the Theory of the Brownian Motion"
- **Pairs Trading Framework**: Gatev et al. (2006) "Pairs Trading: Performance of a Relative-Value Arbitrage Rule"
- **Mean Reversion Testing**: Avellaneda & Lee (2010) "Statistical Arbitrage in the U.S. Equities Market"

### Adaptive Systems
- **Rolling Hedge Ratios**: Alexander & Dimitriu (2005) "Indexing, Cointegration and Equity Market Regimes"
- **Time-Varying Correlations**: Engle (2002) "Dynamic Conditional Correlation" (Nobel Prize work)

### COVID Market Analysis
- **Regime Detection**: Baker et al. (2020) "The Unprecedented Stock Market Reaction to COVID-19"
- **Correlation Breakdown**: Haroon & Rizvi (2020) "COVID-19: Media Coverage and Financial Markets Behavior"

## Key Features

### Adaptive Hedge Ratio System
- **Rolling 30-day regressions** between stocks and sector ETFs
- **Dynamic position sizing** that adjusts when correlations change
- **Time-varying models** replace static relationships

### Mean Reversion Detection
- **Ornstein-Uhlenbeck process** for statistical testing
- **Regime-specific analysis** across market conditions
- **Signal generation** based on statistical significance

### COVID Market Analysis
- **Pre-COVID (Jan-Feb 2020)**: Strategy baseline performance
- **COVID Crash (Mar-Jun 2020)**: Market stress testing
- **Recovery (Jul 2020-Jun 2021)**: Adaptation analysis
- **Post-Vaccine (Jul 2021-2024)**: Long-term robustness

## Technical Implementation

- **Transaction Cost Modeling**: Realistic bid-ask spreads and market impact
- **Risk Management**: Position sizing and filtering based on mean reversion speed
- **Performance Analytics**: Comprehensive regime and drawdown analysis


## Key Insights

This strategy demonstrates how **relationships between stocks and sectors break down during market stress**, requiring adaptive systems rather than static models. The COVID analysis reveals that successful quantitative strategies must account for **regime changes** and **correlation instability**.

## References

1. Gatev, E., Goetzmann, W. N., & Rouwenhorst, K. G. (2006). Pairs trading: Performance of a relative-value arbitrage rule. *The Review of Financial Studies*, 19(3), 797-827.
2. Avellaneda, M., & Lee, J. H. (2010). Statistical arbitrage in the US equities market. *Quantitative Finance*, 10(7), 761-782.
3. Baker, S. R., Bloom, N., Davis, S. J., Kost, K., Sammon, M., & Viratyosin, T. (2020). The unprecedented stock market reaction to COVID-19. *The Review of Asset Pricing Studies*, 10(4), 742-758.
4. Engle, R. (2002). Dynamic conditional correlation: A simple class of multivariate generalized autoregressive conditional heteroskedasticity models. *Journal of Business & Economic Statistics*, 20(3), 339-350.

---
*Built with Python • NumPy • Pandas • Scikit-learn*
