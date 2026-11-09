# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T20:30:13Z**
- feed_generated_utc: 2026-11-09T20:30:14+00:00
- source_sha256: `7aa7933d0f75f0e61d1a683ce6d7b48227e09e7f975348c7948ac5cadc5f12ea`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T20:30+00:00, close=74813.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T20:00+00:00, close=74856.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T20:00+00:00, close=74856.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1175.570000|-4.09|-6.26|-3.16|2520230737|0.09|
|QNT_USDT|195.810000|-2.11|-3.27|-1.18|43671142|2.55|
|XRP_USDT|1.091500|-2.01|-12.56|-1.08|325848774|0.92|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|QNT_USDT|195.810000|194.840000|195.810000|0.64|N|Y/Y|Y/N|Y|N|
|XRP_USDT|1.091500|1.083300|1.092100|1.21|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1175.570000|1158.500000|1176.420000|1.18|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- QNT_USDT: quote_utc=2026-11-09T20:29:59+00:00, last15m_closed_end=2026-11-09T20:30+00:00, prior8high=197.570000, depth_time=2026-11-09T20:30:09+00:00, book20_bid_proxy_usdt=70644, book20_ask_proxy_usdt=58474, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.11%, turnover=43671142. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T20:30:02+00:00, last15m_closed_end=2026-11-09T20:30+00:00, prior8high=1.103100, depth_time=2026-11-09T20:30:12+00:00, book20_bid_proxy_usdt=4446918, book20_ask_proxy_usdt=4365620, funding_indicative=0.000079, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.01%, turnover=325848774. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T20:30:02+00:00, last15m_closed_end=2026-11-09T20:30+00:00, prior8high=1189.910000, depth_time=2026-11-09T20:30:07+00:00, book20_bid_proxy_usdt=98014, book20_ask_proxy_usdt=213496, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.09%, turnover=2520230737. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
