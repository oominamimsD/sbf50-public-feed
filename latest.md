# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T04:00:35Z**
- feed_generated_utc: 2026-11-10T04:00:37+00:00
- source_sha256: `70ac4fa4b6bd7e76f18458d68158874ec76444b554257d866c0b01af4f0f13d3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T04:00+00:00, close=74537.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T04:00+00:00, close=74537.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T04:00+00:00, close=74537.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002671|-43.78|-51.45|-42.51|15068111|3.73|
|JCT_USDT|0.008287|-24.48|91.96|-23.21|26766060|6.04|
|ON_USDT|0.162900|-18.14|-3.89|-16.87|5394653|6.15|
|ZEC_USDT|1151.470000|-6.05|-8.18|-4.78|2368566953|0.09|
|ARB_USDT|0.171180|-5.05|7.43|-3.78|31375211|0.58|
|DOT_USDT|0.849000|-4.15|-9.11|-2.88|10768999|1.18|
|QNT_USDT|192.220000|-3.85|-5.05|-2.58|35936783|3.64|
|DASH_USDT|45.830000|-3.12|-2.90|-1.85|14108333|2.18|
|WLD_USDT|0.315800|-3.09|-17.15|-1.82|25760873|3.17|
|AAVE_USDT|128.460000|-3.06|-1.60|-1.79|13415602|2.34|
|PUMPFUN_USDT|0.003569|-2.93|-13.03|-1.66|7779632|2.80|
|HYPE_USDT|73.858000|-2.83|-13.83|-1.56|47046678|0.14|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|128.460000|128.190000|128.460000|1.94|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.002671|0.002302|0.002672|0.45|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.171180|0.170950|0.171180|0.68|N|Y/Y|N/N|Y|N|
|DASH_USDT|45.830000|45.830000|45.830000|0.55|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.849000|0.846300|0.849000|0.83|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.858000|73.284000|73.858000|0.97|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008287|0.007962|0.008288|1.47|N|Y/Y|N/N|Y|N|
|ON_USDT|0.162900|0.162700|0.162900|0.95|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003569|0.003550|0.003569|0.30|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|192.220000|191.900000|192.220000|1.12|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.315800|0.314400|0.315800|0.31|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1151.470000|1141.980000|1151.310000|0.79|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T04:00:00+00:00, last15m_closed_end=2026-11-10T04:00+00:00, prior8high=132.100000, depth_time=2026-11-10T04:00:27+00:00, book20_bid_proxy_usdt=540911, book20_ask_proxy_usdt=468362, funding_indicative=0.000007, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.06%, turnover=13415602. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T04:00:00+00:00, last15m_closed_end=2026-11-10T04:00+00:00, prior8high=0.002858, depth_time=2026-11-10T04:00:07+00:00, book20_bid_proxy_usdt=21499, book20_ask_proxy_usdt=35391, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-43.78%, turnover=15068111. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T04:00:00+00:00, last15m_closed_end=2026-11-10T04:00+00:00, prior8high=0.174030, depth_time=2026-11-10T04:00:14+00:00, book20_bid_proxy_usdt=62308, book20_ask_proxy_usdt=57533, funding_indicative=-0.000003, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.05%, turnover=31375211. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T04:00:01+00:00, last15m_closed_end=2026-11-10T04:00+00:00, prior8high=46.810000, depth_time=2026-11-10T04:00:20+00:00, book20_bid_proxy_usdt=546615, book20_ask_proxy_usdt=536839, funding_indicative=-0.000024, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.12%, turnover=14108333. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T04:00:00+00:00, last15m_closed_end=2026-11-10T04:00+00:00, prior8high=0.857500, depth_time=2026-11-10T04:00:17+00:00, book20_bid_proxy_usdt=618152, book20_ask_proxy_usdt=719302, funding_indicative=0.000026, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.15%, turnover=10768999. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T04:00:00+00:00, last15m_closed_end=2026-11-10T04:00+00:00, prior8high=74.889000, depth_time=2026-11-10T04:00:31+00:00, book20_bid_proxy_usdt=104479, book20_ask_proxy_usdt=138603, funding_indicative=0.000048, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.83%, turnover=47046678. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T04:00:00+00:00, last15m_closed_end=2026-11-10T04:00+00:00, prior8high=0.009990, depth_time=2026-11-10T04:00:09+00:00, book20_bid_proxy_usdt=17181, book20_ask_proxy_usdt=8921, funding_indicative=0.000440, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-24.48%, turnover=26766060. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ON_USDT: quote_utc=2026-11-10T04:00:00+00:00, last15m_closed_end=2026-11-10T04:00+00:00, prior8high=0.175100, depth_time=2026-11-10T04:00:10+00:00, book20_bid_proxy_usdt=55502, book20_ask_proxy_usdt=70486, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-18.14%, turnover=5394653. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T04:00:00+00:00, last15m_closed_end=2026-11-10T04:00+00:00, prior8high=0.003594, depth_time=2026-11-10T04:00:32+00:00, book20_bid_proxy_usdt=2859795, book20_ask_proxy_usdt=2652726, funding_indicative=0.000027, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.93%, turnover=7779632. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T04:00:00+00:00, last15m_closed_end=2026-11-10T04:00+00:00, prior8high=194.730000, depth_time=2026-11-10T04:00:20+00:00, book20_bid_proxy_usdt=48131, book20_ask_proxy_usdt=46724, funding_indicative=-0.000009, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.85%, turnover=35936783. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-10T04:00:00+00:00, last15m_closed_end=2026-11-10T04:00+00:00, prior8high=0.317600, depth_time=2026-11-10T04:00:25+00:00, book20_bid_proxy_usdt=5606132, book20_ask_proxy_usdt=5881616, funding_indicative=0.000054, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.09%, turnover=25760873. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T04:00:00+00:00, last15m_closed_end=2026-11-10T04:00+00:00, prior8high=1169.100000, depth_time=2026-11-10T04:00:14+00:00, book20_bid_proxy_usdt=259085, book20_ask_proxy_usdt=166200, funding_indicative=0.000065, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.05%, turnover=2368566953. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
