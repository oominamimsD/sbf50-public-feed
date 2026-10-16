# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T03:45:21Z**
- feed_generated_utc: 2026-10-16T03:45:23+00:00
- source_sha256: `c665b2e0a2eb9d1eae0dbc425f5baf173685da34c9aa7ba7492b6dcd8a9ad9d2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T03:45+00:00, close=81861.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T03:00+00:00, close=82016.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T00:00+00:00, close=82195.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WAL_USDT|0.045350|-14.91|36.22|-14.28|5549461|4.41|
|ZEREBRO_USDT|0.044830|-12.60|63.27|-11.97|7044755|6.69|
|ZKSYNC_USDT|0.016586|-5.96|49.14|-5.33|7934728|0.60|
|AKE_USDT|0.030567|-3.28|5.31|-2.65|20402688|2.29|
|NIL_USDT|0.084980|-2.18|-1.85|-1.55|10566329|5.89|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.030567|0.030214|0.030555|0.73|N|Y/N|N/N|Y|N|
|NIL_USDT|0.084980|0.085120|0.084980|3.70|Y|N/N|N/N|Y|N|
|WAL_USDT|0.045350|0.044820|0.045350|0.65|N|Y/Y|N/N|Y|N|
|ZEREBRO_USDT|0.044830|0.044099|0.044830|3.53|N|N/N|N/N|Y|N|
|ZKSYNC_USDT|0.016586|0.016384|0.016586|1.48|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T03:44:59+00:00, last15m_closed_end=2026-10-16T03:45+00:00, prior8high=0.032245, depth_time=2026-10-16T03:45:17+00:00, book20_bid_proxy_usdt=11328, book20_ask_proxy_usdt=17866, funding_indicative=0.000099, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.28%, turnover=20402688. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T03:44:59+00:00, last15m_closed_end=2026-10-16T03:45+00:00, prior8high=0.088420, depth_time=2026-10-16T03:45:20+00:00, book20_bid_proxy_usdt=14564, book20_ask_proxy_usdt=18550, funding_indicative=0.000050, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.18%, turnover=10566329. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-16T03:44:59+00:00, last15m_closed_end=2026-10-16T03:45+00:00, prior8high=0.051020, depth_time=2026-10-16T03:45:10+00:00, book20_bid_proxy_usdt=138690, book20_ask_proxy_usdt=117444, funding_indicative=-0.000554, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.91%, turnover=5549461. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEREBRO_USDT: quote_utc=2026-10-16T03:44:59+00:00, last15m_closed_end=2026-10-16T03:45+00:00, prior8high=0.059435, depth_time=2026-10-16T03:45:12+00:00, book20_bid_proxy_usdt=10332, book20_ask_proxy_usdt=34907, funding_indicative=0.000051, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.60%, turnover=7044755. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZKSYNC_USDT: quote_utc=2026-10-16T03:44:59+00:00, last15m_closed_end=2026-10-16T03:45+00:00, prior8high=0.016741, depth_time=2026-10-16T03:45:15+00:00, book20_bid_proxy_usdt=7976, book20_ask_proxy_usdt=7866, funding_indicative=0.000050, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.96%, turnover=7934728. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
