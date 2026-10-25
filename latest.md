# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T04:30:18Z**
- feed_generated_utc: 2026-10-25T04:30:20+00:00
- source_sha256: `e1ab65b1b3cd13231c49bf977586acadae57bfd91007cc584b56b7bdf59a7cef`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T04:30+00:00, close=80844.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T04:00+00:00, close=80826.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T04:00+00:00, close=80826.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.058840|-12.70|90.11|-14.05|13582911|5.09|
|BIRB_USDT|0.089480|-8.37|84.41|-9.72|8521055|4.47|
|DOT_USDT|1.040600|0.14|-6.87|-1.21|11402179|0.96|
|STRK_USDT|0.046800|0.14|-29.25|-1.21|8470516|2.14|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.089480|0.072160|0.089140|1.15|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.040600|1.039200|1.040600|0.16|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.058840|0.050530|0.058910|0.70|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.046800|0.046250|0.046800|0.50|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T04:30:02+00:00, last15m_closed_end=2026-10-25T04:30+00:00, prior8high=0.091370, depth_time=2026-10-25T04:30:12+00:00, book20_bid_proxy_usdt=8180, book20_ask_proxy_usdt=12692, funding_indicative=-0.008699, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.37%, turnover=8521055. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T04:30:03+00:00, last15m_closed_end=2026-10-25T04:30+00:00, prior8high=1.048000, depth_time=2026-10-25T04:30:10+00:00, book20_bid_proxy_usdt=367140, book20_ask_proxy_usdt=274451, funding_indicative=-0.000126, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=0.14%, turnover=11402179. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T04:30:02+00:00, last15m_closed_end=2026-10-25T04:30+00:00, prior8high=0.060410, depth_time=2026-10-25T04:30:09+00:00, book20_bid_proxy_usdt=52104, book20_ask_proxy_usdt=62873, funding_indicative=-0.001120, next_funding_utc=2026-10-25T05:00:00+00:00, funding_cycle_h=1, 24h_change=-12.70%, turnover=13582911. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T04:30:03+00:00, last15m_closed_end=2026-10-25T04:30+00:00, prior8high=0.047120, depth_time=2026-10-25T04:30:16+00:00, book20_bid_proxy_usdt=966761, book20_ask_proxy_usdt=607034, funding_indicative=0.000050, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=0.14%, turnover=8470516. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
