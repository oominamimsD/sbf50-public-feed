# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T13:45:29Z**
- feed_generated_utc: 2026-11-08T13:45:31+00:00
- source_sha256: `4b8521ec50c0bcb6f79cb32c28e8ae44d7b41bc109b05e2a112839962b59c020`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T13:45+00:00, close=75900.3, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T13:00+00:00, close=75946.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T12:00+00:00, close=75944.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.005351|-10.56|-51.95|-10.79|28665048|1.86|
|IDOL_USDT|0.030334|-8.89|73.12|-9.12|15921682|3.31|
|ONE_USDT|0.001870|-8.19|59.25|-8.42|24820360|0.54|
|TIA_USDT|0.421500|-4.55|-13.99|-4.78|7170682|2.37|
|WLD_USDT|0.324700|-3.24|-19.70|-3.47|24426060|3.08|
|ENA_USDT|0.153930|-2.68|-20.65|-2.91|30394075|0.65|
|AAVE_USDT|129.540000|-2.03|-4.40|-2.26|9465385|0.77|
|LINK_USDT|10.719000|-1.15|-7.36|-1.38|63873187|0.93|
|ADA_USDT|0.179800|-0.99|-7.12|-1.22|10569954|5.56|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|129.540000|129.980000|129.540000|1.18|N|Y/Y|Y/N|Y|N|
|ADA_USDT|0.179800|0.179900|0.179800|5.58|Y|Y/Y|Y/Y|Y|Y|
|AKE_USDT|0.005351|0.005332|0.005351|0.38|N|Y/N|N/N|Y|N|
|ENA_USDT|0.153930|0.152800|0.153930|1.17|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.030334|0.027111|0.030334|0.71|N|Y/Y|N/N|Y|N|
|LINK_USDT|10.719000|10.706000|10.719000|1.38|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001870|0.001830|0.001869|0.84|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.421500|0.421400|0.421500|1.62|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.324700|0.324800|0.324700|2.45|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T13:45:02+00:00, last15m_closed_end=2026-11-08T13:45+00:00, prior8high=131.400000, depth_time=2026-11-08T13:45:19+00:00, book20_bid_proxy_usdt=455229, book20_ask_proxy_usdt=493092, funding_indicative=0.000069, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.03%, turnover=9465385. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T13:45:02+00:00, last15m_closed_end=2026-11-08T13:45+00:00, prior8high=0.181200, depth_time=2026-11-08T13:45:29+00:00, book20_bid_proxy_usdt=10594652, book20_ask_proxy_usdt=9270780, funding_indicative=-0.000041, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.99%, turnover=10569954. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-08T13:45:02+00:00, last15m_closed_end=2026-11-08T13:45+00:00, prior8high=0.005766, depth_time=2026-11-08T13:45:07+00:00, book20_bid_proxy_usdt=36045, book20_ask_proxy_usdt=30739, funding_indicative=0.000050, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.56%, turnover=28665048. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T13:45:02+00:00, last15m_closed_end=2026-11-08T13:45+00:00, prior8high=0.155690, depth_time=2026-11-08T13:45:19+00:00, book20_bid_proxy_usdt=285088, book20_ask_proxy_usdt=248356, funding_indicative=-0.000072, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.68%, turnover=30394075. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T13:45:02+00:00, last15m_closed_end=2026-11-08T13:45+00:00, prior8high=0.032257, depth_time=2026-11-08T13:45:10+00:00, book20_bid_proxy_usdt=7326, book20_ask_proxy_usdt=3356, funding_indicative=0.000846, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.89%, turnover=15921682. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T13:45:02+00:00, last15m_closed_end=2026-11-08T13:45+00:00, prior8high=10.794000, depth_time=2026-11-08T13:45:25+00:00, book20_bid_proxy_usdt=426142, book20_ask_proxy_usdt=411401, funding_indicative=-0.000002, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.15%, turnover=63873187. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T13:45:02+00:00, last15m_closed_end=2026-11-08T13:45+00:00, prior8high=0.001956, depth_time=2026-11-08T13:45:13+00:00, book20_bid_proxy_usdt=11726, book20_ask_proxy_usdt=12544, funding_indicative=-0.000691, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.19%, turnover=24820360. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T13:45:02+00:00, last15m_closed_end=2026-11-08T13:45+00:00, prior8high=0.427600, depth_time=2026-11-08T13:45:14+00:00, book20_bid_proxy_usdt=338646, book20_ask_proxy_usdt=367660, funding_indicative=-0.000049, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.55%, turnover=7170682. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T13:45:02+00:00, last15m_closed_end=2026-11-08T13:45+00:00, prior8high=0.329800, depth_time=2026-11-08T13:45:16+00:00, book20_bid_proxy_usdt=4425029, book20_ask_proxy_usdt=3878154, funding_indicative=-0.000082, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.24%, turnover=24426060. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
