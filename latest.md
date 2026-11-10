# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T18:15:33Z**
- feed_generated_utc: 2026-11-10T18:15:35+00:00
- source_sha256: `0494cec769f4fdb3deb96a57b37e39854a2ace9a1768c1c4195ea2f9b6eddd8a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T18:15+00:00, close=73159.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T18:00+00:00, close=73253.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T16:00+00:00, close=73180.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.835800|-9.39|56.18|-9.37|8886560|2.72|
|ZEC_USDT|1028.790000|-5.90|-14.53|-5.88|2324315092|1.07|
|DASH_USDT|43.380000|-3.89|-5.98|-3.87|13629196|2.30|
|ARB_USDT|0.156270|-3.16|-2.25|-3.14|35748377|0.64|
|UNI_USDT|6.657000|-2.53|-9.46|-2.51|27609472|1.50|
|JCT_USDT|0.005148|-2.40|23.21|-2.38|22502430|3.88|
|ANTHROPIC_USDT|1294.710000|-1.73|-22.65|-1.71|7888207|1.62|
|ONDO_USDT|0.360300|-1.50|-7.42|-1.48|15052029|2.78|
|DOGE_USDT|0.066680|-1.39|-11.65|-1.37|85645091|1.50|
|HYPE_USDT|70.798000|-1.35|-18.94|-1.33|41258611|0.14|
|TIA_USDT|0.419500|-1.24|-3.74|-1.22|9517294|2.38|
|ENA_USDT|0.147450|-1.16|-14.36|-1.14|27221329|0.68|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1294.710000|1286.420000|1294.710000|0.79|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.156270|0.155570|0.156270|0.21|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.380000|42.350000|43.380000|0.88|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.066680|0.066560|0.066680|0.86|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.147450|0.146600|0.147450|0.52|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|70.798000|70.375000|70.798000|0.61|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005148|0.004969|0.005149|0.43|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.360300|0.355900|0.360300|0.47|N|Y/Y|Y/N|Y|N|
|PIEVERSE_USDT|1.835800|1.808000|1.835800|0.71|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.419500|0.412300|0.419500|0.32|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.657000|6.608000|6.664000|0.61|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1028.790000|993.710000|1028.740000|0.82|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-10T18:14:58+00:00, last15m_closed_end=2026-11-10T18:15+00:00, prior8high=1326.010000, depth_time=2026-11-10T18:15:20+00:00, book20_bid_proxy_usdt=21244, book20_ask_proxy_usdt=24452, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=7888207. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T18:14:59+00:00, last15m_closed_end=2026-11-10T18:15+00:00, prior8high=0.162090, depth_time=2026-11-10T18:15:13+00:00, book20_bid_proxy_usdt=61936, book20_ask_proxy_usdt=85202, funding_indicative=-0.000158, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=35748377. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T18:14:59+00:00, last15m_closed_end=2026-11-10T18:15+00:00, prior8high=45.460000, depth_time=2026-11-10T18:15:11+00:00, book20_bid_proxy_usdt=652720, book20_ask_proxy_usdt=697309, funding_indicative=-0.000116, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.89%, turnover=13629196. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-10T18:14:59+00:00, last15m_closed_end=2026-11-10T18:15+00:00, prior8high=0.068140, depth_time=2026-11-10T18:15:24+00:00, book20_bid_proxy_usdt=4808444, book20_ask_proxy_usdt=5278781, funding_indicative=-0.000080, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.39%, turnover=85645091. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-10T18:14:59+00:00, last15m_closed_end=2026-11-10T18:15+00:00, prior8high=0.151150, depth_time=2026-11-10T18:15:31+00:00, book20_bid_proxy_usdt=122860, book20_ask_proxy_usdt=176809, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.16%, turnover=27221329. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T18:14:59+00:00, last15m_closed_end=2026-11-10T18:15+00:00, prior8high=72.358000, depth_time=2026-11-10T18:15:27+00:00, book20_bid_proxy_usdt=94600, book20_ask_proxy_usdt=49888, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.35%, turnover=41258611. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T18:14:59+00:00, last15m_closed_end=2026-11-10T18:15+00:00, prior8high=0.005498, depth_time=2026-11-10T18:15:18+00:00, book20_bid_proxy_usdt=56497, book20_ask_proxy_usdt=42020, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.40%, turnover=22502430. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-10T18:14:59+00:00, last15m_closed_end=2026-11-10T18:15+00:00, prior8high=0.370400, depth_time=2026-11-10T18:15:22+00:00, book20_bid_proxy_usdt=2552291, book20_ask_proxy_usdt=2289961, funding_indicative=-0.000021, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.50%, turnover=15052029. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T18:14:59+00:00, last15m_closed_end=2026-11-10T18:15+00:00, prior8high=2.065500, depth_time=2026-11-10T18:15:06+00:00, book20_bid_proxy_usdt=10818, book20_ask_proxy_usdt=10650, funding_indicative=0.000121, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.39%, turnover=8886560. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-10T18:14:59+00:00, last15m_closed_end=2026-11-10T18:15+00:00, prior8high=0.427500, depth_time=2026-11-10T18:15:28+00:00, book20_bid_proxy_usdt=444077, book20_ask_proxy_usdt=502812, funding_indicative=0.000020, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.24%, turnover=9517294. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T18:14:59+00:00, last15m_closed_end=2026-11-10T18:15+00:00, prior8high=6.882000, depth_time=2026-11-10T18:15:15+00:00, book20_bid_proxy_usdt=3303230, book20_ask_proxy_usdt=2605120, funding_indicative=-0.000006, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=27609472. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T18:14:59+00:00, last15m_closed_end=2026-11-10T18:15+00:00, prior8high=1100.680000, depth_time=2026-11-10T18:15:09+00:00, book20_bid_proxy_usdt=88511, book20_ask_proxy_usdt=246221, funding_indicative=-0.000035, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.90%, turnover=2324315092. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
