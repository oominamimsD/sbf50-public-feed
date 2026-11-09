# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T09:30:27Z**
- feed_generated_utc: 2026-11-09T09:30:29+00:00
- source_sha256: `295f2457155a1c1de41ba2d0f0b0a8c5d7a422ebe22226cd4101a08154c225fc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T09:30+00:00, close=74279.4, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T09:00+00:00, close=74524.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T08:00+00:00, close=73840.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001574|-19.62|35.14|-17.31|8123456|0.64|
|ASTER_USDT|0.634300|-6.69|-9.30|-4.38|5434220|1.58|
|ETH_USDT|2109.810000|-5.85|-6.88|-3.54|1502741513|0.05|
|XRP_USDT|1.094200|-5.32|-12.45|-3.01|262412391|1.83|
|HYPE_USDT|73.540000|-5.02|-16.13|-2.71|46946299|0.14|
|JCT_USDT|0.009386|-4.55|88.51|-2.24|73410815|1.07|
|NEAR_USDT|3.539000|-4.37|-18.28|-2.06|43635648|2.83|
|PUMPFUN_USDT|0.003574|-4.36|-15.26|-2.05|10390701|2.80|
|ZEC_USDT|1217.220000|-4.20|-1.67|-1.89|2275783553|1.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ASTER_USDT|0.634300|0.624900|0.634300|0.80|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2109.810000|2082.230000|2109.800000|1.63|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.540000|72.442000|73.540000|1.73|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.009386|0.007376|0.009386|1.12|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.539000|3.460000|3.539000|1.39|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001574|0.001562|0.001574|1.13|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003574|0.003485|0.003574|1.26|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.094200|1.082500|1.094200|0.65|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1217.220000|1185.330000|1217.470000|0.75|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ASTER_USDT: quote_utc=2026-11-09T09:30:01+00:00, last15m_closed_end=2026-11-09T09:30+00:00, prior8high=0.637200, depth_time=2026-11-09T09:30:09+00:00, book20_bid_proxy_usdt=684955, book20_ask_proxy_usdt=574441, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.69%, turnover=5434220. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T09:30:01+00:00, last15m_closed_end=2026-11-09T09:30+00:00, prior8high=2127.470000, depth_time=2026-11-09T09:30:11+00:00, book20_bid_proxy_usdt=6701748, book20_ask_proxy_usdt=4768240, funding_indicative=-0.000038, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.85%, turnover=1502741513. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T09:30:01+00:00, last15m_closed_end=2026-11-09T09:30+00:00, prior8high=74.219000, depth_time=2026-11-09T09:30:16+00:00, book20_bid_proxy_usdt=69426, book20_ask_proxy_usdt=104715, funding_indicative=0.000034, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.02%, turnover=46946299. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T09:30:01+00:00, last15m_closed_end=2026-11-09T09:30+00:00, prior8high=0.009371, depth_time=2026-11-09T09:30:19+00:00, book20_bid_proxy_usdt=15240, book20_ask_proxy_usdt=21572, funding_indicative=0.001254, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.55%, turnover=73410815. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T09:30:01+00:00, last15m_closed_end=2026-11-09T09:30+00:00, prior8high=3.578000, depth_time=2026-11-09T09:30:21+00:00, book20_bid_proxy_usdt=1342722, book20_ask_proxy_usdt=1644952, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.37%, turnover=43635648. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T09:30:01+00:00, last15m_closed_end=2026-11-09T09:30+00:00, prior8high=0.001622, depth_time=2026-11-09T09:30:07+00:00, book20_bid_proxy_usdt=9322, book20_ask_proxy_usdt=16887, funding_indicative=-0.000096, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-19.62%, turnover=8123456. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T09:30:01+00:00, last15m_closed_end=2026-11-09T09:30+00:00, prior8high=0.003597, depth_time=2026-11-09T09:30:24+00:00, book20_bid_proxy_usdt=2348105, book20_ask_proxy_usdt=3388002, funding_indicative=0.000035, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.36%, turnover=10390701. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T09:30:01+00:00, last15m_closed_end=2026-11-09T09:30+00:00, prior8high=1.101300, depth_time=2026-11-09T09:30:12+00:00, book20_bid_proxy_usdt=4302954, book20_ask_proxy_usdt=3444553, funding_indicative=0.000068, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.32%, turnover=262412391. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T09:30:01+00:00, last15m_closed_end=2026-11-09T09:30+00:00, prior8high=1233.140000, depth_time=2026-11-09T09:30:26+00:00, book20_bid_proxy_usdt=101971, book20_ask_proxy_usdt=380512, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.20%, turnover=2275783553. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
