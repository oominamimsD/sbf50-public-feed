# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T20:15:18Z**
- feed_generated_utc: 2026-11-08T20:15:19+00:00
- source_sha256: `823030ebd92bb117c81ccd441a660330f73d3e1cf6b33b2487369c4fe63c09a3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T20:15+00:00, close=75863.8, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T20:00+00:00, close=75894.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T20:00+00:00, close=75894.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001733|-11.48|48.82|-11.26|15219688|2.31|
|AKE_USDT|0.005197|-2.98|-43.26|-2.76|17623798|1.92|
|NEAR_USDT|3.633000|-1.83|-16.11|-1.61|31758930|2.75|
|ARB_USDT|0.166950|-1.73|0.46|-1.51|18677064|0.60|
|WLD_USDT|0.321400|-1.38|-18.77|-1.16|24408424|3.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005197|0.005112|0.005197|1.29|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.166950|0.166560|0.166950|0.20|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.633000|3.602000|3.633000|0.63|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001733|0.001750|0.001733|1.18|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.321400|0.321600|0.321600|1.76|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-08T20:15:02+00:00, last15m_closed_end=2026-11-08T20:15+00:00, prior8high=0.005317, depth_time=2026-11-08T20:15:08+00:00, book20_bid_proxy_usdt=58798, book20_ask_proxy_usdt=35615, funding_indicative=0.000050, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.98%, turnover=17623798. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-08T20:15:02+00:00, last15m_closed_end=2026-11-08T20:15+00:00, prior8high=0.168610, depth_time=2026-11-08T20:15:15+00:00, book20_bid_proxy_usdt=103874, book20_ask_proxy_usdt=131676, funding_indicative=-0.000034, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=18677064. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-08T20:15:02+00:00, last15m_closed_end=2026-11-08T20:15+00:00, prior8high=3.666000, depth_time=2026-11-08T20:15:09+00:00, book20_bid_proxy_usdt=2811976, book20_ask_proxy_usdt=3473032, funding_indicative=0.000100, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.83%, turnover=31758930. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T20:15:02+00:00, last15m_closed_end=2026-11-08T20:15+00:00, prior8high=0.001846, depth_time=2026-11-08T20:15:07+00:00, book20_bid_proxy_usdt=14395, book20_ask_proxy_usdt=16436, funding_indicative=-0.000338, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.48%, turnover=15219688. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T20:15:02+00:00, last15m_closed_end=2026-11-08T20:15+00:00, prior8high=0.327200, depth_time=2026-11-08T20:15:14+00:00, book20_bid_proxy_usdt=4814548, book20_ask_proxy_usdt=3540086, funding_indicative=-0.000038, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.38%, turnover=24408424. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
