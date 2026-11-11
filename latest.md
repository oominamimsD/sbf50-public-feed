# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T01:45:19Z**
- feed_generated_utc: 2026-11-11T01:45:20+00:00
- source_sha256: `c6b3adfd2ae77f95f1c4a6191550027af13ab547f803236a0ae45a0f5a534d2c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T01:45+00:00, close=73826.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T01:00+00:00, close=73513.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T00:00+00:00, close=73762.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.207580|-17.27|54.35|-18.15|58298980|1.93|
|PIEVERSE_USDT|1.847200|-8.82|57.15|-9.70|5130402|0.54|
|ZEC_USDT|1029.400000|-5.84|-14.48|-6.72|2221882974|0.10|
|DASH_USDT|44.040000|-2.43|-4.55|-3.31|14404856|2.27|
|JCT_USDT|0.005176|-1.87|23.88|-2.75|18705651|5.78|
|UNI_USDT|6.797000|-0.48|-7.56|-1.36|34982167|2.94|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|44.040000|42.610000|44.040000|1.64|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.207580|0.192760|0.208040|0.33|N|Y/Y|N/N|Y|N|
|JCT_USDT|0.005176|0.004964|0.005174|0.88|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.847200|1.808000|1.847200|1.01|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.797000|6.647000|6.797000|1.29|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1029.400000|1016.660000|1030.450000|1.90|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-11-11T01:45:02+00:00, last15m_closed_end=2026-11-11T01:45+00:00, prior8high=43.690000, depth_time=2026-11-11T01:45:13+00:00, book20_bid_proxy_usdt=734672, book20_ask_proxy_usdt=578304, funding_indicative=-0.000177, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.43%, turnover=14404856. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T01:45:02+00:00, last15m_closed_end=2026-11-11T01:45+00:00, prior8high=0.226550, depth_time=2026-11-11T01:45:06+00:00, book20_bid_proxy_usdt=4582, book20_ask_proxy_usdt=32344, funding_indicative=-0.011672, next_funding_utc=2026-11-11T02:00:00+00:00, funding_cycle_h=1, 24h_change=-17.27%, turnover=58298980. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-11T01:45:02+00:00, last15m_closed_end=2026-11-11T01:45+00:00, prior8high=0.005301, depth_time=2026-11-11T01:45:16+00:00, book20_bid_proxy_usdt=68609, book20_ask_proxy_usdt=44048, funding_indicative=0.000357, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.87%, turnover=18705651. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-11T01:45:02+00:00, last15m_closed_end=2026-11-11T01:45+00:00, prior8high=1.870000, depth_time=2026-11-11T01:45:05+00:00, book20_bid_proxy_usdt=16388, book20_ask_proxy_usdt=10624, funding_indicative=0.000110, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.82%, turnover=5130402. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T01:45:02+00:00, last15m_closed_end=2026-11-11T01:45+00:00, prior8high=6.757000, depth_time=2026-11-11T01:45:18+00:00, book20_bid_proxy_usdt=2225935, book20_ask_proxy_usdt=1861892, funding_indicative=0.000024, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.48%, turnover=34982167. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T01:45:02+00:00, last15m_closed_end=2026-11-11T01:45+00:00, prior8high=1049.410000, depth_time=2026-11-11T01:45:11+00:00, book20_bid_proxy_usdt=160532, book20_ask_proxy_usdt=213382, funding_indicative=0.000085, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.84%, turnover=2221882974. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
