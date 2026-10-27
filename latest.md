# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T12:00:48Z**
- feed_generated_utc: 2026-10-27T12:00:52+00:00
- source_sha256: `083425a5aad8b9d6aab2e9c17964ffa098b326f59aa4452ebcbcda56cb04e60a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T12:00+00:00, close=79880.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T12:00+00:00, close=79880.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T12:00+00:00, close=79880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.024910|-10.65|102.85|-10.00|7223429|4.01|
|QNT_USDT|201.790000|-5.37|3.11|-4.72|111551881|0.50|
|AAVE_USDT|131.200000|-4.84|-10.88|-4.19|27389883|0.76|
|PUMPFUN_USDT|0.004149|-4.77|-6.88|-4.12|19221004|2.41|
|DOT_USDT|0.983600|-4.61|-14.23|-3.96|10985318|1.02|
|ENA_USDT|0.200760|-4.56|6.83|-3.91|85155552|0.50|
|WLD_USDT|0.430800|-3.88|-14.91|-3.23|65887014|2.32|
|ONDO_USDT|0.407600|-3.52|-5.77|-2.87|22518872|2.45|
|FILECOIN_USDT|0.889600|-3.37|-12.09|-2.72|6404283|1.12|
|TIA_USDT|0.523900|-3.26|-13.90|-2.61|17067247|1.91|
|AVAX_USDT|8.751000|-2.73|-8.48|-2.08|20548596|1.14|
|PEPE_USDT|0.000004|-2.27|3.74|-1.62|58696558|1.41|
|TAO_USDT|247.740000|-2.27|-7.66|-1.62|49024120|0.81|
|INJ_USDT|7.804000|-2.23|-8.73|-1.58|22388295|1.28|
|HBAR_USDT|0.075650|-2.21|-7.59|-1.56|10665120|1.32|
|NEAR_USDT|4.480000|-2.03|-8.64|-1.38|89266850|2.23|
|ARB_USDT|0.166550|-2.02|-14.86|-1.37|17440359|0.60|
|LINK_USDT|11.317000|-1.83|-5.24|-1.18|129868977|1.77|
|SOL_USDT|100.050000|-1.75|-3.88|-1.10|671916732|1.00|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|131.200000|129.420000|131.200000|0.55|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.751000|8.687000|8.750000|0.82|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.983600|0.979300|0.983500|0.25|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.200760|0.197200|0.200850|0.60|N|Y/Y|Y/N|Y|N|
|FILECOIN_USDT|0.889600|0.884300|0.889900|3.48|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.075650|0.075460|0.075670|0.59|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.804000|7.697000|7.804000|1.28|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.024910|0.024650|0.024910|1.04|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.407600|0.402800|0.407600|0.35|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|1.06|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004149|0.004093|0.004149|0.79|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|201.790000|200.970000|201.730000|0.68|N|Y/N|N/N|Y|N|
|TAO_USDT|247.740000|245.490000|247.680000|1.37|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.523900|0.519500|0.523900|0.54|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.430800|0.427500|0.430800|1.66|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T12:00:02+00:00, last15m_closed_end=2026-10-27T12:00+00:00, prior8high=131.800000, depth_time=2026-10-27T12:00:14+00:00, book20_bid_proxy_usdt=402936, book20_ask_proxy_usdt=442255, funding_indicative=0.000099, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.84%, turnover=27389883. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T12:00:02+00:00, last15m_closed_end=2026-10-27T12:00+00:00, prior8high=8.826000, depth_time=2026-10-27T12:00:37+00:00, book20_bid_proxy_usdt=814984, book20_ask_proxy_usdt=2126719, funding_indicative=0.000052, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.73%, turnover=20548596. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T12:00:02+00:00, last15m_closed_end=2026-10-27T12:00+00:00, prior8high=0.992500, depth_time=2026-10-27T12:00:20+00:00, book20_bid_proxy_usdt=430304, book20_ask_proxy_usdt=264104, funding_indicative=-0.000082, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.61%, turnover=10985318. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-27T12:00:02+00:00, last15m_closed_end=2026-10-27T12:00+00:00, prior8high=0.205910, depth_time=2026-10-27T12:00:22+00:00, book20_bid_proxy_usdt=236812, book20_ask_proxy_usdt=166925, funding_indicative=-0.000001, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.56%, turnover=85155552. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T12:00:02+00:00, last15m_closed_end=2026-10-27T12:00+00:00, prior8high=0.900900, depth_time=2026-10-27T12:00:30+00:00, book20_bid_proxy_usdt=1227882, book20_ask_proxy_usdt=1654895, funding_indicative=0.000060, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.37%, turnover=6404283. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-27T12:00:02+00:00, last15m_closed_end=2026-10-27T12:00+00:00, prior8high=0.076310, depth_time=2026-10-27T12:00:48+00:00, book20_bid_proxy_usdt=1019026, book20_ask_proxy_usdt=1359288, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=10665120. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-27T12:00:02+00:00, last15m_closed_end=2026-10-27T12:00+00:00, prior8high=7.921000, depth_time=2026-10-27T12:00:45+00:00, book20_bid_proxy_usdt=291260, book20_ask_proxy_usdt=337211, funding_indicative=0.000224, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=22388295. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T12:00:02+00:00, last15m_closed_end=2026-10-27T12:00+00:00, prior8high=0.025810, depth_time=2026-10-27T12:00:09+00:00, book20_bid_proxy_usdt=115399, book20_ask_proxy_usdt=104041, funding_indicative=-0.000359, next_funding_utc=2026-10-27T13:00:00+00:00, funding_cycle_h=1, 24h_change=-10.65%, turnover=7223429. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T12:00:02+00:00, last15m_closed_end=2026-10-27T12:00+00:00, prior8high=0.411000, depth_time=2026-10-27T12:00:27+00:00, book20_bid_proxy_usdt=1941096, book20_ask_proxy_usdt=3203003, funding_indicative=0.000026, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.52%, turnover=22518872. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-27T12:00:02+00:00, last15m_closed_end=2026-10-27T12:00+00:00, prior8high=0.000004, depth_time=2026-10-27T12:00:40+00:00, book20_bid_proxy_usdt=195992, book20_ask_proxy_usdt=80626, funding_indicative=0.000062, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=58696558. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T12:00:02+00:00, last15m_closed_end=2026-10-27T12:00+00:00, prior8high=0.004221, depth_time=2026-10-27T12:00:17+00:00, book20_bid_proxy_usdt=2734943, book20_ask_proxy_usdt=2590868, funding_indicative=0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.77%, turnover=19221004. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T12:00:02+00:00, last15m_closed_end=2026-10-27T12:00+00:00, prior8high=206.180000, depth_time=2026-10-27T12:00:12+00:00, book20_bid_proxy_usdt=90396, book20_ask_proxy_usdt=77755, funding_indicative=-0.000193, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.37%, turnover=111551881. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T12:00:02+00:00, last15m_closed_end=2026-10-27T12:00+00:00, prior8high=250.060000, depth_time=2026-10-27T12:00:42+00:00, book20_bid_proxy_usdt=146689, book20_ask_proxy_usdt=162920, funding_indicative=0.000043, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.27%, turnover=49024120. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T12:00:02+00:00, last15m_closed_end=2026-10-27T12:00+00:00, prior8high=0.529500, depth_time=2026-10-27T12:00:34+00:00, book20_bid_proxy_usdt=391574, book20_ask_proxy_usdt=438492, funding_indicative=0.000024, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.26%, turnover=17067247. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T12:00:02+00:00, last15m_closed_end=2026-10-27T12:00+00:00, prior8high=0.435500, depth_time=2026-10-27T12:00:25+00:00, book20_bid_proxy_usdt=3463556, book20_ask_proxy_usdt=3443557, funding_indicative=-0.000071, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.88%, turnover=65887014. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
