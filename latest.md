# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T23:45:15Z**
- feed_generated_utc: 2026-11-09T23:45:16+00:00
- source_sha256: `9f2a5a64a0e6ff78f68514065c51bf8ba6acd7d37153ac43a3d740e33e93a5bd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T23:45+00:00, close=75173.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T23:00+00:00, close=75256.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-09T20:00+00:00, close=74856.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003101|-36.67|-43.63|-36.24|10477903|9.69|
|ZEC_USDT|1154.350000|-5.82|-7.95|-5.39|2513497976|0.09|
|DOT_USDT|0.854700|-4.06|-8.50|-3.63|11404194|1.17|
|QNT_USDT|194.200000|-2.91|-4.07|-2.48|42242500|1.54|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003101|0.003127|0.003095|12.60|Y|N/N|Y/N|Y|N|
|DOT_USDT|0.854700|0.853200|0.854700|0.53|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.200000|193.880000|194.150000|1.19|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1154.350000|1153.000000|1154.350000|1.05|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T23:45:00+00:00, last15m_closed_end=2026-11-09T23:45+00:00, prior8high=0.005150, depth_time=2026-11-09T23:45:07+00:00, book20_bid_proxy_usdt=9038, book20_ask_proxy_usdt=9582, funding_indicative=-0.000199, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=4, 24h_change=-36.67%, turnover=10477903. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-09T23:45:00+00:00, last15m_closed_end=2026-11-09T23:45+00:00, prior8high=0.864800, depth_time=2026-11-09T23:45:12+00:00, book20_bid_proxy_usdt=667274, book20_ask_proxy_usdt=878227, funding_indicative=0.000068, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.06%, turnover=11404194. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-09T23:45:00+00:00, last15m_closed_end=2026-11-09T23:45+00:00, prior8high=197.070000, depth_time=2026-11-09T23:45:14+00:00, book20_bid_proxy_usdt=88010, book20_ask_proxy_usdt=102413, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=42242500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T23:45:00+00:00, last15m_closed_end=2026-11-09T23:45+00:00, prior8high=1184.660000, depth_time=2026-11-09T23:45:09+00:00, book20_bid_proxy_usdt=255686, book20_ask_proxy_usdt=182266, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.82%, turnover=2513497976. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
