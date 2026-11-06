# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T03:45:28Z**
- feed_generated_utc: 2026-11-06T03:45:29+00:00
- source_sha256: `5e73501ca8a7b30e4b4b3446ca3f809fe933b0a100042b1f78ceaa4124cec4e5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T03:45+00:00, close=75864.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T03:00+00:00, close=76162.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T00:00+00:00, close=76050.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|FLUID_USDT|2.421000|-4.38|17.29|-4.20|6917445|8.26|
|XPL_USDT|0.056520|-3.51|-28.39|-3.33|12676684|1.77|
|JCT_USDT|0.002864|-3.37|-50.21|-3.19|12276078|3.49|
|ELSA_USDT|0.078500|-3.26|5.08|-3.08|6977821|3.82|
|XRP_USDT|1.206400|-3.06|-7.87|-2.88|428691715|0.83|
|ZRO_USDT|1.579200|-2.65|-10.49|-2.47|7200950|2.53|
|HYPE_USDT|77.291000|-1.79|-17.71|-1.61|86711938|0.13|
|QNT_USDT|189.330000|-1.29|-4.73|-1.11|39465893|0.53|
|BCH_USDT|275.610000|-1.25|-4.39|-1.07|7001679|2.54|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|275.610000|274.160000|275.610000|1.20|N|Y/Y|Y/Y|Y|N|
|ELSA_USDT|0.078500|0.077150|0.078500|0.26|N|Y/Y|N/N|Y|N|
|FLUID_USDT|2.421000|2.394000|2.421000|0.47|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.291000|77.240000|77.291000|1.79|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.002864|0.002706|0.002864|0.82|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|189.330000|189.420000|189.330000|0.31|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.056520|0.057010|0.056520|4.01|Y|Y/Y|Y/Y|Y|Y|
|XRP_USDT|1.206400|1.208700|1.206400|2.31|Y|Y/Y|Y/Y|Y|Y|
|ZRO_USDT|1.579200|1.593500|1.579200|1.41|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T03:44:59+00:00, last15m_closed_end=2026-11-06T03:45+00:00, prior8high=277.560000, depth_time=2026-11-06T03:45:27+00:00, book20_bid_proxy_usdt=49712, book20_ask_proxy_usdt=39875, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=7001679. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ELSA_USDT: quote_utc=2026-11-06T03:44:59+00:00, last15m_closed_end=2026-11-06T03:45+00:00, prior8high=0.082400, depth_time=2026-11-06T03:45:15+00:00, book20_bid_proxy_usdt=16385, book20_ask_proxy_usdt=19985, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.26%, turnover=6977821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T03:44:59+00:00, last15m_closed_end=2026-11-06T03:45+00:00, prior8high=2.468000, depth_time=2026-11-06T03:45:07+00:00, book20_bid_proxy_usdt=223257, book20_ask_proxy_usdt=129369, funding_indicative=0.000121, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.38%, turnover=6917445. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-06T03:44:59+00:00, last15m_closed_end=2026-11-06T03:45+00:00, prior8high=78.260000, depth_time=2026-11-06T03:45:21+00:00, book20_bid_proxy_usdt=156365, book20_ask_proxy_usdt=126330, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.79%, turnover=86711938. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-06T03:44:59+00:00, last15m_closed_end=2026-11-06T03:45+00:00, prior8high=0.003382, depth_time=2026-11-06T03:45:12+00:00, book20_bid_proxy_usdt=87912, book20_ask_proxy_usdt=107757, funding_indicative=0.000100, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.37%, turnover=12276078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T03:44:59+00:00, last15m_closed_end=2026-11-06T03:45+00:00, prior8high=191.530000, depth_time=2026-11-06T03:45:25+00:00, book20_bid_proxy_usdt=71558, book20_ask_proxy_usdt=49677, funding_indicative=-0.000001, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.29%, turnover=39465893. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T03:44:59+00:00, last15m_closed_end=2026-11-06T03:45+00:00, prior8high=0.058050, depth_time=2026-11-06T03:45:09+00:00, book20_bid_proxy_usdt=450493, book20_ask_proxy_usdt=432473, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.51%, turnover=12676684. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T03:44:59+00:00, last15m_closed_end=2026-11-06T03:45+00:00, prior8high=1.222500, depth_time=2026-11-06T03:45:17+00:00, book20_bid_proxy_usdt=3785034, book20_ask_proxy_usdt=4004617, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.06%, turnover=428691715. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-06T03:44:59+00:00, last15m_closed_end=2026-11-06T03:45+00:00, prior8high=1.616700, depth_time=2026-11-06T03:45:20+00:00, book20_bid_proxy_usdt=61086, book20_ask_proxy_usdt=36118, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.65%, turnover=7200950. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
