# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T20:45:22Z**
- feed_generated_utc: 2026-11-08T20:45:24+00:00
- source_sha256: `b1c47b108f599bea58b9be9a6eefd5c6c3a81a18f6c73f5446de162060f743b3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T20:45+00:00, close=75803.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T20:00+00:00, close=75894.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T20:00+00:00, close=75894.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001711|-12.60|46.94|-12.30|15352719|0.58|
|AKE_USDT|0.005236|-2.25|-42.83|-1.95|17696516|3.82|
|NEAR_USDT|3.630000|-1.91|-16.18|-1.61|32904873|2.75|
|ARB_USDT|0.167290|-1.53|0.66|-1.23|18746418|1.20|
|TRUMPOFFICIAL_USDT|1.171000|-1.51|-31.75|-1.21|5206350|8.54|
|WLD_USDT|0.321100|-1.47|-18.85|-1.17|24831505|3.12|
|ZEC_USDT|1252.410000|-1.43|1.17|-1.13|1491273637|0.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005236|0.005112|0.005236|0.50|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.167290|0.166560|0.167290|0.59|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.630000|3.621000|3.630000|2.96|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001711|0.001721|0.001708|1.37|Y|Y/Y|N/N|Y|N|
|TRUMPOFFICIAL_USDT|1.171000|1.168000|1.172000|2.63|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.321100|0.320800|0.321000|1.19|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1252.410000|1253.520000|1252.420000|1.05|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-08T20:45:02+00:00, last15m_closed_end=2026-11-08T20:45+00:00, prior8high=0.005311, depth_time=2026-11-08T20:45:09+00:00, book20_bid_proxy_usdt=51932, book20_ask_proxy_usdt=46866, funding_indicative=0.000050, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.25%, turnover=17696516. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-08T20:45:02+00:00, last15m_closed_end=2026-11-08T20:45+00:00, prior8high=0.168430, depth_time=2026-11-08T20:45:14+00:00, book20_bid_proxy_usdt=111812, book20_ask_proxy_usdt=79886, funding_indicative=-0.000025, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=18746418. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-08T20:45:02+00:00, last15m_closed_end=2026-11-08T20:45+00:00, prior8high=3.666000, depth_time=2026-11-08T20:45:11+00:00, book20_bid_proxy_usdt=3180135, book20_ask_proxy_usdt=3659331, funding_indicative=0.000100, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=32904873. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T20:45:02+00:00, last15m_closed_end=2026-11-08T20:45+00:00, prior8high=0.001844, depth_time=2026-11-08T20:45:06+00:00, book20_bid_proxy_usdt=10935, book20_ask_proxy_usdt=10953, funding_indicative=-0.000200, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-12.60%, turnover=15352719. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-08T20:45:02+00:00, last15m_closed_end=2026-11-08T20:45+00:00, prior8high=1.179000, depth_time=2026-11-08T20:45:16+00:00, book20_bid_proxy_usdt=1682014, book20_ask_proxy_usdt=2026048, funding_indicative=-0.000110, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.51%, turnover=5206350. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T20:45:02+00:00, last15m_closed_end=2026-11-08T20:45+00:00, prior8high=0.327200, depth_time=2026-11-08T20:45:15+00:00, book20_bid_proxy_usdt=3780175, book20_ask_proxy_usdt=3403269, funding_indicative=-0.000035, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=24831505. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-08T20:45:02+00:00, last15m_closed_end=2026-11-08T20:45+00:00, prior8high=1269.150000, depth_time=2026-11-08T20:45:22+00:00, book20_bid_proxy_usdt=197223, book20_ask_proxy_usdt=222778, funding_indicative=0.000042, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=1491273637. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
