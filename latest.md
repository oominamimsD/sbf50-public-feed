# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T19:30:16Z**
- feed_generated_utc: 2026-10-26T19:30:19+00:00
- source_sha256: `373826bb62d0f5b8673eca3303a4a9bd6f86b241066df97ba656cf488ff8f169`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T19:30+00:00, close=79930, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T19:00+00:00, close=79961.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T16:00+00:00, close=80399.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.118100|-6.48|-36.18|-5.90|20391296|4.47|
|IRYS_USDT|0.026480|-3.98|115.63|-3.40|9628115|3.78|
|NEAR_USDT|4.482000|-1.98|-8.60|-1.40|119756904|4.46|
|LIT_USDT|3.058100|-1.93|0.86|-1.35|5048268|0.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.118100|1.048400|1.118100|0.21|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.026480|0.026060|0.026480|0.51|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.058100|3.047500|3.058100|0.66|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.482000|4.442000|4.482000|1.00|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-26T19:30:00+00:00, last15m_closed_end=2026-10-26T19:30+00:00, prior8high=1.304000, depth_time=2026-10-26T19:30:08+00:00, book20_bid_proxy_usdt=12151, book20_ask_proxy_usdt=22216, funding_indicative=0.000050, next_funding_utc=2026-10-26T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.48%, turnover=20391296. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T19:30:00+00:00, last15m_closed_end=2026-10-26T19:30+00:00, prior8high=0.027470, depth_time=2026-10-26T19:30:10+00:00, book20_bid_proxy_usdt=103604, book20_ask_proxy_usdt=89854, funding_indicative=-0.000677, next_funding_utc=2026-10-26T20:00:00+00:00, funding_cycle_h=1, 24h_change=-3.98%, turnover=9628115. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T19:30:00+00:00, last15m_closed_end=2026-10-26T19:30+00:00, prior8high=3.150400, depth_time=2026-10-26T19:30:15+00:00, book20_bid_proxy_usdt=12988, book20_ask_proxy_usdt=22630, funding_indicative=0.000050, next_funding_utc=2026-10-26T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.93%, turnover=5048268. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T19:30:00+00:00, last15m_closed_end=2026-10-26T19:30+00:00, prior8high=4.569000, depth_time=2026-10-26T19:30:13+00:00, book20_bid_proxy_usdt=4519071, book20_ask_proxy_usdt=2406703, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.98%, turnover=119756904. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
