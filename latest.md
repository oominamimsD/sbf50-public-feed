# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T04:45:19Z**
- feed_generated_utc: 2026-10-25T04:45:22+00:00
- source_sha256: `2682cc60a3b226cb1aca41394aefd6cc41114f5ba3e865f1fffe096a7fae94fc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T04:45+00:00, close=80902.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T04:00+00:00, close=80826.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T04:00+00:00, close=80826.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.057520|-14.65|85.84|-16.07|13596300|1.74|
|BIRB_USDT|0.086700|-11.22|78.68|-12.64|8542797|2.31|
|IRYS_USDT|0.045630|-0.91|257.60|-2.33|33899218|2.19|
|DOT_USDT|1.041400|0.22|-6.80|-1.20|11428132|0.96|
|STRK_USDT|0.046900|0.36|-29.10|-1.06|8503034|2.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.086700|0.072160|0.086700|0.75|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.041400|1.039200|1.041400|0.56|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.045630|0.035120|0.045430|0.82|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.057520|0.050530|0.057520|0.52|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.046900|0.046250|0.046900|0.62|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T04:45:03+00:00, last15m_closed_end=2026-10-25T04:45+00:00, prior8high=0.091370, depth_time=2026-10-25T04:45:11+00:00, book20_bid_proxy_usdt=6765, book20_ask_proxy_usdt=16148, funding_indicative=-0.009327, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.22%, turnover=8542797. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T04:45:03+00:00, last15m_closed_end=2026-10-25T04:45+00:00, prior8high=1.046100, depth_time=2026-10-25T04:45:14+00:00, book20_bid_proxy_usdt=351016, book20_ask_proxy_usdt=325749, funding_indicative=-0.000123, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=0.22%, turnover=11428132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T04:45:03+00:00, last15m_closed_end=2026-10-25T04:45+00:00, prior8high=0.049460, depth_time=2026-10-25T04:45:14+00:00, book20_bid_proxy_usdt=33454, book20_ask_proxy_usdt=33828, funding_indicative=-0.000809, next_funding_utc=2026-10-25T05:00:00+00:00, funding_cycle_h=1, 24h_change=-0.91%, turnover=33899218. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T04:45:02+00:00, last15m_closed_end=2026-10-25T04:45+00:00, prior8high=0.060560, depth_time=2026-10-25T04:45:08+00:00, book20_bid_proxy_usdt=56431, book20_ask_proxy_usdt=68769, funding_indicative=-0.001092, next_funding_utc=2026-10-25T05:00:00+00:00, funding_cycle_h=1, 24h_change=-14.65%, turnover=13596300. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T04:45:03+00:00, last15m_closed_end=2026-10-25T04:45+00:00, prior8high=0.047120, depth_time=2026-10-25T04:45:18+00:00, book20_bid_proxy_usdt=935905, book20_ask_proxy_usdt=635250, funding_indicative=0.000050, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=0.36%, turnover=8503034. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
