# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T00:00:17Z**
- feed_generated_utc: 2026-11-10T00:00:18+00:00
- source_sha256: `140cf6b4a0bda48eb7dd4bda506da0f9603952225e1ff3ac7e0614d0d93e81a2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T00:00+00:00, close=75327.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T00:00+00:00, close=75327.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-10T00:00+00:00, close=75327.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002862|-39.76|-47.98|-40.36|10633042|3.50|
|ON_USDT|0.171100|-14.02|0.94|-14.62|5346018|5.85|
|ZEC_USDT|1163.280000|-4.73|-7.24|-5.33|2387399818|0.09|
|DOT_USDT|0.856600|-3.29|-8.29|-3.89|10624178|1.17|
|QNT_USDT|194.700000|-2.61|-3.82|-3.21|39818702|0.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002862|0.003008|0.002864|11.81|Y|Y/Y|Y/Y|Y|Y|
|DOT_USDT|0.856600|0.853200|0.856600|0.24|N|Y/Y|Y/Y|Y|N|
|ON_USDT|0.171100|0.169200|0.171100|0.30|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.700000|193.880000|194.720000|1.47|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1163.280000|1153.000000|1163.280000|0.92|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T00:00:00+00:00, last15m_closed_end=2026-11-10T00:00+00:00, prior8high=0.005150, depth_time=2026-11-10T00:00:07+00:00, book20_bid_proxy_usdt=158497, book20_ask_proxy_usdt=12935, funding_indicative=-0.000654, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-39.76%, turnover=10633042. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T00:00:00+00:00, last15m_closed_end=2026-11-10T00:00+00:00, prior8high=0.864400, depth_time=2026-11-10T00:00:11+00:00, book20_bid_proxy_usdt=781929, book20_ask_proxy_usdt=549129, funding_indicative=0.000064, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.29%, turnover=10624178. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ON_USDT: quote_utc=2026-11-10T00:00:00+00:00, last15m_closed_end=2026-11-10T00:00+00:00, prior8high=0.178300, depth_time=2026-11-10T00:00:09+00:00, book20_bid_proxy_usdt=56866, book20_ask_proxy_usdt=66648, funding_indicative=0.000050, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.02%, turnover=5346018. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T00:00:00+00:00, last15m_closed_end=2026-11-10T00:00+00:00, prior8high=197.070000, depth_time=2026-11-10T00:00:15+00:00, book20_bid_proxy_usdt=82407, book20_ask_proxy_usdt=46071, funding_indicative=0.000100, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=39818702. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T00:00:00+00:00, last15m_closed_end=2026-11-10T00:00+00:00, prior8high=1184.660000, depth_time=2026-11-10T00:00:12+00:00, book20_bid_proxy_usdt=115814, book20_ask_proxy_usdt=340973, funding_indicative=0.000100, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.73%, turnover=2387399818. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
