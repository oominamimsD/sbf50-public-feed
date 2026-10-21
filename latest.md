# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T04:15:18Z**
- feed_generated_utc: 2026-10-21T04:15:21+00:00
- source_sha256: `20b83514720700a3e6e6e087f2fb19b4ce9f338806faf493672dee0a33e450d7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T04:15+00:00, close=82770.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T04:00+00:00, close=82699, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T04:00+00:00, close=82699, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.186400|-13.61|5.08|-13.83|10525512|0.54|
|XMR_USDT|577.730000|-6.84|9.43|-7.06|20686137|1.38|
|BR_USDT|0.619510|-4.78|43.07|-5.00|34548118|1.45|
|AGT_USDT|0.061619|-4.65|280.90|-4.87|6851488|5.52|
|PHA_USDT|0.056730|-1.88|3.08|-2.10|8305928|3.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.061619|0.060783|0.061619|0.33|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.186400|0.185410|0.186400|1.18|N|Y/Y|Y/N|N|N|
|BR_USDT|0.619510|0.613570|0.619510|0.99|N|Y/Y|N/N|N|N|
|PHA_USDT|0.056730|0.056980|0.056730|3.47|Y|Y/Y|N/N|N|N|
|XMR_USDT|577.730000|571.180000|577.730000|0.29|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T04:14:59+00:00, last15m_closed_end=2026-10-21T04:15+00:00, prior8high=0.064559, depth_time=2026-10-21T04:15:14+00:00, book20_bid_proxy_usdt=3773, book20_ask_proxy_usdt=7312, funding_indicative=0.000047, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.65%, turnover=6851488. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T04:15:00+00:00, last15m_closed_end=2026-10-21T04:15+00:00, prior8high=0.188920, depth_time=2026-10-21T04:15:07+00:00, book20_bid_proxy_usdt=26727, book20_ask_proxy_usdt=34228, funding_indicative=0.000006, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-13.61%, turnover=10525512. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T04:14:59+00:00, last15m_closed_end=2026-10-21T04:15+00:00, prior8high=0.640830, depth_time=2026-10-21T04:15:11+00:00, book20_bid_proxy_usdt=2980, book20_ask_proxy_usdt=3846, funding_indicative=-0.000010, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.78%, turnover=34548118. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T04:15:00+00:00, last15m_closed_end=2026-10-21T04:15+00:00, prior8high=0.058840, depth_time=2026-10-21T04:15:17+00:00, book20_bid_proxy_usdt=67277, book20_ask_proxy_usdt=64318, funding_indicative=0.000018, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.88%, turnover=8305928. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T04:15:00+00:00, last15m_closed_end=2026-10-21T04:15+00:00, prior8high=582.810000, depth_time=2026-10-21T04:15:10+00:00, book20_bid_proxy_usdt=21929, book20_ask_proxy_usdt=15255, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.84%, turnover=20686137. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
