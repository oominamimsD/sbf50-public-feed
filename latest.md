# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T08:30:14Z**
- feed_generated_utc: 2026-10-16T08:30:16+00:00
- source_sha256: `fe6c46c4ebeeee90f089c4190e00a5c555b6a0d5f0f7b95b28392bbf0d11986d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T08:30+00:00, close=82232.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T08:00+00:00, close=82258.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T08:00+00:00, close=82258.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.079140|-17.87|31.54|-17.71|47683252|1.26|
|AKE_USDT|0.028954|-8.38|-0.23|-8.22|21161016|0.34|
|RLC_USDT|0.868200|-5.20|18.42|-5.04|5010825|2.30|
|NIL_USDT|0.083110|-4.33|-4.01|-4.17|8390617|3.61|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.028954|0.028896|0.028954|2.19|N|Y/Y|N/N|Y|N|
|NIL_USDT|0.083110|0.082740|0.083110|1.69|N|Y/Y|Y/N|Y|N|
|RLC_USDT|0.868200|0.860300|0.868600|2.54|N|N/N|Y/Y|Y|N|
|STRK_USDT|0.079140|0.078680|0.079140|1.77|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T08:30:01+00:00, last15m_closed_end=2026-10-16T08:30+00:00, prior8high=0.031217, depth_time=2026-10-16T08:30:09+00:00, book20_bid_proxy_usdt=15184, book20_ask_proxy_usdt=12389, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.38%, turnover=21161016. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T08:30:01+00:00, last15m_closed_end=2026-10-16T08:30+00:00, prior8high=0.086860, depth_time=2026-10-16T08:30:13+00:00, book20_bid_proxy_usdt=16501, book20_ask_proxy_usdt=35118, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.33%, turnover=8390617. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-16T08:30:01+00:00, last15m_closed_end=2026-10-16T08:30+00:00, prior8high=0.888900, depth_time=2026-10-16T08:30:10+00:00, book20_bid_proxy_usdt=69739, book20_ask_proxy_usdt=48019, funding_indicative=-0.000547, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.20%, turnover=5010825. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T08:30:01+00:00, last15m_closed_end=2026-10-16T08:30+00:00, prior8high=0.083550, depth_time=2026-10-16T08:30:06+00:00, book20_bid_proxy_usdt=273958, book20_ask_proxy_usdt=403733, funding_indicative=-0.000016, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-17.87%, turnover=47683252. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
