# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T23:45:16Z**
- feed_generated_utc: 2026-10-20T23:45:18+00:00
- source_sha256: `28f31ab37a6f66c3ab4d873c051500b0f6b64331f464d6d91edda8118d58a6de`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T23:45+00:00, close=82959, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T23:00+00:00, close=83059.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T20:00+00:00, close=82561, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.055769|-13.70|244.74|-14.15|7127161|3.58|
|BAT_USDT|0.194290|-9.95|9.53|-10.40|10087923|2.58|
|ARB_USDT|0.186990|-1.03|1.26|-1.48|85202051|0.54|
|DOT_USDT|1.148100|-0.82|-0.76|-1.27|12882990|0.87|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.055769|0.056252|0.055769|1.57|Y|Y/Y|Y/Y|N|Y|
|ARB_USDT|0.186990|0.187140|0.186990|2.05|Y|Y/Y|Y/Y|N|Y|
|BAT_USDT|0.194290|0.193360|0.194290|0.99|N|Y/Y|N/N|N|N|
|DOT_USDT|1.148100|1.144300|1.148100|0.38|N|Y/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T23:44:59+00:00, last15m_closed_end=2026-10-20T23:45+00:00, prior8high=0.059058, depth_time=2026-10-20T23:45:08+00:00, book20_bid_proxy_usdt=9236, book20_ask_proxy_usdt=12008, funding_indicative=0.000047, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-13.70%, turnover=7127161. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T23:44:59+00:00, last15m_closed_end=2026-10-20T23:45+00:00, prior8high=0.190710, depth_time=2026-10-20T23:45:13+00:00, book20_bid_proxy_usdt=87477, book20_ask_proxy_usdt=119349, funding_indicative=-0.000078, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.03%, turnover=85202051. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-20T23:45:00+00:00, last15m_closed_end=2026-10-20T23:45+00:00, prior8high=0.198600, depth_time=2026-10-20T23:45:09+00:00, book20_bid_proxy_usdt=21181, book20_ask_proxy_usdt=24467, funding_indicative=0.000040, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-9.95%, turnover=10087923. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-20T23:45:00+00:00, last15m_closed_end=2026-10-20T23:45+00:00, prior8high=1.166000, depth_time=2026-10-20T23:45:14+00:00, book20_bid_proxy_usdt=228649, book20_ask_proxy_usdt=411440, funding_indicative=0.000037, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.82%, turnover=12882990. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
