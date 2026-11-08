# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T01:15:12Z**
- feed_generated_utc: 2026-11-08T01:15:13+00:00
- source_sha256: `5e9a76736303ac3a6adb378bba66d0c6bb9355b7a9daa274f4dc1e9ac83f5969`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T01:15+00:00, close=75795.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T01:00+00:00, close=75774, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T00:00+00:00, close=75836.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|QNT_USDT|195.330000|-1.77|-2.84|-1.86|42101937|0.51|
|WLD_USDT|0.331900|-1.10|-17.92|-1.19|25798322|3.01|
|TIA_USDT|0.437100|-1.01|-10.81|-1.10|6914352|2.29|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|QNT_USDT|195.330000|194.800000|195.330000|0.79|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.437100|0.436700|0.437100|0.31|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.331900|0.331200|0.331900|0.25|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- QNT_USDT: quote_utc=2026-11-08T01:15:00+00:00, last15m_closed_end=2026-11-08T01:15+00:00, prior8high=196.770000, depth_time=2026-11-08T01:15:06+00:00, book20_bid_proxy_usdt=125035, book20_ask_proxy_usdt=58465, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=42101937. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T01:15:00+00:00, last15m_closed_end=2026-11-08T01:15+00:00, prior8high=0.443200, depth_time=2026-11-08T01:15:10+00:00, book20_bid_proxy_usdt=333244, book20_ask_proxy_usdt=247705, funding_indicative=0.000011, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.01%, turnover=6914352. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T01:15:00+00:00, last15m_closed_end=2026-11-08T01:15+00:00, prior8high=0.335400, depth_time=2026-11-08T01:15:09+00:00, book20_bid_proxy_usdt=3617954, book20_ask_proxy_usdt=2952827, funding_indicative=-0.000084, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=25798322. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
