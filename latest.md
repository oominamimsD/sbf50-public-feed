# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T20:15:21Z**
- feed_generated_utc: 2026-11-10T20:15:23+00:00
- source_sha256: `f7c7d56d2793aeefd097d030c44bb708649761990786845812be161e85d9f285`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T20:15+00:00, close=73518.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T20:00+00:00, close=73437.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T20:00+00:00, close=73437.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.828300|-9.76|55.54|-10.22|6954120|1.64|
|ZEC_USDT|1039.090000|-4.96|-13.68|-5.42|2284486508|0.10|
|DASH_USDT|42.910000|-4.94|-7.00|-5.40|13344680|2.33|
|JCT_USDT|0.005156|-2.25|23.40|-2.71|20758270|5.82|
|ARB_USDT|0.159000|-1.47|-0.55|-1.93|33799915|0.63|
|ANTHROPIC_USDT|1299.810000|-1.34|-22.35|-1.80|8062260|0.92|
|UNI_USDT|6.744000|-1.25|-8.28|-1.71|29151413|1.48|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1299.810000|1285.250000|1299.810000|1.37|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.159000|0.155860|0.159000|0.63|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|42.910000|42.790000|42.910000|0.80|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005156|0.005022|0.005156|0.35|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.828300|1.810300|1.828300|0.83|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.744000|6.649000|6.744000|0.67|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1039.090000|1020.790000|1039.250000|0.73|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-10T20:15:00+00:00, last15m_closed_end=2026-11-10T20:15+00:00, prior8high=1311.230000, depth_time=2026-11-10T20:15:18+00:00, book20_bid_proxy_usdt=2740, book20_ask_proxy_usdt=21870, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=8062260. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T20:15:00+00:00, last15m_closed_end=2026-11-10T20:15+00:00, prior8high=0.160720, depth_time=2026-11-10T20:15:15+00:00, book20_bid_proxy_usdt=70972, book20_ask_proxy_usdt=63896, funding_indicative=-0.000192, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=33799915. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T20:15:00+00:00, last15m_closed_end=2026-11-10T20:15+00:00, prior8high=43.690000, depth_time=2026-11-10T20:15:08+00:00, book20_bid_proxy_usdt=403109, book20_ask_proxy_usdt=616326, funding_indicative=-0.000162, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.94%, turnover=13344680. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T20:15:00+00:00, last15m_closed_end=2026-11-10T20:15+00:00, prior8high=0.005277, depth_time=2026-11-10T20:15:13+00:00, book20_bid_proxy_usdt=73156, book20_ask_proxy_usdt=35878, funding_indicative=0.000137, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.25%, turnover=20758270. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T20:15:00+00:00, last15m_closed_end=2026-11-10T20:15+00:00, prior8high=1.873800, depth_time=2026-11-10T20:15:07+00:00, book20_bid_proxy_usdt=24608, book20_ask_proxy_usdt=12968, funding_indicative=0.000176, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.76%, turnover=6954120. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T20:15:00+00:00, last15m_closed_end=2026-11-10T20:15+00:00, prior8high=6.745000, depth_time=2026-11-10T20:15:20+00:00, book20_bid_proxy_usdt=1542252, book20_ask_proxy_usdt=1933762, funding_indicative=-0.000008, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=29151413. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T20:15:00+00:00, last15m_closed_end=2026-11-10T20:15+00:00, prior8high=1044.640000, depth_time=2026-11-10T20:15:09+00:00, book20_bid_proxy_usdt=268741, book20_ask_proxy_usdt=127366, funding_indicative=0.000006, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.96%, turnover=2284486508. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
