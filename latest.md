# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T07:30:12Z**
- feed_generated_utc: 2026-10-19T07:30:14+00:00
- source_sha256: `551d4f9ff23b0fd698a8a44604e9572508c84d07e393d4ba25b53d026b59e620`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T07:30+00:00, close=82846.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T07:00+00:00, close=82812.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T04:00+00:00, close=82496.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.240600|-2.81|33.19|-4.91|21848122|0.45|
|STRK_USDT|0.059900|-2.69|-49.77|-4.79|17653493|1.67|
|TIA_USDT|0.611700|-1.00|3.90|-3.10|56800281|1.63|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.240600|2.166400|2.240600|1.14|N|Y/Y|N/N|N|N|
|STRK_USDT|0.059900|0.059350|0.059900|2.46|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.611700|0.605400|0.611700|0.45|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T07:29:59+00:00, last15m_closed_end=2026-10-19T07:30+00:00, prior8high=2.321000, depth_time=2026-10-19T07:30:06+00:00, book20_bid_proxy_usdt=13678, book20_ask_proxy_usdt=7182, funding_indicative=-0.000249, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.81%, turnover=21848122. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T07:29:59+00:00, last15m_closed_end=2026-10-19T07:30+00:00, prior8high=0.060780, depth_time=2026-10-19T07:30:09+00:00, book20_bid_proxy_usdt=578555, book20_ask_proxy_usdt=648750, funding_indicative=0.000050, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.69%, turnover=17653493. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T07:29:59+00:00, last15m_closed_end=2026-10-19T07:30+00:00, prior8high=0.616500, depth_time=2026-10-19T07:30:11+00:00, book20_bid_proxy_usdt=169268, book20_ask_proxy_usdt=291450, funding_indicative=-0.000041, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.00%, turnover=56800281. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
