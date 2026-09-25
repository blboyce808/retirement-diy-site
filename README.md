# Retirement.diy

A Monte Carlo retirement calculator that runs entirely in your browser.

**Live:** https://blboyce808.github.io/retirement-diy-site/

> Deep Analysis. Never Shared. Sleep Easier.

## Why the source is here

Every calculation happens on your device. Nothing you type is uploaded, there are no accounts,
no analytics, no tracking, no ads and no affiliate links. You do not have to take that on trust:
this is the whole application, one self-contained HTML file. Read it, or open your browser's
network tab and watch it ask for nothing.

The only outside requests the page makes are for the charting library and two web fonts, both
from public CDNs. Bundling those so the page makes no outside requests at all is planned.

## What it does

- 2,000 simulated futures a run, seeded so results are reproducible
- Real 2026 federal tax brackets, standard deduction, senior deduction, Social Security
  provisional-income rules and long-term capital gains, indexed to each future's inflation
- Backtests against real US market history from 1871, and stress tests that start your
  retirement in 1929, 1937, 1966, 1973, 2000 or 2008
- Answers "how much can I safely spend?", not just "will I run out?"
- Every input, result and chart has a plain-English explanation behind a question mark
- Full CSV export of every number behind every chart

## Status

Soft launch, under active development. Figures are estimates for planning and education, not
financial advice. See [LICENSE](LICENSE) — source-available, all rights reserved.
