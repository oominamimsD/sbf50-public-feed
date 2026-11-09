# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T14:00:36Z**
- feed_generated_utc: 2026-11-09T14:00:38+00:00
- source_sha256: `d0f9dddfb06652b13db4f6cfd9eeb35518c12d2b00261ec6e6c271e083a977a6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T14:00+00:00, close=74694.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T14:00+00:00, close=74694.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T12:00+00:00, close=74345.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001484|-21.55|27.41|-19.79|5973161|0.67|
|AKE_USDT|0.004804|-9.88|-47.55|-8.12|8871136|2.08|
|ASTER_USDT|0.639700|-5.57|-8.53|-3.81|5708091|1.56|
|ETH_USDT|2124.360000|-5.20|-6.24|-3.44|1591283804|0.05|
|HYPE_USDT|73.453000|-5.19|-16.23|-3.43|47913225|0.14|
|XRP_USDT|1.097400|-5.05|-12.20|-3.29|284082260|0.91|
|NEAR_USDT|3.545000|-4.60|-18.14|-2.84|46369433|2.82|
|TRUMPOFFICIAL_USDT|1.130000|-4.39|-34.14|-2.63|6332225|8.85|
|ZEC_USDT|1217.640000|-4.37|-1.63|-2.61|2263362417|0.08|
|SOL_USDT|86.740000|-3.27|-8.46|-1.51|744501940|1.15|
|HOT_USDT|0.000421|-2.93|16.96|-1.17|5753568|4.76|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004804|0.004635|0.004804|0.18|N|Y/Y|N/Y|Y|N|
|ASTER_USDT|0.639700|0.631700|0.639700|0.20|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2124.360000|2112.170000|2124.480000|2.23|N|Y/Y|Y/Y|Y|N|
|HOT_USDT|0.000421|0.000411|0.000421|0.22|N|N/Y|N/N|Y|N|
|HYPE_USDT|73.453000|73.047000|73.453000|1.52|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.545000|3.502000|3.545000|0.44|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001484|0.001470|0.001484|1.32|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.740000|86.040000|86.750000|0.72|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.130000|1.125000|1.130000|1.76|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.097400|1.079300|1.097400|0.68|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1217.640000|1205.020000|1217.640000|0.81|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T14:00:01+00:00, last15m_closed_end=2026-11-09T14:00+00:00, prior8high=0.005694, depth_time=2026-11-09T14:00:10+00:00, book20_bid_proxy_usdt=29116, book20_ask_proxy_usdt=35313, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.88%, turnover=8871136. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T14:00:01+00:00, last15m_closed_end=2026-11-09T14:00+00:00, prior8high=0.643800, depth_time=2026-11-09T14:00:11+00:00, book20_bid_proxy_usdt=720744, book20_ask_proxy_usdt=823440, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.57%, turnover=5708091. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T14:00:01+00:00, last15m_closed_end=2026-11-09T14:00+00:00, prior8high=2131.940000, depth_time=2026-11-09T14:00:14+00:00, book20_bid_proxy_usdt=3668341, book20_ask_proxy_usdt=2712060, funding_indicative=-0.000007, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.20%, turnover=1591283804. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-09T14:00:01+00:00, last15m_closed_end=2026-11-09T14:00+00:00, prior8high=0.000423, depth_time=2026-11-09T14:00:34+00:00, book20_bid_proxy_usdt=113868, book20_ask_proxy_usdt=95891, funding_indicative=-0.001427, next_funding_utc=2026-11-09T15:00:00+00:00, funding_cycle_h=1, 24h_change=-2.93%, turnover=5753568. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T14:00:01+00:00, last15m_closed_end=2026-11-09T14:00+00:00, prior8high=74.040000, depth_time=2026-11-09T14:00:16+00:00, book20_bid_proxy_usdt=159691, book20_ask_proxy_usdt=81606, funding_indicative=0.000035, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.19%, turnover=47913225. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T14:00:01+00:00, last15m_closed_end=2026-11-09T14:00+00:00, prior8high=3.587000, depth_time=2026-11-09T14:00:21+00:00, book20_bid_proxy_usdt=2369426, book20_ask_proxy_usdt=2605297, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.60%, turnover=46369433. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T14:00:01+00:00, last15m_closed_end=2026-11-09T14:00+00:00, prior8high=0.001521, depth_time=2026-11-09T14:00:06+00:00, book20_bid_proxy_usdt=13880, book20_ask_proxy_usdt=19792, funding_indicative=0.000019, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-21.55%, turnover=5973161. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T14:00:01+00:00, last15m_closed_end=2026-11-09T14:00+00:00, prior8high=87.100000, depth_time=2026-11-09T14:00:32+00:00, book20_bid_proxy_usdt=12204482, book20_ask_proxy_usdt=14351648, funding_indicative=0.000020, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.27%, turnover=744501940. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T14:00:01+00:00, last15m_closed_end=2026-11-09T14:00+00:00, prior8high=1.148000, depth_time=2026-11-09T14:00:25+00:00, book20_bid_proxy_usdt=2521276, book20_ask_proxy_usdt=2085968, funding_indicative=0.000022, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.39%, turnover=6332225. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T14:00:01+00:00, last15m_closed_end=2026-11-09T14:00+00:00, prior8high=1.110100, depth_time=2026-11-09T14:00:20+00:00, book20_bid_proxy_usdt=2235181, book20_ask_proxy_usdt=3657756, funding_indicative=0.000088, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.05%, turnover=284082260. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T14:00:01+00:00, last15m_closed_end=2026-11-09T14:00+00:00, prior8high=1228.080000, depth_time=2026-11-09T14:00:30+00:00, book20_bid_proxy_usdt=141182, book20_ask_proxy_usdt=144346, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.37%, turnover=2263362417. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
