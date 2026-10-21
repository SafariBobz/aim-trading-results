# Track C research summary (pre-upgrade strategy)

**Backtest of past announcements, 1 Apr to 16 Oct 2026. Paper trading only. Research only: not a forecast and not advice.** Published 2026-10-21. Prices: EODHD unadjusted closes (LSE), benchmark VMID. Announcements: Investegate, classified by phrase rules. Full write-up and code are in the private `aim-trading` repository (branch `track-c-research`, folder `research/track_c`). Track B is unchanged.

## Recommendation

**Change Track C v0 before starting it** (do not start it as drafted, do not drop it yet). Suggested changes, for Andy to decide: run it as a forward paper test with a matching control trade for each real one (same filters but no prior upgrade), report FTSE 250 and AIM separately, review at about 60 closed trades or 12 Apr 2027 (whichever is later) against a pass mark written down now, and have a person confirm each trigger.

## Findings

1. **Prior upgrade within 12 months predicts another upgrade.** Mechanical panel of 1,487 results/trading-update announcements (413 companies: FTSE 100, FTSE 250 excluding investment trusts, 150 most-traded AIM companies). Scheduled events, upgrade rate with a prior upgrade vs without: FTSE 100 21.1% vs 4.5%; FTSE 250 27.0% vs 4.4%; AIM 23.9% vs 3.3%; all 24.2% vs 4.0% (about 6x, p < 0.0001). The hand-built sample (25% vs 1.6%) was too extreme.
2. **Trade: buy the close 21 trading days before the announcement, sell the close of the day after, net of costs (AIM 1.46%, main market 1.96%).**

| Set (scheduled events, clean prices) | n | median | trimmed mean (5%) | mean | % up |
|---|---|---|---|---|---|
| All events | 1,230 | +0.2% | +0.8% | +1.5% | 51% |
| Prior upgrade | 438 | +1.2% | +1.9% | +2.7% | 55% |
| No prior upgrade | 792 | -0.3% | +0.2% | +0.8% | 48% |
| v0 filters that can be tested (FTSE 250 + AIM) | 246 | +1.1% | +1.9% | +2.8% | 55% |
| v0, FTSE 250 only | 132 | +0.7% | +0.4% | +0.7% | 52% |
| v0, AIM only (look-ahead bias, see limits) | 114 | +1.8% | +3.9% | +5.2% | 59% |
| Control: same filters, no prior upgrade | 466 | -0.1% | -0.2% | +0.3% | 49% |

   Within v0, the 27% of trades that were upgrades made +5.8% median (+6.9% trimmed mean); the others about 0%; "below expectations" outcomes about -7%.
3. **Thin and not yet reliable.** FTSE 250 alone shows no edge (interval -1.6% to +2.5%). By month the v0 set was +8% in August, about 0% in September, -3% in October. A trade swings by about 15% (standard deviation), so 30 trades cannot show a +1.9% edge; about 250 would be needed.
4. **Hand-built samples re-priced with EODHD (153 upgrades, 146 control events):** no handover finding changed materially. Upgrades +7.7% median net; in line -1.2%; below -9.1%; warnings -18.6%; all non-upgrades -2.7%; announcement day +7.0% median (86% up); 77% of the D-21 to D+1 move happens on the day; run-up D-21 to D-1 median +1.1% (49% beat VMID); break-even upgrade share 15%.

## Method and counts

Companies: FTSE 100 (Wikipedia list, 97), FTSE 250 as at 10 Oct 2026 excluding investment trusts (200), top 150 live AIM names by median daily traded value (stand-in for "over £100m": no market-cap data on the EODHD plan). 30 more were dropped as investment trusts (they publish NAV announcements). 4 left out (Barclays, BPCR, PEY, RTW: filings list unreadable or ticker not found). 4,363 announcement texts read; 1,487 company-days analysed from 1 Apr 2026; 1,395 with clean prices (full window, no split or consolidation, price at least 5p); 1,230 scheduled (results, or an update the company also made about a year earlier). A company can have only one event per day. Prior upgrade = another "ahead" event for that company in the previous 365 days. Draft v0 filters tested: FTSE 250 or AIM, prior upgrade, scheduled, no takeover headline in the previous 60 days, not down more than 10% over the previous 20 days. Not testable: £50m market value, 3% buy/sell gap, update date known 10 to 20 days ahead, sizing and slots.

## Limits

- **Survivorship:** index members are today's. **AIM look-ahead:** AIM names were picked by recent trading volume, which favours companies with recent good news, so AIM figures are probably inflated.
- **Phrase rules, not a person:** 83% of 149 hand-labelled upgrades found, 0 of 132 non-upgrades mislabelled (rules tuned on these); about 70% of 30 sampled "ahead" calls on the panel were clean. Warnings and "below" are badly under-counted.
- **Scheduled is a proxy; prior upgrade overlaps with momentum;** costs are flat; events cluster in results seasons so intervals are too narrow; one six-month market regime.
- Prices are derived percentages only; raw EODHD data is not published here.
