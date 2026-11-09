# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T22:30:15Z**
- feed_generated_utc: 2026-11-09T22:30:16+00:00
- source_sha256: `121a80452c5b1a8a05d4233b0989cb56cd6c77dbd554603488e4a59ca7274a0c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T22:30+00:00, close=75050.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T22:00+00:00, close=75004.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-09T20:00+00:00, close=74856.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1176.510000|-4.01|-6.18|-3.42|2490690681|0.09|
|DOT_USDT|0.860100|-3.45|-7.92|-2.86|11581410|1.16|
|QNT_USDT|195.180000|-2.42|-3.59|-1.83|43260962|1.54|
|XRP_USDT|1.094400|-1.75|-12.33|-1.16|304636922|0.91|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|0.860100|0.856000|0.860100|0.66|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.180000|194.440000|195.180000|0.87|N|Y/Y|Y/N|Y|N|
|XRP_USDT|1.094400|1.087800|1.094400|0.84|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1176.510000|1162.360000|1176.510000|0.77|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-11-09T22:30:00+00:00, last15m_closed_end=2026-11-09T22:30+00:00, prior8high=0.870800, depth_time=2026-11-09T22:30:09+00:00, book20_bid_proxy_usdt=414579, book20_ask_proxy_usdt=530986, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.45%, turnover=11581410. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-09T22:30:00+00:00, last15m_closed_end=2026-11-09T22:30+00:00, prior8high=197.100000, depth_time=2026-11-09T22:30:12+00:00, book20_bid_proxy_usdt=93880, book20_ask_proxy_usdt=66876, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.42%, turnover=43260962. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T22:29:59+00:00, last15m_closed_end=2026-11-09T22:30+00:00, prior8high=1.099700, depth_time=2026-11-09T22:30:14+00:00, book20_bid_proxy_usdt=3061620, book20_ask_proxy_usdt=3770020, funding_indicative=0.000081, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.75%, turnover=304636922. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T22:29:59+00:00, last15m_closed_end=2026-11-09T22:30+00:00, prior8high=1186.440000, depth_time=2026-11-09T22:30:07+00:00, book20_bid_proxy_usdt=494037, book20_ask_proxy_usdt=115001, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.01%, turnover=2490690681. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
