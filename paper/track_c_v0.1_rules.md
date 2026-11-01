# Track C ruleset v0.1 (forward paper test)

Paper trading only. Never place real trades. Track B ruleset v1 is not changed. Evidence summary: `paper/track_c_research.md`. Master copy: `docs/track-c-v0.1-spec.md` in the private aim-trading repo (this is a copy for the morning brief).

**Start: Monday 2 Nov 2026** (Andy, 1 Nov). The first qualifying close on or after that morning is the first trade. Pass mark agreed by Andy on 21 Oct 2026.

## What is being tested
Whether buying a FTSE 250 or AIM share shortly before its scheduled update, only if it upgraded in the last 12 months, beats buying the same kind of share without that condition. Back-test (Apr to Oct 2026): such shares upgrade about 6 times as often (24% vs 4%) and made +1.9% (trimmed mean) per trade after costs, but FTSE 250 alone showed nothing and AIM was biased by how the list was chosen. Only forward trades, chosen before the result is known, can settle it.

## Rules
- **Trigger:** a FTSE 250 or AIM company that made an ahead-of-expectations or raised-profit-guidance statement in the past 12 months, and has a scheduled update or results date announced 10-20 trading days ahead. A person reads the update and the last 12 months of announcements to confirm the prior upgrade.
- **Filters:** market value £50m or more; buy/sell gap 3% or less; no takeover offer period; skip if down more than 10% over the past 20 trading days; price at least 5p.
- **Buy and sell:** buy at the close on the day it qualifies; sell at the close the day after the update, whatever it says. No stop.
- **Size:** £5,000 pot, £1,000 per position, at most five open, at most two per sector. Costs as Track B (AIM 1.46%, main market 1.96% of the position per round trip).
- **Control trade:** for every real paper trade, also record a paper control: a FTSE 250 or AIM company of the same market that passes every filter except the prior-upgrade condition, with an update due in the same week, bought and sold on the same days; chosen by nearest market value. Controls use no pot and no slot.
- **Report separately:** FTSE 250 and AIM, every time.
- **Stop:** the pot stops at £3,750.

## Review
- Interim look 12 Apr 2027 against VWRP, Track B and the controls (about 35 trades by then: a look, not a verdict).
- Verdict at 60 closed trades, or the first review date after that.
- **Pass mark:** mean net return per trade above +1% and above the controls' mean. Anything else means drop or rethink.

## Prices
`paper/latest_closes.csv` (EODHD, weekdays about 18:45 UTC; shares in pence, ETFs in pounds; use its `date` column and treat status `missing` as "price unavailable"). Tickers come from `paper/watchlist.csv` in the private repo; ask Andy to add new Track C tickers.
