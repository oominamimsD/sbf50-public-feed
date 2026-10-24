# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T20:00:21Z**
- feed_generated_utc: 2026-10-24T20:00:25+00:00
- source_sha256: `433bebe6649a1403ff009bfb46702c74a31114765c32192a05b53425718167cb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T20:00+00:00, close=80455.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T20:00+00:00, close=80455.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T20:00+00:00, close=80455.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.044120|-22.48|245.76|-23.34|44147402|2.27|
|BIRB_USDT|0.091690|-6.11|88.97|-6.97|11801005|5.47|
|AGT_USDT|0.069140|-2.79|-4.04|-3.65|9445010|4.34|
|TIA_USDT|0.530100|-0.73|-19.43|-1.59|29300269|1.89|
|INJ_USDT|7.542000|-0.51|-10.87|-1.37|13344059|2.65|
|STRK_USDT|0.047240|-0.14|-28.58|-1.00|9481280|2.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.069140|0.065820|0.069140|0.44|N|Y/Y|Y/Y|Y|N|
|BIRB_USDT|0.091690|0.088740|0.092270|0.94|N|Y/Y|N/N|Y|N|
|INJ_USDT|7.542000|7.498000|7.543000|0.49|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.044120|0.042300|0.044120|0.61|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.047240|0.046770|0.047240|0.32|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.530100|0.518800|0.530100|0.10|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-24T20:00:00+00:00, last15m_closed_end=2026-10-24T20:00+00:00, prior8high=0.069650, depth_time=2026-10-24T20:00:12+00:00, book20_bid_proxy_usdt=12972, book20_ask_proxy_usdt=10650, funding_indicative=0.000139, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.79%, turnover=9445010. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BIRB_USDT: quote_utc=2026-10-24T20:00:00+00:00, last15m_closed_end=2026-10-24T20:00+00:00, prior8high=0.095690, depth_time=2026-10-24T20:00:10+00:00, book20_bid_proxy_usdt=17248, book20_ask_proxy_usdt=70365, funding_indicative=-0.007578, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.11%, turnover=11801005. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-24T20:00:00+00:00, last15m_closed_end=2026-10-24T20:00+00:00, prior8high=7.609000, depth_time=2026-10-24T20:00:18+00:00, book20_bid_proxy_usdt=236297, book20_ask_proxy_usdt=205122, funding_indicative=0.000248, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.51%, turnover=13344059. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-24T20:00:00+00:00, last15m_closed_end=2026-10-24T20:00+00:00, prior8high=0.051690, depth_time=2026-10-24T20:00:08+00:00, book20_bid_proxy_usdt=62456, book20_ask_proxy_usdt=51028, funding_indicative=0.000012, next_funding_utc=2026-10-24T21:00:00+00:00, funding_cycle_h=1, 24h_change=-22.48%, turnover=44147402. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-24T20:00:00+00:00, last15m_closed_end=2026-10-24T20:00+00:00, prior8high=0.047680, depth_time=2026-10-24T20:00:21+00:00, book20_bid_proxy_usdt=773192, book20_ask_proxy_usdt=727722, funding_indicative=0.000039, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.14%, turnover=9481280. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-24T20:00:00+00:00, last15m_closed_end=2026-10-24T20:00+00:00, prior8high=0.533800, depth_time=2026-10-24T20:00:15+00:00, book20_bid_proxy_usdt=215828, book20_ask_proxy_usdt=293138, funding_indicative=-0.000068, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.73%, turnover=29300269. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
