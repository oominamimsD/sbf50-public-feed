# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T05:00:17Z**
- feed_generated_utc: 2026-10-14T05:00:19+00:00
- source_sha256: `278df26091cb4467072273338e9fcda3bae9ac27fc2139a8dcb6346e74f1aa09`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T05:00+00:00, close=83704.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T05:00+00:00, close=83704.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T04:00+00:00, close=83663.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|S_USDT|0.059320|-15.97|35.74|-16.23|24145433|1.68|
|W_USDT|0.016469|-8.36|13.48|-8.62|6839845|3.03|
|MAGIC_USDT|0.114390|-3.51|67.92|-3.77|5477899|1.75|
|DOT_USDT|1.165800|-1.57|-2.96|-1.83|19210171|0.86|
|TIA_USDT|0.578400|-1.12|21.43|-1.38|44956393|1.73|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.165800|1.158500|1.165800|0.46|N|Y/Y|Y/Y|N|N|
|MAGIC_USDT|0.114390|0.113190|0.114360|0.88|N|Y/Y|Y/N|N|N|
|S_USDT|0.059320|0.058620|0.059320|0.85|N|N/N|N/N|N|N|
|TIA_USDT|0.578400|0.571300|0.578400|1.04|N|N/Y|N/N|N|N|
|W_USDT|0.016469|0.016080|0.016469|1.01|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-14T05:00:00+00:00, last15m_closed_end=2026-10-14T05:00+00:00, prior8high=1.173000, depth_time=2026-10-14T05:00:13+00:00, book20_bid_proxy_usdt=449587, book20_ask_proxy_usdt=231770, funding_indicative=0.000026, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.57%, turnover=19210171. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGIC_USDT: quote_utc=2026-10-14T05:00:00+00:00, last15m_closed_end=2026-10-14T05:00+00:00, prior8high=0.118420, depth_time=2026-10-14T05:00:12+00:00, book20_bid_proxy_usdt=170076, book20_ask_proxy_usdt=176459, funding_indicative=-0.000158, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.51%, turnover=5477899. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T05:00:00+00:00, last15m_closed_end=2026-10-14T05:00+00:00, prior8high=0.060850, depth_time=2026-10-14T05:00:07+00:00, book20_bid_proxy_usdt=139338, book20_ask_proxy_usdt=48034, funding_indicative=-0.000065, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.97%, turnover=24145433. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T05:00:00+00:00, last15m_closed_end=2026-10-14T05:00+00:00, prior8high=0.580200, depth_time=2026-10-14T05:00:17+00:00, book20_bid_proxy_usdt=207893, book20_ask_proxy_usdt=177126, funding_indicative=0.000000, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.12%, turnover=44956393. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T05:00:00+00:00, last15m_closed_end=2026-10-14T05:00+00:00, prior8high=0.016514, depth_time=2026-10-14T05:00:10+00:00, book20_bid_proxy_usdt=20717, book20_ask_proxy_usdt=98171, funding_indicative=-0.000152, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.36%, turnover=6839845. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
