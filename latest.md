# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T03:00:18Z**
- feed_generated_utc: 2026-10-26T03:00:21+00:00
- source_sha256: `1e48402f92e2a162323f074326fbd315e5082189daf0030b3e06ac5cdad1799d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T03:00+00:00, close=79535.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T03:00+00:00, close=79535.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T00:00+00:00, close=80114.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004060|-41.76|120.29|-40.44|10966701|7.40|
|T_USDT|0.004952|-8.00|5.31|-6.68|6921484|2.02|
|DASH_USDT|50.430000|-4.86|5.32|-3.54|13647853|1.98|
|WLD_USDT|0.443100|-2.95|-6.97|-1.63|72099173|2.26|
|PEPE_USDT|0.000004|-2.64|11.02|-1.32|69743667|0.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|50.430000|50.380000|50.430000|1.07|N|Y/Y|Y/N|Y|N|
|JCT_USDT|0.004060|0.004008|0.004074|2.60|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.48|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004952|0.004873|0.004954|0.23|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.443100|0.442000|0.443500|0.39|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-10-26T03:00:01+00:00, last15m_closed_end=2026-10-26T03:00+00:00, prior8high=51.660000, depth_time=2026-10-26T03:00:13+00:00, book20_bid_proxy_usdt=709084, book20_ask_proxy_usdt=734592, funding_indicative=0.000070, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.86%, turnover=13647853. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-26T03:00:01+00:00, last15m_closed_end=2026-10-26T03:00+00:00, prior8high=0.005942, depth_time=2026-10-26T03:00:08+00:00, book20_bid_proxy_usdt=19984, book20_ask_proxy_usdt=28438, funding_indicative=0.000050, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-41.76%, turnover=10966701. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T03:00:01+00:00, last15m_closed_end=2026-10-26T03:00+00:00, prior8high=0.000004, depth_time=2026-10-26T03:00:17+00:00, book20_bid_proxy_usdt=56289, book20_ask_proxy_usdt=54743, funding_indicative=0.000020, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.64%, turnover=69743667. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T03:00:01+00:00, last15m_closed_end=2026-10-26T03:00+00:00, prior8high=0.004964, depth_time=2026-10-26T03:00:09+00:00, book20_bid_proxy_usdt=58592, book20_ask_proxy_usdt=51482, funding_indicative=-0.001946, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=1, 24h_change=-8.00%, turnover=6921484. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T03:00:01+00:00, last15m_closed_end=2026-10-26T03:00+00:00, prior8high=0.449200, depth_time=2026-10-26T03:00:15+00:00, book20_bid_proxy_usdt=1857889, book20_ask_proxy_usdt=2303054, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.95%, turnover=72099173. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
