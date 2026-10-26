# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T18:30:14Z**
- feed_generated_utc: 2026-10-26T18:30:16+00:00
- source_sha256: `246d356b154c4d4cb1b9154fe59ed3fd3be287b1ea73a78a658241a163402b5c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T18:30+00:00, close=80224.9, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T18:00+00:00, close=80301.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-26T16:00+00:00, close=80399.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.026480|-3.98|115.63|-3.76|9872080|7.55|
|NEAR_USDT|4.503000|-1.53|-8.17|-1.31|121730057|2.22|
|WLD_USDT|0.438600|-1.43|-13.37|-1.21|72174421|2.28|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|IRYS_USDT|0.026480|0.026240|0.026470|1.18|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.503000|4.474000|4.503000|0.22|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.438600|0.435100|0.438900|0.46|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- IRYS_USDT: quote_utc=2026-10-26T18:30:02+00:00, last15m_closed_end=2026-10-26T18:30+00:00, prior8high=0.027470, depth_time=2026-10-26T18:30:08+00:00, book20_bid_proxy_usdt=106502, book20_ask_proxy_usdt=98788, funding_indicative=-0.000898, next_funding_utc=2026-10-26T19:00:00+00:00, funding_cycle_h=1, 24h_change=-3.98%, turnover=9872080. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T18:30:02+00:00, last15m_closed_end=2026-10-26T18:30+00:00, prior8high=4.569000, depth_time=2026-10-26T18:30:10+00:00, book20_bid_proxy_usdt=3803273, book20_ask_proxy_usdt=5431133, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=121730057. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T18:30:02+00:00, last15m_closed_end=2026-10-26T18:30+00:00, prior8high=0.445400, depth_time=2026-10-26T18:30:13+00:00, book20_bid_proxy_usdt=3180204, book20_ask_proxy_usdt=2399296, funding_indicative=-0.000133, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=72174421. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
