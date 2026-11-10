# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T18:45:28Z**
- feed_generated_utc: 2026-11-10T18:45:29+00:00
- source_sha256: `6affbffac20597cb71813fdcdaed1df1bc0c87b88992d5563a47a2765884bd49`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T18:45+00:00, close=73519, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T18:00+00:00, close=73253.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T16:00+00:00, close=73180.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.843400|-9.01|56.83|-9.48|8952014|1.63|
|ZEC_USDT|1040.530000|-4.83|-13.56|-5.30|2371082557|0.10|
|DASH_USDT|43.460000|-3.72|-5.80|-4.19|13846911|2.30|
|ANTHROPIC_USDT|1295.390000|-1.67|-22.61|-2.14|8028959|1.47|
|UNI_USDT|6.719000|-1.62|-8.62|-2.09|28482354|1.49|
|JCT_USDT|0.005190|-1.61|24.22|-2.08|22637766|3.85|
|AKE_USDT|0.002876|-1.30|-30.79|-1.77|15987770|3.48|
|ARB_USDT|0.159390|-1.23|-0.30|-1.70|36067785|0.63|
|ONDO_USDT|0.363700|-0.57|-6.55|-1.04|15312174|2.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002876|0.002739|0.002876|0.83|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1295.390000|1286.420000|1295.390000|2.71|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.159390|0.155570|0.159400|0.48|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.460000|42.350000|43.480000|0.23|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005190|0.005014|0.005176|0.51|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.363700|0.355900|0.363700|0.66|N|Y/Y|Y/N|Y|N|
|PIEVERSE_USDT|1.843400|1.808000|1.843400|0.45|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.719000|6.608000|6.719000|0.71|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1040.530000|993.710000|1039.810000|0.94|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T18:45:02+00:00, last15m_closed_end=2026-11-10T18:45+00:00, prior8high=0.003062, depth_time=2026-11-10T18:45:20+00:00, book20_bid_proxy_usdt=34988, book20_ask_proxy_usdt=33704, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.30%, turnover=15987770. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-10T18:45:01+00:00, last15m_closed_end=2026-11-10T18:45+00:00, prior8high=1325.380000, depth_time=2026-11-10T18:45:14+00:00, book20_bid_proxy_usdt=8176, book20_ask_proxy_usdt=14003, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.67%, turnover=8028959. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T18:45:02+00:00, last15m_closed_end=2026-11-10T18:45+00:00, prior8high=0.158720, depth_time=2026-11-10T18:45:21+00:00, book20_bid_proxy_usdt=101220, book20_ask_proxy_usdt=64422, funding_indicative=-0.000180, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.23%, turnover=36067785. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T18:45:02+00:00, last15m_closed_end=2026-11-10T18:45+00:00, prior8high=44.240000, depth_time=2026-11-10T18:45:09+00:00, book20_bid_proxy_usdt=596521, book20_ask_proxy_usdt=582038, funding_indicative=-0.000132, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.72%, turnover=13846911. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T18:45:02+00:00, last15m_closed_end=2026-11-10T18:45+00:00, prior8high=0.005498, depth_time=2026-11-10T18:45:18+00:00, book20_bid_proxy_usdt=57502, book20_ask_proxy_usdt=44521, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.61%, turnover=22637766. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-10T18:45:02+00:00, last15m_closed_end=2026-11-10T18:45+00:00, prior8high=0.365600, depth_time=2026-11-10T18:45:26+00:00, book20_bid_proxy_usdt=2100582, book20_ask_proxy_usdt=2423513, funding_indicative=-0.000014, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.57%, turnover=15312174. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T18:45:02+00:00, last15m_closed_end=2026-11-10T18:45+00:00, prior8high=1.965000, depth_time=2026-11-10T18:45:07+00:00, book20_bid_proxy_usdt=19216, book20_ask_proxy_usdt=12016, funding_indicative=0.000134, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.01%, turnover=8952014. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T18:45:02+00:00, last15m_closed_end=2026-11-10T18:45+00:00, prior8high=6.776000, depth_time=2026-11-10T18:45:17+00:00, book20_bid_proxy_usdt=2091687, book20_ask_proxy_usdt=2497266, funding_indicative=-0.000017, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.62%, turnover=28482354. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T18:45:02+00:00, last15m_closed_end=2026-11-10T18:45+00:00, prior8high=1062.810000, depth_time=2026-11-10T18:45:09+00:00, book20_bid_proxy_usdt=137038, book20_ask_proxy_usdt=53456, funding_indicative=-0.000037, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.83%, turnover=2371082557. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
