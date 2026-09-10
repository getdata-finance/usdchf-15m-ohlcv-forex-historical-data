# USDCHF 15m OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-614_822_rows-blue)](https://getdata.finance/datasets/usdchf) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/usdchf)

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
- **Free evaluation sample** on GitHub (`15m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/usdchf) · **614,822** `15m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `15m` sample updated in sync

> **Sample on GitHub** · `USDCHF_15m.csv` (12,501 rows, `2026-03-10` -> `2026-09-09`, 1.22 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/usdchf)** — **614,822** `15m` rows (full `1m`: 9,147,305), **11 timeframes**, `2001-11-28` -> `2026-09-09`.

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
| 15m rows | 12,501 | **614,822** |
| Size | 1.22 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/usdchf) |
| Period | `2026-03-10` -> `2026-09-09` | `2001-11-28` -> `2026-09-09` |
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
| 2026-03-10T18:45:00+00:00 | 0.77979 | 0.77986 | 0.77917 | 0.77973 | 3226 |
| 2026-03-10T19:00:00+00:00 | 0.77973 | 0.7801 | 0.77965 | 0.77979 | 1859 |
| 2026-03-10T19:15:00+00:00 | 0.77979 | 0.78033 | 0.77956 | 0.7803 | 2027 |
| 2026-03-10T19:30:00+00:00 | 0.7803 | 0.78079 | 0.77982 | 0.7802 | 3379 |
| 2026-03-10T19:45:00+00:00 | 0.7802 | 0.78057 | 0.78011 | 0.78023 | 2022 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-09T01:00:00+00:00 | 0.80884 | 0.80922 | 0.80883 | 0.80899 | 1751 |
| 2026-09-09T01:15:00+00:00 | 0.80899 | 0.80937 | 0.80883 | 0.80928 | 1257 |
| 2026-09-09T01:30:00+00:00 | 0.80928 | 0.8094 | 0.80916 | 0.80929 | 1031 |
| 2026-09-09T01:45:00+00:00 | 0.80929 | 0.80929 | 0.80897 | 0.809 | 1189 |
| 2026-09-09T02:00:00+00:00 | 0.809 | 0.80907 | 0.809 | 0.80907 | 78 |

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

The complete **USDCHF** archive on **[getdata.finance](https://getdata.finance/datasets/usdchf)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **614,822** rows at `15m`, plus all other timeframes in the same ZIP.

**[-> Get the full USDCHF dataset on getdata.finance](https://getdata.finance/datasets/usdchf)**

---
*GetData · USDCHF 15m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/usdchf)*
