# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T06:15:43Z**
- feed_generated_utc: 2026-10-30T06:15:46+00:00
- source_sha256: `a367e4089ca7002d0c4b803f4d08971c3785f8bb455da9bf9028ec9f2e16e7c2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T06:15+00:00, close=78609.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-30T06:00+00:00, close=78524.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T04:00+00:00, close=78198.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CRV_USDT|0.272400|-18.92|-25.83|-15.10|7985254|3.67|
|TIA_USDT|0.459600|-16.31|-19.14|-12.49|18914818|2.18|
|PYTH_USDT|0.061360|-16.16|-17.28|-12.34|5255804|1.63|
|LDO_USDT|0.327600|-13.42|-14.35|-9.60|6410896|3.05|
|FARTCOIN_USDT|0.118270|-12.00|-17.20|-8.18|15308827|1.69|
|PENGU_USDT|0.007190|-11.57|-6.96|-7.75|9966540|1.39|
|APT_USDT|0.622900|-11.43|-19.33|-7.61|12529817|3.21|
|FET_USDT|0.163900|-11.30|-11.54|-7.48|14006623|6.10|
|ETHFI_USDT|0.604000|-11.11|-8.80|-7.29|5959981|1.66|
|BTW_USDT|1.469900|-10.26|-17.88|-6.44|11029845|3.40|
|SEI_USDT|0.048500|-9.24|-16.48|-5.42|7244676|2.06|
|INJ_USDT|7.383000|-9.21|-6.92|-5.39|31109604|2.71|
|SHIB_USDT|0.000005|-6.45|-5.63|-2.63|7937885|2.12|
|DASH_USDT|48.170000|-6.44|-4.19|-2.62|27001193|2.08|
|JASMY_USDT|0.003715|-5.99|-18.45|-2.17|5789695|2.70|
|ETH_USDT|2246.390000|-5.13|-6.30|-1.31|2468372931|0.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.622900|0.612100|0.623000|0.70|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.469900|1.445300|1.469900|0.75|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.272400|0.267600|0.272400|1.42|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.170000|47.600000|48.170000|2.45|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.604000|0.593300|0.604000|1.07|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.118270|0.116190|0.118270|2.73|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.163900|0.158700|0.163900|1.37|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.383000|7.180000|7.384000|1.04|N|Y/Y|Y/Y|Y|N|
|JASMY_USDT|0.003715|0.003605|0.003715|0.87|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.327600|0.319000|0.327400|2.45|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007190|0.007048|0.007190|0.52|N|Y/Y|Y/Y|Y|N|
|PYTH_USDT|0.061360|0.060350|0.061360|1.79|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.048500|0.047970|0.048500|3.62|N|Y/Y|Y/Y|Y|N|
|SHIB_USDT|0.000005|0.000005|0.000005|1.84|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.459600|0.454400|0.459700|1.93|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-30T06:15:02+00:00, last15m_closed_end=2026-10-30T06:15+00:00, prior8high=0.628000, depth_time=2026-10-30T06:15:21+00:00, book20_bid_proxy_usdt=121226, book20_ask_proxy_usdt=101434, funding_indicative=-0.000119, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-11.43%, turnover=12529817. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T06:15:02+00:00, last15m_closed_end=2026-10-30T06:15+00:00, prior8high=1.528200, depth_time=2026-10-30T06:15:29+00:00, book20_bid_proxy_usdt=9531, book20_ask_proxy_usdt=18797, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.26%, turnover=11029845. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T06:15:03+00:00, last15m_closed_end=2026-10-30T06:15+00:00, prior8high=0.277500, depth_time=2026-10-30T06:15:04+00:00, book20_bid_proxy_usdt=879415, book20_ask_proxy_usdt=150308, funding_indicative=-0.000100, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-18.92%, turnover=7985254. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-30T06:15:02+00:00, last15m_closed_end=2026-10-30T06:15+00:00, prior8high=48.820000, depth_time=2026-10-30T06:15:35+00:00, book20_bid_proxy_usdt=407869, book20_ask_proxy_usdt=455059, funding_indicative=-0.000144, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.44%, turnover=27001193. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T06:15:03+00:00, last15m_closed_end=2026-10-30T06:15+00:00, prior8high=0.614200, depth_time=2026-10-30T06:15:26+00:00, book20_bid_proxy_usdt=318387, book20_ask_proxy_usdt=174184, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.11%, turnover=5959981. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-30T06:15:02+00:00, last15m_closed_end=2026-10-30T06:15+00:00, prior8high=0.120530, depth_time=2026-10-30T06:15:18+00:00, book20_bid_proxy_usdt=47995, book20_ask_proxy_usdt=65282, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-12.00%, turnover=15308827. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-30T06:15:02+00:00, last15m_closed_end=2026-10-30T06:15+00:00, prior8high=0.164100, depth_time=2026-10-30T06:15:25+00:00, book20_bid_proxy_usdt=897766, book20_ask_proxy_usdt=721070, funding_indicative=-0.000320, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-11.30%, turnover=14006623. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T06:15:02+00:00, last15m_closed_end=2026-10-30T06:15+00:00, prior8high=7.440000, depth_time=2026-10-30T06:15:34+00:00, book20_bid_proxy_usdt=198272, book20_ask_proxy_usdt=110287, funding_indicative=-0.000032, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-9.21%, turnover=31109604. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JASMY_USDT: quote_utc=2026-10-30T06:15:03+00:00, last15m_closed_end=2026-10-30T06:15+00:00, prior8high=0.003797, depth_time=2026-10-30T06:15:42+00:00, book20_bid_proxy_usdt=91358, book20_ask_proxy_usdt=60755, funding_indicative=0.000100, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.99%, turnover=5789695. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-30T06:15:02+00:00, last15m_closed_end=2026-10-30T06:15+00:00, prior8high=0.327200, depth_time=2026-10-30T06:15:15+00:00, book20_bid_proxy_usdt=638221, book20_ask_proxy_usdt=327804, funding_indicative=0.000096, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-13.42%, turnover=6410896. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-30T06:15:02+00:00, last15m_closed_end=2026-10-30T06:15+00:00, prior8high=0.007269, depth_time=2026-10-30T06:15:20+00:00, book20_bid_proxy_usdt=114766, book20_ask_proxy_usdt=108345, funding_indicative=-0.000010, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.57%, turnover=9966540. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-30T06:15:03+00:00, last15m_closed_end=2026-10-30T06:15+00:00, prior8high=0.062440, depth_time=2026-10-30T06:15:12+00:00, book20_bid_proxy_usdt=140001, book20_ask_proxy_usdt=219484, funding_indicative=-0.000190, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.16%, turnover=5255804. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-30T06:15:02+00:00, last15m_closed_end=2026-10-30T06:15+00:00, prior8high=0.048730, depth_time=2026-10-30T06:15:32+00:00, book20_bid_proxy_usdt=146817, book20_ask_proxy_usdt=177616, funding_indicative=-0.000104, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-9.24%, turnover=7244676. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SHIB_USDT: quote_utc=2026-10-30T06:15:02+00:00, last15m_closed_end=2026-10-30T06:15+00:00, prior8high=0.000005, depth_time=2026-10-30T06:15:36+00:00, book20_bid_proxy_usdt=135312, book20_ask_proxy_usdt=136213, funding_indicative=0.000100, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.45%, turnover=7937885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-30T06:15:02+00:00, last15m_closed_end=2026-10-30T06:15+00:00, prior8high=0.466000, depth_time=2026-10-30T06:15:10+00:00, book20_bid_proxy_usdt=283375, book20_ask_proxy_usdt=159772, funding_indicative=0.000023, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.31%, turnover=18914818. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
