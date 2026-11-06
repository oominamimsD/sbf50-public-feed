# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T19:15:14Z**
- feed_generated_utc: 2026-11-06T19:15:15+00:00
- source_sha256: `e79b630cd30b6ccb29634735d90cc59fe916ca780f827bb4aa8756a6f93e74ef`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T19:15+00:00, close=75753.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T19:00+00:00, close=75764.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T16:00+00:00, close=75832.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.126600|-33.36|-52.33|-33.26|29242980|7.90|
|ANTHROPIC_USDT|1349.010000|-5.74|-19.53|-5.64|5320515|1.78|
|AKE_USDT|0.003603|-4.30|-80.95|-4.20|53114850|2.78|
|LIT_USDT|3.316600|-2.23|17.43|-2.13|11891024|0.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003603|0.003535|0.003603|0.41|N|Y/Y|Y/N|Y|N|
|ANTHROPIC_USDT|1349.010000|1326.270000|1349.010000|0.81|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.316600|3.306100|3.316600|0.63|N|Y/Y|N/N|Y|N|
|UAI_USDT|0.126600|0.112900|0.126600|2.42|N|Y/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-06T19:15:00+00:00, last15m_closed_end=2026-11-06T19:15+00:00, prior8high=0.004389, depth_time=2026-11-06T19:15:11+00:00, book20_bid_proxy_usdt=30664, book20_ask_proxy_usdt=21833, funding_indicative=-0.000817, next_funding_utc=2026-11-06T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.30%, turnover=53114850. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-06T19:15:00+00:00, last15m_closed_end=2026-11-06T19:15+00:00, prior8high=1385.470000, depth_time=2026-11-06T19:15:09+00:00, book20_bid_proxy_usdt=46914, book20_ask_proxy_usdt=18386, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.74%, turnover=5320515. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-06T19:15:00+00:00, last15m_closed_end=2026-11-06T19:15+00:00, prior8high=3.455000, depth_time=2026-11-06T19:15:12+00:00, book20_bid_proxy_usdt=25327, book20_ask_proxy_usdt=20077, funding_indicative=0.000050, next_funding_utc=2026-11-06T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.23%, turnover=11891024. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-06T19:15:00+00:00, last15m_closed_end=2026-11-06T19:15+00:00, prior8high=0.249200, depth_time=2026-11-06T19:15:06+00:00, book20_bid_proxy_usdt=138272, book20_ask_proxy_usdt=140742, funding_indicative=0.000050, next_funding_utc=2026-11-06T20:00:00+00:00, funding_cycle_h=4, 24h_change=-33.36%, turnover=29242980. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
