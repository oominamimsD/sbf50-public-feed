# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T15:00:27Z**
- feed_generated_utc: 2026-11-03T15:00:29+00:00
- source_sha256: `fd9ad91bbfc6f9d2a231c2fdaa820fa5078e5bcb0e893f839640aad9d9c4281d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T15:00+00:00, close=77364.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T15:00+00:00, close=77364.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T12:00+00:00, close=77085.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.004101|-25.46|-86.67|-25.32|12299338|4.88|
|UAI_USDT|0.100900|-23.96|-59.44|-23.82|9122179|9.91|
|XPL_USDT|0.064300|-8.83|-13.44|-8.69|11083793|1.55|
|NEAR_USDT|3.869000|-5.03|-15.39|-4.89|79292206|2.58|
|TIA_USDT|0.439900|-4.14|-17.88|-4.00|13150060|2.27|
|QNT_USDT|194.720000|-3.89|-7.39|-3.75|52155950|3.60|
|DASH_USDT|46.200000|-3.12|-11.52|-2.98|8583519|2.16|
|ENA_USDT|0.170210|-2.75|-19.09|-2.61|68839010|0.59|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004101|0.003997|0.004109|1.78|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|46.200000|45.970000|46.200000|0.74|N|Y/N|Y/Y|Y|N|
|ENA_USDT|0.170210|0.169280|0.170200|0.82|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.869000|3.854000|3.869000|1.37|N|Y/N|Y/Y|Y|N|
|QNT_USDT|194.720000|194.220000|194.720000|1.03|N|Y/N|Y/Y|Y|N|
|TIA_USDT|0.439900|0.438000|0.439900|0.69|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.100900|0.096800|0.101000|1.14|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.064300|0.064060|0.064300|0.49|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T15:00:01+00:00, last15m_closed_end=2026-11-03T15:00+00:00, prior8high=0.004479, depth_time=2026-11-03T15:00:09+00:00, book20_bid_proxy_usdt=39378, book20_ask_proxy_usdt=35044, funding_indicative=-0.000451, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-25.46%, turnover=12299338. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T15:00:01+00:00, last15m_closed_end=2026-11-03T15:00+00:00, prior8high=46.820000, depth_time=2026-11-03T15:00:24+00:00, book20_bid_proxy_usdt=510630, book20_ask_proxy_usdt=538534, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.12%, turnover=8583519. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-03T15:00:01+00:00, last15m_closed_end=2026-11-03T15:00+00:00, prior8high=0.174220, depth_time=2026-11-03T15:00:26+00:00, book20_bid_proxy_usdt=246646, book20_ask_proxy_usdt=122526, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.75%, turnover=68839010. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T15:00:01+00:00, last15m_closed_end=2026-11-03T15:00+00:00, prior8high=3.945000, depth_time=2026-11-03T15:00:16+00:00, book20_bid_proxy_usdt=3264314, book20_ask_proxy_usdt=1177268, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.03%, turnover=79292206. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T15:00:01+00:00, last15m_closed_end=2026-11-03T15:00+00:00, prior8high=200.480000, depth_time=2026-11-03T15:00:21+00:00, book20_bid_proxy_usdt=72868, book20_ask_proxy_usdt=65886, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.89%, turnover=52155950. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T15:00:01+00:00, last15m_closed_end=2026-11-03T15:00+00:00, prior8high=0.449000, depth_time=2026-11-03T15:00:19+00:00, book20_bid_proxy_usdt=374201, book20_ask_proxy_usdt=294192, funding_indicative=-0.000029, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.14%, turnover=13150060. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-03T15:00:01+00:00, last15m_closed_end=2026-11-03T15:00+00:00, prior8high=0.172500, depth_time=2026-11-03T15:00:11+00:00, book20_bid_proxy_usdt=184140, book20_ask_proxy_usdt=117494, funding_indicative=-0.000167, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-23.96%, turnover=9122179. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T15:00:01+00:00, last15m_closed_end=2026-11-03T15:00+00:00, prior8high=0.065420, depth_time=2026-11-03T15:00:13+00:00, book20_bid_proxy_usdt=321054, book20_ask_proxy_usdt=431089, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.83%, turnover=11083793. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
