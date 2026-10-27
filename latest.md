# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T09:30:46Z**
- feed_generated_utc: 2026-10-27T09:30:50+00:00
- source_sha256: `15fa6194e2f9e2b7e1a88b0672c66fb9223b8da41cd785571a8fd681063147f3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 17; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T09:30+00:00, close=79670.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T09:00+00:00, close=79834.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T08:00+00:00, close=79774.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BULLA_USDT|0.114870|-22.96|59.49|-22.07|11870465|7.83|
|IRYS_USDT|0.025740|-6.67|109.60|-5.78|7598954|3.88|
|PUMPFUN_USDT|0.004127|-4.64|-7.38|-3.75|21484342|2.42|
|AAVE_USDT|130.820000|-4.32|-11.13|-3.43|24425036|0.76|
|ENA_USDT|0.202500|-3.74|7.75|-2.85|85314885|1.48|
|DOT_USDT|0.989500|-3.23|-13.71|-2.34|10699165|1.01|
|ONDO_USDT|0.406500|-2.93|-6.03|-2.04|23160812|2.46|
|NEAR_USDT|4.444000|-2.82|-9.38|-1.93|91744747|2.25|
|FILECOIN_USDT|0.894800|-2.81|-11.58|-1.92|5764723|1.12|
|QNT_USDT|204.790000|-2.61|4.64|-1.72|130913188|0.98|
|AVAX_USDT|8.763000|-2.60|-8.35|-1.71|29421025|1.14|
|WLD_USDT|0.434100|-2.44|-14.26|-1.55|66051308|2.30|
|TAO_USDT|247.500000|-2.37|-7.75|-1.48|44660338|1.21|
|INJ_USDT|7.765000|-2.13|-9.19|-1.24|22311232|1.29|
|SOL_USDT|99.720000|-2.08|-4.19|-1.19|667833400|1.00|
|ARB_USDT|0.166690|-1.94|-14.79|-1.05|19901435|0.60|
|TIA_USDT|0.525500|-1.90|-13.64|-1.01|17062111|1.90|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.820000|130.610000|130.800000|2.00|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.763000|8.755000|8.761000|0.81|N|Y/Y|Y/Y|Y|N|
|BULLA_USDT|0.114870|0.108110|0.114870|1.19|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.989500|0.990100|0.989400|1.32|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.202500|0.202590|0.202440|4.50|Y|Y/Y|N/N|Y|N|
|FILECOIN_USDT|0.894800|0.894100|0.894400|1.12|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.765000|7.750000|7.765000|1.42|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.025740|0.025430|0.025740|1.00|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.444000|4.409000|4.444000|0.71|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.406500|0.406700|0.406200|2.15|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.004127|0.004140|0.004125|2.98|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|204.790000|202.380000|204.790000|1.61|N|N/N|N/N|Y|N|
|SOL_USDT|99.720000|99.510000|99.720000|0.66|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|247.500000|247.770000|247.390000|1.26|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.434100|0.434000|0.434100|1.63|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T09:30:01+00:00, last15m_closed_end=2026-10-27T09:30+00:00, prior8high=132.300000, depth_time=2026-10-27T09:30:16+00:00, book20_bid_proxy_usdt=359996, book20_ask_proxy_usdt=378550, funding_indicative=0.000094, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.32%, turnover=24425036. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T09:30:01+00:00, last15m_closed_end=2026-10-27T09:30+00:00, prior8high=8.828000, depth_time=2026-10-27T09:30:35+00:00, book20_bid_proxy_usdt=853649, book20_ask_proxy_usdt=1125738, funding_indicative=-0.000034, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.60%, turnover=29421025. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-27T09:30:01+00:00, last15m_closed_end=2026-10-27T09:30+00:00, prior8high=0.133100, depth_time=2026-10-27T09:30:09+00:00, book20_bid_proxy_usdt=18564, book20_ask_proxy_usdt=10085, funding_indicative=-0.000743, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-22.96%, turnover=11870465. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T09:30:01+00:00, last15m_closed_end=2026-10-27T09:30+00:00, prior8high=1.001200, depth_time=2026-10-27T09:30:20+00:00, book20_bid_proxy_usdt=351224, book20_ask_proxy_usdt=300745, funding_indicative=-0.000062, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.23%, turnover=10699165. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-27T09:30:01+00:00, last15m_closed_end=2026-10-27T09:30+00:00, prior8high=0.208980, depth_time=2026-10-27T09:30:20+00:00, book20_bid_proxy_usdt=140987, book20_ask_proxy_usdt=210226, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.74%, turnover=85314885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T09:30:02+00:00, last15m_closed_end=2026-10-27T09:30+00:00, prior8high=0.903000, depth_time=2026-10-27T09:30:27+00:00, book20_bid_proxy_usdt=1023920, book20_ask_proxy_usdt=1505214, funding_indicative=0.000033, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.81%, turnover=5764723. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-27T09:30:01+00:00, last15m_closed_end=2026-10-27T09:30+00:00, prior8high=7.851000, depth_time=2026-10-27T09:30:43+00:00, book20_bid_proxy_usdt=217683, book20_ask_proxy_usdt=245037, funding_indicative=0.000191, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=22311232. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T09:30:01+00:00, last15m_closed_end=2026-10-27T09:30+00:00, prior8high=0.027080, depth_time=2026-10-27T09:30:11+00:00, book20_bid_proxy_usdt=75835, book20_ask_proxy_usdt=101837, funding_indicative=-0.000335, next_funding_utc=2026-10-27T10:00:00+00:00, funding_cycle_h=1, 24h_change=-6.67%, turnover=7598954. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T09:30:01+00:00, last15m_closed_end=2026-10-27T09:30+00:00, prior8high=4.488000, depth_time=2026-10-27T09:30:27+00:00, book20_bid_proxy_usdt=1843644, book20_ask_proxy_usdt=2438219, funding_indicative=0.000077, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.82%, turnover=91744747. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T09:30:01+00:00, last15m_closed_end=2026-10-27T09:30+00:00, prior8high=0.411600, depth_time=2026-10-27T09:30:24+00:00, book20_bid_proxy_usdt=1922421, book20_ask_proxy_usdt=2837957, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.93%, turnover=23160812. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T09:30:01+00:00, last15m_closed_end=2026-10-27T09:30+00:00, prior8high=0.004216, depth_time=2026-10-27T09:30:14+00:00, book20_bid_proxy_usdt=966367, book20_ask_proxy_usdt=1594054, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.64%, turnover=21484342. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T09:30:01+00:00, last15m_closed_end=2026-10-27T09:30+00:00, prior8high=211.660000, depth_time=2026-10-27T09:30:31+00:00, book20_bid_proxy_usdt=49291, book20_ask_proxy_usdt=83416, funding_indicative=-0.000267, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=130913188. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-27T09:30:01+00:00, last15m_closed_end=2026-10-27T09:30+00:00, prior8high=100.360000, depth_time=2026-10-27T09:30:45+00:00, book20_bid_proxy_usdt=16058076, book20_ask_proxy_usdt=12620738, funding_indicative=0.000054, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.08%, turnover=667833400. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T09:30:01+00:00, last15m_closed_end=2026-10-27T09:30+00:00, prior8high=250.230000, depth_time=2026-10-27T09:30:40+00:00, book20_bid_proxy_usdt=154990, book20_ask_proxy_usdt=178493, funding_indicative=0.000049, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.37%, turnover=44660338. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T09:30:01+00:00, last15m_closed_end=2026-10-27T09:30+00:00, prior8high=0.439800, depth_time=2026-10-27T09:30:37+00:00, book20_bid_proxy_usdt=4489993, book20_ask_proxy_usdt=3654543, funding_indicative=-0.000194, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.44%, turnover=66051308. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
