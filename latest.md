# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T00:00:19Z**
- feed_generated_utc: 2026-10-26T00:00:22+00:00
- source_sha256: `7a2354d14ad898a4b6f03f87fa5a923b425a76009e7dc0fb0c45337fa83f96aa`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T00:00+00:00, close=80114.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T00:00+00:00, close=80114.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T00:00+00:00, close=80114.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.006124|-11.31|232.28|-10.71|9941671|1.63|
|PEPE_USDT|0.000004|-2.91|11.50|-2.31|74624778|0.47|
|DASH_USDT|51.630000|-2.60|7.83|-2.00|13763219|3.87|
|T_USDT|0.005248|-2.50|11.61|-1.90|8624547|9.53|
|XMR_USDT|594.490000|-2.10|2.05|-1.50|6553189|1.01|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|51.630000|50.870000|51.630000|0.40|N|Y/Y|Y/N|Y|N|
|JCT_USDT|0.006124|0.006069|0.006124|1.10|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|1.16|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.005248|0.005155|0.005248|0.71|N|Y/Y|N/N|Y|N|
|XMR_USDT|594.490000|589.580000|594.290000|0.60|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-10-26T00:00:01+00:00, last15m_closed_end=2026-10-26T00:00+00:00, prior8high=51.970000, depth_time=2026-10-26T00:00:13+00:00, book20_bid_proxy_usdt=858856, book20_ask_proxy_usdt=504034, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.60%, turnover=13763219. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-26T00:00:01+00:00, last15m_closed_end=2026-10-26T00:00+00:00, prior8high=0.006991, depth_time=2026-10-26T00:00:08+00:00, book20_bid_proxy_usdt=58775, book20_ask_proxy_usdt=28928, funding_indicative=0.000050, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.31%, turnover=9941671. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T00:00:01+00:00, last15m_closed_end=2026-10-26T00:00+00:00, prior8high=0.000004, depth_time=2026-10-26T00:00:10+00:00, book20_bid_proxy_usdt=34702, book20_ask_proxy_usdt=37033, funding_indicative=0.000045, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=74624778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T00:00:01+00:00, last15m_closed_end=2026-10-26T00:00+00:00, prior8high=0.005411, depth_time=2026-10-26T00:00:15+00:00, book20_bid_proxy_usdt=58148, book20_ask_proxy_usdt=89418, funding_indicative=-0.005181, next_funding_utc=2026-10-26T01:00:00+00:00, funding_cycle_h=1, 24h_change=-2.50%, turnover=8624547. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T00:00:01+00:00, last15m_closed_end=2026-10-26T00:00+00:00, prior8high=600.790000, depth_time=2026-10-26T00:00:18+00:00, book20_bid_proxy_usdt=17307, book20_ask_proxy_usdt=24144, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=6553189. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
