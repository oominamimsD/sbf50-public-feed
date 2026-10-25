# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T03:00:18Z**
- feed_generated_utc: 2026-10-25T03:00:21+00:00
- source_sha256: `bbdc549c3c519649c511860123c8fa44dd168fb140a9597379936d11def25044`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T03:00+00:00, close=80875.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T03:00+00:00, close=80875.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T00:00+00:00, close=80845, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.075010|-32.09|54.59|-33.48|9198183|6.67|
|ORDER_USDT|0.052310|-23.15|69.01|-24.54|13436284|3.83|
|IRYS_USDT|0.037390|-18.80|193.02|-20.19|31587540|2.67|
|STRK_USDT|0.046300|-0.92|-30.00|-2.31|8341478|2.16|
|DOT_USDT|1.041400|0.22|-6.80|-1.17|11480106|0.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.075010|0.069260|0.075010|0.62|N|Y/Y|Y/N|Y|N|
|DOT_USDT|1.041400|1.042200|1.041500|0.85|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.037390|0.031610|0.037620|2.27|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.052310|0.050660|0.052230|0.73|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.046300|0.046300|0.046330|0.85|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T03:00:01+00:00, last15m_closed_end=2026-10-25T03:00+00:00, prior8high=0.078910, depth_time=2026-10-25T03:00:08+00:00, book20_bid_proxy_usdt=31689, book20_ask_proxy_usdt=8769, funding_indicative=-0.011941, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=-32.09%, turnover=9198183. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T03:00:01+00:00, last15m_closed_end=2026-10-25T03:00+00:00, prior8high=1.055300, depth_time=2026-10-25T03:00:17+00:00, book20_bid_proxy_usdt=470782, book20_ask_proxy_usdt=265603, funding_indicative=-0.000111, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=0.22%, turnover=11480106. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T03:00:01+00:00, last15m_closed_end=2026-10-25T03:00+00:00, prior8high=0.037920, depth_time=2026-10-25T03:00:13+00:00, book20_bid_proxy_usdt=25096, book20_ask_proxy_usdt=22170, funding_indicative=0.000012, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=1, 24h_change=-18.80%, turnover=31587540. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T03:00:01+00:00, last15m_closed_end=2026-10-25T03:00+00:00, prior8high=0.057510, depth_time=2026-10-25T03:00:10+00:00, book20_bid_proxy_usdt=88449, book20_ask_proxy_usdt=61264, funding_indicative=-0.001032, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=1, 24h_change=-23.15%, turnover=13436284. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T03:00:02+00:00, last15m_closed_end=2026-10-25T03:00+00:00, prior8high=0.047560, depth_time=2026-10-25T03:00:14+00:00, book20_bid_proxy_usdt=1109112, book20_ask_proxy_usdt=583322, funding_indicative=0.000050, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.92%, turnover=8341478. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
