# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T05:00:20Z**
- feed_generated_utc: 2026-10-25T05:00:23+00:00
- source_sha256: `26e939f72c6d4c2b758dd436daadaad6f83df3277762cd00ab80b5b6121c1902`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T05:00+00:00, close=80894.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T05:00+00:00, close=80894.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T04:00+00:00, close=80826.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.085950|-11.99|77.14|-13.40|7654204|1.16|
|IRYS_USDT|0.043300|-5.97|239.34|-7.38|33288577|2.31|
|DOT_USDT|1.039000|-0.96|-7.01|-2.37|11413068|0.96|
|TIA_USDT|0.531700|-0.43|-19.19|-1.84|21503268|1.88|
|STRK_USDT|0.046900|0.36|-29.10|-1.05|8521661|2.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.085950|0.072830|0.086040|0.62|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.039000|1.039200|1.039000|1.95|Y|Y/Y|Y/Y|Y|Y|
|IRYS_USDT|0.043300|0.035430|0.043520|0.92|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.046900|0.046250|0.046850|1.58|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.531700|0.529700|0.531700|0.38|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T05:00:03+00:00, last15m_closed_end=2026-10-25T05:00+00:00, prior8high=0.091370, depth_time=2026-10-25T05:00:09+00:00, book20_bid_proxy_usdt=10741, book20_ask_proxy_usdt=9639, funding_indicative=-0.010007, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.99%, turnover=7654204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T05:00:03+00:00, last15m_closed_end=2026-10-25T05:00+00:00, prior8high=1.044800, depth_time=2026-10-25T05:00:14+00:00, book20_bid_proxy_usdt=435438, book20_ask_proxy_usdt=285210, funding_indicative=-0.000126, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.96%, turnover=11413068. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T05:00:03+00:00, last15m_closed_end=2026-10-25T05:00+00:00, prior8high=0.049460, depth_time=2026-10-25T05:00:11+00:00, book20_bid_proxy_usdt=30457, book20_ask_proxy_usdt=16754, funding_indicative=-0.000817, next_funding_utc=2026-10-25T06:00:00+00:00, funding_cycle_h=1, 24h_change=-5.97%, turnover=33288577. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T05:00:03+00:00, last15m_closed_end=2026-10-25T05:00+00:00, prior8high=0.047120, depth_time=2026-10-25T05:00:19+00:00, book20_bid_proxy_usdt=1073289, book20_ask_proxy_usdt=570585, funding_indicative=0.000050, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=0.36%, turnover=8521661. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-25T05:00:03+00:00, last15m_closed_end=2026-10-25T05:00+00:00, prior8high=0.535300, depth_time=2026-10-25T05:00:16+00:00, book20_bid_proxy_usdt=284646, book20_ask_proxy_usdt=245703, funding_indicative=-0.000012, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.43%, turnover=21503268. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
