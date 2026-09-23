# USDCHF 15m OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-615_773_rows-blue)](https://getdata.finance/datasets/usdchf) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/usdchf)

### -> [**Download the full USDCHF dataset on getdata.finance**](https://getdata.finance/datasets/usdchf)

**USDCHF 15m OHLCV forex historical data** — ultra high-quality 15m OHLCV for **US Dollar / Swiss Franc**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 15m OHLCV** for **US Dollar / Swiss Franc** (Forex)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`15m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/usdchf) · **615,773** `15m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `15m` sample updated in sync

> **Sample on GitHub** · `USDCHF_15m.csv` (12,653 rows, `2026-03-23` -> `2026-09-23`, 1.20 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/usdchf)** — **615,773** `15m` rows (full `1m`: 9,147,305), **11 timeframes**, `2001-11-28` -> `2026-09-23`.

## Download sample

**[USDCHF_15m.csv](https://github.com/getdata-finance/usdchf-15m-ohlcv-forex-historical-data/blob/main/USDCHF_15m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/usdchf-15m-ohlcv-forex-historical-data/main/USDCHF_15m.csv)) · [GitHub Releases](https://github.com/getdata-finance/usdchf-15m-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/usdchf-15m-ohlcv-forex-historical-data/](https://getdata-finance.github.io/usdchf-15m-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/usdchf](https://getdata.finance/datasets/usdchf)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/usdchf))** |
|---|--:|---|
| Instrument | US Dollar / Swiss Franc · Forex | US Dollar / Swiss Franc · Forex |
| Timeframes | `15m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 15m rows | 12,653 | **615,773** |
| Size | 1.20 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/usdchf) |
| Period | `2026-03-23` -> `2026-09-23` | `2001-11-28` -> `2026-09-23` |
| File | `USDCHF_15m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/usdchf) |
| Coverage report | — | [USDCHF coverage](https://getdata.finance/coverage/usdchf) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`15m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/usdchf)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `15m` sample · [getdata.finance](https://getdata.finance/datasets/usdchf) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `15m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`USDCHF_15m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-23T02:30:00+00:00 | 0.78701 | 0.78764 | 0.78701 | 0.78729 | 1530 |
| 2026-03-23T02:45:00+00:00 | 0.78729 | 0.78776 | 0.78728 | 0.78743 | 1421 |
| 2026-03-23T03:00:00+00:00 | 0.78743 | 0.78787 | 0.78729 | 0.78769 | 1440 |
| 2026-03-23T03:15:00+00:00 | 0.78769 | 0.78773 | 0.7874 | 0.78745 | 1127 |
| 2026-03-23T03:30:00+00:00 | 0.78745 | 0.78752 | 0.78715 | 0.78722 | 1381 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-23T01:00:00+00:00 | 0.82077 | 0.82098 | 0.82069 | 0.82092 | 1327 |
| 2026-09-23T01:15:00+00:00 | 0.82092 | 0.82153 | 0.82091 | 0.82145 | 1110 |
| 2026-09-23T01:30:00+00:00 | 0.82145 | 0.82147 | 0.82102 | 0.82122 | 1073 |
| 2026-09-23T01:45:00+00:00 | 0.82122 | 0.82131 | 0.82114 | 0.82119 | 1021 |
| 2026-09-23T02:00:00+00:00 | 0.82119 | 0.82129 | 0.82119 | 0.82122 | 214 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('USDCHF_15m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('USDCHF_15m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('USDCHF_15m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='15min')
print(pf.stats())
```

## Download full data

The complete **USDCHF** archive on **[getdata.finance](https://getdata.finance/datasets/usdchf)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **615,773** rows at `15m`, plus all other timeframes in the same ZIP.

**[-> Get the full USDCHF dataset on getdata.finance](https://getdata.finance/datasets/usdchf)**

---
*GetData · USDCHF 15m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/usdchf)*
