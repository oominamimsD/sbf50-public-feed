# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T10:00:12Z**
- feed_generated_utc: 2026-10-16T10:00:13+00:00
- source_sha256: `902776b7a698cef96704ce6fa0288571ae8b9939df51a75c8a15a97fda1a2bfa`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T10:00+00:00, close=81985.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T10:00+00:00, close=81985.9, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T08:00+00:00, close=82258.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.078740|-18.28|30.88|-17.80|46764567|1.27|
|NIL_USDT|0.082700|-4.81|-4.49|-4.33|7489400|1.21|
|AKE_USDT|0.030113|-4.72|3.75|-4.24|21393449|1.66|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.030113|0.028483|0.030113|0.53|N|Y/Y|N/N|Y|N|
|NIL_USDT|0.082700|0.082610|0.082700|4.81|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.078740|0.077970|0.078740|0.43|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T09:59:59+00:00, last15m_closed_end=2026-10-16T10:00+00:00, prior8high=0.031827, depth_time=2026-10-16T10:00:11+00:00, book20_bid_proxy_usdt=17628, book20_ask_proxy_usdt=10149, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.72%, turnover=21393449. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T09:59:59+00:00, last15m_closed_end=2026-10-16T10:00+00:00, prior8high=0.084570, depth_time=2026-10-16T10:00:08+00:00, book20_bid_proxy_usdt=38545, book20_ask_proxy_usdt=16259, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.81%, turnover=7489400. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T09:59:59+00:00, last15m_closed_end=2026-10-16T10:00+00:00, prior8high=0.080920, depth_time=2026-10-16T10:00:06+00:00, book20_bid_proxy_usdt=257552, book20_ask_proxy_usdt=401825, funding_indicative=0.000042, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-18.28%, turnover=46764567. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
