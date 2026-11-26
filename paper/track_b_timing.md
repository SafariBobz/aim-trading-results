# Track B timing back-test (paper only)

Run 2026-11-26. Latest price date 2026-11-25. 153 back-test signals (Apr-Oct 2026) + 17 live v1 signals. EODHD unadjusted daily prices. GBP 1,250 a trade, no slot limits, costs included in net GBP (returns are before costs). Open trades are marked to the last close.

## Results by version

### All signals

| Version | Trades | Closed | Win rate | Median return | Mean net GBP/trade | Total net GBP | Total without best trade | Intraday exits (gaps) |
|---|---|---|---|---|---|---|---|---|
| Buy next-day close, exit at close (v1) | 115 | 112 | 41% | +0.00% | -0.52 | -60 | -994 | 0 (0) |
| Buy next-day close, exit intraday | 115 | 112 | 38% | +0.00% | -5.68 | -653 | -1,411 | 48 (4) |
| Buy news-day close, exit at close (v1) | 121 | 115 | 45% | -0.26% | +11.66 | +1,411 | +525 | 0 (0) |
| Buy news-day close, exit intraday | 121 | 117 | 42% | -0.17% | +7.34 | +888 | +45 | 46 (4) |
| Buy news-day open, exit at close (v1) | 129 | 125 | 49% | +1.19% | +35.06 | +4,523 | +3,657 | 0 (0) |
| Buy news-day open, exit intraday | 129 | 126 | 44% | +0.00% | +23.47 | +3,027 | +2,162 | 59 (6) |

### Back-test only

| Version | Trades | Closed | Win rate | Median return | Mean net GBP/trade | Total net GBP | Total without best trade | Intraday exits (gaps) |
|---|---|---|---|---|---|---|---|---|
| Buy next-day close, exit at close (v1) | 103 | 103 | 43% | +0.00% | +4.27 | +440 | -494 | 0 (0) |
| Buy next-day close, exit intraday | 103 | 103 | 40% | +0.00% | -1.77 | -182 | -940 | 43 (3) |
| Buy news-day close, exit at close (v1) | 107 | 107 | 47% | -0.17% | +16.58 | +1,774 | +888 | 0 (0) |
| Buy news-day close, exit intraday | 107 | 107 | 45% | +0.00% | +13.75 | +1,472 | +628 | 40 (3) |
| Buy news-day open, exit at close (v1) | 115 | 115 | 52% | +1.56% | +42.33 | +4,868 | +4,003 | 0 (0) |
| Buy news-day open, exit intraday | 115 | 115 | 47% | +0.31% | +30.19 | +3,472 | +2,607 | 52 (5) |

### Live only

| Version | Trades | Closed | Win rate | Median return | Mean net GBP/trade | Total net GBP | Total without best trade | Intraday exits (gaps) |
|---|---|---|---|---|---|---|---|---|
| Buy next-day close, exit at close (v1) | 12 | 9 | 25% | -1.34% | -41.65 | -500 | -621 | 0 (0) |
| Buy next-day close, exit intraday | 12 | 9 | 25% | -1.34% | -39.27 | -471 | -592 | 5 (1) |
| Buy news-day close, exit at close (v1) | 14 | 8 | 29% | -1.06% | -25.93 | -363 | -500 | 0 (0) |
| Buy news-day close, exit intraday | 14 | 10 | 21% | -1.06% | -41.68 | -584 | -721 | 6 (1) |
| Buy news-day open, exit at close (v1) | 14 | 10 | 21% | -0.52% | -24.67 | -345 | -570 | 0 (0) |
| Buy news-day open, exit intraday | 14 | 11 | 21% | -0.12% | -31.80 | -445 | -577 | 7 (1) |

## Where the move happens (median and mean, %)

| Leg | Median | Mean | % up | n |
|---|---|---|---|---|
| Pre-news close to news-day open | +5.00 | +5.56 | 91% | 167 |
| News-day open to close | +1.89 | +2.14 | 57% | 167 |
| News-day close to next-day close | +0.00 | +0.50 | 47% | 167 |

## Check: does the next-day-close / exit-at-close version reproduce the October back-test?

84 closed trades in the October file; 84 found here; 84 with identical entry and exit prices. Net GBP on the matched trades: October +683.25, now +683.25.

## Per-trade, live signals

| Signal | Ticker | Version | Entry | Exit | Return | Net GBP | Exit reason |
|---|---|---|---|---|---|---|---|
| 2026-10-13 | GNC | d1_close/close | 2026-10-14 279.00 | 2026-11-11 297.80 | +6.74% | +65.73 | time (20 days) |
| 2026-10-13 | GNC | d1_close/intraday | 2026-10-14 279.00 | 2026-11-11 297.80 | +6.74% | +65.73 | time (20 days) |
| 2026-10-13 | GNC | d_close/close | 2026-10-13 268.40 | 2026-11-10 301.80 | +12.44% | +137.05 | time (20 days) |
| 2026-10-13 | GNC | d_close/intraday | 2026-10-13 268.40 | 2026-11-10 301.80 | +12.44% | +137.05 | time (20 days) |
| 2026-10-13 | GNC | d_open/close | 2026-10-13 277.00 | 2026-11-10 301.80 | +8.95% | +93.41 | time (20 days) |
| 2026-10-13 | GNC | d_open/intraday | 2026-10-13 277.00 | 2026-11-10 301.80 | +8.95% | +93.41 | time (20 days) |
| 2026-10-13 | VIC | d1_close/close | 2026-10-14 87.40 | 2026-11-11 87.00 | -0.46% | -17.97 | time (20 days) |
| 2026-10-13 | VIC | d1_close/intraday | 2026-10-14 87.40 | 2026-11-11 87.00 | -0.46% | -17.97 | time (20 days) |
| 2026-10-13 | VIC | d_close/close | 2026-10-13 85.70 | 2026-11-10 90.00 | +5.02% | +50.47 | time (20 days) |
| 2026-10-13 | VIC | d_close/intraday | 2026-10-13 85.70 | 2026-11-10 90.00 | +5.02% | +50.47 | time (20 days) |
| 2026-10-13 | VIC | d_open/close | 2026-10-13 82.00 | 2026-10-30 82.00 | +0.00% | -12.25 | exit at close (breakeven) |
| 2026-10-13 | VIC | d_open/intraday | 2026-10-13 82.00 | 2026-10-30 82.00 | +0.00% | -12.25 | exit touched intraday (breakeven) |
| 2026-10-14 | BOOM | d1_close/close | 2026-10-15 492.50 | 2026-11-12 462.50 | -6.09% | -88.39 | time (20 days) |
| 2026-10-14 | BOOM | d1_close/intraday | 2026-10-15 492.50 | 2026-11-09 453.10 | -8.00% | -112.25 | exit touched intraday (initial) |
| 2026-10-14 | BOOM | d_close/close | 2026-10-14 500.00 | 2026-11-05 460.00 | -8.00% | -112.25 | exit at close (initial) |
| 2026-10-14 | BOOM | d_close/intraday | 2026-10-14 500.00 | 2026-10-26 460.00 | -8.00% | -112.25 | exit touched intraday (initial) |
| 2026-10-14 | BOOM | d_open/close | 2026-10-14 517.50 | 2026-10-20 475.00 | -8.21% | -114.91 | exit at close (initial) |
| 2026-10-14 | BOOM | d_open/intraday | 2026-10-14 517.50 | 2026-10-20 476.10 | -8.00% | -112.25 | exit touched intraday (initial) |
| 2026-10-14 | VTU | d1_close/close | 2026-10-15 85.50 | 2026-11-12 86.10 | +0.70% | -3.48 | time (20 days) |
| 2026-10-14 | VTU | d1_close/intraday | 2026-10-15 85.50 | 2026-11-12 86.10 | +0.70% | -3.48 | time (20 days) |
| 2026-10-14 | VTU | d_close/close | 2026-10-14 84.80 | 2026-11-11 85.00 | +0.24% | -9.30 | time (20 days) |
| 2026-10-14 | VTU | d_close/intraday | 2026-10-14 84.80 | 2026-11-11 85.00 | +0.24% | -9.30 | time (20 days) |
| 2026-10-14 | VTU | d_open/close | 2026-10-14 85.70 | 2026-11-11 85.00 | -0.82% | -22.46 | time (20 days) |
| 2026-10-14 | VTU | d_open/intraday | 2026-10-14 85.70 | 2026-11-11 85.00 | -0.82% | -22.46 | time (20 days) |
| 2026-10-15 | TPX | d1_close/close | 2026-10-16 94.00 | 2026-11-13 104.00 | +10.64% | +120.73 | time (20 days) |
| 2026-10-15 | TPX | d1_close/intraday | 2026-10-16 94.00 | 2026-11-13 104.00 | +10.64% | +120.73 | time (20 days) |
| 2026-10-15 | TPX | d_close/close | 2026-10-15 95.00 | 2026-11-12 103.50 | +8.95% | +99.59 | time (20 days) |
| 2026-10-15 | TPX | d_close/intraday | 2026-10-15 95.00 | 2026-11-10 95.00 | +0.00% | -12.25 | exit touched intraday (breakeven) |
| 2026-10-15 | TPX | d_open/close | 2026-10-15 87.00 | 2026-11-12 103.50 | +18.97% | +224.82 | time (20 days) |
| 2026-10-15 | TPX | d_open/intraday | 2026-10-15 87.00 | 2026-11-06 97.06 | +11.56% | +132.29 | exit touched intraday (trailing) |
| 2026-10-20 | XPP | d1_close/close | 2026-10-21 1770.00 | 2026-11-05 1600.00 | -9.60% | -138.56 | exit at close (initial) |
| 2026-10-20 | XPP | d1_close/intraday | 2026-10-21 1770.00 | 2026-10-23 1616.00 | -8.70% | -127.26 | gap below exit (initial) |
| 2026-10-20 | XPP | d_close/close | 2026-10-20 1754.00 | 2026-11-05 1600.00 | -8.78% | -128.25 | exit at close (initial) |
| 2026-10-20 | XPP | d_close/intraday | 2026-10-20 1754.00 | 2026-11-05 1560.00 | -11.06% | -156.76 | gap below exit (initial) |
| 2026-10-20 | XPP | d_open/close | 2026-10-20 1704.00 | 2026-11-06 1564.00 | -8.22% | -121.20 | exit at close (initial) |
| 2026-10-20 | XPP | d_open/intraday | 2026-10-20 1704.00 | 2026-11-05 1560.00 | -8.45% | -124.13 | gap below exit (initial) |
| 2026-10-22 | ATG | d1_close/close | 2026-10-23 479.20 | 2026-11-20 430.00 | -10.27% | -146.84 | exit at close (initial) |
| 2026-10-22 | ATG | d1_close/intraday | 2026-10-23 479.20 | 2026-11-20 440.86 | -8.00% | -118.50 | exit touched intraday (initial) |
| 2026-10-22 | ATG | d_close/close | 2026-10-22 483.00 | 2026-11-19 446.20 | -7.62% | -113.74 | time (20 days) |
| 2026-10-22 | ATG | d_close/intraday | 2026-10-22 483.00 | 2026-11-19 444.36 | -8.00% | -118.50 | exit touched intraday (initial) |
| 2026-10-22 | ATG | d_open/close | 2026-10-22 478.60 | 2026-11-19 446.20 | -6.77% | -103.12 | time (20 days) |
| 2026-10-22 | ATG | d_open/intraday | 2026-10-22 478.60 | 2026-11-19 446.20 | -6.77% | -103.12 | time (20 days) |
| 2026-10-28 | ELM | d1_close/close | 2026-10-29 189.60 | 2026-11-25 185.40 | -2.22% | -46.19 | open (marked to last close) |
| 2026-10-28 | ELM | d1_close/intraday | 2026-10-29 189.60 | 2026-11-25 185.40 | -2.22% | -46.19 | open (marked to last close) |
| 2026-10-28 | ELM | d_close/close | 2026-10-28 188.20 | 2026-11-25 185.40 | -1.49% | -37.10 | time (20 days) |
| 2026-10-28 | ELM | d_close/intraday | 2026-10-28 188.20 | 2026-11-25 185.40 | -1.49% | -37.10 | time (20 days) |
| 2026-10-28 | ELM | d_open/close | 2026-10-28 185.00 | 2026-11-25 185.40 | +0.22% | -15.80 | time (20 days) |
| 2026-10-28 | ELM | d_open/intraday | 2026-10-28 185.00 | 2026-11-25 185.40 | +0.22% | -15.80 | time (20 days) |
| 2026-11-03 | IWG | d1_close/close | 2026-11-04 217.40 | 2026-11-20 199.10 | -8.42% | -123.72 | exit at close (initial) |
| 2026-11-03 | IWG | d1_close/intraday | 2026-11-04 217.40 | 2026-11-20 200.01 | -8.00% | -118.50 | exit touched intraday (initial) |
| 2026-11-03 | IWG | d_close/close | 2026-11-03 214.20 | 2026-11-25 207.40 | -3.17% | -58.18 | open (marked to last close) |
| 2026-11-03 | IWG | d_close/intraday | 2026-11-03 214.20 | 2026-11-23 197.06 | -8.00% | -118.50 | exit touched intraday (initial) |
| 2026-11-03 | IWG | d_open/close | 2026-11-03 201.00 | 2026-11-20 199.10 | -0.95% | -30.32 | exit at close (breakeven) |
| 2026-11-03 | IWG | d_open/intraday | 2026-11-03 201.00 | 2026-11-20 201.00 | +0.00% | -18.50 | exit touched intraday (breakeven) |
| 2026-11-05 | HTWS | d1_close/close | 2026-11-06 220.60 | 2026-11-25 225.80 | +2.36% | +10.97 | open (marked to last close) |
| 2026-11-05 | HTWS | d1_close/intraday | 2026-11-06 220.60 | 2026-11-25 225.80 | +2.36% | +10.97 | open (marked to last close) |
| 2026-11-05 | HTWS | d_close/close | 2026-11-05 219.80 | 2026-11-25 225.80 | +2.73% | +15.62 | open (marked to last close) |
| 2026-11-05 | HTWS | d_close/intraday | 2026-11-05 219.80 | 2026-11-25 225.80 | +2.73% | +15.62 | open (marked to last close) |
| 2026-11-05 | HTWS | d_open/close | 2026-11-05 222.40 | 2026-11-25 225.80 | +1.53% | +0.61 | open (marked to last close) |
| 2026-11-05 | HTWS | d_open/intraday | 2026-11-05 222.40 | 2026-11-25 225.80 | +1.53% | +0.61 | open (marked to last close) |
| 2026-11-10 | FCH | d_close/close | 2026-11-10 234.00 | 2026-11-25 226.50 | -3.21% | -58.56 | open (marked to last close) |
| 2026-11-10 | FCH | d_close/intraday | 2026-11-10 234.00 | 2026-11-25 226.50 | -3.21% | -58.56 | open (marked to last close) |
| 2026-11-10 | FCH | d_open/close | 2026-11-10 224.00 | 2026-11-25 226.50 | +1.12% | -4.55 | open (marked to last close) |
| 2026-11-10 | FCH | d_open/intraday | 2026-11-10 224.00 | 2026-11-25 226.50 | +1.12% | -4.55 | open (marked to last close) |
| 2026-11-10 | PTEC | d1_close/close | 2026-11-11 369.40 | 2026-11-20 337.60 | -8.61% | -126.11 | exit at close (initial) |
| 2026-11-10 | PTEC | d1_close/intraday | 2026-11-11 369.40 | 2026-11-17 339.85 | -8.00% | -118.50 | exit touched intraday (initial) |
| 2026-11-10 | PTEC | d_close/close | 2026-11-10 364.80 | 2026-11-25 340.00 | -6.80% | -103.48 | open (marked to last close) |
| 2026-11-10 | PTEC | d_close/intraday | 2026-11-10 364.80 | 2026-11-17 335.62 | -8.00% | -118.50 | exit touched intraday (initial) |
| 2026-11-10 | PTEC | d_open/close | 2026-11-10 377.20 | 2026-11-19 345.80 | -8.32% | -122.56 | exit at close (initial) |
| 2026-11-10 | PTEC | d_open/intraday | 2026-11-10 377.20 | 2026-11-17 347.02 | -8.00% | -118.50 | exit touched intraday (initial) |
| 2026-11-23 | DRX | d1_close/close | 2026-11-24 850.00 | 2026-11-25 858.50 | +1.00% | -6.00 | open (marked to last close) |
| 2026-11-23 | DRX | d1_close/intraday | 2026-11-24 850.00 | 2026-11-25 858.50 | +1.00% | -6.00 | open (marked to last close) |
| 2026-11-23 | DRX | d_close/close | 2026-11-23 864.00 | 2026-11-25 858.50 | -0.64% | -26.46 | open (marked to last close) |
| 2026-11-23 | DRX | d_close/intraday | 2026-11-23 864.00 | 2026-11-25 858.50 | -0.64% | -26.46 | open (marked to last close) |
| 2026-11-23 | DRX | d_open/close | 2026-11-23 860.50 | 2026-11-25 858.50 | -0.23% | -21.41 | open (marked to last close) |
| 2026-11-23 | DRX | d_open/intraday | 2026-11-23 860.50 | 2026-11-25 858.50 | -0.23% | -21.41 | open (marked to last close) |
| 2026-11-25 | ROSE | d_close/close | 2026-11-25 304.00 | 2026-11-25 304.00 | +0.00% | -18.50 | open (marked to last close) |
| 2026-11-25 | ROSE | d_close/intraday | 2026-11-25 304.00 | 2026-11-25 304.00 | +0.00% | -18.50 | open (marked to last close) |
| 2026-11-25 | ROSE | d_open/close | 2026-11-25 324.00 | 2026-11-25 304.00 | -6.17% | -95.66 | open (marked to last close) |
| 2026-11-25 | ROSE | d_open/intraday | 2026-11-25 324.00 | 2026-11-25 298.08 | -8.00% | -118.50 | exit touched intraday (initial) |

Not traded (news-day-open version): 41 signals - CLBS 2026-04-09 (market value under GBP 50m), CLX 2026-04-13 (market value under GBP 50m), SYS 2026-04-13 (market value under GBP 50m), CRPR 2026-04-14 (market value under GBP 50m), FPO 2026-04-14 (market value under GBP 50m), TPX 2026-04-22 (market value under GBP 50m), CTG 2026-04-27 (market value under GBP 50m), OHGR 2026-04-27 (market value under GBP 50m), HDD 2026-04-28 (market value under GBP 50m), NCYT 2026-04-30 (market value under GBP 50m), CCT 2026-05-12 (market value under GBP 50m), FDEV 2026-05-12 (more than 20% above the pre-news close), XPF 2026-05-12 (market value under GBP 50m), GATC 2026-05-14 (market value under GBP 50m), HDD 2026-05-27 (market value under GBP 50m), GDP 2026-07-01 (market value under GBP 50m), VNET 2026-07-07 (market value under GBP 50m), SYS 2026-07-08 (market value under GBP 50m), SHOE 2026-07-16 (market value under GBP 50m), CSSG 2026-07-20 (market value under GBP 50m), WINE 2026-07-23 (market value under GBP 50m), SWG 2026-07-27 (market value under GBP 50m), EMR 2026-07-28 (market value under GBP 50m), PCIP 2026-07-28 (market value under GBP 50m), AEO 2026-08-06 (market value under GBP 50m), TAP 2026-08-20 (market value under GBP 50m), EMR 2026-08-26 (market value under GBP 50m), IHC 2026-09-08 (market value under GBP 50m), CNS 2026-09-09 (market value under GBP 50m), LPA 2026-09-11 (market value under GBP 50m), KMK 2026-09-14 (market value under GBP 50m), AEO 2026-09-15 (market value under GBP 50m), WINK 2026-09-16 (market value under GBP 50m), REVB 2026-09-17 (market value under GBP 50m), TBLD 2026-09-24 (market value under GBP 50m), MRK 2026-09-30 (market value under GBP 50m), NAH 2026-09-30 (market value under GBP 50m), SNX 2026-10-06 (market value under GBP 50m), HAS 2026-11-18 (more than 20% above the pre-news close), HFD 2026-11-26 (no price for D or D-1), HILS 2026-11-26 (no price for D or D-1)
