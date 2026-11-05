# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T22:00:41Z**
- feed_generated_utc: 2026-11-05T22:00:42+00:00
- source_sha256: `b01b2550ace6db66c0c7541fa5fa826f195744ef72aee72f33c1cb44beaa0244`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T22:00+00:00, close=75826.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T22:00+00:00, close=75826.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T20:00+00:00, close=76344.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002159|-16.31|-89.74|-16.07|19827923|4.63|
|XPL_USDT|0.058640|-6.87|-25.70|-6.63|11864558|1.71|
|FLUID_USDT|2.364000|-6.63|14.53|-6.39|8315688|4.23|
|DASH_USDT|44.730000|-6.20|-13.12|-5.96|15488453|2.24|
|ATOM_USDT|1.393000|-5.62|-14.59|-5.38|5223513|7.18|
|PENGU_USDT|0.006520|-5.60|-19.81|-5.36|6135117|1.53|
|ETHFI_USDT|0.537100|-5.57|-20.95|-5.33|5550221|3.72|
|ZRO_USDT|1.609500|-5.13|-8.77|-4.89|6941745|1.24|
|BCH_USDT|272.290000|-4.39|-5.54|-4.15|8844184|3.67|
|SEI_USDT|0.045400|-4.23|-15.04|-3.99|6027636|2.20|
|OP_USDT|0.102120|-4.09|-10.35|-3.85|7023656|1.96|
|SHIB_USDT|0.000005|-2.28|-9.87|-2.04|5859249|2.21|
|XRP_USDT|1.221800|-1.83|-6.69|-1.59|444003243|0.82|
|QNT_USDT|189.080000|-1.42|-4.86|-1.18|44133816|0.53|
|HYPE_USDT|77.625000|-1.36|-17.36|-1.12|90614316|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002159|0.002009|0.002159|0.13|N|Y/Y|Y/Y|Y|N|
|ATOM_USDT|1.393000|1.400000|1.393000|1.44|Y|Y/Y|Y/N|Y|N|
|BCH_USDT|272.290000|271.110000|272.290000|0.70|N|Y/Y|Y/N|Y|N|
|DASH_USDT|44.730000|44.600000|44.730000|0.39|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.537100|0.524000|0.537100|1.43|N|Y/Y|Y/Y|Y|N|
|FLUID_USDT|2.364000|2.355000|2.364000|0.17|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.625000|77.493000|77.625000|1.67|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.102120|0.102450|0.102120|2.46|Y|Y/Y|Y/Y|Y|Y|
|PENGU_USDT|0.006520|0.006492|0.006520|0.77|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|189.080000|187.390000|189.080000|0.55|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.045400|0.045210|0.045400|2.68|N|Y/Y|Y/Y|Y|N|
|SHIB_USDT|0.000005|0.000005|0.000005|0.08|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.058640|0.058300|0.058640|1.48|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.221800|1.217300|1.221800|0.70|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.609500|1.594300|1.609200|0.17|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T21:59:59+00:00, last15m_closed_end=2026-11-05T22:00+00:00, prior8high=0.002268, depth_time=2026-11-05T22:00:06+00:00, book20_bid_proxy_usdt=24521, book20_ask_proxy_usdt=30378, funding_indicative=-0.000674, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-16.31%, turnover=19827923. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-11-05T22:00:00+00:00, last15m_closed_end=2026-11-05T22:00+00:00, prior8high=1.448000, depth_time=2026-11-05T22:00:16+00:00, book20_bid_proxy_usdt=2016688, book20_ask_proxy_usdt=1834239, funding_indicative=-0.000028, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.62%, turnover=5223513. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-05T22:00:00+00:00, last15m_closed_end=2026-11-05T22:00+00:00, prior8high=278.650000, depth_time=2026-11-05T22:00:26+00:00, book20_bid_proxy_usdt=51409, book20_ask_proxy_usdt=69498, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.39%, turnover=8844184. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-05T22:00:00+00:00, last15m_closed_end=2026-11-05T22:00+00:00, prior8high=45.980000, depth_time=2026-11-05T22:00:11+00:00, book20_bid_proxy_usdt=946784, book20_ask_proxy_usdt=402936, funding_indicative=-0.000010, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-6.20%, turnover=15488453. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-11-05T22:00:00+00:00, last15m_closed_end=2026-11-05T22:00+00:00, prior8high=0.543400, depth_time=2026-11-05T22:00:21+00:00, book20_bid_proxy_usdt=241720, book20_ask_proxy_usdt=147144, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.57%, turnover=5550221. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T21:59:59+00:00, last15m_closed_end=2026-11-05T22:00+00:00, prior8high=2.419000, depth_time=2026-11-05T22:00:11+00:00, book20_bid_proxy_usdt=222319, book20_ask_proxy_usdt=194274, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.63%, turnover=8315688. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T21:59:59+00:00, last15m_closed_end=2026-11-05T22:00+00:00, prior8high=78.964000, depth_time=2026-11-05T22:00:40+00:00, book20_bid_proxy_usdt=83833, book20_ask_proxy_usdt=73480, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.36%, turnover=90614316. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-05T22:00:00+00:00, last15m_closed_end=2026-11-05T22:00+00:00, prior8high=0.105280, depth_time=2026-11-05T22:00:31+00:00, book20_bid_proxy_usdt=94860, book20_ask_proxy_usdt=94620, funding_indicative=0.000004, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.09%, turnover=7023656. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-11-05T22:00:00+00:00, last15m_closed_end=2026-11-05T22:00+00:00, prior8high=0.006626, depth_time=2026-11-05T22:00:18+00:00, book20_bid_proxy_usdt=207676, book20_ask_proxy_usdt=171934, funding_indicative=0.000026, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.60%, turnover=6135117. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-05T21:59:59+00:00, last15m_closed_end=2026-11-05T22:00+00:00, prior8high=193.570000, depth_time=2026-11-05T22:00:37+00:00, book20_bid_proxy_usdt=81918, book20_ask_proxy_usdt=57352, funding_indicative=-0.000010, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.42%, turnover=44133816. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-11-05T22:00:00+00:00, last15m_closed_end=2026-11-05T22:00+00:00, prior8high=0.046420, depth_time=2026-11-05T22:00:28+00:00, book20_bid_proxy_usdt=281980, book20_ask_proxy_usdt=249907, funding_indicative=0.000068, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.23%, turnover=6027636. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SHIB_USDT: quote_utc=2026-11-05T22:00:00+00:00, last15m_closed_end=2026-11-05T22:00+00:00, prior8high=0.000005, depth_time=2026-11-05T22:00:33+00:00, book20_bid_proxy_usdt=202411, book20_ask_proxy_usdt=266151, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.28%, turnover=5859249. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-05T22:00:00+00:00, last15m_closed_end=2026-11-05T22:00+00:00, prior8high=0.060140, depth_time=2026-11-05T22:00:09+00:00, book20_bid_proxy_usdt=619479, book20_ask_proxy_usdt=434960, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.87%, turnover=11864558. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-05T21:59:59+00:00, last15m_closed_end=2026-11-05T22:00+00:00, prior8high=1.245300, depth_time=2026-11-05T22:00:35+00:00, book20_bid_proxy_usdt=3712328, book20_ask_proxy_usdt=3304835, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.83%, turnover=444003243. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T22:00:00+00:00, last15m_closed_end=2026-11-05T22:00+00:00, prior8high=1.657100, depth_time=2026-11-05T22:00:22+00:00, book20_bid_proxy_usdt=39047, book20_ask_proxy_usdt=41566, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.13%, turnover=6941745. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
