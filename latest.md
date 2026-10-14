# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T15:45:45Z**
- feed_generated_utc: 2026-10-14T15:45:47+00:00
- source_sha256: `4ea246123d0ad7d1fbc51b1877506ab043123beeaa5c52a38d70d7bdf91f9378`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T15:45+00:00, close=81653.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T15:00+00:00, close=81928.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T12:00+00:00, close=83424.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.078330|-9.89|50.08|-7.82|26104165|1.28|
|W_USDT|0.015282|-9.05|5.30|-6.98|6059992|0.66|
|TIA_USDT|0.538400|-6.73|13.03|-4.66|30956847|1.86|
|ENA_USDT|0.196340|-6.30|-17.51|-4.23|38252908|0.51|
|SILVER_USDT|55.980000|-5.74|-8.78|-3.67|369885512|1.79|
|UNI_USDT|7.206000|-4.83|-16.83|-2.76|19356584|1.39|
|ONDO_USDT|0.445300|-4.35|-11.61|-2.28|31413497|2.25|
|FILECOIN_USDT|1.085000|-4.24|-5.69|-2.17|27950507|0.92|
|AVAX_USDT|9.820000|-4.01|-14.64|-1.94|36033265|1.02|
|RENDER_USDT|1.909000|-3.92|-10.37|-1.85|8831521|5.24|
|XLM_USDT|0.183630|-3.84|-14.06|-1.77|12860551|0.55|
|ZRO_USDT|1.915000|-3.58|-14.94|-1.51|10413324|0.52|
|PEPE_USDT|0.000004|-3.47|-6.13|-1.40|73948535|0.25|
|LINK_USDT|12.464000|-3.33|-10.56|-1.26|97161984|0.80|
|FET_USDT|0.205100|-3.25|-16.38|-1.18|7973055|9.75|
|PUMPFUN_USDT|0.004767|-3.22|-23.92|-1.15|20480098|2.10|
|ETH_USDT|2434.700000|-3.20|-9.83|-1.13|1843130806|0.04|
|ICP_USDT|3.013000|-3.18|-11.43|-1.11|9391261|3.32|
|ATOM_USDT|1.747000|-3.15|-2.01|-1.08|13020343|5.73|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AVAX_USDT|9.820000|9.782000|9.821000|0.52|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.196340|0.194180|0.196200|1.47|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.205100|0.204800|0.205100|0.60|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.085000|1.086600|1.085000|0.91|N|Y/Y|Y/N|Y|N|
|LINK_USDT|12.464000|12.299000|12.464000|0.47|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.445300|0.443200|0.445400|0.80|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.41|N|Y/Y|N/N|Y|N|
|RENDER_USDT|1.909000|1.887000|1.909000|0.44|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|55.980000|56.110000|55.980000|1.72|Y|Y/Y|Y/Y|Y|Y|
|STRK_USDT|0.078330|0.076650|0.078320|1.61|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.538400|0.534400|0.538400|0.28|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.206000|7.120000|7.205000|0.63|N|Y/Y|Y/Y|Y|N|
|W_USDT|0.015282|0.015086|0.015282|0.30|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.183630|0.181690|0.183570|0.26|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.915000|1.885000|1.915000|0.74|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AVAX_USDT: quote_utc=2026-10-14T15:45:01+00:00, last15m_closed_end=2026-10-14T15:45+00:00, prior8high=10.083000, depth_time=2026-10-14T15:45:28+00:00, book20_bid_proxy_usdt=522794, book20_ask_proxy_usdt=722171, funding_indicative=0.000000, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.01%, turnover=36033265. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-14T15:45:01+00:00, last15m_closed_end=2026-10-14T15:45+00:00, prior8high=0.202510, depth_time=2026-10-14T15:45:16+00:00, book20_bid_proxy_usdt=103127, book20_ask_proxy_usdt=88791, funding_indicative=0.000011, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.30%, turnover=38252908. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T15:45:01+00:00, last15m_closed_end=2026-10-14T15:45+00:00, prior8high=0.212000, depth_time=2026-10-14T15:45:44+00:00, book20_bid_proxy_usdt=1013154, book20_ask_proxy_usdt=1087748, funding_indicative=0.000086, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.25%, turnover=7973055. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-14T15:45:01+00:00, last15m_closed_end=2026-10-14T15:45+00:00, prior8high=1.125800, depth_time=2026-10-14T15:45:26+00:00, book20_bid_proxy_usdt=377654, book20_ask_proxy_usdt=443293, funding_indicative=-0.000095, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.24%, turnover=27950507. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-14T15:45:01+00:00, last15m_closed_end=2026-10-14T15:45+00:00, prior8high=12.803000, depth_time=2026-10-14T15:45:42+00:00, book20_bid_proxy_usdt=393759, book20_ask_proxy_usdt=365036, funding_indicative=0.000032, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.33%, turnover=97161984. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-14T15:45:01+00:00, last15m_closed_end=2026-10-14T15:45+00:00, prior8high=0.458100, depth_time=2026-10-14T15:45:24+00:00, book20_bid_proxy_usdt=1080481, book20_ask_proxy_usdt=2066509, funding_indicative=-0.000123, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.35%, turnover=31413497. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-14T15:45:01+00:00, last15m_closed_end=2026-10-14T15:45+00:00, prior8high=0.000004, depth_time=2026-10-14T15:45:39+00:00, book20_bid_proxy_usdt=42718, book20_ask_proxy_usdt=48116, funding_indicative=0.000014, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.47%, turnover=73948535. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RENDER_USDT: quote_utc=2026-10-14T15:45:01+00:00, last15m_closed_end=2026-10-14T15:45+00:00, prior8high=1.951000, depth_time=2026-10-14T15:45:32+00:00, book20_bid_proxy_usdt=1199735, book20_ask_proxy_usdt=1564593, funding_indicative=-0.000014, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.92%, turnover=8831521. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T15:45:01+00:00, last15m_closed_end=2026-10-14T15:45+00:00, prior8high=57.320000, depth_time=2026-10-14T15:45:18+00:00, book20_bid_proxy_usdt=38653554, book20_ask_proxy_usdt=31588139, funding_indicative=0.000141, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.74%, turnover=369885512. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T15:45:01+00:00, last15m_closed_end=2026-10-14T15:45+00:00, prior8high=0.081880, depth_time=2026-10-14T15:45:07+00:00, book20_bid_proxy_usdt=243771, book20_ask_proxy_usdt=149287, funding_indicative=0.000046, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.89%, turnover=26104165. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T15:45:01+00:00, last15m_closed_end=2026-10-14T15:45+00:00, prior8high=0.554200, depth_time=2026-10-14T15:45:13+00:00, book20_bid_proxy_usdt=147608, book20_ask_proxy_usdt=186408, funding_indicative=0.000020, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.73%, turnover=30956847. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T15:45:01+00:00, last15m_closed_end=2026-10-14T15:45+00:00, prior8high=7.336000, depth_time=2026-10-14T15:45:21+00:00, book20_bid_proxy_usdt=907153, book20_ask_proxy_usdt=1875221, funding_indicative=0.000051, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.83%, turnover=19356584. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T15:45:01+00:00, last15m_closed_end=2026-10-14T15:45+00:00, prior8high=0.015599, depth_time=2026-10-14T15:45:10+00:00, book20_bid_proxy_usdt=25588, book20_ask_proxy_usdt=37654, funding_indicative=-0.000238, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.05%, turnover=6059992. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-14T15:45:01+00:00, last15m_closed_end=2026-10-14T15:45+00:00, prior8high=0.187250, depth_time=2026-10-14T15:45:34+00:00, book20_bid_proxy_usdt=103876, book20_ask_proxy_usdt=188036, funding_indicative=-0.000136, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.84%, turnover=12860551. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-14T15:45:01+00:00, last15m_closed_end=2026-10-14T15:45+00:00, prior8high=1.973000, depth_time=2026-10-14T15:45:37+00:00, book20_bid_proxy_usdt=29089, book20_ask_proxy_usdt=28760, funding_indicative=0.000019, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.58%, turnover=10413324. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
