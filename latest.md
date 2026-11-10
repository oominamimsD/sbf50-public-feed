# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T01:15:17Z**
- feed_generated_utc: 2026-11-10T01:15:18+00:00
- source_sha256: `8feefcc38751ecd484e77612a19d60ddb4a669f11073efae57007fd6fcc1348c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T01:15+00:00, close=75181.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T01:00+00:00, close=75052, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-10T00:00+00:00, close=75327.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002550|-47.92|-53.65|-47.50|12545056|7.83|
|ARB_USDT|0.174400|-5.23|9.45|-4.81|31119294|0.57|
|ZEC_USDT|1175.650000|-4.08|-6.25|-3.66|2375460148|0.09|
|DOT_USDT|0.854600|-4.07|-8.51|-3.65|10593353|1.17|
|QNT_USDT|194.220000|-2.90|-4.06|-2.48|39764617|0.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002550|0.002154|0.002548|4.14|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.174400|0.173630|0.174400|1.76|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.854600|0.852500|0.854600|3.85|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.220000|193.200000|194.220000|1.34|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1175.650000|1152.430000|1175.650000|1.17|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T01:15:00+00:00, last15m_closed_end=2026-11-10T01:15+00:00, prior8high=0.005150, depth_time=2026-11-10T01:15:07+00:00, book20_bid_proxy_usdt=25269, book20_ask_proxy_usdt=94183, funding_indicative=-0.000576, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-47.92%, turnover=12545056. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T01:14:59+00:00, last15m_closed_end=2026-11-10T01:15+00:00, prior8high=0.176000, depth_time=2026-11-10T01:15:02+00:00, book20_bid_proxy_usdt=387001, book20_ask_proxy_usdt=30021, funding_indicative=-0.000020, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.23%, turnover=31119294. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T01:15:00+00:00, last15m_closed_end=2026-11-10T01:15+00:00, prior8high=0.858500, depth_time=2026-11-10T01:15:14+00:00, book20_bid_proxy_usdt=714870, book20_ask_proxy_usdt=743968, funding_indicative=0.000021, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.07%, turnover=10593353. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T01:15:00+00:00, last15m_closed_end=2026-11-10T01:15+00:00, prior8high=195.740000, depth_time=2026-11-10T01:15:16+00:00, book20_bid_proxy_usdt=53556, book20_ask_proxy_usdt=59556, funding_indicative=0.000100, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.90%, turnover=39764617. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T01:15:00+00:00, last15m_closed_end=2026-11-10T01:15+00:00, prior8high=1174.770000, depth_time=2026-11-10T01:15:12+00:00, book20_bid_proxy_usdt=132620, book20_ask_proxy_usdt=236869, funding_indicative=0.000099, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.08%, turnover=2375460148. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
