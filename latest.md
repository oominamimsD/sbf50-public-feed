# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T11:45:46Z**
- feed_generated_utc: 2026-11-09T11:45:48+00:00
- source_sha256: `2aa66df986316e84a36db351acc8f9cc385f3497608fe803572b03c5294c337a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T11:45+00:00, close=74545, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T11:00+00:00, close=74125.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T08:00+00:00, close=73840.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001510|-22.86|29.70|-20.90|6728660|0.66|
|JCT_USDT|0.008535|-13.20|71.41|-11.24|71508387|2.34|
|ASTER_USDT|0.631800|-7.06|-9.66|-5.10|5587791|1.58|
|XRP_USDT|1.085600|-6.07|-13.14|-4.11|279095464|0.92|
|ETH_USDT|2119.510000|-5.42|-6.45|-3.46|1575172171|0.05|
|HYPE_USDT|73.288000|-5.35|-16.42|-3.39|49218125|0.14|
|TRUMPOFFICIAL_USDT|1.128000|-5.13|-34.26|-3.17|6497864|8.87|
|NEAR_USDT|3.515000|-5.02|-18.84|-3.06|46724890|2.85|
|ZEC_USDT|1208.790000|-4.87|-2.35|-2.91|2327821845|0.08|
|SOL_USDT|86.230000|-3.84|-9.00|-1.88|729055778|1.16|
|XLM_USDT|0.145930|-3.49|-13.32|-1.53|28181248|0.69|
|DOGE_USDT|0.068950|-3.35|-8.84|-1.39|74686547|1.45|
|DOT_USDT|0.861400|-3.31|-9.03|-1.35|10438147|1.16|
|HOT_USDT|0.000416|-3.16|15.68|-1.20|8029186|2.40|
|UNI_USDT|6.784000|-3.12|-6.50|-1.16|27101792|2.95|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ASTER_USDT|0.631800|0.623900|0.631800|0.31|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.068950|0.068500|0.068940|0.34|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.861400|0.854600|0.861500|0.68|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2119.510000|2098.500000|2119.530000|0.95|N|Y/Y|Y/Y|Y|N|
|HOT_USDT|0.000416|0.000417|0.000416|0.33|N|N/N|N/N|Y|N|
|HYPE_USDT|73.288000|72.747000|73.288000|1.18|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008535|0.008581|0.008560|1.16|N|N/Y|N/N|Y|N|
|NEAR_USDT|3.515000|3.480000|3.515000|2.08|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001510|0.001523|0.001510|1.83|Y|Y/Y|Y/Y|Y|Y|
|SOL_USDT|86.230000|85.770000|86.230000|1.77|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.128000|1.124000|1.128000|0.97|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.784000|6.721000|6.784000|0.38|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.145930|0.144930|0.145930|0.72|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.085600|1.076200|1.085600|1.25|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1208.790000|1192.400000|1208.780000|0.79|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ASTER_USDT: quote_utc=2026-11-09T11:45:01+00:00, last15m_closed_end=2026-11-09T11:45+00:00, prior8high=0.634300, depth_time=2026-11-09T11:45:10+00:00, book20_bid_proxy_usdt=851504, book20_ask_proxy_usdt=713669, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.06%, turnover=5587791. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-09T11:45:01+00:00, last15m_closed_end=2026-11-09T11:45+00:00, prior8high=0.069550, depth_time=2026-11-09T11:45:35+00:00, book20_bid_proxy_usdt=4113668, book20_ask_proxy_usdt=4245645, funding_indicative=0.000031, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.35%, turnover=74686547. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-09T11:45:01+00:00, last15m_closed_end=2026-11-09T11:45+00:00, prior8high=0.872200, depth_time=2026-11-09T11:45:39+00:00, book20_bid_proxy_usdt=630467, book20_ask_proxy_usdt=882142, funding_indicative=0.000078, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.31%, turnover=10438147. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T11:45:01+00:00, last15m_closed_end=2026-11-09T11:45+00:00, prior8high=2132.860000, depth_time=2026-11-09T11:45:18+00:00, book20_bid_proxy_usdt=6569581, book20_ask_proxy_usdt=2433392, funding_indicative=-0.000031, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.42%, turnover=1575172171. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-09T11:45:01+00:00, last15m_closed_end=2026-11-09T11:45+00:00, prior8high=0.000447, depth_time=2026-11-09T11:45:41+00:00, book20_bid_proxy_usdt=99575, book20_ask_proxy_usdt=126466, funding_indicative=-0.001344, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=1, 24h_change=-3.16%, turnover=8029186. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T11:45:01+00:00, last15m_closed_end=2026-11-09T11:45+00:00, prior8high=74.029000, depth_time=2026-11-09T11:45:20+00:00, book20_bid_proxy_usdt=101911, book20_ask_proxy_usdt=92203, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.35%, turnover=49218125. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T11:45:01+00:00, last15m_closed_end=2026-11-09T11:45+00:00, prior8high=0.009792, depth_time=2026-11-09T11:45:11+00:00, book20_bid_proxy_usdt=67525, book20_ask_proxy_usdt=64776, funding_indicative=0.001308, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.20%, turnover=71508387. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T11:45:01+00:00, last15m_closed_end=2026-11-09T11:45+00:00, prior8high=3.570000, depth_time=2026-11-09T11:45:26+00:00, book20_bid_proxy_usdt=2627768, book20_ask_proxy_usdt=2033346, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.02%, turnover=46724890. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T11:45:01+00:00, last15m_closed_end=2026-11-09T11:45+00:00, prior8high=0.001610, depth_time=2026-11-09T11:45:08+00:00, book20_bid_proxy_usdt=52163, book20_ask_proxy_usdt=16614, funding_indicative=0.000003, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-22.86%, turnover=6728660. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T11:45:01+00:00, last15m_closed_end=2026-11-09T11:45+00:00, prior8high=87.140000, depth_time=2026-11-09T11:45:31+00:00, book20_bid_proxy_usdt=15359221, book20_ask_proxy_usdt=14092217, funding_indicative=0.000017, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.84%, turnover=729055778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T11:45:01+00:00, last15m_closed_end=2026-11-09T11:45+00:00, prior8high=1.148000, depth_time=2026-11-09T11:45:21+00:00, book20_bid_proxy_usdt=3013057, book20_ask_proxy_usdt=2574184, funding_indicative=0.000005, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.13%, turnover=6497864. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-09T11:45:01+00:00, last15m_closed_end=2026-11-09T11:45+00:00, prior8high=6.865000, depth_time=2026-11-09T11:45:44+00:00, book20_bid_proxy_usdt=2949766, book20_ask_proxy_usdt=2131735, funding_indicative=0.000090, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.12%, turnover=27101792. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-09T11:45:01+00:00, last15m_closed_end=2026-11-09T11:45+00:00, prior8high=0.146930, depth_time=2026-11-09T11:45:31+00:00, book20_bid_proxy_usdt=154321, book20_ask_proxy_usdt=163011, funding_indicative=-0.000028, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.49%, turnover=28181248. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T11:45:01+00:00, last15m_closed_end=2026-11-09T11:45+00:00, prior8high=1.096000, depth_time=2026-11-09T11:45:15+00:00, book20_bid_proxy_usdt=4932329, book20_ask_proxy_usdt=4197460, funding_indicative=0.000098, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.07%, turnover=279095464. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T11:45:01+00:00, last15m_closed_end=2026-11-09T11:45+00:00, prior8high=1225.880000, depth_time=2026-11-09T11:45:29+00:00, book20_bid_proxy_usdt=345261, book20_ask_proxy_usdt=366232, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.87%, turnover=2327821845. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
