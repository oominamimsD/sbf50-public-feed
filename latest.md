# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T13:00:34Z**
- feed_generated_utc: 2026-10-20T13:00:37+00:00
- source_sha256: `5253873587c44c74aa73386d43878e61c8dfdafe30b5ff4c3f80877d41b359a3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1201; contracts: 1193; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T13:00+00:00, close=81577.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T13:00+00:00, close=81577.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T12:00+00:00, close=81467.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.068885|-19.29|313.42|-18.88|8544441|0.44|
|NEAR_USDT|4.688000|-4.87|-15.51|-4.46|162199524|2.13|
|ARB_USDT|0.188610|-4.58|0.07|-4.17|95190081|0.53|
|SAND_USDT|0.056940|-4.39|-8.29|-3.98|5297795|1.76|
|BTW_USDT|1.702500|-2.82|-3.03|-2.41|35775557|1.76|
|UNI_USDT|7.143000|-2.68|-3.70|-2.27|9415312|1.40|
|AVAX_USDT|9.471000|-2.23|-11.32|-1.82|138802170|1.06|
|STRK_USDT|0.055980|-2.18|-38.25|-1.77|17363053|1.79|
|QNT_USDT|193.470000|-2.05|-15.28|-1.64|70396423|1.55|
|LTC_USDT|58.800000|-1.85|-6.60|-1.44|12943342|3.40|
|TAO_USDT|263.770000|-1.68|-7.86|-1.27|58939621|1.14|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.068885|0.066520|0.068877|0.71|N|Y/Y|Y/N|Y|N|
|ARB_USDT|0.188610|0.187860|0.188610|0.44|N|Y/Y|Y/N|Y|N|
|AVAX_USDT|9.471000|9.384000|9.471000|0.96|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.702500|1.675000|1.701200|0.52|N|Y/Y|Y/Y|Y|N|
|LTC_USDT|58.800000|58.250000|58.800000|1.17|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.688000|4.630000|4.688000|0.59|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|193.470000|192.430000|193.470000|0.53|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.056940|0.056510|0.056940|0.85|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.055980|0.055410|0.055980|1.99|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|263.770000|262.590000|263.770000|1.22|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.143000|7.106000|7.143000|1.07|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T13:00:02+00:00, last15m_closed_end=2026-10-20T13:00+00:00, prior8high=0.070454, depth_time=2026-10-20T13:00:08+00:00, book20_bid_proxy_usdt=2519, book20_ask_proxy_usdt=4378, funding_indicative=0.000047, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-19.29%, turnover=8544441. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T13:00:02+00:00, last15m_closed_end=2026-10-20T13:00+00:00, prior8high=0.190320, depth_time=2026-10-20T13:00:13+00:00, book20_bid_proxy_usdt=70333, book20_ask_proxy_usdt=70563, funding_indicative=0.000085, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.58%, turnover=95190081. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-20T13:00:03+00:00, last15m_closed_end=2026-10-20T13:00+00:00, prior8high=9.491000, depth_time=2026-10-20T13:00:22+00:00, book20_bid_proxy_usdt=1506100, book20_ask_proxy_usdt=1030145, funding_indicative=-0.000030, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=138802170. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T13:00:02+00:00, last15m_closed_end=2026-10-20T13:00+00:00, prior8high=1.878700, depth_time=2026-10-20T13:00:17+00:00, book20_bid_proxy_usdt=12124, book20_ask_proxy_usdt=9917, funding_indicative=-0.003325, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.82%, turnover=35775557. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-20T13:00:03+00:00, last15m_closed_end=2026-10-20T13:00+00:00, prior8high=59.030000, depth_time=2026-10-20T13:00:30+00:00, book20_bid_proxy_usdt=1626671, book20_ask_proxy_usdt=1343596, funding_indicative=0.000100, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=12943342. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T13:00:02+00:00, last15m_closed_end=2026-10-20T13:00+00:00, prior8high=4.728000, depth_time=2026-10-20T13:00:10+00:00, book20_bid_proxy_usdt=3978439, book20_ask_proxy_usdt=3075587, funding_indicative=0.000009, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.87%, turnover=162199524. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T13:00:03+00:00, last15m_closed_end=2026-10-20T13:00+00:00, prior8high=195.540000, depth_time=2026-10-20T13:00:28+00:00, book20_bid_proxy_usdt=80806, book20_ask_proxy_usdt=67625, funding_indicative=0.000079, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=70396423. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T13:00:03+00:00, last15m_closed_end=2026-10-20T13:00+00:00, prior8high=0.057080, depth_time=2026-10-20T13:00:13+00:00, book20_bid_proxy_usdt=824343, book20_ask_proxy_usdt=1143255, funding_indicative=-0.001766, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.39%, turnover=5297795. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-20T13:00:03+00:00, last15m_closed_end=2026-10-20T13:00+00:00, prior8high=0.056490, depth_time=2026-10-20T13:00:25+00:00, book20_bid_proxy_usdt=627747, book20_ask_proxy_usdt=696379, funding_indicative=0.000017, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.18%, turnover=17363053. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T13:00:02+00:00, last15m_closed_end=2026-10-20T13:00+00:00, prior8high=265.120000, depth_time=2026-10-20T13:00:33+00:00, book20_bid_proxy_usdt=136237, book20_ask_proxy_usdt=82079, funding_indicative=0.000039, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=58939621. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T13:00:03+00:00, last15m_closed_end=2026-10-20T13:00+00:00, prior8high=7.197000, depth_time=2026-10-20T13:00:20+00:00, book20_bid_proxy_usdt=1873390, book20_ask_proxy_usdt=1889265, funding_indicative=0.000019, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.68%, turnover=9415312. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
