# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T07:45:33Z**
- feed_generated_utc: 2026-11-11T07:45:35+00:00
- source_sha256: `ffeffb1713157541c71ddb41e41907ce5c94dcab77c60ee81e6e27a48be7ab4e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T07:45+00:00, close=73837, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T07:00+00:00, close=73586.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T04:00+00:00, close=73740.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.193140|-23.03|43.61|-23.92|67954405|3.11|
|AKE_USDT|0.002616|-10.22|-37.05|-11.11|9245344|3.82|
|ZEC_USDT|986.160000|-9.80|-18.08|-10.69|2203910384|0.10|
|ONE_USDT|0.001626|-9.38|45.60|-10.27|12442843|4.92|
|UNI_USDT|6.427000|-5.90|-12.59|-6.79|39903081|1.56|
|DASH_USDT|43.780000|-3.01|-5.11|-3.90|16163153|2.28|
|ARB_USDT|0.158140|-2.00|-1.08|-2.89|31582823|0.63|
|QNT_USDT|177.860000|-1.57|-8.98|-2.46|46363013|0.56|
|DOT_USDT|0.829800|-1.41|-11.96|-2.30|8630314|1.21|
|HBAR_USDT|0.065190|-0.89|-6.91|-1.78|6154837|1.53|
|VVV_USDT|19.077000|-0.84|-14.68|-1.73|5474024|2.10|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002616|0.002607|0.002616|0.86|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.158140|0.157280|0.158140|0.54|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.780000|43.260000|43.780000|4.61|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.829800|0.824500|0.829800|3.68|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.065190|0.064970|0.065190|2.84|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.193140|0.199690|0.193160|1.22|N|Y/N|N/N|Y|N|
|ONE_USDT|0.001626|0.001621|0.001626|1.14|N|Y/Y|N/N|Y|N|
|QNT_USDT|177.860000|177.180000|177.860000|0.78|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.427000|6.373000|6.427000|0.95|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.077000|18.851000|19.077000|0.85|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|986.160000|965.410000|986.160000|0.52|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T07:45:00+00:00, last15m_closed_end=2026-11-11T07:45+00:00, prior8high=0.002864, depth_time=2026-11-11T07:45:10+00:00, book20_bid_proxy_usdt=46796, book20_ask_proxy_usdt=85524, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.22%, turnover=9245344. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T07:45:00+00:00, last15m_closed_end=2026-11-11T07:45+00:00, prior8high=0.163690, depth_time=2026-11-11T07:45:20+00:00, book20_bid_proxy_usdt=73378, book20_ask_proxy_usdt=98213, funding_indicative=0.000001, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.00%, turnover=31582823. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T07:45:00+00:00, last15m_closed_end=2026-11-11T07:45+00:00, prior8high=45.400000, depth_time=2026-11-11T07:45:18+00:00, book20_bid_proxy_usdt=787642, book20_ask_proxy_usdt=706507, funding_indicative=-0.000132, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.01%, turnover=16163153. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-11T07:45:00+00:00, last15m_closed_end=2026-11-11T07:45+00:00, prior8high=0.845600, depth_time=2026-11-11T07:45:24+00:00, book20_bid_proxy_usdt=512278, book20_ask_proxy_usdt=545791, funding_indicative=0.000044, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=8630314. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T07:45:00+00:00, last15m_closed_end=2026-11-11T07:45+00:00, prior8high=0.065870, depth_time=2026-11-11T07:45:29+00:00, book20_bid_proxy_usdt=859607, book20_ask_proxy_usdt=718148, funding_indicative=-0.000024, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.89%, turnover=6154837. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T07:45:00+00:00, last15m_closed_end=2026-11-11T07:45+00:00, prior8high=0.274880, depth_time=2026-11-11T07:45:07+00:00, book20_bid_proxy_usdt=14580, book20_ask_proxy_usdt=12020, funding_indicative=-0.009724, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=1, 24h_change=-23.03%, turnover=67954405. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T07:45:00+00:00, last15m_closed_end=2026-11-11T07:45+00:00, prior8high=0.001832, depth_time=2026-11-11T07:45:15+00:00, book20_bid_proxy_usdt=15291, book20_ask_proxy_usdt=21470, funding_indicative=-0.003446, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.38%, turnover=12442843. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T07:45:00+00:00, last15m_closed_end=2026-11-11T07:45+00:00, prior8high=180.860000, depth_time=2026-11-11T07:45:24+00:00, book20_bid_proxy_usdt=72694, book20_ask_proxy_usdt=91345, funding_indicative=-0.000097, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.57%, turnover=46363013. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T07:45:00+00:00, last15m_closed_end=2026-11-11T07:45+00:00, prior8high=6.687000, depth_time=2026-11-11T07:45:17+00:00, book20_bid_proxy_usdt=3155110, book20_ask_proxy_usdt=2875300, funding_indicative=0.000002, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.90%, turnover=39903081. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T07:45:00+00:00, last15m_closed_end=2026-11-11T07:45+00:00, prior8high=19.229000, depth_time=2026-11-11T07:45:31+00:00, book20_bid_proxy_usdt=33180, book20_ask_proxy_usdt=19714, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.84%, turnover=5474024. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T07:45:00+00:00, last15m_closed_end=2026-11-11T07:45+00:00, prior8high=1023.190000, depth_time=2026-11-11T07:45:12+00:00, book20_bid_proxy_usdt=510582, book20_ask_proxy_usdt=221123, funding_indicative=0.000057, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-9.80%, turnover=2203910384. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
