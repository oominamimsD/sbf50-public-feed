# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T23:45:26Z**
- feed_generated_utc: 2026-11-10T23:45:27+00:00
- source_sha256: `e172d487e7640fc8d063a57f06187e4711df706e4c8c396132aea01d8369e1b2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T23:45+00:00, close=73805, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T23:00+00:00, close=73666.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T20:00+00:00, close=73437.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.211700|-15.63|57.42|-16.48|53291413|7.56|
|PIEVERSE_USDT|1.845100|-8.93|56.97|-9.78|5496169|1.08|
|DASH_USDT|42.920000|-4.91|-6.97|-5.76|14206600|2.33|
|ZEC_USDT|1046.040000|-4.32|-13.10|-5.17|2250040746|0.86|
|UNI_USDT|6.684000|-2.13|-9.09|-2.98|31909598|1.50|
|JCT_USDT|0.005195|-1.51|24.34|-2.36|19176860|3.85|
|HBAR_USDT|0.065500|-0.42|-6.46|-1.27|8946290|1.53|
|ARB_USDT|0.160780|-0.37|0.56|-1.22|34397916|0.62|
|XAU_USDT|4042.550000|-0.16|2.47|-1.01|516589724|0.03|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.160780|0.158140|0.160780|0.14|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|42.920000|42.400000|42.920000|1.10|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.065500|0.065190|0.065500|0.69|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.211700|0.183240|0.212170|0.45|N|Y/Y|N/N|Y|N|
|JCT_USDT|0.005195|0.005119|0.005195|0.56|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.845100|1.831900|1.845200|0.46|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.684000|6.611000|6.682000|0.89|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4042.550000|4034.120000|4042.550000|0.88|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1046.040000|1030.550000|1046.040000|0.93|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-11-10T23:45:02+00:00, last15m_closed_end=2026-11-10T23:45+00:00, prior8high=0.161710, depth_time=2026-11-10T23:45:19+00:00, book20_bid_proxy_usdt=73129, book20_ask_proxy_usdt=67584, funding_indicative=-0.000182, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.37%, turnover=34397916. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T23:45:02+00:00, last15m_closed_end=2026-11-10T23:45+00:00, prior8high=43.460000, depth_time=2026-11-10T23:45:11+00:00, book20_bid_proxy_usdt=864313, book20_ask_proxy_usdt=787046, funding_indicative=-0.000157, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.91%, turnover=14206600. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-10T23:45:02+00:00, last15m_closed_end=2026-11-10T23:45+00:00, prior8high=0.066260, depth_time=2026-11-10T23:45:21+00:00, book20_bid_proxy_usdt=601359, book20_ask_proxy_usdt=794723, funding_indicative=0.000046, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.42%, turnover=8946290. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-10T23:45:02+00:00, last15m_closed_end=2026-11-10T23:45+00:00, prior8high=0.220530, depth_time=2026-11-10T23:45:06+00:00, book20_bid_proxy_usdt=14866, book20_ask_proxy_usdt=8996, funding_indicative=-0.018253, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=1, 24h_change=-15.63%, turnover=53291413. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T23:45:02+00:00, last15m_closed_end=2026-11-10T23:45+00:00, prior8high=0.005358, depth_time=2026-11-10T23:45:17+00:00, book20_bid_proxy_usdt=36054, book20_ask_proxy_usdt=52971, funding_indicative=0.000476, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.51%, turnover=19176860. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T23:45:02+00:00, last15m_closed_end=2026-11-10T23:45+00:00, prior8high=1.858500, depth_time=2026-11-10T23:45:08+00:00, book20_bid_proxy_usdt=23491, book20_ask_proxy_usdt=19409, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.93%, turnover=5496169. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T23:45:02+00:00, last15m_closed_end=2026-11-10T23:45+00:00, prior8high=6.769000, depth_time=2026-11-10T23:45:15+00:00, book20_bid_proxy_usdt=2283915, book20_ask_proxy_usdt=2811616, funding_indicative=-0.000007, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=31909598. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-11-10T23:45:02+00:00, last15m_closed_end=2026-11-10T23:45+00:00, prior8high=4044.140000, depth_time=2026-11-10T23:45:24+00:00, book20_bid_proxy_usdt=1314299, book20_ask_proxy_usdt=2139248, funding_indicative=0.000073, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.16%, turnover=516589724. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T23:45:02+00:00, last15m_closed_end=2026-11-10T23:45+00:00, prior8high=1069.190000, depth_time=2026-11-10T23:45:14+00:00, book20_bid_proxy_usdt=429429, book20_ask_proxy_usdt=142473, funding_indicative=0.000024, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.32%, turnover=2250040746. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
