# Multi-Timeframe Trading Signal Research

A small study project on trading signals. It trades TSLA on hourly bars and uses the daily chart as context.
Every idea is compared with simply holding SPY over the same hours, with a flat fee of 5 dollars per trade.

There are two notebooks. `research_pipeline.ipynb` is the main one and goes step by step.
It covers three simple rules, how a backtest works, a train and test split, a daily trend filter, position sizing and a small machine learning model.
`plot_chart.ipynb` is a market chart with candles, moving averages and the levels of the previous day.

The data comes live from Yahoo Finance, so the numbers change every time you run it.
Hourly data only goes back about two years, which is the main limit of the study.

This is for learning only. It is not financial advice.

## How to run

```
pip install -r requirements.txt
jupyter notebook
```

Then open `research_pipeline.ipynb` and run the cells from top to bottom.
