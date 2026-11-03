# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T22:30:13Z**
- feed_generated_utc: 2026-11-03T22:30:15+00:00
- source_sha256: `1f2a04229cb94d90625cab3c1575b7ccd3dfac9e233b3e45eac612b5c81a35b1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T22:30+00:00, close=77753, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T22:00+00:00, close=77870.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T20:00+00:00, close=77586.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003919|-5.70|-81.44|-5.81|13724275|7.65|
|EVAA_USDT|1.451900|-4.25|107.80|-4.36|5237979|2.07|
|QNT_USDT|192.540000|-1.47|-2.70|-1.58|58783769|3.63|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003919|0.003856|0.003919|0.70|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.451900|1.427900|1.451900|0.95|N|Y/Y|N/N|Y|N|
|QNT_USDT|192.540000|190.330000|192.590000|2.00|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T22:30:03+00:00, last15m_closed_end=2026-11-03T22:30+00:00, prior8high=0.004140, depth_time=2026-11-03T22:30:07+00:00, book20_bid_proxy_usdt=25032, book20_ask_proxy_usdt=47945, funding_indicative=-0.000700, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.70%, turnover=13724275. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-11-03T22:30:03+00:00, last15m_closed_end=2026-11-03T22:30+00:00, prior8high=1.483100, depth_time=2026-11-03T22:30:09+00:00, book20_bid_proxy_usdt=12371, book20_ask_proxy_usdt=11606, funding_indicative=0.000050, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.25%, turnover=5237979. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T22:30:03+00:00, last15m_closed_end=2026-11-03T22:30+00:00, prior8high=194.210000, depth_time=2026-11-03T22:30:12+00:00, book20_bid_proxy_usdt=67441, book20_ask_proxy_usdt=82948, funding_indicative=0.000062, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=58783769. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
