# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T01:45:41Z**
- feed_generated_utc: 2026-10-17T01:45:44+00:00
- source_sha256: `0ddca87435c237d07cbd9fe2ae88197b3b3f4962f11d07782effc04229e914c0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T01:45+00:00, close=81505.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T01:00+00:00, close=81532.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T00:00+00:00, close=81578.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.958200|-6.81|-3.85|-7.03|16390224|0.51|
|RIVER_USDT|1.084000|-3.73|-8.29|-3.95|5488895|9.22|
|ZEC_USDT|1146.350000|-3.50|-5.91|-3.72|1385199398|0.09|
|ARB_USDT|0.188870|-3.11|4.46|-3.33|31774715|0.53|
|INJ_USDT|8.713000|-2.95|25.74|-3.17|115218448|1.15|
|FILECOIN_USDT|1.135400|-2.69|6.11|-2.91|23247387|0.88|
|APT_USDT|0.834100|-2.56|4.19|-2.78|12549834|1.20|
|TAO_USDT|274.070000|-2.33|-0.21|-2.55|81656549|1.09|
|FET_USDT|0.195100|-2.25|-10.09|-2.47|11505547|5.13|
|SUI_USDT|1.002000|-1.81|-5.25|-2.03|99064868|1.00|
|ONDO_USDT|0.449400|-1.68|-6.39|-1.90|28919796|2.23|
|STRK_USDT|0.072720|-1.66|-3.43|-1.88|21265955|4.12|
|AVAX_USDT|9.918000|-1.63|-2.68|-1.85|126060220|1.01|
|AAVE_USDT|154.810000|-1.57|-8.84|-1.79|31345536|0.65|
|ICP_USDT|2.992000|-1.51|-0.89|-1.73|8910120|3.34|
|ENA_USDT|0.196960|-1.48|-8.63|-1.70|41007821|0.51|
|FARTCOIN_USDT|0.152800|-1.24|-6.46|-1.46|7195492|0.66|
|SEI_USDT|0.063680|-0.96|-2.74|-1.18|18516196|1.57|
|QNT_USDT|199.760000|-0.88|-19.91|-1.10|67251926|0.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.810000|153.940000|154.810000|1.09|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.834100|0.835700|0.834300|0.79|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.188870|0.188800|0.188870|1.75|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.918000|9.893000|9.918000|1.00|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.195100|0.195400|0.195100|4.85|Y|Y/Y|Y/Y|Y|Y|
|FILECOIN_USDT|1.135400|1.133500|1.135700|0.47|N|Y/N|N/N|Y|N|
|ICP_USDT|2.992000|2.999000|2.992000|2.47|Y|Y/Y|Y/Y|Y|Y|
|INJ_USDT|8.713000|8.619000|8.714000|0.29|N|Y/Y|N/N|Y|N|
|ONDO_USDT|0.449400|0.448900|0.449300|0.44|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.084000|1.078000|1.084000|0.07|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.072720|0.071710|0.072720|0.85|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|1.002000|1.003100|1.002100|1.10|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|274.070000|273.390000|274.070000|0.28|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1146.350000|1141.130000|1146.160000|1.52|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.958200|1.938500|1.958200|0.41|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T01:45:02+00:00, last15m_closed_end=2026-10-17T01:45+00:00, prior8high=155.250000, depth_time=2026-10-17T01:45:38+00:00, book20_bid_proxy_usdt=271326, book20_ask_proxy_usdt=388454, funding_indicative=0.000054, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.57%, turnover=31345536. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T01:45:02+00:00, last15m_closed_end=2026-10-17T01:45+00:00, prior8high=0.848400, depth_time=2026-10-17T01:45:21+00:00, book20_bid_proxy_usdt=121263, book20_ask_proxy_usdt=155421, funding_indicative=0.000026, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.56%, turnover=12549834. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T01:45:02+00:00, last15m_closed_end=2026-10-17T01:45+00:00, prior8high=0.191670, depth_time=2026-10-17T01:45:15+00:00, book20_bid_proxy_usdt=58304, book20_ask_proxy_usdt=95892, funding_indicative=-0.000112, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.11%, turnover=31774715. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T01:45:02+00:00, last15m_closed_end=2026-10-17T01:45+00:00, prior8high=9.967000, depth_time=2026-10-17T01:45:36+00:00, book20_bid_proxy_usdt=611857, book20_ask_proxy_usdt=1784577, funding_indicative=0.000066, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=126060220. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T01:45:02+00:00, last15m_closed_end=2026-10-17T01:45+00:00, prior8high=0.199100, depth_time=2026-10-17T01:45:26+00:00, book20_bid_proxy_usdt=1780536, book20_ask_proxy_usdt=1110424, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.25%, turnover=11505547. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T01:45:02+00:00, last15m_closed_end=2026-10-17T01:45+00:00, prior8high=1.159600, depth_time=2026-10-17T01:45:19+00:00, book20_bid_proxy_usdt=546580, book20_ask_proxy_usdt=486611, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.69%, turnover=23247387. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-17T01:45:02+00:00, last15m_closed_end=2026-10-17T01:45+00:00, prior8high=3.033000, depth_time=2026-10-17T01:45:40+00:00, book20_bid_proxy_usdt=1379380, book20_ask_proxy_usdt=869132, funding_indicative=0.000054, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=8910120. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-17T01:45:02+00:00, last15m_closed_end=2026-10-17T01:45+00:00, prior8high=8.742000, depth_time=2026-10-17T01:45:17+00:00, book20_bid_proxy_usdt=226608, book20_ask_proxy_usdt=194742, funding_indicative=0.000121, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.95%, turnover=115218448. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-17T01:45:02+00:00, last15m_closed_end=2026-10-17T01:45+00:00, prior8high=0.454700, depth_time=2026-10-17T01:45:31+00:00, book20_bid_proxy_usdt=2783921, book20_ask_proxy_usdt=2044730, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=28919796. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T01:45:02+00:00, last15m_closed_end=2026-10-17T01:45+00:00, prior8high=1.094000, depth_time=2026-10-17T01:45:09+00:00, book20_bid_proxy_usdt=505532, book20_ask_proxy_usdt=346963, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.73%, turnover=5488895. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T01:45:02+00:00, last15m_closed_end=2026-10-17T01:45+00:00, prior8high=0.074200, depth_time=2026-10-17T01:45:34+00:00, book20_bid_proxy_usdt=252930, book20_ask_proxy_usdt=296505, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.66%, turnover=21265955. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T01:45:02+00:00, last15m_closed_end=2026-10-17T01:45+00:00, prior8high=1.021600, depth_time=2026-10-17T01:45:29+00:00, book20_bid_proxy_usdt=765338, book20_ask_proxy_usdt=1598603, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=99064868. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T01:45:02+00:00, last15m_closed_end=2026-10-17T01:45+00:00, prior8high=276.100000, depth_time=2026-10-17T01:45:24+00:00, book20_bid_proxy_usdt=83209, book20_ask_proxy_usdt=139028, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.33%, turnover=81656549. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T01:45:02+00:00, last15m_closed_end=2026-10-17T01:45+00:00, prior8high=1153.700000, depth_time=2026-10-17T01:45:12+00:00, book20_bid_proxy_usdt=269245, book20_ask_proxy_usdt=157783, funding_indicative=0.000085, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.50%, turnover=1385199398. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T01:45:02+00:00, last15m_closed_end=2026-10-17T01:45+00:00, prior8high=2.053600, depth_time=2026-10-17T01:45:07+00:00, book20_bid_proxy_usdt=36399, book20_ask_proxy_usdt=74466, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.81%, turnover=16390224. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
