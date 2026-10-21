# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T03:45:21Z**
- feed_generated_utc: 2026-10-21T03:45:24+00:00
- source_sha256: `231eec2d0061c6d1998737cf3f3cd16324a4467e4c8f1fce4ff8bbf1fe23ede9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1201; contracts: 1193; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T03:45+00:00, close=82725.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T03:00+00:00, close=82770, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T00:00+00:00, close=82984.8, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.185890|-13.84|4.79|-14.01|10548607|0.54|
|XMR_USDT|575.530000|-7.20|9.02|-7.37|20626191|0.17|
|BR_USDT|0.620280|-4.67|43.24|-4.84|35490480|7.74|
|Q_USDT|0.117162|-4.55|184.87|-4.72|5079934|0.85|
|AGT_USDT|0.062832|-2.78|288.40|-2.95|6973769|4.94|
|TIA_USDT|0.612400|-1.65|6.08|-1.82|48831207|3.27|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.062832|0.061376|0.062831|0.48|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.185890|0.185410|0.185890|1.26|N|Y/Y|N/N|N|N|
|BR_USDT|0.620280|0.613570|0.620660|0.88|N|Y/Y|N/N|N|N|
|Q_USDT|0.117162|0.116120|0.117162|0.82|N|Y/Y|N/N|N|N|
|TIA_USDT|0.612400|0.608800|0.612200|0.53|N|Y/Y|Y/Y|N|N|
|XMR_USDT|575.530000|574.120000|575.550000|0.98|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T03:45:01+00:00, last15m_closed_end=2026-10-21T03:45+00:00, prior8high=0.065605, depth_time=2026-10-21T03:45:17+00:00, book20_bid_proxy_usdt=9546, book20_ask_proxy_usdt=3463, funding_indicative=0.000047, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.78%, turnover=6973769. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T03:45:01+00:00, last15m_closed_end=2026-10-21T03:45+00:00, prior8high=0.191790, depth_time=2026-10-21T03:45:07+00:00, book20_bid_proxy_usdt=25336, book20_ask_proxy_usdt=21231, funding_indicative=0.000051, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-13.84%, turnover=10548607. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T03:45:01+00:00, last15m_closed_end=2026-10-21T03:45+00:00, prior8high=0.652610, depth_time=2026-10-21T03:45:13+00:00, book20_bid_proxy_usdt=2674, book20_ask_proxy_usdt=3292, funding_indicative=-0.000011, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.67%, turnover=35490480. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T03:45:01+00:00, last15m_closed_end=2026-10-21T03:45+00:00, prior8high=0.122549, depth_time=2026-10-21T03:45:15+00:00, book20_bid_proxy_usdt=13820, book20_ask_proxy_usdt=18883, funding_indicative=-0.000179, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.55%, turnover=5079934. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T03:45:01+00:00, last15m_closed_end=2026-10-21T03:45+00:00, prior8high=0.619700, depth_time=2026-10-21T03:45:21+00:00, book20_bid_proxy_usdt=190907, book20_ask_proxy_usdt=250239, funding_indicative=-0.000058, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.65%, turnover=48831207. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T03:45:01+00:00, last15m_closed_end=2026-10-21T03:45+00:00, prior8high=601.630000, depth_time=2026-10-21T03:45:11+00:00, book20_bid_proxy_usdt=9488, book20_ask_proxy_usdt=12182, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-7.20%, turnover=20626191. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
