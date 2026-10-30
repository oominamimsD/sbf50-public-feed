# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T11:30:43Z**
- feed_generated_utc: 2026-10-30T11:30:47+00:00
- source_sha256: `774a6a558f2c089c7733a99e645d132985750804a51f2425d3b198f2ce4f56d7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T11:30+00:00, close=77766.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T11:00+00:00, close=77794.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T08:00+00:00, close=78147.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PYTH_USDT|0.060760|-16.98|-18.09|-12.13|5343426|1.65|
|TIA_USDT|0.464300|-15.45|-18.31|-10.60|20122727|2.15|
|CRV_USDT|0.286400|-14.76|-22.02|-9.91|9268225|3.49|
|ENA_USDT|0.185980|-13.06|-6.33|-8.21|114781337|0.54|
|LIT_USDT|2.835100|-12.95|-21.55|-8.10|17805775|0.35|
|FARTCOIN_USDT|0.117870|-12.29|-17.48|-7.44|15651765|0.85|
|LDO_USDT|0.333500|-11.86|-12.81|-7.01|6305365|3.00|
|PENGU_USDT|0.007208|-11.35|-6.72|-6.50|10178344|1.39|
|INJ_USDT|7.220000|-11.21|-8.97|-6.36|31925429|1.39|
|APT_USDT|0.624400|-11.21|-19.14|-6.36|11627130|1.60|
|FET_USDT|0.165500|-10.44|-10.68|-5.59|14048663|6.05|
|ETHFI_USDT|0.608600|-10.43|-8.10|-5.58|5886523|1.64|
|TRUMPOFFICIAL_USDT|1.562000|-9.60|-10.43|-4.75|10884367|6.40|
|TAO_USDT|234.160000|-9.51|-9.11|-4.66|87505231|1.28|
|JUP_USDT|0.255900|-9.19|-17.45|-4.34|6950799|3.91|
|BTW_USDT|1.488100|-9.15|-16.86|-4.30|9227646|2.02|
|ZEC_USDT|1263.610000|-6.90|2.37|-2.05|2194603965|0.08|
|BNB_USDT|704.500000|-6.32|-3.66|-1.47|55569807|1.42|
|DOGE_USDT|0.075850|-5.92|-4.19|-1.07|130074393|1.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.624400|0.612600|0.624300|0.53|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.286400|0.280800|0.286400|0.89|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.185980|0.186800|0.186360|2.49|Y|N/Y|Y/Y|Y|N|
|ETHFI_USDT|0.608600|0.603900|0.608600|1.32|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.117870|0.116190|0.117870|0.57|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.165500|0.163000|0.165500|0.71|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.220000|7.100000|7.220000|0.38|N|Y/Y|Y/Y|Y|N|
|JUP_USDT|0.255900|0.252800|0.255900|0.14|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.333500|0.325300|0.333500|0.56|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|2.835100|2.777900|2.835100|0.44|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007208|0.007058|0.007208|1.42|N|Y/Y|Y/Y|Y|N|
|PYTH_USDT|0.060760|0.060610|0.060790|2.66|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|234.160000|231.840000|234.150000|1.00|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.464300|0.457700|0.464400|1.80|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.562000|1.533000|1.562000|2.06|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-30T11:30:03+00:00, last15m_closed_end=2026-10-30T11:30+00:00, prior8high=0.629900, depth_time=2026-10-30T11:30:28+00:00, book20_bid_proxy_usdt=102907, book20_ask_proxy_usdt=113386, funding_indicative=0.000079, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.21%, turnover=11627130. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T11:30:03+00:00, last15m_closed_end=2026-10-30T11:30+00:00, prior8high=0.288000, depth_time=2026-10-30T11:30:11+00:00, book20_bid_proxy_usdt=461960, book20_ask_proxy_usdt=424771, funding_indicative=-0.000224, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-14.76%, turnover=9268225. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-30T11:30:03+00:00, last15m_closed_end=2026-10-30T11:30+00:00, prior8high=0.191700, depth_time=2026-10-30T11:30:15+00:00, book20_bid_proxy_usdt=100636, book20_ask_proxy_usdt=102266, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.06%, turnover=114781337. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T11:30:03+00:00, last15m_closed_end=2026-10-30T11:30+00:00, prior8high=0.613800, depth_time=2026-10-30T11:30:34+00:00, book20_bid_proxy_usdt=255716, book20_ask_proxy_usdt=190919, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.43%, turnover=5886523. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-30T11:30:03+00:00, last15m_closed_end=2026-10-30T11:30+00:00, prior8high=0.119010, depth_time=2026-10-30T11:30:20+00:00, book20_bid_proxy_usdt=49980, book20_ask_proxy_usdt=51823, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.29%, turnover=15651765. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-30T11:30:03+00:00, last15m_closed_end=2026-10-30T11:30+00:00, prior8high=0.165800, depth_time=2026-10-30T11:30:31+00:00, book20_bid_proxy_usdt=1143894, book20_ask_proxy_usdt=743326, funding_indicative=0.000100, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.44%, turnover=14048663. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T11:30:03+00:00, last15m_closed_end=2026-10-30T11:30+00:00, prior8high=7.256000, depth_time=2026-10-30T11:30:27+00:00, book20_bid_proxy_usdt=329031, book20_ask_proxy_usdt=261817, funding_indicative=0.000049, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.21%, turnover=31925429. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-30T11:30:03+00:00, last15m_closed_end=2026-10-30T11:30+00:00, prior8high=0.257100, depth_time=2026-10-30T11:30:38+00:00, book20_bid_proxy_usdt=376284, book20_ask_proxy_usdt=405174, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.19%, turnover=6950799. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-30T11:30:03+00:00, last15m_closed_end=2026-10-30T11:30+00:00, prior8high=0.334600, depth_time=2026-10-30T11:30:22+00:00, book20_bid_proxy_usdt=331651, book20_ask_proxy_usdt=303347, funding_indicative=0.000094, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.86%, turnover=6305365. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T11:30:03+00:00, last15m_closed_end=2026-10-30T11:30+00:00, prior8high=2.848000, depth_time=2026-10-30T11:30:17+00:00, book20_bid_proxy_usdt=24900, book20_ask_proxy_usdt=24532, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.95%, turnover=17805775. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-30T11:30:03+00:00, last15m_closed_end=2026-10-30T11:30+00:00, prior8high=0.007281, depth_time=2026-10-30T11:30:24+00:00, book20_bid_proxy_usdt=141613, book20_ask_proxy_usdt=93644, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.35%, turnover=10178344. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-30T11:30:03+00:00, last15m_closed_end=2026-10-30T11:30+00:00, prior8high=0.061880, depth_time=2026-10-30T11:30:08+00:00, book20_bid_proxy_usdt=170339, book20_ask_proxy_usdt=217102, funding_indicative=-0.000122, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-16.98%, turnover=5343426. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-30T11:30:03+00:00, last15m_closed_end=2026-10-30T11:30+00:00, prior8high=235.330000, depth_time=2026-10-30T11:30:40+00:00, book20_bid_proxy_usdt=53660, book20_ask_proxy_usdt=69746, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.51%, turnover=87505231. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-30T11:30:03+00:00, last15m_closed_end=2026-10-30T11:30+00:00, prior8high=0.470200, depth_time=2026-10-30T11:30:10+00:00, book20_bid_proxy_usdt=192350, book20_ask_proxy_usdt=551692, funding_indicative=0.000001, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-15.45%, turnover=20122727. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-30T11:30:03+00:00, last15m_closed_end=2026-10-30T11:30+00:00, prior8high=1.573000, depth_time=2026-10-30T11:30:36+00:00, book20_bid_proxy_usdt=1295755, book20_ask_proxy_usdt=1478069, funding_indicative=-0.000075, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.60%, turnover=10884367. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
