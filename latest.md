# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T02:45:28Z**
- feed_generated_utc: 2026-11-08T02:45:30+00:00
- source_sha256: `9b9cf8d6e93c48bbea59cdeeb4e3cb4758084bc21bee615a3c274e9d85f97e29`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T02:45+00:00, close=75660.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T02:00+00:00, close=75713.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T00:00+00:00, close=75836.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.005111|-14.57|-54.11|-14.49|50277077|3.91|
|AIN_USDT|0.141950|-8.87|-38.85|-8.79|9582415|2.11|
|ONE_USDT|0.001919|-5.77|63.44|-5.69|26833608|0.52|
|QNT_USDT|193.630000|-2.62|-3.69|-2.54|43396940|0.52|
|ENA_USDT|0.154260|-2.47|-20.48|-2.39|28171373|0.65|
|WLD_USDT|0.329500|-1.81|-18.52|-1.73|25649104|3.03|
|PEPE_USDT|0.000005|-1.50|-3.18|-1.42|39185901|1.87|
|ZEC_USDT|1239.510000|-1.45|-3.50|-1.37|1811031913|0.65|
|TIA_USDT|0.435400|-1.40|-11.16|-1.32|7113030|2.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AIN_USDT|0.141950|0.142030|0.141950|0.97|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.005111|0.004987|0.005111|1.19|N|Y/N|N/N|Y|N|
|ENA_USDT|0.154260|0.155050|0.154260|2.68|Y|Y/Y|Y/Y|Y|Y|
|ONE_USDT|0.001919|0.001939|0.001918|1.23|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.68|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|193.630000|193.700000|193.630000|0.57|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.435400|0.435200|0.435400|1.35|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.329500|0.329600|0.329500|0.60|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1239.510000|1238.450000|1239.440000|1.03|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AIN_USDT: quote_utc=2026-11-08T02:44:59+00:00, last15m_closed_end=2026-11-08T02:45+00:00, prior8high=0.146520, depth_time=2026-11-08T02:45:09+00:00, book20_bid_proxy_usdt=6902, book20_ask_proxy_usdt=10159, funding_indicative=0.000277, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.87%, turnover=9582415. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-08T02:44:59+00:00, last15m_closed_end=2026-11-08T02:45+00:00, prior8high=0.005856, depth_time=2026-11-08T02:45:07+00:00, book20_bid_proxy_usdt=38674, book20_ask_proxy_usdt=43069, funding_indicative=-0.000081, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.57%, turnover=50277077. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T02:44:59+00:00, last15m_closed_end=2026-11-08T02:45+00:00, prior8high=0.157740, depth_time=2026-11-08T02:45:17+00:00, book20_bid_proxy_usdt=111601, book20_ask_proxy_usdt=205992, funding_indicative=-0.000055, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.47%, turnover=28171373. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T02:44:59+00:00, last15m_closed_end=2026-11-08T02:45+00:00, prior8high=0.002107, depth_time=2026-11-08T02:45:12+00:00, book20_bid_proxy_usdt=13820, book20_ask_proxy_usdt=7746, funding_indicative=-0.000088, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.77%, turnover=26833608. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-08T02:44:59+00:00, last15m_closed_end=2026-11-08T02:45+00:00, prior8high=0.000005, depth_time=2026-11-08T02:45:22+00:00, book20_bid_proxy_usdt=39788, book20_ask_proxy_usdt=54976, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.50%, turnover=39185901. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T02:44:59+00:00, last15m_closed_end=2026-11-08T02:45+00:00, prior8high=195.930000, depth_time=2026-11-08T02:45:13+00:00, book20_bid_proxy_usdt=56343, book20_ask_proxy_usdt=112078, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.62%, turnover=43396940. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T02:44:59+00:00, last15m_closed_end=2026-11-08T02:45+00:00, prior8high=0.438900, depth_time=2026-11-08T02:45:27+00:00, book20_bid_proxy_usdt=293788, book20_ask_proxy_usdt=244978, funding_indicative=0.000013, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.40%, turnover=7113030. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T02:44:59+00:00, last15m_closed_end=2026-11-08T02:45+00:00, prior8high=0.332600, depth_time=2026-11-08T02:45:19+00:00, book20_bid_proxy_usdt=3950186, book20_ask_proxy_usdt=3381494, funding_indicative=-0.000107, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=25649104. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-08T02:44:59+00:00, last15m_closed_end=2026-11-08T02:45+00:00, prior8high=1258.450000, depth_time=2026-11-08T02:45:25+00:00, book20_bid_proxy_usdt=145211, book20_ask_proxy_usdt=257436, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.45%, turnover=1811031913. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
