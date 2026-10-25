# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T17:15:16Z**
- feed_generated_utc: 2026-10-25T17:15:19+00:00
- source_sha256: `cf28e151864408ea1cf8b55e92ce0c255dbf07e16c60414a00b68a9457c03c56`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T17:15+00:00, close=80752.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T17:00+00:00, close=80777.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T16:00+00:00, close=80602.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.036730|-4.44|201.06|-4.62|22118102|5.44|
|BTW_USDT|1.611200|-2.87|-30.11|-3.05|12932745|7.44|
|XMR_USDT|601.370000|-0.96|3.23|-1.14|7123480|0.83|
|STRK_USDT|0.045330|-0.89|-26.36|-1.07|9806042|2.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.611200|1.557100|1.613600|0.68|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.036730|0.034870|0.036670|0.54|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045330|0.045150|0.045320|0.41|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|601.370000|602.450000|601.370000|1.33|Y|Y/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-25T17:15:01+00:00, last15m_closed_end=2026-10-25T17:15+00:00, prior8high=1.687100, depth_time=2026-10-25T17:15:10+00:00, book20_bid_proxy_usdt=6127, book20_ask_proxy_usdt=12268, funding_indicative=-0.007910, next_funding_utc=2026-10-25T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.87%, turnover=12932745. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T17:15:01+00:00, last15m_closed_end=2026-10-25T17:15+00:00, prior8high=0.039980, depth_time=2026-10-25T17:15:08+00:00, book20_bid_proxy_usdt=44524, book20_ask_proxy_usdt=52072, funding_indicative=-0.000123, next_funding_utc=2026-10-25T18:00:00+00:00, funding_cycle_h=1, 24h_change=-4.44%, turnover=22118102. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T17:15:01+00:00, last15m_closed_end=2026-10-25T17:15+00:00, prior8high=0.046020, depth_time=2026-10-25T17:15:15+00:00, book20_bid_proxy_usdt=1064306, book20_ask_proxy_usdt=652968, funding_indicative=0.000047, next_funding_utc=2026-10-25T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.89%, turnover=9806042. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-25T17:15:01+00:00, last15m_closed_end=2026-10-25T17:15+00:00, prior8high=610.000000, depth_time=2026-10-25T17:15:12+00:00, book20_bid_proxy_usdt=9657, book20_ask_proxy_usdt=18894, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.96%, turnover=7123480. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
