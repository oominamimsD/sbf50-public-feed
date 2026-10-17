# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T19:45:13Z**
- feed_generated_utc: 2026-10-17T19:45:15+00:00
- source_sha256: `2b881c4babc697cb4f280399ded45307c05d9b7846a72b9fd69972ee210d3f32`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T19:45+00:00, close=81588.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T19:00+00:00, close=81466.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T16:00+00:00, close=81315.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DNA_USDT|0.253100|-6.98|UNKNOWN|-7.31|7179954|3.95|
|STRK_USDT|0.065310|-1.26|-30.09|-1.59|15473917|1.53|
|QNT_USDT|199.030000|-0.68|-18.80|-1.01|62222159|0.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DNA_USDT|0.253100|0.249000|0.253100|0.75|N|Y/Y|?|Y|N|
|QNT_USDT|199.030000|196.660000|199.030000|0.61|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.065310|0.064620|0.065310|0.91|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DNA_USDT: quote_utc=2026-10-17T19:44:59+00:00, last15m_closed_end=2026-10-17T19:45+00:00, prior8high=0.269400, depth_time=2026-10-17T19:45:08+00:00, book20_bid_proxy_usdt=68273, book20_ask_proxy_usdt=61096, funding_indicative=-0.001298, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.98%, turnover=7179954. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-17T19:44:59+00:00, last15m_closed_end=2026-10-17T19:45+00:00, prior8high=200.890000, depth_time=2026-10-17T19:45:12+00:00, book20_bid_proxy_usdt=59192, book20_ask_proxy_usdt=80588, funding_indicative=-0.000048, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.68%, turnover=62222159. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T19:44:59+00:00, last15m_closed_end=2026-10-17T19:45+00:00, prior8high=0.068240, depth_time=2026-10-17T19:45:10+00:00, book20_bid_proxy_usdt=224478, book20_ask_proxy_usdt=217514, funding_indicative=0.000050, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.26%, turnover=15473917. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
