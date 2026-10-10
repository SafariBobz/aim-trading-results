# Track B back-test (ruleset v1, paper only)

Run 2026-10-10. 153 signals, 103 trades taken (84 closed, 19 open). Latest price date: 2026-10-09. Unadjusted EODHD closes. GBP 1,250 per trade; costs GBP 12.25 (AIM) / 18.50 (FTSE 250) per round trip, included in net GBP; "return" columns are gross of costs.

Open trades are marked to the last close, so their returns are unrealised; the "closed only" row excludes them. Positions are fractional shares.

## Skipped / not traded

| Signal date | Ticker | Status | Reason |
|---|---|---|---|
| 2026-04-09 | CLBS | skipped | market cap GBP 36.7m < 50m |
| 2026-04-13 | CLX | skipped | market cap GBP 43m < 50m |
| 2026-04-13 | SYS | skipped | market cap GBP 11m < 50m |
| 2026-04-14 | CRPR | skipped | market cap GBP 27m < 50m |
| 2026-04-14 | FPO | skipped | market cap GBP 20m < 50m |
| 2026-04-22 | TPX | skipped | market cap GBP 35m < 50m |
| 2026-04-27 | CTG | skipped | market cap GBP 31m < 50m |
| 2026-04-27 | OHGR | skipped | market cap GBP 33m < 50m |
| 2026-04-28 | HDD | skipped | market cap GBP 28m < 50m |
| 2026-04-30 | IGR | skipped | rise >20% vs D-1 close on D or D+1 |
| 2026-04-30 | NCYT | skipped | market cap GBP 22.6m < 50m |
| 2026-05-12 | CCT | skipped | market cap GBP 43m < 50m |
| 2026-05-12 | XPF | skipped | market cap GBP 28m < 50m |
| 2026-05-14 | GATC | skipped | market cap GBP 34.2m < 50m |
| 2026-05-14 | WOSG | skipped | rise >20% vs D-1 close on D or D+1 |
| 2026-05-21 | AJB | skipped | rise >20% vs D-1 close on D or D+1 |
| 2026-05-27 | HDD | skipped | market cap GBP 40m < 50m |
| 2026-06-04 | CMCX | skipped | rise >20% vs D-1 close on D or D+1 |
| 2026-06-05 | RPI | skipped | rise >20% vs D-1 close on D or D+1 |
| 2026-07-01 | CMCX | skipped | rise >20% vs D-1 close on D or D+1 |
| 2026-07-01 | GDP | skipped | market cap GBP 27m < 50m |
| 2026-07-07 | KLR | skipped | rise >20% vs D-1 close on D or D+1 |
| 2026-07-07 | VNET | skipped | market cap GBP 19m < 50m |
| 2026-07-08 | SYS | skipped | market cap GBP 17m < 50m |
| 2026-07-09 | PTEC | skipped | rise >20% vs D-1 close on D or D+1 |
| 2026-07-16 | SHOE | skipped | market cap GBP 23m < 50m |
| 2026-07-20 | CSSG | skipped | market cap GBP 9m < 50m |
| 2026-07-21 | IQE | skipped | rise >20% vs D-1 close on D or D+1 |
| 2026-07-22 | HDD | skipped | rise >20% vs D-1 close on D or D+1 |
| 2026-07-23 | WINE | skipped | market cap GBP 47.7m < 50m |
| 2026-07-27 | SWG | skipped | market cap GBP 11m < 50m |
| 2026-07-28 | EMR | skipped | market cap GBP 11m < 50m |
| 2026-07-28 | PCIP | skipped | market cap GBP 32m < 50m |
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
| 2026-09-30 | MRK | skipped | market cap GBP 48m < 50m |
| 2026-09-30 | NAH | skipped | market cap GBP 18m < 50m |
| 2026-09-30 | SAGA | skipped | rise >20% vs D-1 close on D or D+1 |
| 2026-10-06 | SNX | skipped | market cap GBP 31m < 50m |

## Summaries

### All trades vs closed only

| Group | Trades | Winners (net) | Win rate | Mean gross return | Median gross return | Best | Worst | Net GBP |
|---|---|---|---|---|---|---|---|---|
| All trades (open marked to last close) | 103 | 45 | 44% | +1.83% | +0.00% | +75.7% | -13.1% | +811.98 |
| Closed only | 84 | 37 | 44% | +1.86% | +0.04% | +75.7% | -13.1% | +683.25 |

### Excluding borderline signals (15 of 103 trades taken are borderline; they stay in every other table)

| Group | Trades | Winners (net) | Win rate | Mean gross return | Median gross return | Best | Worst | Net GBP |
|---|---|---|---|---|---|---|---|---|
| Excl. borderline - all trades | 88 | 38 | 43% | +1.67% | +0.00% | +75.7% | -13.1% | +526.46 |
| Excl. borderline - closed only | 70 | 31 | 44% | +1.72% | +0.04% | +75.7% | -13.1% | +454.68 |

### By entry month (all trades / closed only)

| Group | Trades | Winners (net) | Win rate | Mean gross return | Median gross return | Best | Worst | Net GBP |
|---|---|---|---|---|---|---|---|---|
| 2026-04 - all | 16 | 8 | 50% | +2.61% | +1.72% | +22.4% | -11.6% | +288.67 |
| 2026-05 - all | 16 | 10 | 62% | +4.96% | +4.47% | +31.8% | -10.2% | +757.79 |
| 2026-06 - all | 13 | 4 | 31% | -0.62% | +0.00% | +12.4% | -9.7% | -273.19 |
| 2026-07 - all | 17 | 12 | 71% | +8.52% | +4.28% | +75.7% | -4.6% | +1,539.67 |
| 2026-08 - all | 12 | 1 | 8% | -3.45% | -4.99% | +17.6% | -9.4% | -708.07 |
| 2026-09 - all | 19 | 4 | 21% | -2.54% | -5.11% | +29.7% | -13.1% | -897.96 |
| 2026-10 - all | 10 | 6 | 60% | +2.02% | +2.34% | +6.0% | -4.1% | +105.09 |
| 2026-04 - closed | 16 | 8 | 50% | +2.61% | +1.72% | +22.4% | -11.6% | +288.67 |
| 2026-05 - closed | 16 | 10 | 62% | +4.96% | +4.47% | +31.8% | -10.2% | +757.79 |
| 2026-06 - closed | 13 | 4 | 31% | -0.62% | +0.00% | +12.4% | -9.7% | -273.19 |
| 2026-07 - closed | 17 | 12 | 71% | +8.52% | +4.28% | +75.7% | -4.6% | +1,539.67 |
| 2026-08 - closed | 12 | 1 | 8% | -3.45% | -4.99% | +17.6% | -9.4% | -708.07 |
| 2026-09 - closed | 10 | 2 | 20% | -6.04% | -8.41% | +5.2% | -13.1% | -921.60 |
| 2026-10 - closed | 0 | 0 | - | - | - | - | - | - |

### By market (all trades / closed only)

| Group | Trades | Winners (net) | Win rate | Mean gross return | Median gross return | Best | Worst | Net GBP |
|---|---|---|---|---|---|---|---|---|
| AIM - all | 58 | 25 | 43% | +3.26% | +0.00% | +75.7% | -11.1% | +1,652.48 |
| FTSE 250 - all | 45 | 20 | 44% | -0.01% | +0.07% | +11.0% | -13.1% | -840.49 |
| AIM - closed | 46 | 22 | 48% | +3.88% | +0.69% | +75.7% | -11.1% | +1,664.74 |
| FTSE 250 - closed | 38 | 15 | 39% | -0.59% | -0.22% | +11.0% | -13.1% | -981.49 |

### By strength (all trades / closed only)

| Group | Trades | Winners (net) | Win rate | Mean gross return | Median gross return | Best | Worst | Net GBP |
|---|---|---|---|---|---|---|---|---|
| materially - all | 19 | 8 | 42% | +6.32% | +0.63% | +75.7% | -8.4% | +1,225.36 |
| ahead - all | 56 | 23 | 41% | +0.77% | +0.00% | +22.4% | -13.1% | -266.38 |
| raised guidance - all | 28 | 14 | 50% | +0.90% | +1.32% | +31.8% | -12.0% | -147.00 |
| materially - closed | 12 | 5 | 42% | +7.81% | +0.69% | +75.7% | -8.4% | +993.10 |
| ahead - closed | 48 | 20 | 42% | +0.95% | +0.00% | +22.4% | -13.1% | -123.76 |
| raised guidance - closed | 24 | 12 | 50% | +0.69% | +1.32% | +31.8% | -12.0% | -186.09 |

### 5-slot portfolio (max 5 open, one per sector)

| Group | Trades | Winners (net) | Win rate | Mean gross return | Median gross return | Best | Worst | Net GBP |
|---|---|---|---|---|---|---|---|---|
| Portfolio - all | 34 | 13 | 38% | +2.70% | +0.00% | +75.7% | -12.0% | +632.26 |
| Portfolio - closed only | 29 | 11 | 38% | +2.44% | +0.00% | +75.7% | -12.0% | +442.57 |

34 of 103 trades taken; skipped: 59 no free slot, 10 sector already held. Net GBP +632.26 = +10.12% of the GBP 6,250 maximum capital deployed (not time-weighted).

### FTSE 250 over the same window

Benchmark used: **VMID.LSE** (Vanguard FTSE 250 ETF; MCX.INDX failed; its unadjusted close excludes distributions).
Close 2026-04-09 to close 2026-10-09: **+8.36%**. Window runs from the first entry (2026-04-09) to the last available close.
For reference, the FTSE 250 trades here: mean gross return -0.01% over holding periods of varying length (not directly comparable to the index window).

## Per-trade results

| Signal | Ticker | Market | Strength | Borderline | Entry date | Entry | Exit date | Exit | Return | Net GBP | Exit reason | Portfolio |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 2026-04-08 | SOLI | AIM | ahead | - | 2026-04-09 | 160.00 | 2026-05-08 | 170.00 | +6.25% | +65.88 | time (20 days) | yes |
| 2026-04-13 | MRK | AIM | ahead | - | 2026-04-14 | 49.00 | 2026-05-13 | 49.00 | +0.00% | -12.25 | time (20 days) | yes |
| 2026-04-15 | RNK | FTSE 250 | raised guidance | yes | 2026-04-16 | 108.00 | 2026-04-29 | 95.50 | -11.57% | -163.18 | stop (initial) | yes |
| 2026-04-16 | MERC | AIM | materially | - | 2026-04-17 | 30.00 | 2026-05-18 | 29.00 | -3.33% | -53.92 | time (20 days) | yes |
| 2026-04-16 | MGNS | FTSE 250 | materially | - | 2026-04-17 | 4940.00 | 2026-05-15 | 4526.00 | -8.38% | -123.26 | stop (initial) | yes |
| 2026-04-17 | OPT | AIM | ahead | - | 2026-04-20 | 192.00 | 2026-05-19 | 188.50 | -1.82% | -35.04 | time (20 days) | no (no free slot) |
| 2026-04-20 | PLUS | FTSE 250 | ahead | - | 2026-04-21 | 4504.00 | 2026-05-20 | 4630.00 | +2.80% | +16.47 | time (20 days) | no (no free slot) |
| 2026-04-20 | RSW | FTSE 250 | raised guidance | - | 2026-04-21 | 4562.00 | 2026-05-20 | 5060.00 | +10.92% | +117.95 | time (20 days) | no (no free slot) |
| 2026-04-20 | SUP | AIM | materially | - | 2026-04-21 | 157.50 | 2026-05-20 | 158.50 | +0.63% | -4.31 | time (20 days) | no (no free slot) |
| 2026-04-21 | AOM | AIM | ahead | - | 2026-04-22 | 196.00 | 2026-05-21 | 240.00 | +22.45% | +268.36 | time (20 days) | no (no free slot) |
| 2026-04-21 | G4M | AIM | ahead | - | 2026-04-22 | 270.00 | 2026-04-28 | 245.00 | -9.26% | -127.99 | stop (initial) | no (no free slot) |
| 2026-04-22 | SNR | FTSE 250 | materially | - | 2026-04-23 | 288.00 | 2026-05-22 | 287.00 | -0.35% | -22.84 | time (20 days) | no (no free slot) |
| 2026-04-22 | TENG | AIM | ahead | - | 2026-04-23 | 87.00 | 2026-05-22 | 94.00 | +8.05% | +88.32 | time (20 days) | no (no free slot) |
| 2026-04-24 | CCC | FTSE 250 | materially | yes | 2026-04-27 | 3800.00 | 2026-05-27 | 4218.00 | +11.00% | +119.00 | time (20 days) | no (no free slot) |
| 2026-04-28 | ELCO | AIM | ahead | yes | 2026-04-29 | 120.50 | 2026-05-29 | 130.00 | +7.88% | +86.30 | time (20 days) | yes |
| 2026-04-29 | KEYS | AIM | ahead | - | 2026-04-30 | 522.00 | 2026-06-01 | 556.00 | +6.51% | +69.17 | time (20 days) | no (no free slot) |
| 2026-04-30 | BBSN | AIM | ahead | - | 2026-05-01 | 74.00 | 2026-06-02 | 88.00 | +18.92% | +224.24 | time (20 days) | no (no free slot) |
| 2026-04-30 | VTU | AIM | ahead | - | 2026-05-01 | 64.80 | 2026-06-02 | 75.00 | +15.74% | +184.51 | time (20 days) | no (no free slot) |
| 2026-05-06 | RFX | AIM | raised guidance | - | 2026-05-07 | 432.50 | 2026-06-05 | 462.50 | +6.94% | +74.46 | time (20 days) | no (no free slot) |
| 2026-05-07 | HTWS | FTSE 250 | raised guidance | - | 2026-05-08 | 234.80 | 2026-06-08 | 223.00 | -5.03% | -81.32 | time (20 days) | no (no free slot) |
| 2026-05-07 | MHA | AIM | ahead | - | 2026-05-08 | 160.00 | 2026-06-01 | 147.00 | -8.13% | -113.81 | stop (initial) | yes |
| 2026-05-07 | PTAL | AIM | raised guidance | - | 2026-05-08 | 31.20 | 2026-06-08 | 32.00 | +2.56% | +19.80 | time (20 days) | no (no free slot) |
| 2026-05-08 | CFX | AIM | raised guidance | - | 2026-05-11 | 1330.00 | 2026-06-09 | 1400.00 | +5.26% | +53.54 | time (20 days) | no (no free slot) |
| 2026-05-12 | FDEV | AIM | raised guidance | - | 2026-05-13 | 369.00 | 2026-06-11 | 486.50 | +31.84% | +385.79 | time (20 days) | no (no free slot) |
| 2026-05-12 | NWF | AIM | materially | - | 2026-05-13 | 133.50 | 2026-06-11 | 134.50 | +0.75% | -2.89 | time (20 days) | yes |
| 2026-05-12 | WIZZ | FTSE 250 | raised guidance | yes | 2026-05-13 | 947.50 | 2026-06-11 | 1025.00 | +8.18% | +83.74 | time (20 days) | no (no free slot) |
| 2026-05-18 | KNOS | FTSE 250 | ahead | - | 2026-05-19 | 846.00 | 2026-06-17 | 833.00 | -1.54% | -37.71 | time (20 days) | yes |
| 2026-05-19 | CURY | FTSE 250 | raised guidance | - | 2026-05-20 | 142.50 | 2026-06-18 | 152.60 | +7.09% | +70.10 | time (20 days) | yes |
| 2026-05-21 | BTG | AIM | ahead | - | 2026-05-22 | 121.50 | 2026-06-22 | 119.00 | -2.06% | -37.97 | time (20 days) | no (no free slot) |
| 2026-05-21 | HILS | FTSE 250 | ahead | yes | 2026-05-22 | 2760.00 | 2026-06-22 | 2865.00 | +3.80% | +29.05 | time (20 days) | no (no free slot) |
| 2026-05-22 | SCT | FTSE 250 | raised guidance | - | 2026-05-26 | 1674.00 | 2026-06-23 | 1760.00 | +5.14% | +45.72 | time (20 days) | no (no free slot) |
| 2026-05-27 | CHRT | AIM | ahead | - | 2026-05-28 | 1474.00 | 2026-06-01 | 1324.00 | -10.18% | -139.45 | stop (initial) | no (no free slot) |
| 2026-05-29 | DNM | AIM | ahead | yes | 2026-06-01 | 21.50 | 2026-06-29 | 21.50 | +0.00% | -12.25 | time (20 days) | yes |
| 2026-06-01 | APN | FTSE 250 | ahead | yes | 2026-06-02 | 282.50 | 2026-06-30 | 311.00 | +10.09% | +107.61 | time (20 days) | yes |
| 2026-06-01 | RCN | AIM | ahead | - | 2026-06-02 | 6.40 | 2026-06-30 | 6.12 | -4.30% | -65.96 | time (20 days) | no (sector already held) |
| 2026-06-03 | RFX | AIM | raised guidance | - | 2026-06-04 | 483.00 | 2026-06-10 | 443.00 | -8.28% | -115.77 | stop (initial) | no (no free slot) |
| 2026-06-09 | OXIG | FTSE 250 | ahead | yes | 2026-06-10 | 2844.00 | 2026-07-08 | 2804.00 | -1.41% | -36.08 | stop (breakeven) | no (no free slot) |
| 2026-06-16 | OPT | AIM | ahead | yes | 2026-06-17 | 192.50 | 2026-07-15 | 192.50 | +0.00% | -12.25 | time (20 days) | yes |
| 2026-06-16 | TAM | AIM | ahead | - | 2026-06-17 | 694.00 | 2026-07-15 | 780.00 | +12.39% | +142.65 | time (20 days) | yes |
| 2026-06-23 | ENSI | AIM | ahead | yes | 2026-06-24 | 97.00 | 2026-06-29 | 88.50 | -8.76% | -121.79 | stop (initial) | no (no free slot) |
| 2026-06-23 | FTC | AIM | ahead | - | 2026-06-24 | 310.00 | 2026-06-25 | 280.00 | -9.68% | -133.22 | stop (initial) | yes |
| 2026-06-24 | VTU | AIM | ahead | - | 2026-06-25 | 74.80 | 2026-07-23 | 76.80 | +2.67% | +21.17 | time (20 days) | yes |
| 2026-06-26 | DEVO | AIM | ahead | yes | 2026-06-29 | 17.00 | 2026-07-27 | 17.00 | +0.00% | -12.25 | time (20 days) | yes |
| 2026-06-26 | DFCH | AIM | materially | - | 2026-06-29 | 65.00 | 2026-07-27 | 70.00 | +7.69% | +83.90 | time (20 days) | no (sector already held) |
| 2026-06-29 | SOLI | AIM | ahead | - | 2026-06-30 | 205.00 | 2026-07-22 | 187.50 | -8.54% | -118.96 | stop (initial) | yes |
| 2026-06-30 | MTEC | AIM | ahead | - | 2026-07-01 | 37.75 | 2026-07-29 | 36.00 | -4.64% | -70.20 | time (20 days) | no (no free slot) |
| 2026-07-09 | CCC | FTSE 250 | materially | - | 2026-07-10 | 4454.00 | 2026-08-07 | 4828.00 | +8.40% | +86.46 | time (20 days) | no (no free slot) |
| 2026-07-14 | GNS | FTSE 250 | ahead | - | 2026-07-15 | 2166.00 | 2026-08-12 | 2256.00 | +4.16% | +33.44 | time (20 days) | yes |
| 2026-07-14 | RNK | FTSE 250 | ahead | - | 2026-07-15 | 95.70 | 2026-08-12 | 99.80 | +4.28% | +35.05 | time (20 days) | yes |
| 2026-07-15 | EAH | AIM | ahead | yes | 2026-07-16 | 87.00 | 2026-08-13 | 102.50 | +17.82% | +210.45 | time (20 days) | no (no free slot) |
| 2026-07-16 | SOM | AIM | ahead | - | 2026-07-17 | 208.00 | 2026-08-14 | 230.00 | +10.58% | +119.96 | time (20 days) | no (no free slot) |
| 2026-07-17 | EYE | AIM | materially | - | 2026-07-20 | 475.00 | 2026-08-17 | 496.00 | +4.42% | +43.01 | time (20 days) | no (no free slot) |
| 2026-07-21 | RGG | AIM | materially | - | 2026-07-22 | 37.00 | 2026-08-19 | 65.00 | +75.68% | +933.70 | time (20 days) | yes |
| 2026-07-21 | ROSE | FTSE 250 | ahead | yes | 2026-07-22 | 339.00 | 2026-08-19 | 343.00 | +1.18% | -3.75 | time (20 days) | no (no free slot) |
| 2026-07-22 | GNC | FTSE 250 | raised guidance | - | 2026-07-23 | 243.40 | 2026-08-20 | 263.60 | +8.30% | +85.24 | time (20 days) | yes |
| 2026-07-22 | TSTL | AIM | ahead | - | 2026-07-23 | 392.50 | 2026-08-20 | 425.00 | +8.28% | +91.25 | time (20 days) | no (sector already held) |
| 2026-07-23 | FAN | FTSE 250 | ahead | - | 2026-07-24 | 635.00 | 2026-08-21 | 652.00 | +2.68% | +14.96 | time (20 days) | no (no free slot) |
| 2026-07-23 | FNX | AIM | ahead | - | 2026-07-24 | 168.50 | 2026-08-21 | 176.00 | +4.45% | +43.39 | time (20 days) | no (no free slot) |
| 2026-07-24 | DSCV | FTSE 250 | ahead | - | 2026-07-27 | 761.00 | 2026-08-24 | 758.00 | -0.39% | -23.43 | stop (breakeven) | no (no free slot) |
| 2026-07-24 | RSW | FTSE 250 | ahead | - | 2026-07-27 | 5165.00 | 2026-08-24 | 5035.00 | -2.52% | -49.96 | time (20 days) | yes |
| 2026-07-30 | HMSO | FTSE 250 | raised guidance | - | 2026-07-31 | 382.00 | 2026-08-28 | 377.40 | -1.20% | -33.55 | time (20 days) | no (no free slot) |
| 2026-07-30 | HTWS | FTSE 250 | raised guidance | - | 2026-07-31 | 195.80 | 2026-08-28 | 202.40 | +3.37% | +23.63 | time (20 days) | no (no free slot) |
| 2026-07-31 | CFX | AIM | materially | yes | 2026-08-03 | 1480.00 | 2026-09-01 | 1440.00 | -2.70% | -46.03 | time (20 days) | no (no free slot) |
| 2026-08-03 | CKN | FTSE 250 | materially | - | 2026-08-04 | 5075.00 | 2026-09-02 | 5070.00 | -0.10% | -19.73 | time (20 days) | no (no free slot) |
| 2026-08-05 | FOUR | FTSE 250 | ahead | - | 2026-08-06 | 5000.00 | 2026-08-17 | 4580.00 | -8.40% | -123.50 | stop (initial) | no (no free slot) |
| 2026-08-06 | DLN | FTSE 250 | raised guidance | - | 2026-08-07 | 2100.00 | 2026-09-07 | 1955.00 | -6.90% | -104.81 | time (20 days) | no (no free slot) |
| 2026-08-11 | PPHC | AIM | raised guidance | - | 2026-08-12 | 835.00 | 2026-09-10 | 815.00 | -2.40% | -42.19 | time (20 days) | no (sector already held) |
| 2026-08-12 | BBY | FTSE 250 | raised guidance | - | 2026-08-13 | 922.50 | 2026-09-10 | 840.00 | -8.94% | -130.29 | stop (initial) | yes |
| 2026-08-12 | HILS | FTSE 250 | ahead | - | 2026-08-13 | 2930.00 | 2026-09-11 | 2840.00 | -3.07% | -56.90 | time (20 days) | yes |
| 2026-08-17 | GATC | AIM | raised guidance | - | 2026-08-18 | 167.50 | 2026-08-24 | 152.50 | -8.96% | -124.19 | stop (initial) | no (no free slot) |
| 2026-08-18 | MTEC | AIM | ahead | - | 2026-08-19 | 42.50 | 2026-09-17 | 50.00 | +17.65% | +208.34 | time (20 days) | yes |
| 2026-08-25 | VLX | FTSE 250 | ahead | - | 2026-08-26 | 619.00 | 2026-09-24 | 624.00 | +0.81% | -8.40 | time (20 days) | yes |
| 2026-08-26 | APN | FTSE 250 | ahead | - | 2026-08-27 | 317.50 | 2026-09-11 | 287.50 | -9.45% | -136.61 | stop (initial) | yes |
| 2026-08-27 | VTU | AIM | ahead | - | 2026-08-28 | 90.80 | 2026-09-10 | 82.70 | -8.92% | -123.76 | stop (initial) | no (no free slot) |
| 2026-09-03 | HFG | FTSE 250 | raised guidance | - | 2026-09-04 | 698.00 | 2026-10-02 | 698.50 | +0.07% | -17.60 | time (20 days) | no (no free slot) |
| 2026-09-03 | ROSE | FTSE 250 | ahead | - | 2026-09-04 | 341.00 | 2026-09-25 | 312.00 | -8.50% | -124.80 | stop (initial) | no (no free slot) |
| 2026-09-07 | CNC | AIM | ahead | - | 2026-09-08 | 277.50 | 2026-09-15 | 255.00 | -8.11% | -113.60 | stop (initial) | no (no free slot) |
| 2026-09-07 | WRKS | AIM | ahead | - | 2026-09-08 | 94.90 | 2026-09-23 | 84.40 | -11.06% | -150.55 | stop (initial) | no (no free slot) |
| 2026-09-08 | FCH | FTSE 250 | raised guidance | - | 2026-09-09 | 197.20 | 2026-09-16 | 180.80 | -8.32% | -122.46 | stop (initial) | no (no free slot) |
| 2026-09-08 | SOM | AIM | raised guidance | - | 2026-09-09 | 253.00 | 2026-10-07 | 263.00 | +3.95% | +37.16 | time (20 days) | no (no free slot) |
| 2026-09-09 | EWG | FTSE 250 | raised guidance | - | 2026-09-10 | 94.10 | 2026-10-08 | 99.00 | +5.21% | +46.59 | time (20 days) | no (sector already held) |
| 2026-09-09 | VCT | FTSE 250 | raised guidance | - | 2026-09-10 | 998.00 | 2026-09-24 | 878.00 | -12.02% | -168.80 | stop (initial) | yes |
| 2026-09-14 | BIG | AIM | ahead | - | 2026-09-15 | 97.80 | 2026-10-09 | 92.80 | -5.11% | -76.16 | open (marked to last close) | no (sector already held) |
| 2026-09-14 | KEYS | AIM | materially | - | 2026-09-15 | 710.00 | 2026-10-09 | 690.00 | -2.82% | -47.46 | open (marked to last close) | no (sector already held) |
| 2026-09-15 | KIE | FTSE 250 | raised guidance | - | 2026-09-16 | 287.20 | 2026-10-09 | 296.80 | +3.34% | +23.28 | open (marked to last close) | yes |
| 2026-09-17 | BYIT | FTSE 250 | raised guidance | - | 2026-09-18 | 457.00 | 2026-10-09 | 453.20 | -0.83% | -28.89 | open (marked to last close) | yes |
| 2026-09-17 | GFRD | FTSE 250 | ahead | - | 2026-09-18 | 684.00 | 2026-10-09 | 684.00 | +0.00% | -18.50 | open (marked to last close) | no (sector already held) |
| 2026-09-23 | CDGP | AIM | materially | - | 2026-09-24 | 48.50 | 2026-10-09 | 46.00 | -5.15% | -76.68 | open (marked to last close) | yes |
| 2026-09-24 | RPI | FTSE 250 | ahead | - | 2026-09-25 | 711.50 | 2026-09-28 | 618.50 | -13.07% | -181.89 | stop (initial) | no (sector already held) |
| 2026-09-28 | CCT | AIM | ahead | - | 2026-09-29 | 321.00 | 2026-10-09 | 318.00 | -0.93% | -23.93 | open (marked to last close) | no (sector already held) |
| 2026-09-28 | LIKE | AIM | materially | - | 2026-09-29 | 34.40 | 2026-10-09 | 44.60 | +29.65% | +358.39 | open (marked to last close) | yes |
| 2026-09-28 | WVIA | AIM | ahead | - | 2026-09-29 | 295.00 | 2026-10-09 | 277.50 | -5.93% | -86.40 | open (marked to last close) | yes |
| 2026-09-29 | ZIG | FTSE 250 | raised guidance | - | 2026-09-30 | 472.50 | 2026-10-08 | 432.00 | -8.57% | -125.64 | stop (initial) | no (no free slot) |
| 2026-09-30 | AVG | AIM | ahead | - | 2026-10-01 | 740.00 | 2026-10-09 | 750.00 | +1.35% | +4.64 | open (marked to last close) | no (no free slot) |
| 2026-09-30 | EVPL | AIM | materially | - | 2026-10-01 | 439.50 | 2026-10-09 | 421.50 | -4.10% | -63.44 | open (marked to last close) | no (no free slot) |
| 2026-09-30 | GRG | FTSE 250 | raised guidance | yes | 2026-10-01 | 1988.00 | 2026-10-09 | 2108.00 | +6.04% | +56.95 | open (marked to last close) | no (no free slot) |
| 2026-09-30 | YNGA | AIM | ahead | - | 2026-10-01 | 951.00 | 2026-10-09 | 996.00 | +4.73% | +46.90 | open (marked to last close) | no (no free slot) |
| 2026-10-01 | RGG | AIM | materially | - | 2026-10-02 | 110.00 | 2026-10-09 | 109.00 | -0.91% | -23.61 | open (marked to last close) | no (no free slot) |
| 2026-10-05 | QTX | AIM | ahead | - | 2026-10-06 | 237.50 | 2026-10-09 | 237.50 | +0.00% | -12.25 | open (marked to last close) | no (no free slot) |
| 2026-10-06 | CKN | FTSE 250 | materially | - | 2026-10-07 | 5160.00 | 2026-10-09 | 5405.00 | +4.75% | +40.85 | open (marked to last close) | no (no free slot) |
| 2026-10-07 | AVON | FTSE 250 | ahead | - | 2026-10-08 | 2255.00 | 2026-10-09 | 2330.00 | +3.33% | +23.07 | open (marked to last close) | no (no free slot) |
| 2026-10-07 | BPT | FTSE 250 | materially | - | 2026-10-08 | 382.60 | 2026-10-09 | 401.80 | +5.02% | +44.23 | open (marked to last close) | no (no free slot) |
| 2026-10-08 | ITM | AIM | raised guidance | - | 2026-10-09 | 93.85 | 2026-10-09 | 93.85 | +0.00% | -12.25 | open (marked to last close) | no (no free slot) |
