# US30 4h OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-27_944_rows-blue)](https://getdata.finance/datasets/us30) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/us30)

### -> [**Download the full US30 dataset on getdata.finance**](https://getdata.finance/datasets/us30)

**US30 4h OHLCV index historical data** — ultra high-quality 4h OHLCV for **Dow Jones 30**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 4h OHLCV** for **Dow Jones 30** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`4h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/us30) · **27,944** `4h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `4h` sample updated in sync

> **Sample on GitHub** · `US30_4h.csv` (804 rows, `2026-03-10` -> `2026-09-09`, 62.92 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/us30)** — **27,944** `4h` rows (full `1m`: 5,980,529), **11 timeframes**, `2009-03-11` -> `2026-09-09`.

## Download sample

**[US30_4h.csv](https://github.com/getdata-finance/us30-4h-ohlcv-index-historical-data/blob/main/US30_4h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/us30-4h-ohlcv-index-historical-data/main/US30_4h.csv)) · [GitHub Releases](https://github.com/getdata-finance/us30-4h-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/us30-4h-ohlcv-index-historical-data/](https://getdata-finance.github.io/us30-4h-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/us30](https://getdata.finance/datasets/us30)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/us30))** |
|---|--:|---|
| Instrument | Dow Jones 30 · Index | Dow Jones 30 · Index |
| Timeframes | `4h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 4h rows | 804 | **27,944** |
| Size | 62.92 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/us30) |
| Period | `2026-03-10` -> `2026-09-09` | `2009-03-11` -> `2026-09-09` |
| File | `US30_4h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/us30) |
| Coverage report | — | [US30 coverage](https://getdata.finance/coverage/us30) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`4h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/us30)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `4h` sample · [getdata.finance](https://getdata.finance/datasets/us30) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `4h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`US30_4h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-10T20:00:00+00:00 | 47700.08 | 47763.34 | 47649.64 | 47742.64 | 18376 |
| 2026-03-11T00:00:00+00:00 | 47742.64 | 47929.14 | 47739.64 | 47918.64 | 34405 |
| 2026-03-11T04:00:00+00:00 | 47918.64 | 47920.64 | 47678.15 | 47727.65 | 36287 |
| 2026-03-11T08:00:00+00:00 | 47727.65 | 47833.15 | 47507.15 | 47615.65 | 88655 |
| 2026-03-11T12:00:00+00:00 | 47615.65 | 47717.65 | 47203.39 | 47212.89 | 313883 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-08T08:00:00+00:00 | 52905.99 | 53095.99 | 52886.49 | 53014.99 | 47612 |
| 2026-09-08T12:00:00+00:00 | 53014.99 | 53079.99 | 52714.84 | 52822.84 | 134811 |
| 2026-09-08T16:00:00+00:00 | 52822.84 | 52906.84 | 52731.34 | 52794.84 | 81596 |
| 2026-09-08T20:00:00+00:00 | 52794.84 | 52799.99 | 52739.99 | 52748.86 | 10148 |
| 2026-09-09T00:00:00+00:00 | 52748.86 | 52791.86 | 52737.86 | 52746.86 | 9244 |

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

df = pd.read_csv('US30_4h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('US30_4h.csv', parse_dates=['datetime'])
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

df = pd.read_csv('US30_4h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='4h')
print(pf.stats())
```

## Download full data

The complete **US30** archive on **[getdata.finance](https://getdata.finance/datasets/us30)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **27,944** rows at `4h`, plus all other timeframes in the same ZIP.

**[-> Get the full US30 dataset on getdata.finance](https://getdata.finance/datasets/us30)**

---
*GetData · US30 4h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/us30)*
