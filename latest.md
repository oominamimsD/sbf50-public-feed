# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T10:45:31Z**
- feed_generated_utc: 2026-10-20T10:45:34+00:00
- source_sha256: `f9b540dfd230560f512bf53d2ec7c364e451151d5b7a1068ed0e64ea9db4f261`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T10:45+00:00, close=81494.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T10:00+00:00, close=81450, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T08:00+00:00, close=81519.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.068728|-21.03|312.48|-20.52|9638136|1.02|
|NEAR_USDT|4.662000|-4.93|-15.98|-4.42|174098078|2.15|
|SAND_USDT|0.056890|-3.80|-8.37|-3.29|5561609|3.52|
|ATOM_USDT|1.716000|-3.37|-6.12|-2.86|5212186|5.83|
|ARB_USDT|0.189620|-3.07|0.61|-2.56|96164432|0.53|
|UNI_USDT|7.134000|-2.11|-3.82|-1.60|10338094|1.40|
|TAO_USDT|262.960000|-1.99|-8.14|-1.48|60245159|1.14|
|AVAX_USDT|9.398000|-1.71|-12.01|-1.20|144261209|1.06|
|SEI_USDT|0.059670|-1.64|-10.09|-1.13|6140940|1.68|
|ENA_USDT|0.184970|-1.56|-16.55|-1.05|30161482|0.54|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.068728|0.066550|0.068733|0.66|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.189620|0.188610|0.189620|0.30|N|Y/Y|N/N|Y|N|
|ATOM_USDT|1.716000|1.711000|1.716000|0.28|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.398000|9.402000|9.398000|0.74|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.184970|0.184710|0.184970|0.80|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.662000|4.678000|4.663000|3.07|Y|Y/Y|Y/Y|Y|Y|
|SAND_USDT|0.056890|0.056320|0.056890|0.65|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.059670|0.059410|0.059670|0.60|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|262.960000|261.790000|262.960000|0.65|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.134000|7.093000|7.134000|0.61|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T10:44:59+00:00, last15m_closed_end=2026-10-20T10:45+00:00, prior8high=0.072535, depth_time=2026-10-20T10:45:09+00:00, book20_bid_proxy_usdt=8294, book20_ask_proxy_usdt=8425, funding_indicative=0.000047, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-21.03%, turnover=9638136. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T10:45:00+00:00, last15m_closed_end=2026-10-20T10:45+00:00, prior8high=0.190590, depth_time=2026-10-20T10:45:18+00:00, book20_bid_proxy_usdt=76524, book20_ask_proxy_usdt=84150, funding_indicative=0.000096, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.07%, turnover=96164432. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-10-20T10:45:00+00:00, last15m_closed_end=2026-10-20T10:45+00:00, prior8high=1.731000, depth_time=2026-10-20T10:45:13+00:00, book20_bid_proxy_usdt=1713927, book20_ask_proxy_usdt=1290524, funding_indicative=0.000063, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.37%, turnover=5212186. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-20T10:45:00+00:00, last15m_closed_end=2026-10-20T10:45+00:00, prior8high=9.490000, depth_time=2026-10-20T10:45:26+00:00, book20_bid_proxy_usdt=1047987, book20_ask_proxy_usdt=964869, funding_indicative=0.000001, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=144261209. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-20T10:45:00+00:00, last15m_closed_end=2026-10-20T10:45+00:00, prior8high=0.186750, depth_time=2026-10-20T10:45:30+00:00, book20_bid_proxy_usdt=147406, book20_ask_proxy_usdt=205621, funding_indicative=0.000050, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.56%, turnover=30161482. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T10:45:00+00:00, last15m_closed_end=2026-10-20T10:45+00:00, prior8high=4.756000, depth_time=2026-10-20T10:45:11+00:00, book20_bid_proxy_usdt=4349056, book20_ask_proxy_usdt=4440972, funding_indicative=0.000073, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.93%, turnover=174098078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T10:45:00+00:00, last15m_closed_end=2026-10-20T10:45+00:00, prior8high=0.056960, depth_time=2026-10-20T10:45:13+00:00, book20_bid_proxy_usdt=753727, book20_ask_proxy_usdt=1059042, funding_indicative=-0.001674, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.80%, turnover=5561609. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-20T10:45:00+00:00, last15m_closed_end=2026-10-20T10:45+00:00, prior8high=0.059910, depth_time=2026-10-20T10:45:28+00:00, book20_bid_proxy_usdt=453620, book20_ask_proxy_usdt=197836, funding_indicative=-0.000020, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=6140940. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T10:45:00+00:00, last15m_closed_end=2026-10-20T10:45+00:00, prior8high=263.770000, depth_time=2026-10-20T10:45:24+00:00, book20_bid_proxy_usdt=120008, book20_ask_proxy_usdt=93949, funding_indicative=0.000042, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.99%, turnover=60245159. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T10:45:00+00:00, last15m_closed_end=2026-10-20T10:45+00:00, prior8high=7.161000, depth_time=2026-10-20T10:45:19+00:00, book20_bid_proxy_usdt=2121006, book20_ask_proxy_usdt=1775091, funding_indicative=0.000072, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.11%, turnover=10338094. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
