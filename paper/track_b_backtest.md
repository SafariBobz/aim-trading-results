# Track B back-test (ruleset v1, paper only)

Run 2026-10-10. 57 signals, 40 trades taken (21 closed, 19 open). Latest price date: 2026-10-09. Unadjusted EODHD closes. GBP 1,250 per trade; costs GBP 12.25 (AIM) / 18.50 (FTSE 250) per round trip, included in net GBP; "return" columns are gross of costs.

Open trades are marked to the last close, so their returns are unrealised; the "closed only" row excludes them. Positions are fractional shares.

## Skipped / not traded

| Signal date | Ticker | Status | Reason |
|---|---|---|---|
| 2026-08-06 | AEO | skipped | market cap GBP 6.09m < 50m |
| 2026-08-18 | KNOS | skipped | rise >20% vs D-1 close on D or D+1 |
| 2026-08-20 | TAP | skipped | market cap GBP 10.14m < 50m |
| 2026-08-26 | EMR | skipped | market cap GBP 12m < 50m |
| 2026-09-02 | RGG | skipped | rise >20% vs D-1 close on D or D+1 |
| 2026-09-08 | IHC | skipped | market cap GBP 17m < 50m |
| 2026-09-09 | CNS | skipped | market cap GBP 43.5m < 50m |
| 2026-09-11 | LPA | skipped | market cap GBP 10.5m < 50m |
| 2026-09-14 | KMK | skipped | market cap GBP 41.28m < 50m |
| 2026-09-15 | AEO | skipped | market cap GBP 6.09m < 50m |
| 2026-09-16 | WINK | skipped | market cap GBP 22.91m < 50m |
| 2026-09-17 | REVB | skipped | market cap GBP 46.27m < 50m |
| 2026-09-24 | TBLD | skipped | market cap GBP 42.28m < 50m |
| 2026-09-30 | SAGA | skipped | rise >20% vs D-1 close on D or D+1 |
| 2026-09-30 | MRK | skipped | market cap GBP 48m < 50m |
| 2026-09-30 | NAH | skipped | market cap GBP 18m < 50m |
| 2026-10-06 | SNX | skipped | market cap GBP 31m < 50m |

## Summaries

### All trades vs closed only

| Group | Trades | Winners (net) | Win rate | Mean gross return | Median gross return | Best | Worst | Net GBP |
|---|---|---|---|---|---|---|---|---|
| All trades (open marked to last close) | 40 | 11 | 28% | -1.67% | -1.66% | +29.7% | -13.1% | -1,454.91 |
| Closed only | 21 | 3 | 14% | -4.72% | -8.32% | +17.6% | -13.1% | -1,583.64 |

### By market (all trades / closed only)

| Group | Trades | Winners (net) | Win rate | Mean gross return | Median gross return | Best | Worst | Net GBP |
|---|---|---|---|---|---|---|---|---|
| AIM - all | 19 | 5 | 26% | -0.37% | -2.40% | +29.7% | -11.1% | -321.06 |
| FTSE 250 - all | 21 | 6 | 29% | -2.84% | -0.83% | +6.0% | -13.1% | -1,133.85 |
| AIM - closed | 7 | 2 | 29% | -2.55% | -8.11% | +17.6% | -11.1% | -308.80 |
| FTSE 250 - closed | 14 | 1 | 7% | -5.80% | -8.36% | +5.2% | -13.1% | -1,274.84 |

### By strength (all trades / closed only)

| Group | Trades | Winners (net) | Win rate | Mean gross return | Median gross return | Best | Worst | Net GBP |
|---|---|---|---|---|---|---|---|---|
| materially - all | 8 | 3 | 38% | +3.29% | -0.50% | +29.7% | -5.2% | +212.54 |
| ahead - all | 18 | 4 | 22% | -3.04% | -4.09% | +17.6% | -13.1% | -954.30 |
| raised guidance - all | 14 | 4 | 29% | -2.74% | -1.61% | +6.0% | -12.0% | -713.14 |
| materially - closed | 1 | 0 | 0% | -0.10% | -0.10% | -0.1% | -0.1% | -19.73 |
| ahead - closed | 10 | 1 | 10% | -5.21% | -8.45% | +17.6% | -13.1% | -811.68 |
| raised guidance - closed | 10 | 2 | 20% | -4.69% | -7.61% | +5.2% | -12.0% | -752.23 |

### 5-slot portfolio (max 5 open, one per sector)

| Group | Trades | Winners (net) | Win rate | Mean gross return | Median gross return | Best | Worst | Net GBP |
|---|---|---|---|---|---|---|---|---|
| Portfolio - all | 14 | 3 | 21% | -1.45% | -5.54% | +29.7% | -12.0% | -481.35 |
| Portfolio - closed only | 9 | 1 | 11% | -4.60% | -8.40% | +17.6% | -12.0% | -671.05 |

14 of 40 trades taken; skipped: 18 no free slot, 8 sector already held. Net GBP -481.35 = -7.70% of the GBP 6,250 maximum capital deployed (not time-weighted).

### FTSE 250 over the same window

Benchmark used: **VMID.LSE** (Vanguard FTSE 250 ETF; MCX.INDX failed; its unadjusted close excludes distributions).
Close 2026-08-04 to close 2026-10-09: **-1.72%**. Window runs from the first entry (2026-08-04) to the last available close.
For reference, the FTSE 250 trades here: mean gross return -2.84% over holding periods of varying length (not directly comparable to the index window).

## Per-trade results

| Signal | Ticker | Market | Strength | Entry date | Entry | Exit date | Exit | Return | Net GBP | Exit reason | Portfolio |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 2026-08-03 | CKN | FTSE 250 | materially | 2026-08-04 | 5075.00 | 2026-09-02 | 5070.00 | -0.10% | -19.73 | time (20 days) | yes |
| 2026-08-05 | FOUR | FTSE 250 | ahead | 2026-08-06 | 5000.00 | 2026-08-17 | 4580.00 | -8.40% | -123.50 | stop (initial) | yes |
| 2026-08-06 | DLN | FTSE 250 | raised guidance | 2026-08-07 | 2100.00 | 2026-09-07 | 1955.00 | -6.90% | -104.81 | time (20 days) | yes |
| 2026-08-11 | PPHC | AIM | raised guidance | 2026-08-12 | 835.00 | 2026-09-10 | 815.00 | -2.40% | -42.19 | time (20 days) | no (sector already held) |
| 2026-08-12 | BBY | FTSE 250 | raised guidance | 2026-08-13 | 922.50 | 2026-09-10 | 840.00 | -8.94% | -130.29 | stop (initial) | yes |
| 2026-08-12 | HILS | FTSE 250 | ahead | 2026-08-13 | 2930.00 | 2026-09-11 | 2840.00 | -3.07% | -56.90 | time (20 days) | yes |
| 2026-08-17 | GATC | AIM | raised guidance | 2026-08-18 | 167.50 | 2026-08-24 | 152.50 | -8.96% | -124.19 | stop (initial) | no (sector already held) |
| 2026-08-18 | MTEC | AIM | ahead | 2026-08-19 | 42.50 | 2026-09-17 | 50.00 | +17.65% | +208.34 | time (20 days) | yes |
| 2026-08-25 | VLX | FTSE 250 | ahead | 2026-08-26 | 619.00 | 2026-09-24 | 624.00 | +0.81% | -8.40 | time (20 days) | no (no free slot) |
| 2026-08-26 | APN | FTSE 250 | ahead | 2026-08-27 | 317.50 | 2026-09-11 | 287.50 | -9.45% | -136.61 | stop (initial) | no (no free slot) |
| 2026-08-27 | VTU | AIM | ahead | 2026-08-28 | 90.80 | 2026-09-10 | 82.70 | -8.92% | -123.76 | stop (initial) | no (no free slot) |
| 2026-09-03 | HFG | FTSE 250 | raised guidance | 2026-09-04 | 698.00 | 2026-10-02 | 698.50 | +0.07% | -17.60 | time (20 days) | no (no free slot) |
| 2026-09-03 | ROSE | FTSE 250 | ahead | 2026-09-04 | 341.00 | 2026-09-25 | 312.00 | -8.50% | -124.80 | stop (initial) | yes |
| 2026-09-07 | CNC | AIM | ahead | 2026-09-08 | 277.50 | 2026-09-15 | 255.00 | -8.11% | -113.60 | stop (initial) | no (no free slot) |
| 2026-09-07 | WRKS | AIM | ahead | 2026-09-08 | 94.90 | 2026-09-23 | 84.40 | -11.06% | -150.55 | stop (initial) | yes |
| 2026-09-08 | FCH | FTSE 250 | raised guidance | 2026-09-09 | 197.20 | 2026-09-16 | 180.80 | -8.32% | -122.46 | stop (initial) | no (no free slot) |
| 2026-09-08 | SOM | AIM | raised guidance | 2026-09-09 | 253.00 | 2026-10-07 | 263.00 | +3.95% | +37.16 | time (20 days) | no (no free slot) |
| 2026-09-09 | EWG | FTSE 250 | raised guidance | 2026-09-10 | 94.10 | 2026-10-08 | 99.00 | +5.21% | +46.59 | time (20 days) | no (sector already held) |
| 2026-09-09 | VCT | FTSE 250 | raised guidance | 2026-09-10 | 998.00 | 2026-09-24 | 878.00 | -12.02% | -168.80 | stop (initial) | yes |
| 2026-09-14 | BIG | AIM | ahead | 2026-09-15 | 97.80 | 2026-10-09 | 92.80 | -5.11% | -76.16 | open (marked to last close) | no (sector already held) |
| 2026-09-14 | KEYS | AIM | materially | 2026-09-15 | 710.00 | 2026-10-09 | 690.00 | -2.82% | -47.46 | open (marked to last close) | no (sector already held) |
| 2026-09-15 | KIE | FTSE 250 | raised guidance | 2026-09-16 | 287.20 | 2026-10-09 | 296.80 | +3.34% | +23.28 | open (marked to last close) | yes |
| 2026-09-17 | BYIT | FTSE 250 | raised guidance | 2026-09-18 | 457.00 | 2026-10-09 | 453.20 | -0.83% | -28.89 | open (marked to last close) | yes |
| 2026-09-17 | GFRD | FTSE 250 | ahead | 2026-09-18 | 684.00 | 2026-10-09 | 684.00 | +0.00% | -18.50 | open (marked to last close) | no (sector already held) |
| 2026-09-23 | CDGP | AIM | materially | 2026-09-24 | 48.50 | 2026-10-09 | 46.00 | -5.15% | -76.68 | open (marked to last close) | yes |
| 2026-09-24 | RPI | FTSE 250 | ahead | 2026-09-25 | 711.50 | 2026-09-28 | 618.50 | -13.07% | -181.89 | stop (initial) | no (sector already held) |
| 2026-09-28 | CCT | AIM | ahead | 2026-09-29 | 321.00 | 2026-10-09 | 318.00 | -0.93% | -23.93 | open (marked to last close) | no (sector already held) |
| 2026-09-28 | LIKE | AIM | materially | 2026-09-29 | 34.40 | 2026-10-09 | 44.60 | +29.65% | +358.39 | open (marked to last close) | yes |
| 2026-09-28 | WVIA | AIM | ahead | 2026-09-29 | 295.00 | 2026-10-09 | 277.50 | -5.93% | -86.40 | open (marked to last close) | yes |
| 2026-09-29 | ZIG | FTSE 250 | raised guidance | 2026-09-30 | 472.50 | 2026-10-08 | 432.00 | -8.57% | -125.64 | stop (initial) | no (no free slot) |
| 2026-09-30 | AVG | AIM | ahead | 2026-10-01 | 740.00 | 2026-10-09 | 750.00 | +1.35% | +4.64 | open (marked to last close) | no (no free slot) |
| 2026-09-30 | EVPL | AIM | materially | 2026-10-01 | 439.50 | 2026-10-09 | 421.50 | -4.10% | -63.44 | open (marked to last close) | no (no free slot) |
| 2026-09-30 | GRG | FTSE 250 | raised guidance | 2026-10-01 | 1988.00 | 2026-10-09 | 2108.00 | +6.04% | +56.95 | open (marked to last close) | no (no free slot) |
| 2026-09-30 | YNGA | AIM | ahead | 2026-10-01 | 951.00 | 2026-10-09 | 996.00 | +4.73% | +46.90 | open (marked to last close) | no (no free slot) |
| 2026-10-01 | RGG | AIM | materially | 2026-10-02 | 110.00 | 2026-10-09 | 109.00 | -0.91% | -23.61 | open (marked to last close) | no (no free slot) |
| 2026-10-05 | QTX | AIM | ahead | 2026-10-06 | 237.50 | 2026-10-09 | 237.50 | +0.00% | -12.25 | open (marked to last close) | no (no free slot) |
| 2026-10-06 | CKN | FTSE 250 | materially | 2026-10-07 | 5160.00 | 2026-10-09 | 5405.00 | +4.75% | +40.85 | open (marked to last close) | no (no free slot) |
| 2026-10-07 | AVON | FTSE 250 | ahead | 2026-10-08 | 2255.00 | 2026-10-09 | 2330.00 | +3.33% | +23.07 | open (marked to last close) | no (no free slot) |
| 2026-10-07 | BPT | FTSE 250 | materially | 2026-10-08 | 382.60 | 2026-10-09 | 401.80 | +5.02% | +44.23 | open (marked to last close) | no (no free slot) |
| 2026-10-08 | ITM | AIM | raised guidance | 2026-10-09 | 93.85 | 2026-10-09 | 93.85 | +0.00% | -12.25 | open (marked to last close) | no (no free slot) |
