# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T10:45:42Z**
- feed_generated_utc: 2026-11-09T10:45:44+00:00
- source_sha256: `f0d4d838bd6b0c65e0ccaff3cd686bb370bfabc2945e124ebf9d10adb358d573`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T10:45+00:00, close=74116, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T10:00+00:00, close=74254.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T08:00+00:00, close=73840.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001545|-21.06|32.71|-18.54|7686658|0.65|
|ASTER_USDT|0.624600|-8.12|-10.69|-5.60|5557484|1.60|
|JCT_USDT|0.009055|-7.92|81.86|-5.40|73590685|1.10|
|XRP_USDT|1.085500|-6.08|-13.15|-3.56|270248325|0.92|
|ETH_USDT|2105.560000|-6.04|-7.07|-3.52|1526030595|0.05|
|HYPE_USDT|72.867000|-5.89|-16.90|-3.37|47611504|0.14|
|ZEC_USDT|1198.200000|-5.70|-3.20|-3.18|2312627402|0.08|
|NEAR_USDT|3.499000|-5.45|-19.21|-2.93|44531942|2.86|
|TRUMPOFFICIAL_USDT|1.127000|-5.21|-34.32|-2.69|6746771|8.88|
|PUMPFUN_USDT|0.003565|-4.60|-15.48|-2.08|10465484|2.81|
|TAO_USDT|215.790000|-4.53|-8.11|-2.01|52116316|1.39|
|SOL_USDT|86.000000|-4.10|-9.24|-1.58|704134598|1.16|
|DOT_USDT|0.856200|-3.89|-9.58|-1.37|10427918|1.17|
|UNI_USDT|6.742000|-3.72|-7.08|-1.20|27785379|1.48|
|DOGE_USDT|0.068760|-3.61|-9.09|-1.09|73141198|1.45|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ASTER_USDT|0.624600|0.628900|0.624600|3.86|Y|Y/Y|Y/Y|Y|Y|
|DOGE_USDT|0.068760|0.068780|0.068760|0.26|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.856200|0.859100|0.856200|0.74|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2105.560000|2098.500000|2105.690000|0.47|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|72.867000|72.835000|72.867000|0.55|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.009055|0.008130|0.009031|0.40|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.499000|3.499000|3.499000|1.47|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001545|0.001535|0.001545|0.88|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003565|0.003520|0.003565|0.38|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.000000|85.990000|86.000000|0.63|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|215.790000|214.370000|215.790000|0.39|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.127000|1.132000|1.126000|3.32|Y|Y/Y|Y/Y|Y|Y|
|UNI_USDT|6.742000|6.647000|6.742000|0.17|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.085500|1.085200|1.085500|0.76|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1198.200000|1201.730000|1197.850000|0.91|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ASTER_USDT: quote_utc=2026-11-09T10:45:01+00:00, last15m_closed_end=2026-11-09T10:45+00:00, prior8high=0.637200, depth_time=2026-11-09T10:45:07+00:00, book20_bid_proxy_usdt=827299, book20_ask_proxy_usdt=591366, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.12%, turnover=5557484. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-09T10:45:01+00:00, last15m_closed_end=2026-11-09T10:45+00:00, prior8high=0.069600, depth_time=2026-11-09T10:45:42+00:00, book20_bid_proxy_usdt=3489111, book20_ask_proxy_usdt=4722209, funding_indicative=0.000017, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.61%, turnover=73141198. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-09T10:45:01+00:00, last15m_closed_end=2026-11-09T10:45+00:00, prior8high=0.872200, depth_time=2026-11-09T10:45:34+00:00, book20_bid_proxy_usdt=744810, book20_ask_proxy_usdt=736332, funding_indicative=0.000046, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.89%, turnover=10427918. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T10:45:01+00:00, last15m_closed_end=2026-11-09T10:45+00:00, prior8high=2127.470000, depth_time=2026-11-09T10:45:16+00:00, book20_bid_proxy_usdt=4819402, book20_ask_proxy_usdt=3049764, funding_indicative=-0.000031, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.04%, turnover=1526030595. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T10:45:01+00:00, last15m_closed_end=2026-11-09T10:45+00:00, prior8high=74.219000, depth_time=2026-11-09T10:45:19+00:00, book20_bid_proxy_usdt=97700, book20_ask_proxy_usdt=61032, funding_indicative=0.000031, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.89%, turnover=47611504. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T10:45:01+00:00, last15m_closed_end=2026-11-09T10:45+00:00, prior8high=0.009792, depth_time=2026-11-09T10:45:12+00:00, book20_bid_proxy_usdt=58416, book20_ask_proxy_usdt=54338, funding_indicative=0.001346, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.92%, turnover=73590685. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T10:45:01+00:00, last15m_closed_end=2026-11-09T10:45+00:00, prior8high=3.578000, depth_time=2026-11-09T10:45:24+00:00, book20_bid_proxy_usdt=2198767, book20_ask_proxy_usdt=2688058, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.45%, turnover=44531942. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T10:45:01+00:00, last15m_closed_end=2026-11-09T10:45+00:00, prior8high=0.001610, depth_time=2026-11-09T10:45:07+00:00, book20_bid_proxy_usdt=8366, book20_ask_proxy_usdt=19138, funding_indicative=-0.000071, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-21.06%, turnover=7686658. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T10:45:01+00:00, last15m_closed_end=2026-11-09T10:45+00:00, prior8high=0.003597, depth_time=2026-11-09T10:45:30+00:00, book20_bid_proxy_usdt=2670728, book20_ask_proxy_usdt=2951933, funding_indicative=0.000037, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.60%, turnover=10465484. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T10:45:01+00:00, last15m_closed_end=2026-11-09T10:45+00:00, prior8high=87.260000, depth_time=2026-11-09T10:45:33+00:00, book20_bid_proxy_usdt=15275504, book20_ask_proxy_usdt=16233250, funding_indicative=0.000002, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.10%, turnover=704134598. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-09T10:45:01+00:00, last15m_closed_end=2026-11-09T10:45+00:00, prior8high=218.060000, depth_time=2026-11-09T10:45:31+00:00, book20_bid_proxy_usdt=257930, book20_ask_proxy_usdt=134877, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.53%, turnover=52116316. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T10:45:01+00:00, last15m_closed_end=2026-11-09T10:45+00:00, prior8high=1.153000, depth_time=2026-11-09T10:45:27+00:00, book20_bid_proxy_usdt=3044910, book20_ask_proxy_usdt=2741458, funding_indicative=0.000048, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.21%, turnover=6746771. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-09T10:45:01+00:00, last15m_closed_end=2026-11-09T10:45+00:00, prior8high=6.802000, depth_time=2026-11-09T10:45:39+00:00, book20_bid_proxy_usdt=3052925, book20_ask_proxy_usdt=2452573, funding_indicative=0.000085, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.72%, turnover=27785379. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T10:45:01+00:00, last15m_closed_end=2026-11-09T10:45+00:00, prior8high=1.101300, depth_time=2026-11-09T10:45:14+00:00, book20_bid_proxy_usdt=4660207, book20_ask_proxy_usdt=3508851, funding_indicative=0.000084, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.08%, turnover=270248325. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T10:45:01+00:00, last15m_closed_end=2026-11-09T10:45+00:00, prior8high=1233.140000, depth_time=2026-11-09T10:45:22+00:00, book20_bid_proxy_usdt=371821, book20_ask_proxy_usdt=324164, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.70%, turnover=2312627402. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
