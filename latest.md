# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T08:45:45Z**
- feed_generated_utc: 2026-11-09T08:45:47+00:00
- source_sha256: `2b9c1a05d5f23a50146294c0bbd14612c88d991e93abafccadec49fc14b0e629`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 17; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T08:45+00:00, close=74301.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T08:00+00:00, close=73840.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T08:00+00:00, close=73840.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001573|-19.66|35.07|-17.38|9204119|0.64|
|AKE_USDT|0.004560|-14.87|-50.21|-12.59|10941758|2.19|
|CLAUDIA_USDT|0.007159|-14.16|292.05|-11.88|6720157|4.19|
|JCT_USDT|0.008516|-13.40|71.03|-11.12|72558189|2.35|
|ASTER_USDT|0.635500|-6.51|-9.13|-4.23|5409915|1.57|
|ETH_USDT|2113.160000|-5.70|-6.73|-3.42|1464745119|0.05|
|XRP_USDT|1.092200|-5.50|-12.61|-3.22|262703352|0.92|
|HYPE_USDT|73.415000|-5.18|-16.27|-2.90|45709129|0.14|
|PUMPFUN_USDT|0.003546|-5.11|-15.93|-2.83|10164226|5.64|
|NEAR_USDT|3.523000|-4.80|-18.65|-2.52|42194598|5.68|
|TAO_USDT|215.330000|-4.73|-8.30|-2.45|41744577|1.39|
|ZEC_USDT|1213.650000|-4.48|-1.95|-2.20|2258396165|0.08|
|UNI_USDT|6.714000|-4.12|-7.46|-1.84|29036406|1.49|
|XLM_USDT|0.145690|-3.65|-13.46|-1.37|27698507|0.69|
|SOL_USDT|86.500000|-3.54|-8.71|-1.26|668773947|1.16|
|ADA_USDT|0.174400|-3.48|-9.63|-1.20|21854821|5.74|
|LIT_USDT|3.087400|-3.31|-4.41|-1.03|13580056|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004560|0.004511|0.004560|0.53|N|Y/Y|Y/Y|Y|N|
|ASTER_USDT|0.635500|0.624700|0.635500|0.34|N|Y/Y|Y/Y|Y|N|
|CLAUDIA_USDT|0.007159|0.006700|0.007159|0.92|N|Y/N|N/N|Y|N|
|ETH_USDT|2113.160000|2081.410000|2113.160000|0.89|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.415000|72.442000|73.415000|1.43|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008516|0.007376|0.008516|0.66|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.523000|3.460000|3.523000|0.90|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001573|0.001562|0.001573|0.67|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003546|0.003485|0.003547|2.11|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.500000|85.090000|86.500000|0.57|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|215.330000|212.000000|215.310000|0.75|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.714000|6.646000|6.714000|4.14|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.145690|0.143780|0.145710|0.94|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.092200|1.081600|1.092200|1.46|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1213.650000|1185.330000|1213.650000|0.67|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T08:45:01+00:00, last15m_closed_end=2026-11-09T08:45+00:00, prior8high=0.004675, depth_time=2026-11-09T08:45:09+00:00, book20_bid_proxy_usdt=51692, book20_ask_proxy_usdt=36412, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-14.87%, turnover=10941758. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T08:45:01+00:00, last15m_closed_end=2026-11-09T08:45+00:00, prior8high=0.634800, depth_time=2026-11-09T08:45:15+00:00, book20_bid_proxy_usdt=607843, book20_ask_proxy_usdt=703476, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.51%, turnover=5409915. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLAUDIA_USDT: quote_utc=2026-11-09T08:45:01+00:00, last15m_closed_end=2026-11-09T08:45+00:00, prior8high=0.007490, depth_time=2026-11-09T08:45:11+00:00, book20_bid_proxy_usdt=219, book20_ask_proxy_usdt=385, funding_indicative=0.000118, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-14.16%, turnover=6720157. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T08:45:01+00:00, last15m_closed_end=2026-11-09T08:45+00:00, prior8high=2120.740000, depth_time=2026-11-09T08:45:19+00:00, book20_bid_proxy_usdt=2507444, book20_ask_proxy_usdt=4375385, funding_indicative=-0.000033, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.70%, turnover=1464745119. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T08:45:01+00:00, last15m_closed_end=2026-11-09T08:45+00:00, prior8high=74.327000, depth_time=2026-11-09T08:45:22+00:00, book20_bid_proxy_usdt=124526, book20_ask_proxy_usdt=66756, funding_indicative=0.000040, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.18%, turnover=45709129. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T08:45:01+00:00, last15m_closed_end=2026-11-09T08:45+00:00, prior8high=0.010326, depth_time=2026-11-09T08:45:14+00:00, book20_bid_proxy_usdt=27539, book20_ask_proxy_usdt=28768, funding_indicative=0.001320, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.40%, turnover=72558189. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T08:45:01+00:00, last15m_closed_end=2026-11-09T08:45+00:00, prior8high=3.563000, depth_time=2026-11-09T08:45:28+00:00, book20_bid_proxy_usdt=2103567, book20_ask_proxy_usdt=2470787, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.80%, turnover=42194598. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T08:45:01+00:00, last15m_closed_end=2026-11-09T08:45+00:00, prior8high=0.001638, depth_time=2026-11-09T08:45:07+00:00, book20_bid_proxy_usdt=36005, book20_ask_proxy_usdt=17365, funding_indicative=-0.000076, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-19.66%, turnover=9204119. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T08:45:01+00:00, last15m_closed_end=2026-11-09T08:45+00:00, prior8high=0.003566, depth_time=2026-11-09T08:45:27+00:00, book20_bid_proxy_usdt=2286352, book20_ask_proxy_usdt=2452251, funding_indicative=0.000034, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.11%, turnover=10164226. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T08:45:01+00:00, last15m_closed_end=2026-11-09T08:45+00:00, prior8high=86.630000, depth_time=2026-11-09T08:45:44+00:00, book20_bid_proxy_usdt=13224001, book20_ask_proxy_usdt=14991990, funding_indicative=-0.000043, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.54%, turnover=668773947. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-09T08:45:01+00:00, last15m_closed_end=2026-11-09T08:45+00:00, prior8high=215.530000, depth_time=2026-11-09T08:45:33+00:00, book20_bid_proxy_usdt=103722, book20_ask_proxy_usdt=146407, funding_indicative=0.000036, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.73%, turnover=41744577. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-09T08:45:01+00:00, last15m_closed_end=2026-11-09T08:45+00:00, prior8high=6.793000, depth_time=2026-11-09T08:45:39+00:00, book20_bid_proxy_usdt=1911796, book20_ask_proxy_usdt=3274708, funding_indicative=0.000037, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.12%, turnover=29036406. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-09T08:45:01+00:00, last15m_closed_end=2026-11-09T08:45+00:00, prior8high=0.145970, depth_time=2026-11-09T08:45:41+00:00, book20_bid_proxy_usdt=145770, book20_ask_proxy_usdt=189666, funding_indicative=0.000043, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.65%, turnover=27698507. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T08:45:01+00:00, last15m_closed_end=2026-11-09T08:45+00:00, prior8high=1.098500, depth_time=2026-11-09T08:45:22+00:00, book20_bid_proxy_usdt=4328873, book20_ask_proxy_usdt=3279474, funding_indicative=0.000068, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.50%, turnover=262703352. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T08:45:01+00:00, last15m_closed_end=2026-11-09T08:45+00:00, prior8high=1224.120000, depth_time=2026-11-09T08:45:37+00:00, book20_bid_proxy_usdt=578575, book20_ask_proxy_usdt=505488, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.48%, turnover=2258396165. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
