# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T17:15:30Z**
- feed_generated_utc: 2026-11-10T17:15:31+00:00
- source_sha256: `fc97cf959e3f4d0524244db4bba0fba3ff52a6bef1e2ce33b1348c7f504dd3fe`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T17:15+00:00, close=72965.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T17:00+00:00, close=72844.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T16:00+00:00, close=73180.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.876100|-7.40|59.61|-7.11|9605284|5.33|
|ZEC_USDT|1014.250000|-7.23|-15.74|-6.94|2329768951|0.10|
|DASH_USDT|42.810000|-5.16|-7.21|-4.87|13555595|2.34|
|AKE_USDT|0.002795|-4.08|-32.74|-3.79|15536142|3.58|
|ARB_USDT|0.157190|-2.59|-1.68|-2.30|39423996|0.64|
|UNI_USDT|6.690000|-2.04|-9.01|-1.75|25720087|2.99|
|QNT_USDT|177.120000|-1.98|-9.36|-1.69|41139781|1.13|
|TIA_USDT|0.416600|-1.93|-4.40|-1.64|9487595|2.40|
|ONDO_USDT|0.358800|-1.91|-7.81|-1.62|15108651|2.79|
|NEAR_USDT|3.510000|-1.43|-9.04|-1.14|36310147|2.85|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002795|0.002637|0.002790|0.45|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.157190|0.156750|0.157160|1.03|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|42.810000|42.950000|42.810000|0.37|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.510000|3.469000|3.510000|1.17|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.358800|0.356600|0.358700|1.56|N|Y/Y|Y/N|Y|N|
|PIEVERSE_USDT|1.876100|1.817800|1.876100|1.09|N|Y/Y|N/N|Y|N|
|QNT_USDT|177.120000|177.330000|177.090000|2.50|Y|Y/Y|Y/Y|Y|Y|
|TIA_USDT|0.416600|0.414500|0.416100|2.86|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.690000|6.656000|6.690000|1.26|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1014.250000|993.710000|1013.500000|1.15|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T17:15:02+00:00, last15m_closed_end=2026-11-10T17:15+00:00, prior8high=0.003336, depth_time=2026-11-10T17:15:14+00:00, book20_bid_proxy_usdt=32311, book20_ask_proxy_usdt=29446, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.08%, turnover=15536142. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T17:15:02+00:00, last15m_closed_end=2026-11-10T17:15+00:00, prior8high=0.166600, depth_time=2026-11-10T17:15:14+00:00, book20_bid_proxy_usdt=67710, book20_ask_proxy_usdt=52519, funding_indicative=-0.000113, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.59%, turnover=39423996. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T17:14:59+00:00, last15m_closed_end=2026-11-10T17:15+00:00, prior8high=47.390000, depth_time=2026-11-10T17:15:12+00:00, book20_bid_proxy_usdt=533495, book20_ask_proxy_usdt=374736, funding_indicative=-0.000047, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.16%, turnover=13555595. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-10T17:15:02+00:00, last15m_closed_end=2026-11-10T17:15+00:00, prior8high=3.760000, depth_time=2026-11-10T17:15:29+00:00, book20_bid_proxy_usdt=3999465, book20_ask_proxy_usdt=1724927, funding_indicative=0.000100, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=36310147. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-10T17:15:02+00:00, last15m_closed_end=2026-11-10T17:15+00:00, prior8high=0.383600, depth_time=2026-11-10T17:15:27+00:00, book20_bid_proxy_usdt=1430699, book20_ask_proxy_usdt=2385079, funding_indicative=-0.000014, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.91%, turnover=15108651. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T17:15:02+00:00, last15m_closed_end=2026-11-10T17:15+00:00, prior8high=2.065500, depth_time=2026-11-10T17:15:07+00:00, book20_bid_proxy_usdt=14325, book20_ask_proxy_usdt=9108, funding_indicative=0.000246, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.40%, turnover=9605284. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T17:15:02+00:00, last15m_closed_end=2026-11-10T17:15+00:00, prior8high=186.060000, depth_time=2026-11-10T17:15:22+00:00, book20_bid_proxy_usdt=40282, book20_ask_proxy_usdt=85278, funding_indicative=-0.000090, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.98%, turnover=41139781. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-10T17:15:03+00:00, last15m_closed_end=2026-11-10T17:15+00:00, prior8high=0.438000, depth_time=2026-11-10T17:15:24+00:00, book20_bid_proxy_usdt=351592, book20_ask_proxy_usdt=421074, funding_indicative=0.000030, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.93%, turnover=9487595. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T17:15:02+00:00, last15m_closed_end=2026-11-10T17:15+00:00, prior8high=7.157000, depth_time=2026-11-10T17:15:18+00:00, book20_bid_proxy_usdt=1360836, book20_ask_proxy_usdt=1928070, funding_indicative=0.000069, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=25720087. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T17:15:02+00:00, last15m_closed_end=2026-11-10T17:15+00:00, prior8high=1198.440000, depth_time=2026-11-10T17:15:10+00:00, book20_bid_proxy_usdt=165518, book20_ask_proxy_usdt=187370, funding_indicative=-0.000010, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-7.23%, turnover=2329768951. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
