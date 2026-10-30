# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T11:00:40Z**
- feed_generated_utc: 2026-10-30T11:00:43+00:00
- source_sha256: `2cd176f3fb3e56f222690cd2ae8da305407eae6214ab546992753175896563fa`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T11:00+00:00, close=77794.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T11:00+00:00, close=77794.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T08:00+00:00, close=78147.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TIA_USDT|0.469100|-14.58|-17.47|-9.73|19838582|2.13|
|PYTH_USDT|0.061280|-14.48|-17.39|-9.63|5265647|1.63|
|CRV_USDT|0.287100|-13.23|-21.83|-8.38|9215336|3.49|
|FARTCOIN_USDT|0.118720|-11.66|-16.88|-6.81|15562897|0.84|
|PENGU_USDT|0.007253|-10.79|-6.14|-5.94|10005103|1.38|
|LDO_USDT|0.334200|-10.30|-12.62|-5.45|6268477|5.99|
|ETHFI_USDT|0.612800|-9.81|-7.47|-4.96|5816512|1.63|
|INJ_USDT|7.240000|-9.56|-8.72|-4.71|31533057|4.14|
|TAO_USDT|234.860000|-9.24|-8.84|-4.39|86819796|1.28|
|LIT_USDT|2.817400|-8.66|-22.04|-3.81|17746258|0.35|
|TRUMPOFFICIAL_USDT|1.571000|-7.85|-9.91|-3.00|10777006|6.37|
|BTW_USDT|1.531900|-6.48|-14.41|-1.63|9102827|0.65|
|BNB_USDT|704.000000|-6.10|-3.73|-1.25|55053291|2.84|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BNB_USDT|704.000000|701.500000|704.000000|1.65|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.531900|1.415800|1.533200|0.85|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.287100|0.278500|0.287200|0.32|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.612800|0.603900|0.613300|2.24|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.118720|0.116180|0.118800|1.81|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.240000|7.100000|7.240000|0.82|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.334200|0.324500|0.334200|1.23|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|2.817400|2.789700|2.817400|0.54|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007253|0.007058|0.007263|1.73|N|Y/Y|Y/Y|Y|N|
|PYTH_USDT|0.061280|0.060580|0.061280|3.73|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|234.860000|231.840000|234.940000|1.57|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.469100|0.457700|0.470200|4.07|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.571000|1.531000|1.571000|0.34|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BNB_USDT: quote_utc=2026-10-30T11:00:04+00:00, last15m_closed_end=2026-10-30T11:00+00:00, prior8high=706.600000, depth_time=2026-10-30T11:00:39+00:00, book20_bid_proxy_usdt=847776, book20_ask_proxy_usdt=1344545, funding_indicative=0.000000, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.10%, turnover=55053291. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T11:00:04+00:00, last15m_closed_end=2026-10-30T11:00+00:00, prior8high=1.533400, depth_time=2026-10-30T11:00:36+00:00, book20_bid_proxy_usdt=15156, book20_ask_proxy_usdt=17785, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.48%, turnover=9102827. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T11:00:05+00:00, last15m_closed_end=2026-10-30T11:00+00:00, prior8high=0.286500, depth_time=2026-10-30T11:00:14+00:00, book20_bid_proxy_usdt=589022, book20_ask_proxy_usdt=545281, funding_indicative=-0.000219, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-13.23%, turnover=9215336. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T11:00:05+00:00, last15m_closed_end=2026-10-30T11:00+00:00, prior8high=0.612200, depth_time=2026-10-30T11:00:20+00:00, book20_bid_proxy_usdt=200184, book20_ask_proxy_usdt=167845, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.81%, turnover=5816512. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-30T11:00:04+00:00, last15m_closed_end=2026-10-30T11:00+00:00, prior8high=0.118120, depth_time=2026-10-30T11:00:17+00:00, book20_bid_proxy_usdt=41986, book20_ask_proxy_usdt=48102, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.66%, turnover=15562897. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T11:00:04+00:00, last15m_closed_end=2026-10-30T11:00+00:00, prior8high=7.252000, depth_time=2026-10-30T11:00:27+00:00, book20_bid_proxy_usdt=260272, book20_ask_proxy_usdt=262412, funding_indicative=0.000069, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.56%, turnover=31533057. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-30T11:00:05+00:00, last15m_closed_end=2026-10-30T11:00+00:00, prior8high=0.333200, depth_time=2026-10-30T11:00:19+00:00, book20_bid_proxy_usdt=260824, book20_ask_proxy_usdt=310866, funding_indicative=0.000097, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.30%, turnover=6268477. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T11:00:04+00:00, last15m_closed_end=2026-10-30T11:00+00:00, prior8high=2.848000, depth_time=2026-10-30T11:00:31+00:00, book20_bid_proxy_usdt=20066, book20_ask_proxy_usdt=32372, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.66%, turnover=17746258. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-30T11:00:05+00:00, last15m_closed_end=2026-10-30T11:00+00:00, prior8high=0.007209, depth_time=2026-10-30T11:00:20+00:00, book20_bid_proxy_usdt=84991, book20_ask_proxy_usdt=100181, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.79%, turnover=10005103. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-30T11:00:05+00:00, last15m_closed_end=2026-10-30T11:00+00:00, prior8high=0.061880, depth_time=2026-10-30T11:00:11+00:00, book20_bid_proxy_usdt=265415, book20_ask_proxy_usdt=205492, funding_indicative=-0.000124, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-14.48%, turnover=5265647. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-30T11:00:04+00:00, last15m_closed_end=2026-10-30T11:00+00:00, prior8high=234.770000, depth_time=2026-10-30T11:00:29+00:00, book20_bid_proxy_usdt=111876, book20_ask_proxy_usdt=59827, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.24%, turnover=86819796. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-30T11:00:04+00:00, last15m_closed_end=2026-10-30T11:00+00:00, prior8high=0.469800, depth_time=2026-10-30T11:00:09+00:00, book20_bid_proxy_usdt=224400, book20_ask_proxy_usdt=189965, funding_indicative=-0.000013, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-14.58%, turnover=19838582. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-30T11:00:05+00:00, last15m_closed_end=2026-10-30T11:00+00:00, prior8high=1.564000, depth_time=2026-10-30T11:00:33+00:00, book20_bid_proxy_usdt=1293873, book20_ask_proxy_usdt=1337953, funding_indicative=-0.000106, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.85%, turnover=10777006. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
