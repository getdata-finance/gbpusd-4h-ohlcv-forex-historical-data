# GBPUSD 4h OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-38_437_rows-blue)](https://getdata.finance/datasets/gbpusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/gbpusd)

### -> [**Download the full GBPUSD dataset on getdata.finance**](https://getdata.finance/datasets/gbpusd)

**GBPUSD 4h OHLCV forex historical data** — ultra high-quality 4h OHLCV for **British Pound / US Dollar**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 4h OHLCV** for **British Pound / US Dollar** (Forex)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`4h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/gbpusd) · **38,437** `4h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `4h` sample updated in sync

> **Sample on GitHub** · `GBPUSD_4h.csv` (231 rows, `2026-07-09` -> `2026-09-02`, 14.94 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/gbpusd)** — **38,437** `4h` rows (full `1m`: 9,194,075), **11 timeframes**, `2001-11-28` -> `2026-09-02`.

## Download sample

**[GBPUSD_4h.csv](https://github.com/getdata-finance/gbpusd-4h-ohlcv-forex-historical-data/blob/main/GBPUSD_4h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/gbpusd-4h-ohlcv-forex-historical-data/main/GBPUSD_4h.csv)) · [GitHub Releases](https://github.com/getdata-finance/gbpusd-4h-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/gbpusd-4h-ohlcv-forex-historical-data/](https://getdata-finance.github.io/gbpusd-4h-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/gbpusd](https://getdata.finance/datasets/gbpusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/gbpusd))** |
|---|--:|---|
| Instrument | British Pound / US Dollar · Forex | British Pound / US Dollar · Forex |
| Timeframes | `4h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 4h rows | 231 | **38,437** |
| Size | 14.94 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/gbpusd) |
| Period | `2026-07-09` -> `2026-09-02` | `2001-11-28` -> `2026-09-02` |
| File | `GBPUSD_4h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/gbpusd) |
| Coverage report | — | [GBPUSD coverage](https://getdata.finance/coverage/gbpusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`4h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/gbpusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `4h` sample · [getdata.finance](https://getdata.finance/datasets/gbpusd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `4h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`GBPUSD_4h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-09T16:00:00+00:00 | 1.34097 | 1.34192 | 1.34047 | 1.34078 | 23846 |
| 2026-07-09T20:00:00+00:00 | 1.34078 | 1.34249 | 1.33917 | 1.34224 | 18269 |
| 2026-07-10T00:00:00+00:00 | 1.34224 | 1.34517 | 1.34195 | 1.34302 | 38945 |
| 2026-07-10T04:00:00+00:00 | 1.34302 | 1.34361 | 1.34085 | 1.34098 | 47489 |
| 2026-07-10T08:00:00+00:00 | 1.34098 | 1.34373 | 1.34091 | 1.3421 | 50474 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-01T08:00:00+00:00 | 1.35412 | 1.35484 | 1.3529 | 1.35298 | 48800 |
| 2026-09-01T12:00:00+00:00 | 1.35298 | 1.3552 | 1.35141 | 1.35145 | 61799 |
| 2026-09-01T16:00:00+00:00 | 1.35145 | 1.35211 | 1.35061 | 1.35151 | 25874 |
| 2026-09-01T20:00:00+00:00 | 1.35151 | 1.35189 | 1.3506 | 1.35067 | 22726 |
| 2026-09-02T00:00:00+00:00 | 1.35067 | 1.35086 | 1.35024 | 1.35026 | 12102 |

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

df = pd.read_csv('GBPUSD_4h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('GBPUSD_4h.csv', parse_dates=['datetime'])
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

df = pd.read_csv('GBPUSD_4h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='4h')
print(pf.stats())
```

## Download full data

The complete **GBPUSD** archive on **[getdata.finance](https://getdata.finance/datasets/gbpusd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **38,437** rows at `4h`, plus all other timeframes in the same ZIP.

**[-> Get the full GBPUSD dataset on getdata.finance](https://getdata.finance/datasets/gbpusd)**

---
*GetData · GBPUSD 4h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/gbpusd)*
