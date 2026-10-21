# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T08:15:21Z**
- feed_generated_utc: 2026-10-21T08:15:24+00:00
- source_sha256: `b51dd313a7ac9d32d479bd66c570434ff8b88022646a83d743be648f951da612`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T08:15+00:00, close=83164.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T08:00+00:00, close=83117.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T08:00+00:00, close=83117.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.044945|-30.45|177.83|-31.15|7057939|4.67|
|BAT_USDT|0.188530|-12.62|6.28|-13.32|10983311|0.53|
|BR_USDT|0.604400|-7.11|39.58|-7.81|27926514|3.64|
|XMR_USDT|586.860000|-5.37|11.16|-6.07|21142949|1.36|
|PHA_USDT|0.057080|-1.27|3.72|-1.97|5153267|3.50|
|SILVER_USDT|57.440000|-0.88|-3.28|-1.58|213165200|1.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.044945|0.038698|0.044945|5.16|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.188530|0.181950|0.188530|1.64|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.604400|0.575440|0.602400|3.17|N|Y/Y|N/N|N|N|
|PHA_USDT|0.057080|0.056400|0.057080|0.27|N|Y/Y|N/N|N|N|
|SILVER_USDT|57.440000|57.210000|57.440000|0.23|N|Y/Y|N/N|N|N|
|XMR_USDT|586.860000|576.740000|586.860000|1.04|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T08:15:01+00:00, last15m_closed_end=2026-10-21T08:15+00:00, prior8high=0.062194, depth_time=2026-10-21T08:15:08+00:00, book20_bid_proxy_usdt=8141, book20_ask_proxy_usdt=12821, funding_indicative=0.000047, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-30.45%, turnover=7057939. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T08:15:01+00:00, last15m_closed_end=2026-10-21T08:15+00:00, prior8high=0.190510, depth_time=2026-10-21T08:15:11+00:00, book20_bid_proxy_usdt=23967, book20_ask_proxy_usdt=29496, funding_indicative=-0.000131, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-12.62%, turnover=10983311. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T08:15:01+00:00, last15m_closed_end=2026-10-21T08:15+00:00, prior8high=0.595260, depth_time=2026-10-21T08:15:13+00:00, book20_bid_proxy_usdt=2455, book20_ask_proxy_usdt=6271, funding_indicative=0.000050, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.11%, turnover=27926514. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T08:15:01+00:00, last15m_closed_end=2026-10-21T08:15+00:00, prior8high=0.057200, depth_time=2026-10-21T08:15:18+00:00, book20_bid_proxy_usdt=83674, book20_ask_proxy_usdt=70364, funding_indicative=-0.000014, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.27%, turnover=5153267. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T08:15:01+00:00, last15m_closed_end=2026-10-21T08:15+00:00, prior8high=57.550000, depth_time=2026-10-21T08:15:20+00:00, book20_bid_proxy_usdt=37113911, book20_ask_proxy_usdt=40129696, funding_indicative=0.000019, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.88%, turnover=213165200. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T08:15:01+00:00, last15m_closed_end=2026-10-21T08:15+00:00, prior8high=588.220000, depth_time=2026-10-21T08:15:16+00:00, book20_bid_proxy_usdt=9248, book20_ask_proxy_usdt=23747, funding_indicative=0.000100, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.37%, turnover=21142949. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
