# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T05:45:41Z**
- feed_generated_utc: 2026-10-27T05:45:45+00:00
- source_sha256: `1463e494d023b75bd22953301d570a1a49d2d8f721d3700ec01aac6ceee3c496`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.08 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T05:45+00:00, close=79855.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T05:00+00:00, close=79721.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T04:00+00:00, close=79790.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|QNT_USDT|198.600000|-5.55|1.48|-4.91|126990668|1.51|
|ZRO_USDT|1.614000|-5.45|-15.14|-4.81|5014814|0.62|
|PUMPFUN_USDT|0.004166|-3.74|-6.50|-3.10|21188037|2.40|
|DOT_USDT|0.986800|-3.50|-13.95|-2.86|11219649|1.01|
|AAVE_USDT|132.180000|-3.32|-10.21|-2.68|23983602|0.76|
|NEAR_USDT|4.425000|-3.23|-9.76|-2.59|99540364|2.26|
|FILECOIN_USDT|0.895300|-2.75|-11.53|-2.11|6451892|1.12|
|ONDO_USDT|0.407300|-2.74|-5.84|-2.10|22876557|2.45|
|AVAX_USDT|8.752000|-2.72|-8.47|-2.08|53279413|1.14|
|FET_USDT|0.172100|-2.54|-8.94|-1.90|6723723|5.81|
|INJ_USDT|7.738000|-2.47|-9.50|-1.83|25028471|1.29|
|TIA_USDT|0.524300|-2.12|-13.83|-1.48|18031733|1.91|
|PENGU_USDT|0.007413|-2.12|-1.04|-1.48|5574003|1.35|
|ZEC_USDT|1221.510000|-2.10|8.55|-1.46|1469853784|0.08|
|TAO_USDT|248.240000|-2.07|-7.47|-1.43|45713706|0.40|
|ICP_USDT|2.576000|-2.05|-9.70|-1.41|5061972|3.88|
|WLD_USDT|0.436200|-1.97|-13.84|-1.33|70282726|2.29|
|SOL_USDT|100.070000|-1.73|-3.86|-1.09|686693622|1.00|
|ARB_USDT|0.167180|-1.65|-14.54|-1.01|20499939|0.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|132.180000|131.800000|132.140000|0.69|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.752000|8.679000|8.752000|4.17|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.986800|0.985300|0.986700|2.27|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.172100|0.171000|0.172100|0.22|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.895300|0.892300|0.895400|3.95|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.738000|7.756000|7.738000|1.28|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.425000|4.405000|4.425000|0.23|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.407300|0.405500|0.407300|1.00|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007413|0.007410|0.007413|1.06|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004166|0.004134|0.004165|0.39|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|198.600000|197.050000|198.700000|1.05|N|Y/Y|N/N|Y|N|
|TAO_USDT|248.240000|247.860000|248.190000|1.94|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.524300|0.522700|0.524100|1.24|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1221.510000|1216.570000|1220.880000|1.23|N|Y/Y|N/N|Y|N|
|ZRO_USDT|1.614000|1.599400|1.614000|1.73|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T05:45:02+00:00, last15m_closed_end=2026-10-27T05:45+00:00, prior8high=133.600000, depth_time=2026-10-27T05:45:15+00:00, book20_bid_proxy_usdt=475352, book20_ask_proxy_usdt=383088, funding_indicative=0.000082, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.32%, turnover=23983602. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T05:45:02+00:00, last15m_closed_end=2026-10-27T05:45+00:00, prior8high=8.822000, depth_time=2026-10-27T05:45:26+00:00, book20_bid_proxy_usdt=1027037, book20_ask_proxy_usdt=2137020, funding_indicative=-0.000084, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.72%, turnover=53279413. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T05:45:02+00:00, last15m_closed_end=2026-10-27T05:45+00:00, prior8high=0.996000, depth_time=2026-10-27T05:45:14+00:00, book20_bid_proxy_usdt=270185, book20_ask_proxy_usdt=800503, funding_indicative=-0.000146, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.50%, turnover=11219649. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-27T05:45:02+00:00, last15m_closed_end=2026-10-27T05:45+00:00, prior8high=0.172900, depth_time=2026-10-27T05:45:28+00:00, book20_bid_proxy_usdt=1802812, book20_ask_proxy_usdt=850912, funding_indicative=-0.000017, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=6723723. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T05:45:02+00:00, last15m_closed_end=2026-10-27T05:45+00:00, prior8high=0.901600, depth_time=2026-10-27T05:45:20+00:00, book20_bid_proxy_usdt=1066951, book20_ask_proxy_usdt=1450227, funding_indicative=-0.000035, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.75%, turnover=6451892. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-27T05:45:02+00:00, last15m_closed_end=2026-10-27T05:45+00:00, prior8high=7.937000, depth_time=2026-10-27T05:45:30+00:00, book20_bid_proxy_usdt=234723, book20_ask_proxy_usdt=275581, funding_indicative=0.000195, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.47%, turnover=25028471. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T05:45:02+00:00, last15m_closed_end=2026-10-27T05:45+00:00, prior8high=4.467000, depth_time=2026-10-27T05:45:18+00:00, book20_bid_proxy_usdt=3940682, book20_ask_proxy_usdt=4739986, funding_indicative=0.000026, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.23%, turnover=99540364. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T05:45:02+00:00, last15m_closed_end=2026-10-27T05:45+00:00, prior8high=0.408700, depth_time=2026-10-27T05:45:23+00:00, book20_bid_proxy_usdt=2225782, book20_ask_proxy_usdt=3044030, funding_indicative=0.000008, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.74%, turnover=22876557. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-27T05:45:02+00:00, last15m_closed_end=2026-10-27T05:45+00:00, prior8high=0.007462, depth_time=2026-10-27T05:45:35+00:00, book20_bid_proxy_usdt=182539, book20_ask_proxy_usdt=316496, funding_indicative=0.000024, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.12%, turnover=5574003. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T05:45:02+00:00, last15m_closed_end=2026-10-27T05:45+00:00, prior8high=0.004179, depth_time=2026-10-27T05:45:12+00:00, book20_bid_proxy_usdt=1529547, book20_ask_proxy_usdt=2614343, funding_indicative=0.000015, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.74%, turnover=21188037. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T05:45:02+00:00, last15m_closed_end=2026-10-27T05:45+00:00, prior8high=203.340000, depth_time=2026-10-27T05:45:07+00:00, book20_bid_proxy_usdt=61455, book20_ask_proxy_usdt=72965, funding_indicative=-0.000122, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.55%, turnover=126990668. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T05:45:02+00:00, last15m_closed_end=2026-10-27T05:45+00:00, prior8high=249.550000, depth_time=2026-10-27T05:45:40+00:00, book20_bid_proxy_usdt=130489, book20_ask_proxy_usdt=100310, funding_indicative=0.000025, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.07%, turnover=45713706. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T05:45:02+00:00, last15m_closed_end=2026-10-27T05:45+00:00, prior8high=0.531100, depth_time=2026-10-27T05:45:31+00:00, book20_bid_proxy_usdt=361530, book20_ask_proxy_usdt=557528, funding_indicative=0.000022, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.12%, turnover=18031733. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-27T05:45:02+00:00, last15m_closed_end=2026-10-27T05:45+00:00, prior8high=1229.280000, depth_time=2026-10-27T05:45:38+00:00, book20_bid_proxy_usdt=158442, book20_ask_proxy_usdt=360281, funding_indicative=0.000072, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=1469853784. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T05:45:02+00:00, last15m_closed_end=2026-10-27T05:45+00:00, prior8high=1.624500, depth_time=2026-10-27T05:45:09+00:00, book20_bid_proxy_usdt=52463, book20_ask_proxy_usdt=80880, funding_indicative=0.000033, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.45%, turnover=5014814. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
