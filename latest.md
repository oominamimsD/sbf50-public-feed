# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T17:30:18Z**
- feed_generated_utc: 2026-10-17T17:30:19+00:00
- source_sha256: `a748c7953498af6ada1347a79751ef487582ea96b53f193afead2b50da514489`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T17:30+00:00, close=81235, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T17:00+00:00, close=81226.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T16:00+00:00, close=81315.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EIGEN_USDT|0.249800|-2.53|6.02|-2.44|9377713|4.00|
|FILECOIN_USDT|1.064900|-2.06|-5.57|-1.97|25890634|3.75|
|QNT_USDT|197.280000|-1.56|-19.52|-1.47|64360122|1.01|
|ZEC_USDT|1124.540000|-1.47|-8.70|-1.38|1157769884|0.09|
|ARB_USDT|0.181220|-1.46|-2.91|-1.37|29345881|0.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.181220|0.180230|0.181220|0.23|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.249800|0.248300|0.249800|1.39|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|1.064900|1.066200|1.064900|1.20|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|197.280000|195.160000|197.260000|0.55|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1124.540000|1111.380000|1124.070000|1.36|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-17T17:30:01+00:00, last15m_closed_end=2026-10-17T17:30+00:00, prior8high=0.185920, depth_time=2026-10-17T17:30:16+00:00, book20_bid_proxy_usdt=87013, book20_ask_proxy_usdt=90122, funding_indicative=-0.000029, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.46%, turnover=29345881. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-17T17:30:01+00:00, last15m_closed_end=2026-10-17T17:30+00:00, prior8high=0.259200, depth_time=2026-10-17T17:30:07+00:00, book20_bid_proxy_usdt=663596, book20_ask_proxy_usdt=434185, funding_indicative=0.000050, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.53%, turnover=9377713. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T17:30:01+00:00, last15m_closed_end=2026-10-17T17:30+00:00, prior8high=1.102800, depth_time=2026-10-17T17:30:09+00:00, book20_bid_proxy_usdt=276472, book20_ask_proxy_usdt=749081, funding_indicative=-0.000067, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.06%, turnover=25890634. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-17T17:30:01+00:00, last15m_closed_end=2026-10-17T17:30+00:00, prior8high=202.040000, depth_time=2026-10-17T17:30:12+00:00, book20_bid_proxy_usdt=72653, book20_ask_proxy_usdt=60827, funding_indicative=-0.000097, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.56%, turnover=64360122. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T17:30:01+00:00, last15m_closed_end=2026-10-17T17:30+00:00, prior8high=1164.590000, depth_time=2026-10-17T17:30:15+00:00, book20_bid_proxy_usdt=610151, book20_ask_proxy_usdt=89992, funding_indicative=0.000064, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=1157769884. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
