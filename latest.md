# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T01:30:19Z**
- feed_generated_utc: 2026-11-11T01:30:20+00:00
- source_sha256: `e360c9c8e38ca7102631f76aa2a643a965565a54ad99f2c3709d45e097311205`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T01:30+00:00, close=73749.6, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-11T01:00+00:00, close=73513.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T00:00+00:00, close=73762.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.208100|-17.07|54.74|-17.86|58057070|0.48|
|PIEVERSE_USDT|1.824100|-9.96|55.18|-10.75|5114486|0.55|
|ZEC_USDT|1031.060000|-5.69|-14.35|-6.48|2188776129|0.10|
|JCT_USDT|0.005091|-3.48|21.85|-4.27|18673879|3.93|
|DASH_USDT|43.620000|-3.36|-5.46|-4.15|14202692|2.29|
|UNI_USDT|6.752000|-1.14|-8.17|-1.93|34653258|2.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|43.620000|42.540000|43.620000|0.91|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.208100|0.192760|0.208850|0.60|N|Y/Y|N/N|Y|N|
|JCT_USDT|0.005091|0.004964|0.005095|1.30|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.824100|1.808000|1.826300|0.76|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.752000|6.624000|6.752000|1.09|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1031.060000|1025.270000|1030.640000|1.72|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-11-11T01:30:03+00:00, last15m_closed_end=2026-11-11T01:30+00:00, prior8high=43.660000, depth_time=2026-11-11T01:30:16+00:00, book20_bid_proxy_usdt=313576, book20_ask_proxy_usdt=579829, funding_indicative=-0.000205, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.36%, turnover=14202692. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T01:30:03+00:00, last15m_closed_end=2026-11-11T01:30+00:00, prior8high=0.226550, depth_time=2026-11-11T01:30:07+00:00, book20_bid_proxy_usdt=8841, book20_ask_proxy_usdt=7743, funding_indicative=-0.011785, next_funding_utc=2026-11-11T02:00:00+00:00, funding_cycle_h=1, 24h_change=-17.07%, turnover=58057070. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-11T01:30:03+00:00, last15m_closed_end=2026-11-11T01:30+00:00, prior8high=0.005301, depth_time=2026-11-11T01:30:11+00:00, book20_bid_proxy_usdt=53772, book20_ask_proxy_usdt=47098, funding_indicative=0.000369, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.48%, turnover=18673879. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-11T01:30:03+00:00, last15m_closed_end=2026-11-11T01:30+00:00, prior8high=1.870000, depth_time=2026-11-11T01:30:03+00:00, book20_bid_proxy_usdt=16917, book20_ask_proxy_usdt=6514, funding_indicative=0.000078, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.96%, turnover=5114486. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T01:30:03+00:00, last15m_closed_end=2026-11-11T01:30+00:00, prior8high=6.740000, depth_time=2026-11-11T01:30:18+00:00, book20_bid_proxy_usdt=1386963, book20_ask_proxy_usdt=1979585, funding_indicative=0.000005, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.14%, turnover=34653258. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T01:30:03+00:00, last15m_closed_end=2026-11-11T01:30+00:00, prior8high=1049.410000, depth_time=2026-11-11T01:30:12+00:00, book20_bid_proxy_usdt=190126, book20_ask_proxy_usdt=144885, funding_indicative=0.000076, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.69%, turnover=2188776129. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
