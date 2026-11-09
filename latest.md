# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T10:30:35Z**
- feed_generated_utc: 2026-11-09T10:30:37+00:00
- source_sha256: `6ca3e9703527d01ee531617e9cd2fd493b82ce4534ebf4236667dc1bf759f97e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T10:30+00:00, close=74258, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T10:00+00:00, close=74254.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T08:00+00:00, close=73840.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001546|-21.05|32.74|-18.71|7643141|5.18|
|JCT_USDT|0.009036|-8.11|81.48|-5.77|73472152|2.22|
|ASTER_USDT|0.629500|-7.39|-9.99|-5.05|5464750|1.59|
|ETH_USDT|2107.330000|-5.96|-6.99|-3.62|1518858762|0.05|
|XRP_USDT|1.089200|-5.76|-12.85|-3.42|268148601|0.92|
|HYPE_USDT|73.066000|-5.63|-16.67|-3.29|47417956|0.14|
|ZEC_USDT|1206.930000|-5.01|-2.50|-2.67|2290092089|0.08|
|NEAR_USDT|3.524000|-4.78|-18.63|-2.44|44084236|2.84|
|TRUMPOFFICIAL_USDT|1.139000|-4.20|-33.62|-1.86|6645592|8.78|
|PUMPFUN_USDT|0.003588|-3.98|-14.93|-1.64|10435144|2.79|
|SOL_USDT|86.150000|-3.93|-9.08|-1.59|699433693|1.16|
|DOGE_USDT|0.068840|-3.50|-8.98|-1.16|72908257|1.45|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ASTER_USDT|0.629500|0.629500|0.629500|0.39|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.068840|0.068400|0.068840|0.21|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2107.330000|2094.080000|2107.330000|0.84|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.066000|72.750000|73.066000|0.98|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.009036|0.008121|0.009039|0.51|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.524000|3.472000|3.524000|0.58|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001546|0.001550|0.001545|1.28|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003588|0.003511|0.003588|0.53|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.150000|85.830000|86.140000|0.31|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.139000|1.126000|1.139000|1.34|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.089200|1.085100|1.089200|0.48|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1206.930000|1196.990000|1206.930000|0.58|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ASTER_USDT: quote_utc=2026-11-09T10:30:00+00:00, last15m_closed_end=2026-11-09T10:30+00:00, prior8high=0.637200, depth_time=2026-11-09T10:30:12+00:00, book20_bid_proxy_usdt=595957, book20_ask_proxy_usdt=597609, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.39%, turnover=5464750. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-09T10:30:00+00:00, last15m_closed_end=2026-11-09T10:30+00:00, prior8high=0.069600, depth_time=2026-11-09T10:30:34+00:00, book20_bid_proxy_usdt=4372346, book20_ask_proxy_usdt=4352167, funding_indicative=0.000018, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.50%, turnover=72908257. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T10:29:59+00:00, last15m_closed_end=2026-11-09T10:30+00:00, prior8high=2127.470000, depth_time=2026-11-09T10:30:12+00:00, book20_bid_proxy_usdt=1782373, book20_ask_proxy_usdt=3004217, funding_indicative=-0.000029, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.96%, turnover=1518858762. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T10:30:00+00:00, last15m_closed_end=2026-11-09T10:30+00:00, prior8high=74.219000, depth_time=2026-11-09T10:30:19+00:00, book20_bid_proxy_usdt=92635, book20_ask_proxy_usdt=74836, funding_indicative=0.000034, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.63%, turnover=47417956. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T10:29:59+00:00, last15m_closed_end=2026-11-09T10:30+00:00, prior8high=0.009792, depth_time=2026-11-09T10:30:10+00:00, book20_bid_proxy_usdt=47336, book20_ask_proxy_usdt=43620, funding_indicative=0.001343, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.11%, turnover=73472152. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T10:30:00+00:00, last15m_closed_end=2026-11-09T10:30+00:00, prior8high=3.578000, depth_time=2026-11-09T10:30:24+00:00, book20_bid_proxy_usdt=1825911, book20_ask_proxy_usdt=1874272, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.78%, turnover=44084236. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T10:30:00+00:00, last15m_closed_end=2026-11-09T10:30+00:00, prior8high=0.001610, depth_time=2026-11-09T10:30:07+00:00, book20_bid_proxy_usdt=13480, book20_ask_proxy_usdt=20352, funding_indicative=-0.000101, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-21.05%, turnover=7643141. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T10:30:00+00:00, last15m_closed_end=2026-11-09T10:30+00:00, prior8high=0.003597, depth_time=2026-11-09T10:30:29+00:00, book20_bid_proxy_usdt=2980823, book20_ask_proxy_usdt=1992192, funding_indicative=0.000045, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.98%, turnover=10435144. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T10:29:59+00:00, last15m_closed_end=2026-11-09T10:30+00:00, prior8high=87.260000, depth_time=2026-11-09T10:30:31+00:00, book20_bid_proxy_usdt=19921257, book20_ask_proxy_usdt=14675046, funding_indicative=0.000002, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.93%, turnover=699433693. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T10:30:00+00:00, last15m_closed_end=2026-11-09T10:30+00:00, prior8high=1.153000, depth_time=2026-11-09T10:30:24+00:00, book20_bid_proxy_usdt=2558379, book20_ask_proxy_usdt=2797834, funding_indicative=0.000048, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.20%, turnover=6645592. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T10:29:59+00:00, last15m_closed_end=2026-11-09T10:30+00:00, prior8high=1.101300, depth_time=2026-11-09T10:30:17+00:00, book20_bid_proxy_usdt=3886244, book20_ask_proxy_usdt=3777922, funding_indicative=0.000083, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.76%, turnover=268148601. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T10:29:59+00:00, last15m_closed_end=2026-11-09T10:30+00:00, prior8high=1233.140000, depth_time=2026-11-09T10:30:22+00:00, book20_bid_proxy_usdt=317444, book20_ask_proxy_usdt=195146, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.01%, turnover=2290092089. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
