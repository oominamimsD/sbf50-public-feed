# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T15:00:32Z**
- feed_generated_utc: 2026-10-31T15:00:34+00:00
- source_sha256: `ce0561fdace8c2132d03b3c95abd29d4ae73fca58fb40fedd91825dc02a03151`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T15:00+00:00, close=77382.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T15:00+00:00, close=77382.7, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T12:00+00:00, close=77577.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.010948|-42.13|-68.71|-41.90|12014891|2.74|
|Q_USDT|0.033070|-30.34|-72.05|-30.11|11394113|6.04|
|BEAT_USDT|0.098440|-6.38|35.61|-6.15|6466369|3.05|
|TRX_USDT|0.315280|-6.28|-4.26|-6.05|6422234|0.32|
|BTW_USDT|1.141400|-6.23|-32.95|-6.00|7929332|1.75|
|HYPE_USDT|86.896000|-5.89|10.83|-5.66|92191377|0.12|
|WLD_USDT|0.397600|-3.47|-25.31|-3.24|39516514|2.51|
|FET_USDT|0.162100|-1.81|-13.45|-1.58|5434304|6.17|
|BCH_USDT|288.730000|-1.56|0.44|-1.33|5202555|8.66|
|DASH_USDT|48.380000|-1.34|-10.15|-1.11|6682716|2.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010948|0.010972|0.010957|1.37|Y|Y/Y|Y/Y|Y|Y|
|BCH_USDT|288.730000|289.300000|288.710000|0.48|N|Y/N|N/N|Y|N|
|BEAT_USDT|0.098440|0.097030|0.098340|1.04|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.141400|1.086200|1.141400|0.44|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.380000|47.750000|48.330000|1.25|N|N/Y|Y/Y|Y|N|
|FET_USDT|0.162100|0.160500|0.162100|0.85|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|86.896000|86.372000|86.839000|0.27|N|Y/Y|N/N|Y|N|
|Q_USDT|0.033070|0.031630|0.033070|1.90|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.315280|0.315310|0.315280|0.61|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.397600|0.395200|0.397600|7.21|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T15:00:04+00:00, last15m_closed_end=2026-10-31T15:00+00:00, prior8high=0.011940, depth_time=2026-10-31T15:00:10+00:00, book20_bid_proxy_usdt=10109, book20_ask_proxy_usdt=10862, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-42.13%, turnover=12014891. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-10-31T15:00:04+00:00, last15m_closed_end=2026-10-31T15:00+00:00, prior8high=293.170000, depth_time=2026-10-31T15:00:27+00:00, book20_bid_proxy_usdt=24485, book20_ask_proxy_usdt=68506, funding_indicative=0.000062, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.56%, turnover=5202555. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T15:00:04+00:00, last15m_closed_end=2026-10-31T15:00+00:00, prior8high=0.100370, depth_time=2026-10-31T15:00:14+00:00, book20_bid_proxy_usdt=15939, book20_ask_proxy_usdt=10979, funding_indicative=0.000123, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.38%, turnover=6466369. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T15:00:04+00:00, last15m_closed_end=2026-10-31T15:00+00:00, prior8high=1.149700, depth_time=2026-10-31T15:00:18+00:00, book20_bid_proxy_usdt=10391, book20_ask_proxy_usdt=16819, funding_indicative=-0.000156, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.23%, turnover=7929332. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T15:00:04+00:00, last15m_closed_end=2026-10-31T15:00+00:00, prior8high=48.490000, depth_time=2026-10-31T15:00:31+00:00, book20_bid_proxy_usdt=643509, book20_ask_proxy_usdt=494442, funding_indicative=-0.000124, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=6682716. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T15:00:04+00:00, last15m_closed_end=2026-10-31T15:00+00:00, prior8high=0.161700, depth_time=2026-10-31T15:00:26+00:00, book20_bid_proxy_usdt=1413217, book20_ask_proxy_usdt=961928, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=5434304. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T15:00:04+00:00, last15m_closed_end=2026-10-31T15:00+00:00, prior8high=88.490000, depth_time=2026-10-31T15:00:21+00:00, book20_bid_proxy_usdt=128419, book20_ask_proxy_usdt=80289, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.89%, turnover=92191377. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T15:00:04+00:00, last15m_closed_end=2026-10-31T15:00+00:00, prior8high=0.032810, depth_time=2026-10-31T15:00:12+00:00, book20_bid_proxy_usdt=60400, book20_ask_proxy_usdt=41728, funding_indicative=-0.000526, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=1, 24h_change=-30.34%, turnover=11394113. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T15:00:04+00:00, last15m_closed_end=2026-10-31T15:00+00:00, prior8high=0.322470, depth_time=2026-10-31T15:00:17+00:00, book20_bid_proxy_usdt=213900, book20_ask_proxy_usdt=80821, funding_indicative=-0.000630, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.28%, turnover=6422234. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T15:00:04+00:00, last15m_closed_end=2026-10-31T15:00+00:00, prior8high=0.399000, depth_time=2026-10-31T15:00:24+00:00, book20_bid_proxy_usdt=2949216, book20_ask_proxy_usdt=3889454, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.47%, turnover=39516514. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
