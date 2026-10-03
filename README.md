<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Dominick%20Dupuy&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=systematic%20trading%20%C2%B7%20quantitative%20research&descSize=18&descAlignY=58" alt="Dominick Dupuy - systematic trading and quantitative research" />

<a href="https://github.com/dominickdupuy">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=900&color=4FC3F7&center=true&vCenter=true&width=640&lines=hypothesis+%E2%86%92+signal+%E2%86%92+backtest+%E2%86%92+risk;no+edge+without+a+reason+it+should+exist;out-of-sample+or+it+didn't+happen;CS+%2B+Statistics+%40+University+of+Florida" alt="Typing animation of research principles" />
</a>

<br/>

[![Website](https://img.shields.io/badge/domdupuy.com-0f2027?style=for-the-badge&logo=googlechrome&logoColor=white)](https://domdupuy.com)
[![GitHub](https://img.shields.io/badge/@dominickdupuy-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dominickdupuy)
![Location](https://img.shields.io/badge/Gainesville,_FL-2c5364?style=for-the-badge&logo=googlemaps&logoColor=white)
![University of Florida](https://img.shields.io/badge/University_of_Florida-FA4616?style=for-the-badge&logoColor=white)

</div>

---

## `>_` about

```python
class Dominick:
    school  = "University of Florida"        # CS + Statistics
    focus   = ["systematic trading", "alpha research", "backtesting", "risk"]
    method  = "state the edge, test it honestly, size for the drawdown"
    stack   = ["Python", "C++", "TypeScript", "Go"]

    def build_strategy(self, idea):
        hypothesis = self.explain_why_edge_exists(idea)
        signal     = self.forecast(hypothesis)
        results    = self.backtest(signal, costs=True, out_of_sample=True)
        return self.size_for_risk(results)
```

## `>_` research loop

```mermaid
flowchart LR
    A([Hypothesis<br/>why does edge exist?]) --> B[Signal<br/>rank / forecast]
    B --> C[Backtest<br/>costs + slippage]
    C --> D[Risk & sizing<br/>vol target, drawdown cap]
    D --> E{Validation<br/>walk-forward, OOS}
    E -->|passes| F([Paper trade, then live])
    E -->|fails| A
```

Every strategy starts from a named source of edge (risk premium, behavioral bias, structural flow, or information), not from a curve fit.

## `>_` focus areas

<table>
  <tr>
    <td width="50%" valign="top">

**Alpha research**
Time-series momentum, mean reversion, regression and MLP forecasts on futures and equities.

**Backtesting infrastructure**
Engines for equities and options.

**Risk**
Volatility targeting, drawdown control, regime awareness.

  </td>
    <td width="50%" valign="top">

**Machine learning**
Neural nets from scratch, GNNs, time-series models (NHiTS, TFT, LSTM).

**Prediction markets**
Trading engine and competition tooling.

**Competitions**
Optiver quant competition submission, Gator Quant Hacks site.

  </td>
  </tr>
</table>

## `>_` selected projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/dominickdupuy/UK_GasFuturesStrategy">UK_GasFuturesStrategy</a></h3>
      UK MSI futures strategy using multilinear regression and an MLP, targeting <b>+2 Sharpe</b>.<br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/futures-0f2027?style=flat-square" alt="futures" />
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/dominickdupuy/options-ngin">options-ngin</a></h3>
      Options backtesting engine.<br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/options-0f2027?style=flat-square" alt="options" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/dominickdupuy/predict-ngin">predict-ngin</a></h3>
      Prediction market trading engine.<br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/prediction_markets-0f2027?style=flat-square" alt="prediction markets" />
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/dominickdupuy/TradingClose">TradingClose</a></h3>
      Optiver quant competition submission.<br/><br/>
      <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
      <img src="https://img.shields.io/badge/quant-0f2027?style=flat-square" alt="quant" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/dominickdupuy/WikiRaceGNN">WikiRaceGNN</a></h3>
      GraphSAGE GNN scaled to all ~7M Wikipedia pages, cutting node traversals by <b>~400%</b> vs conventional methods.<br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/GNN-0f2027?style=flat-square" alt="GNN" />
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/dominickdupuy/gatorqh">gatorqh</a></h3>
      Site for Gator Quant Hacks 2026, including the Systematic Trading track briefing.<br/><br/>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
      <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
    </td>
  </tr>
</table>

<details>
<summary><b>More repositories</b></summary>
<br/>

| Project | What it is |
|---|---|
| [Systematic-Trading](https://github.com/dominickdupuy/Systematic-Trading) | Systematic strategy research in Python |
| [comp-backtest](https://github.com/dominickdupuy/comp-backtest) | Backtest harness for competition-style strategy evaluation |
| [SportsAnalysis](https://github.com/dominickdupuy/SportsAnalysis) | NBA prediction ensemble (NHiTS, TFT, LSTM, GNN) |
| [NeuralNetworkv2](https://github.com/dominickdupuy/NeuralNetworkv2) | From-scratch network with backpropagation and adaptive structure, applied to stock prices |
| [TradingBot](https://github.com/dominickdupuy/TradingBot) | Web app for researching financial data and market indicators |
| [Blockchain](https://github.com/dominickdupuy/Blockchain) | Cryptocurrency with a P2P network, written in Go |

</details>

## `>_` toolkit

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)

</div>

## `>_` github stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=dominickdupuy&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dominickdupuy&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="Top languages" />

</div>

## `>_` principles

1. No edge without a reason it should exist.
2. Out-of-sample or it didn't happen.
3. Costs and slippage are part of the strategy, not an afterthought.
4. Size positions for the drawdown you can survive, not the return you want.

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" alt="" />
