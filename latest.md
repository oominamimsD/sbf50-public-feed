# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T02:15:18Z**
- feed_generated_utc: 2026-10-25T02:15:20+00:00
- source_sha256: `7f227f9426e79bcecbbf65bb4e7125b1196ea7395e6218522bfce33bad20356f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T02:15+00:00, close=80825.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T02:00+00:00, close=80872.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T00:00+00:00, close=80845, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.074880|-23.32|54.32|-24.65|9562479|1.34|
|IRYS_USDT|0.036190|-21.41|183.62|-22.74|32439639|2.77|
|ORDER_USDT|0.052980|-21.39|71.17|-22.72|13381327|1.89|
|STRK_USDT|0.046470|-0.55|-29.75|-1.88|8220394|2.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.074880|0.069260|0.074880|1.47|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.036190|0.031610|0.036140|1.86|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.052980|0.050660|0.052980|0.77|N|Y/N|N/N|Y|N|
|STRK_USDT|0.046470|0.046420|0.046470|0.72|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T02:15:01+00:00, last15m_closed_end=2026-10-25T02:15+00:00, prior8high=0.100590, depth_time=2026-10-25T02:15:08+00:00, book20_bid_proxy_usdt=9304, book20_ask_proxy_usdt=6770, funding_indicative=-0.016381, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=-23.32%, turnover=9562479. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T02:15:00+00:00, last15m_closed_end=2026-10-25T02:15+00:00, prior8high=0.047160, depth_time=2026-10-25T02:15:11+00:00, book20_bid_proxy_usdt=36990, book20_ask_proxy_usdt=26446, funding_indicative=0.000012, next_funding_utc=2026-10-25T03:00:00+00:00, funding_cycle_h=1, 24h_change=-21.41%, turnover=32439639. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T02:15:01+00:00, last15m_closed_end=2026-10-25T02:15+00:00, prior8high=0.073400, depth_time=2026-10-25T02:15:12+00:00, book20_bid_proxy_usdt=61666, book20_ask_proxy_usdt=70848, funding_indicative=-0.001436, next_funding_utc=2026-10-25T03:00:00+00:00, funding_cycle_h=1, 24h_change=-21.39%, turnover=13381327. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T02:15:01+00:00, last15m_closed_end=2026-10-25T02:15+00:00, prior8high=0.047560, depth_time=2026-10-25T02:15:17+00:00, book20_bid_proxy_usdt=971862, book20_ask_proxy_usdt=688831, funding_indicative=0.000050, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.55%, turnover=8220394. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
