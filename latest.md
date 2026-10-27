# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T11:45:45Z**
- feed_generated_utc: 2026-10-27T11:45:49+00:00
- source_sha256: `cc8897a49b518ac75501f8f81065281f4f2ff361e02d5d6a152d51c68b9b0ea6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 17; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T11:45+00:00, close=79851.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T11:00+00:00, close=79941, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T08:00+00:00, close=79774.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.025000|-9.35|103.58|-8.67|7526804|8.01|
|ENA_USDT|0.201380|-4.27|7.16|-3.59|88556925|0.50|
|AAVE_USDT|131.450000|-3.86|-10.71|-3.18|27749883|0.76|
|QNT_USDT|202.320000|-3.78|3.38|-3.10|124076799|0.49|
|PUMPFUN_USDT|0.004166|-3.74|-6.50|-3.06|20575920|2.40|
|DOT_USDT|0.985600|-3.61|-14.05|-2.93|11224365|1.01|
|ZRO_USDT|1.654000|-3.11|-13.03|-2.43|5163821|0.60|
|WLD_USDT|0.431200|-3.10|-14.83|-2.42|68580851|2.32|
|FILECOIN_USDT|0.892200|-3.09|-11.83|-2.41|6509092|1.12|
|AVAX_USDT|8.761000|-2.62|-8.37|-1.94|21545964|1.14|
|ONDO_USDT|0.408000|-2.57|-5.68|-1.89|23260494|2.45|
|TIA_USDT|0.524200|-2.14|-13.85|-1.46|17595047|1.91|
|TAO_USDT|248.160000|-2.11|-7.50|-1.43|50072774|1.21|
|HBAR_USDT|0.075740|-2.09|-7.48|-1.41|10945048|1.32|
|PEPE_USDT|0.000004|-2.06|3.96|-1.38|60453341|0.23|
|NEAR_USDT|4.488000|-1.85|-8.48|-1.17|94302094|2.23|
|ARB_USDT|0.167050|-1.72|-14.60|-1.04|18005653|0.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|131.450000|129.420000|131.450000|0.50|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.761000|8.687000|8.761000|0.57|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.985600|0.979300|0.985600|0.14|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.201380|0.197200|0.201380|0.85|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|0.892200|0.884300|0.892200|5.62|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.075740|0.075460|0.075740|0.41|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.025000|0.024650|0.025000|0.45|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.408000|0.402800|0.408000|0.63|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.60|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004166|0.004093|0.004166|0.17|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|202.320000|200.970000|202.320000|1.03|N|N/N|N/N|Y|N|
|TAO_USDT|248.160000|245.490000|248.160000|0.29|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.524200|0.519500|0.524200|0.82|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.431200|0.427500|0.431200|0.62|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.654000|1.605300|1.654000|0.74|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T11:45:01+00:00, last15m_closed_end=2026-10-27T11:45+00:00, prior8high=131.800000, depth_time=2026-10-27T11:45:13+00:00, book20_bid_proxy_usdt=432190, book20_ask_proxy_usdt=338219, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.86%, turnover=27749883. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T11:45:01+00:00, last15m_closed_end=2026-10-27T11:45+00:00, prior8high=8.826000, depth_time=2026-10-27T11:45:32+00:00, book20_bid_proxy_usdt=942438, book20_ask_proxy_usdt=1113434, funding_indicative=0.000047, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.62%, turnover=21545964. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T11:45:01+00:00, last15m_closed_end=2026-10-27T11:45+00:00, prior8high=0.992500, depth_time=2026-10-27T11:45:21+00:00, book20_bid_proxy_usdt=355130, book20_ask_proxy_usdt=317415, funding_indicative=-0.000075, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.61%, turnover=11224365. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-27T11:45:01+00:00, last15m_closed_end=2026-10-27T11:45+00:00, prior8high=0.205910, depth_time=2026-10-27T11:45:12+00:00, book20_bid_proxy_usdt=206663, book20_ask_proxy_usdt=179699, funding_indicative=0.000002, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.27%, turnover=88556925. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T11:45:01+00:00, last15m_closed_end=2026-10-27T11:45+00:00, prior8high=0.900900, depth_time=2026-10-27T11:45:30+00:00, book20_bid_proxy_usdt=1313693, book20_ask_proxy_usdt=1377124, funding_indicative=0.000055, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.09%, turnover=6509092. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-27T11:45:01+00:00, last15m_closed_end=2026-10-27T11:45+00:00, prior8high=0.076310, depth_time=2026-10-27T11:45:41+00:00, book20_bid_proxy_usdt=1198496, book20_ask_proxy_usdt=1127585, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=10945048. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T11:45:01+00:00, last15m_closed_end=2026-10-27T11:45+00:00, prior8high=0.026140, depth_time=2026-10-27T11:45:08+00:00, book20_bid_proxy_usdt=102515, book20_ask_proxy_usdt=115412, funding_indicative=-0.000484, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=1, 24h_change=-9.35%, turnover=7526804. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T11:45:01+00:00, last15m_closed_end=2026-10-27T11:45+00:00, prior8high=0.411000, depth_time=2026-10-27T11:45:34+00:00, book20_bid_proxy_usdt=2074767, book20_ask_proxy_usdt=3244834, funding_indicative=0.000028, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.57%, turnover=23260494. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-27T11:45:01+00:00, last15m_closed_end=2026-10-27T11:45+00:00, prior8high=0.000004, depth_time=2026-10-27T11:45:44+00:00, book20_bid_proxy_usdt=73447, book20_ask_proxy_usdt=66024, funding_indicative=0.000058, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.06%, turnover=60453341. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T11:45:01+00:00, last15m_closed_end=2026-10-27T11:45+00:00, prior8high=0.004221, depth_time=2026-10-27T11:45:19+00:00, book20_bid_proxy_usdt=2445067, book20_ask_proxy_usdt=2073270, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.74%, turnover=20575920. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T11:45:01+00:00, last15m_closed_end=2026-10-27T11:45+00:00, prior8high=206.650000, depth_time=2026-10-27T11:45:17+00:00, book20_bid_proxy_usdt=80495, book20_ask_proxy_usdt=77881, funding_indicative=-0.000205, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.78%, turnover=124076799. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T11:45:01+00:00, last15m_closed_end=2026-10-27T11:45+00:00, prior8high=250.060000, depth_time=2026-10-27T11:45:39+00:00, book20_bid_proxy_usdt=65899, book20_ask_proxy_usdt=269846, funding_indicative=0.000035, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.11%, turnover=50072774. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T11:45:01+00:00, last15m_closed_end=2026-10-27T11:45+00:00, prior8high=0.529500, depth_time=2026-10-27T11:45:37+00:00, book20_bid_proxy_usdt=372434, book20_ask_proxy_usdt=444523, funding_indicative=0.000012, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.14%, turnover=17595047. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T11:45:01+00:00, last15m_closed_end=2026-10-27T11:45+00:00, prior8high=0.435500, depth_time=2026-10-27T11:45:27+00:00, book20_bid_proxy_usdt=3091978, book20_ask_proxy_usdt=4326409, funding_indicative=-0.000080, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.10%, turnover=68580851. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T11:45:01+00:00, last15m_closed_end=2026-10-27T11:45+00:00, prior8high=1.668700, depth_time=2026-10-27T11:45:24+00:00, book20_bid_proxy_usdt=49038, book20_ask_proxy_usdt=26202, funding_indicative=0.000026, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.11%, turnover=5163821. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
