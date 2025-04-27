# # Dynamic-CDO-Stress-Testing-Dashboard

This project implements a Dynamic CDO Portfolio Stress Testing engine built with Python, Dash, and Plotly.

It simulates correlated defaults, stochastic recovery rates, and macroeconomic-driven credit deterioration over a 60-month horizon for a synthetic portfolio of 100 obligors across multiple sectors.
The results are visualized in real-time through an interactive dashboard with animation of loss evolution.

# Features
- Gaussian Copula Simulation for correlated default generation across obligors.
- Dynamic Default Probabilities adjusted monthly based on macroeconomic shocks.
- Sector-specific Correlation Structures to model systemic risk more realistically.
- Stochastic Recovery Rates modeled using Beta distributions to capture LGD (Loss Given Default) variability.
- Normal environment
- Recession
- Credit Crunch
- Market Shock
- Tranche-based Loss Analysis (Equity, Mezzanine, Senior tranches).
- Real-Time Dashboard built using Dash and Plotly:
- Interactive controls for macro shock mean, volatility, sector correlation scaling, recovery distribution skewness, and stress scenario selection.
- Smooth animated visualization of cumulative portfolio loss distribution over 60 months.
