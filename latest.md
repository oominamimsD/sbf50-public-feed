# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T16:30:13Z**
- feed_generated_utc: 2026-10-15T16:30:14+00:00
- source_sha256: `722cde98914d28d20ebec95cebe1f9b6d51056d8f9aedfa5910a9a9e47fb627d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T16:30+00:00, close=82043.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-15T16:00+00:00, close=82375.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-15T16:00+00:00, close=82375.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WAL_USDT|0.051450|-3.47|54.55|-3.07|14071699|1.94|
|LIT_USDT|3.041000|-1.63|-15.09|-1.23|7365657|0.33|
|BTW_USDT|1.880600|-1.40|35.46|-1.00|30323840|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.880600|1.885400|1.881500|0.58|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.041000|2.976000|3.041000|0.98|N|N/Y|Y/Y|Y|N|
|WAL_USDT|0.051450|0.052900|0.051450|1.35|Y|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-15T16:29:59+00:00, last15m_closed_end=2026-10-15T16:30+00:00, prior8high=2.013500, depth_time=2026-10-15T16:30:12+00:00, book20_bid_proxy_usdt=11273, book20_ask_proxy_usdt=12042, funding_indicative=0.000050, next_funding_utc=2026-10-15T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.40%, turnover=30323840. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-15T16:29:59+00:00, last15m_closed_end=2026-10-15T16:30+00:00, prior8high=3.095900, depth_time=2026-10-15T16:30:09+00:00, book20_bid_proxy_usdt=29521, book20_ask_proxy_usdt=55876, funding_indicative=0.000050, next_funding_utc=2026-10-15T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.63%, turnover=7365657. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-15T16:29:59+00:00, last15m_closed_end=2026-10-15T16:30+00:00, prior8high=0.056770, depth_time=2026-10-15T16:30:08+00:00, book20_bid_proxy_usdt=137494, book20_ask_proxy_usdt=143294, funding_indicative=-0.000745, next_funding_utc=2026-10-15T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.47%, turnover=14071699. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
