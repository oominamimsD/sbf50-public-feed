# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T03:15:13Z**
- feed_generated_utc: 2026-10-16T03:15:15+00:00
- source_sha256: `701d2ead3500b0d8bd31095d7559a26f00b87358f18cce504220d8b7ac044c54`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T03:15+00:00, close=82147.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T03:00+00:00, close=82016.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T00:00+00:00, close=82195.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WAL_USDT|0.046020|-13.65|38.23|-13.38|5535591|2.17|
|AKE_USDT|0.030749|-2.70|5.94|-2.43|20298688|1.63|
|BTW_USDT|1.858100|-2.58|33.83|-2.31|21739691|0.54|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.030749|0.030965|0.030742|1.93|Y|Y/N|N/N|Y|N|
|BTW_USDT|1.858100|1.800900|1.858200|3.44|N|N/Y|Y/Y|Y|N|
|WAL_USDT|0.046020|0.044820|0.046020|1.09|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T03:15:02+00:00, last15m_closed_end=2026-10-16T03:15+00:00, prior8high=0.032381, depth_time=2026-10-16T03:15:10+00:00, book20_bid_proxy_usdt=17896, book20_ask_proxy_usdt=12125, funding_indicative=0.000111, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.70%, turnover=20298688. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-16T03:15:02+00:00, last15m_closed_end=2026-10-16T03:15+00:00, prior8high=1.973100, depth_time=2026-10-16T03:15:13+00:00, book20_bid_proxy_usdt=8735, book20_ask_proxy_usdt=10798, funding_indicative=0.000050, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.58%, turnover=21739691. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-16T03:15:02+00:00, last15m_closed_end=2026-10-16T03:15+00:00, prior8high=0.051850, depth_time=2026-10-16T03:15:07+00:00, book20_bid_proxy_usdt=145631, book20_ask_proxy_usdt=173567, funding_indicative=-0.000597, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-13.65%, turnover=5535591. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
