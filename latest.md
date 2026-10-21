# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T07:15:20Z**
- feed_generated_utc: 2026-10-21T07:15:23+00:00
- source_sha256: `fb8239d40e4f39d65e0202f98a8c425f4733267a245d8191d896e0533f28bed1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T07:15+00:00, close=82788.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T07:00+00:00, close=82752, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T04:00+00:00, close=82699, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.186010|-13.79|4.86|-14.04|10716687|6.99|
|BR_USDT|0.581590|-10.61|34.31|-10.86|30207204|0.17|
|XMR_USDT|588.070000|-5.18|11.39|-5.43|21506462|1.02|
|PHA_USDT|0.056960|-1.48|3.50|-1.73|5880428|3.51|
|SILVER_USDT|57.330000|-1.06|-3.46|-1.31|220942358|1.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.186010|0.181950|0.186010|1.92|N|Y/Y|Y/N|N|N|
|BR_USDT|0.581590|0.577510|0.581590|1.03|N|Y/Y|N/N|N|N|
|PHA_USDT|0.056960|0.055950|0.056960|0.63|N|Y/Y|N/N|N|N|
|SILVER_USDT|57.330000|57.210000|57.330000|0.60|N|Y/Y|Y/N|N|N|
|XMR_USDT|588.070000|575.320000|588.070000|3.51|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-21T07:15:00+00:00, last15m_closed_end=2026-10-21T07:15+00:00, prior8high=0.186710, depth_time=2026-10-21T07:15:10+00:00, book20_bid_proxy_usdt=29880, book20_ask_proxy_usdt=20247, funding_indicative=-0.000132, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-13.79%, turnover=10716687. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T07:15:00+00:00, last15m_closed_end=2026-10-21T07:15+00:00, prior8high=0.595790, depth_time=2026-10-21T07:15:12+00:00, book20_bid_proxy_usdt=2475, book20_ask_proxy_usdt=2565, funding_indicative=0.000043, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.61%, turnover=30207204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T07:15:00+00:00, last15m_closed_end=2026-10-21T07:15+00:00, prior8high=0.057320, depth_time=2026-10-21T07:15:17+00:00, book20_bid_proxy_usdt=69272, book20_ask_proxy_usdt=98903, funding_indicative=-0.000048, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.48%, turnover=5880428. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T07:15:00+00:00, last15m_closed_end=2026-10-21T07:15+00:00, prior8high=57.780000, depth_time=2026-10-21T07:15:18+00:00, book20_bid_proxy_usdt=44612424, book20_ask_proxy_usdt=31605939, funding_indicative=0.000040, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.06%, turnover=220942358. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T07:15:00+00:00, last15m_closed_end=2026-10-21T07:15+00:00, prior8high=581.680000, depth_time=2026-10-21T07:15:15+00:00, book20_bid_proxy_usdt=16651, book20_ask_proxy_usdt=12143, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.18%, turnover=21506462. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
