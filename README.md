# retirementDIY.org

A Monte Carlo retirement calculator that runs entirely in your browser.

**Live:** https://retirementDIY.org

> No login. No fees. Just math.

## Why the source is here

Every calculation happens on your device. Nothing you type is uploaded, and there are no accounts,
no cookies, no tracking, no ads and no affiliate links. You do not have to take that on trust:
this is the whole application, one self-contained HTML file. Read it, or open your browser's
network tab and watch what it asks for.

The page makes one outside request, and only one: an anonymous visit count to GoatCounter, an
open-source counter. It receives the page's address and title and the site that linked you there,
never anything you type, and a browser sending Global Privacy Control or Do Not Track is not counted
at all. Everything else, the charting library and the heading font included, is embedded in the
file, so nothing is fetched from a CDN or a font service. Disconnect from the internet and reload
it: everything still works.

## What it does

- 2,000 simulated futures a run, seeded so results are reproducible
- Real 2026 federal tax brackets, standard deduction, senior deduction, Social Security
  provisional-income rules and long-term capital gains, indexed to each future's inflation
- Backtests against real US market history from 1871, and stress tests that start your
  retirement in 1929, 1937, 1966, 1973, 2000 or 2008
- Answers "how much could I spend, and how often does it last?", not just "will I run out?"
- Every input, result and chart has a plain-English explanation behind a question mark
- Checked against the Trinity study, FI Calc and Portfolio Visualizer; the arithmetic is written
  out in full on a companion page
- A spreadsheet export of your settings and the year-by-year results

## Status

Soft launch, under active development. Figures are estimates for planning and education, not
financial advice. See [LICENSE](LICENSE) — source-available, all rights reserved.
