## Hi, I'm Ahmed Baahmed

Quantitative analyst working on portfolio risk, quantitative research and forecasting.

I live in Luxembourg and have been building statistical and quantitative models for more than 12 years, first for financial institutions and energy companies, then in data science and quantitative finance. With a post-graduation in applied mathematics: a postgraduate degree in Probability, Stochastic Analysis and Finance at the University of Luxembourg, and an M.Sc. in Operations Research, Optimization and Decision Making.

What I enjoy most is taking a model from an idea to something a team can actually use to make decisions, whether that's a VaR model, a trading signal or a price forecast.

### What I work on

- Market and portfolio risk: GARCH-based VaR and Expected Shortfall, stress tests, and backtesting with Kupiec and Christoffersen tests.
- Quantitative research: I research and backtest systematic strategies such as statistical arbitrage, mean reversion and factor models, using walk-forward tests and realistic transaction costs.
- Portfolio construction: mean-variance, Hierarchical Risk Parity, robust optimization, risk budgeting, and cleaning noisy covariance matrices with shrinkage and random matrix theory.
- Machine learning and deep learning: gradient boosting for forecasting, and LSTM and autoencoder models for time-series anomaly detection. I always compare them with simple statistical baselines before trusting them.
- Energy markets: day-ahead power price and load forecasting, and regime-switching models for price spikes.
- Model validation: checking how models behave out of sample, and writing down what they assume and where they break.

### Recent experience

- Since 2024 I've been a quantitative analyst at MG Consulting, working on risk analytics and statistical modelling. I built GARCH VaR models for equity and FX portfolios that lifted coverage from about 81% to 93% (the target was 95%), and I've validated more than six risk models.
- Since 2023 I've also been forecasting power prices and load for an energy company as a freelancer. My day-ahead price models cut the error by 24% compared with a seasonal-naive benchmark, and the load forecasts run at about 1.9% MAPE.
- From 2021 to 2023 I was a graduate research assistant in quantitative finance at the University of Luxembourg. I built a backtesting engine and tested pairs-trading and mean-reversion strategies. The best ones reached an out-of-sample Sharpe ratio of about 1.3. I also compared machine learning models with classical statistics for return forecasting.
- In 2024 I worked as a data scientist at IEE, where my LSTM and autoencoder models on more than 10 million sensor records reached an F1 score of 0.93 and cut false alarms by 31%.
- Before that I was a data scientist at Vodafone, and from 2013 to 2019 I worked as a statistician on forecasting and risk for financial and energy clients in Algeria.

### Projects

| Project | What it's about |
|---|---|
| Covariance Matrix Cleaning for Portfolio Construction (my thesis) | Comparing Mean-Variance, Hierarchical Risk Parity and Robust Optimization out of sample, with and without cleaning the covariance matrix |
| Multivariate Volatility and Dynamic Correlations | EWMA, CCC and DCC covariance models on SPY, TLT and GLD. Tracks how the stock-bond correlation moved (mostly negative from 2000 to 2020, positive in 2022) and compares which covariance model gives the best-backtesting portfolio VaR |
| Extreme Value Theory for Tail Risk | Hill tail index and peaks-over-threshold GPD fits on S&P 500 data back to 1928, with 99.9% VaR and ES compared against normal and Student-t. Then EVT on GARCH-standardized residuals (McNeil-Frey) with a backtest |
| Options Portfolio VaR: Delta-Normal vs. Delta-Gamma vs. Monte Carlo | A book of SPX options (long straddle, short puts, call spread) priced with Black-Scholes, using VIX as implied vol. Compares the three VaR methods, shows how delta-normal underestimates risk on non-linear positions, and simulates the underlying with GARCH instead of constant volatility |

I'm still publishing these repositories and will add the links here as they go up.

### Tools

Mostly Python (pandas, NumPy, statsmodels, arch, SciPy, cvxpy, scikit-learn, XGBoost, PyTorch), plus SQL, R, SAS and VBA.

### Languages

French and English fluently, and German at an intermediate level.

### Get in touch

I'm open to roles in portfolio risk, quantitative research and quantitative investment. The easiest way to reach me is on [LinkedIn](https://www.linkedin.com/in/ahmed-bhd).
