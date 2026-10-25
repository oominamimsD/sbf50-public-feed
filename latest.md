# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T03:30:19Z**
- feed_generated_utc: 2026-10-25T03:30:22+00:00
- source_sha256: `a73bacf0b14bccf04fd3dceb537d3c48f02a63915fff2ce53b7ca43e1487db30`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T03:30+00:00, close=80913.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T03:00+00:00, close=80875.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T00:00+00:00, close=80845, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.057030|-15.38|84.26|-16.82|13493366|1.75|
|BIRB_USDT|0.083860|-14.13|72.83|-15.57|9257250|3.58|
|IRYS_USDT|0.042960|-6.71|236.67|-8.15|32498389|9.33|
|STRK_USDT|0.046740|0.02|-29.34|-1.42|8454195|2.14|
|DOT_USDT|1.041300|0.21|-6.81|-1.23|11572662|0.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.083860|0.069430|0.083860|2.37|N|Y/Y|Y/N|Y|N|
|DOT_USDT|1.041300|1.040400|1.041300|0.97|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.042960|0.031610|0.042960|2.11|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.057030|0.050530|0.057030|1.22|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.046740|0.046250|0.046740|0.50|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T03:29:59+00:00, last15m_closed_end=2026-10-25T03:30+00:00, prior8high=0.079960, depth_time=2026-10-25T03:30:10+00:00, book20_bid_proxy_usdt=11948, book20_ask_proxy_usdt=5717, funding_indicative=-0.009926, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.13%, turnover=9257250. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T03:29:59+00:00, last15m_closed_end=2026-10-25T03:30+00:00, prior8high=1.055300, depth_time=2026-10-25T03:30:18+00:00, book20_bid_proxy_usdt=451722, book20_ask_proxy_usdt=385905, funding_indicative=-0.000102, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=0.21%, turnover=11572662. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T03:29:59+00:00, last15m_closed_end=2026-10-25T03:30+00:00, prior8high=0.041290, depth_time=2026-10-25T03:30:13+00:00, book20_bid_proxy_usdt=35105, book20_ask_proxy_usdt=30816, funding_indicative=-0.000303, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=1, 24h_change=-6.71%, turnover=32498389. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T03:29:59+00:00, last15m_closed_end=2026-10-25T03:30+00:00, prior8high=0.056790, depth_time=2026-10-25T03:30:08+00:00, book20_bid_proxy_usdt=53225, book20_ask_proxy_usdt=41983, funding_indicative=-0.001032, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=1, 24h_change=-15.38%, turnover=13493366. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T03:30:00+00:00, last15m_closed_end=2026-10-25T03:30+00:00, prior8high=0.047180, depth_time=2026-10-25T03:30:16+00:00, book20_bid_proxy_usdt=997723, book20_ask_proxy_usdt=697727, funding_indicative=0.000050, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=0.02%, turnover=8454195. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
