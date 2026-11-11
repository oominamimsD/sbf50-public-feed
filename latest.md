# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T08:15:33Z**
- feed_generated_utc: 2026-11-11T08:15:34+00:00
- source_sha256: `8ccdffb396da50fccd808e8a34696c1e2fd5bf9e2049d89356ff36fcbf8ac31d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T08:15+00:00, close=74093.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T08:00+00:00, close=74064.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-11T08:00+00:00, close=74064.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.203570|-18.87|51.37|-20.11|67249523|9.86|
|AKE_USDT|0.002590|-11.11|-37.68|-12.35|9118669|7.72|
|ONE_USDT|0.001599|-10.89|43.17|-12.13|12198160|0.62|
|ZEC_USDT|998.690000|-8.65|-17.03|-9.89|2161783122|0.10|
|UNI_USDT|6.465000|-5.34|-12.07|-6.58|39793283|1.55|
|DASH_USDT|44.200000|-2.08|-4.20|-3.32|16492977|2.26|
|ARB_USDT|0.159700|-1.04|-0.11|-2.28|29349295|0.63|
|QNT_USDT|179.300000|-0.77|-8.24|-2.01|46097952|1.12|
|VVV_USDT|19.130000|-0.56|-14.44|-1.80|5417458|0.52|
|DOT_USDT|0.840400|-0.15|-10.84|-1.39|8634588|1.19|
|HBAR_USDT|0.065730|-0.07|-6.14|-1.31|6392192|1.52|
|PEPE_USDT|0.000005|0.10|7.44|-1.14|76042013|0.19|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002590|0.002543|0.002590|0.87|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.159700|0.157280|0.159700|1.44|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|44.200000|43.260000|44.190000|0.86|N|Y/N|Y/Y|Y|N|
|DOT_USDT|0.840400|0.824500|0.840500|0.89|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.065730|0.064970|0.065730|5.03|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.203570|0.183320|0.203590|1.23|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001599|0.001605|0.001599|1.02|N|Y/Y|Y/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.44|N|Y/Y|N/N|Y|N|
|QNT_USDT|179.300000|177.180000|179.300000|0.82|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.465000|6.373000|6.465000|1.85|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.130000|18.851000|19.128000|0.98|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|998.690000|965.410000|998.730000|0.77|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T08:15:01+00:00, last15m_closed_end=2026-11-11T08:15+00:00, prior8high=0.002803, depth_time=2026-11-11T08:15:09+00:00, book20_bid_proxy_usdt=57965, book20_ask_proxy_usdt=45183, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.11%, turnover=9118669. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T08:15:01+00:00, last15m_closed_end=2026-11-11T08:15+00:00, prior8high=0.162500, depth_time=2026-11-11T08:15:19+00:00, book20_bid_proxy_usdt=62783, book20_ask_proxy_usdt=82070, funding_indicative=0.000005, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.04%, turnover=29349295. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T08:15:01+00:00, last15m_closed_end=2026-11-11T08:15+00:00, prior8high=45.030000, depth_time=2026-11-11T08:15:16+00:00, book20_bid_proxy_usdt=639248, book20_ask_proxy_usdt=583840, funding_indicative=-0.000084, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.08%, turnover=16492977. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-11T08:15:01+00:00, last15m_closed_end=2026-11-11T08:15+00:00, prior8high=0.845000, depth_time=2026-11-11T08:15:27+00:00, book20_bid_proxy_usdt=508398, book20_ask_proxy_usdt=738515, funding_indicative=0.000085, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.15%, turnover=8634588. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T08:15:01+00:00, last15m_closed_end=2026-11-11T08:15+00:00, prior8high=0.065870, depth_time=2026-11-11T08:15:29+00:00, book20_bid_proxy_usdt=559191, book20_ask_proxy_usdt=840336, funding_indicative=-0.000011, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.07%, turnover=6392192. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T08:15:01+00:00, last15m_closed_end=2026-11-11T08:15+00:00, prior8high=0.249740, depth_time=2026-11-11T08:15:07+00:00, book20_bid_proxy_usdt=13480, book20_ask_proxy_usdt=17200, funding_indicative=-0.005800, next_funding_utc=2026-11-11T09:00:00+00:00, funding_cycle_h=1, 24h_change=-18.87%, turnover=67249523. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T08:15:01+00:00, last15m_closed_end=2026-11-11T08:15+00:00, prior8high=0.001765, depth_time=2026-11-11T08:15:11+00:00, book20_bid_proxy_usdt=22952, book20_ask_proxy_usdt=16058, funding_indicative=-0.002676, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.89%, turnover=12198160. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T08:15:01+00:00, last15m_closed_end=2026-11-11T08:15+00:00, prior8high=0.000005, depth_time=2026-11-11T08:15:32+00:00, book20_bid_proxy_usdt=34132, book20_ask_proxy_usdt=28897, funding_indicative=-0.000055, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=0.10%, turnover=76042013. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T08:15:01+00:00, last15m_closed_end=2026-11-11T08:15+00:00, prior8high=180.560000, depth_time=2026-11-11T08:15:20+00:00, book20_bid_proxy_usdt=70509, book20_ask_proxy_usdt=96985, funding_indicative=-0.000091, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.77%, turnover=46097952. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T08:15:01+00:00, last15m_closed_end=2026-11-11T08:15+00:00, prior8high=6.675000, depth_time=2026-11-11T08:15:16+00:00, book20_bid_proxy_usdt=1394787, book20_ask_proxy_usdt=2631082, funding_indicative=0.000002, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.34%, turnover=39793283. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T08:15:01+00:00, last15m_closed_end=2026-11-11T08:15+00:00, prior8high=19.206000, depth_time=2026-11-11T08:15:25+00:00, book20_bid_proxy_usdt=16674, book20_ask_proxy_usdt=42204, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.56%, turnover=5417458. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T08:15:01+00:00, last15m_closed_end=2026-11-11T08:15+00:00, prior8high=1018.650000, depth_time=2026-11-11T08:15:14+00:00, book20_bid_proxy_usdt=1056920, book20_ask_proxy_usdt=169836, funding_indicative=0.000036, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.65%, turnover=2161783122. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
