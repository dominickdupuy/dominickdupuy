# Dominick Dupuy

CS + Statistics @ University of Florida. Gainesville, FL.
I build systematic trading research: form a hypothesis, backtest it honestly, size it for risk, and stress-test it before believing it.

[domdupuy.com](https://domdupuy.com)

---

## Research loop

```
hypothesis  ->  signal  ->  backtest  ->  risk & sizing  ->  validation  ->  execution
 (why does      (rank /      (costs,       (vol target,       (walk-forward,   (paper first,
  edge exist?)   forecast)    slippage)     drawdown cap)      out-of-sample)   then live)
```

Every strategy starts from a stated source of edge (risk premium, behavioral bias, structural flow, or information), not from a curve fit.

## What I work on

- **Alpha research**: time-series momentum, mean reversion, regression and MLP forecasts on futures and equities
- **Backtesting infrastructure**: engines for equities and options
- **Risk**: volatility targeting, drawdown control, regime awareness
- **Machine learning**: neural nets from scratch, GNNs, time-series models (NHiTS, TFT, LSTM)
- **Prediction markets**: trading engine and competition tooling

## Selected projects

| Project | What it is |
|---|---|
| [UK_GasFuturesStrategy](https://github.com/dominickdupuy/UK_GasFuturesStrategy) | UK MSI futures strategy using multilinear regression and an MLP, targeting +2 Sharpe |
| [options-ngin](https://github.com/dominickdupuy/options-ngin) | Options backtesting engine |
| [predict-ngin](https://github.com/dominickdupuy/predict-ngin) | Prediction market trading engine |
| [TradingClose](https://github.com/dominickdupuy/TradingClose) | Optiver quant competition submission (C++) |
| [Systematic-Trading](https://github.com/dominickdupuy/Systematic-Trading) | Systematic strategy research in Python |
| [comp-backtest](https://github.com/dominickdupuy/comp-backtest) | Backtest harness for competition-style strategy evaluation |
| [WikiRaceGNN](https://github.com/dominickdupuy/WikiRaceGNN) | GraphSAGE GNN scaled to all ~7M Wikipedia pages, cutting node traversals by ~400% vs conventional methods |
| [SportsAnalysis](https://github.com/dominickdupuy/SportsAnalysis) | NBA prediction ensemble (NHiTS, TFT, LSTM, GNN) |
| [NeuralNetworkv2](https://github.com/dominickdupuy/NeuralNetworkv2) | From-scratch network with backpropagation and adaptive structure, applied to stock prices |
| [gatorqh](https://github.com/dominickdupuy/gatorqh) | Site for Gator Quant Hacks 2026, including the Systematic Trading track briefing |

## Toolkit

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)

## Principles

1. No edge without a reason it should exist.
2. Out-of-sample or it didn't happen.
3. Costs and slippage are part of the strategy, not an afterthought.
4. Size positions for the drawdown you can survive, not the return you want.
