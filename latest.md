# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T18:30:20Z**
- feed_generated_utc: 2026-10-14T18:30:21+00:00
- source_sha256: `3a88dcf778af017ac1589f12c72e50cbc5399f013b59cc6913f06fdba4d10c09`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T18:30+00:00, close=81606.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T18:00+00:00, close=81556.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T16:00+00:00, close=81600.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.123100|-10.74|71.73|-10.74|58991623|7.54|
|S_USDT|0.052680|-3.85|32.22|-3.85|7649613|1.90|
|STRK_USDT|0.075730|-1.87|53.11|-1.87|24828890|1.32|
|BAT_USDT|0.171660|-1.58|73.11|-1.58|36565076|1.75|
|FET_USDT|0.200900|-1.47|-11.30|-1.47|9154437|9.96|
|AAVE_USDT|154.320000|-1.00|-10.15|-1.00|23865144|0.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.320000|154.150000|154.320000|1.31|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.171660|0.169480|0.171680|0.41|N|Y/Y|N/N|Y|N|
|BTW_USDT|2.123100|2.064400|2.123100|0.36|N|Y/Y|N/N|Y|N|
|FET_USDT|0.200900|0.202000|0.200900|1.98|Y|Y/Y|Y/Y|Y|Y|
|STRK_USDT|0.075730|0.075170|0.075730|0.34|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.052680|0.052320|0.052680|0.76|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-14T18:30:00+00:00, last15m_closed_end=2026-10-14T18:30+00:00, prior8high=158.400000, depth_time=2026-10-14T18:30:18+00:00, book20_bid_proxy_usdt=257617, book20_ask_proxy_usdt=365818, funding_indicative=0.000033, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=23865144. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-14T18:30:00+00:00, last15m_closed_end=2026-10-14T18:30+00:00, prior8high=0.174590, depth_time=2026-10-14T18:30:15+00:00, book20_bid_proxy_usdt=29644, book20_ask_proxy_usdt=26855, funding_indicative=0.000048, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=36565076. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-14T18:30:00+00:00, last15m_closed_end=2026-10-14T18:30+00:00, prior8high=2.406000, depth_time=2026-10-14T18:30:07+00:00, book20_bid_proxy_usdt=5732, book20_ask_proxy_usdt=13391, funding_indicative=-0.000008, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-10.74%, turnover=58991623. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T18:30:00+00:00, last15m_closed_end=2026-10-14T18:30+00:00, prior8high=0.208600, depth_time=2026-10-14T18:30:16+00:00, book20_bid_proxy_usdt=1192497, book20_ask_proxy_usdt=1023267, funding_indicative=-0.000040, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=9154437. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T18:30:00+00:00, last15m_closed_end=2026-10-14T18:30+00:00, prior8high=0.077570, depth_time=2026-10-14T18:30:11+00:00, book20_bid_proxy_usdt=160883, book20_ask_proxy_usdt=208382, funding_indicative=0.000049, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.87%, turnover=24828890. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T18:30:00+00:00, last15m_closed_end=2026-10-14T18:30+00:00, prior8high=0.054540, depth_time=2026-10-14T18:30:09+00:00, book20_bid_proxy_usdt=191722, book20_ask_proxy_usdt=118748, funding_indicative=-0.000063, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.85%, turnover=7649613. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
