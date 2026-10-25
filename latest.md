# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T01:30:15Z**
- feed_generated_utc: 2026-10-25T01:30:18+00:00
- source_sha256: `a40cef3a24d8613ed99837004b6e1f6309133359edfe142530d8f51ee81d26d9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T01:30+00:00, close=80769, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T01:00+00:00, close=80842.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T00:00+00:00, close=80845, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.033470|-27.31|162.30|-28.57|34262681|2.99|
|BIRB_USDT|0.074090|-24.13|52.69|-25.39|10289450|4.07|
|ORDER_USDT|0.053270|-20.96|72.11|-22.22|13319790|1.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.074090|0.069260|0.074090|1.42|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.033470|0.033300|0.033390|1.48|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.053270|0.053730|0.053770|0.57|N|Y/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T01:30:01+00:00, last15m_closed_end=2026-10-25T01:30+00:00, prior8high=0.100590, depth_time=2026-10-25T01:30:12+00:00, book20_bid_proxy_usdt=17810, book20_ask_proxy_usdt=13305, funding_indicative=-0.018498, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=-24.13%, turnover=10289450. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T01:30:00+00:00, last15m_closed_end=2026-10-25T01:30+00:00, prior8high=0.047160, depth_time=2026-10-25T01:30:09+00:00, book20_bid_proxy_usdt=38570, book20_ask_proxy_usdt=58869, funding_indicative=-0.000111, next_funding_utc=2026-10-25T02:00:00+00:00, funding_cycle_h=1, 24h_change=-27.31%, turnover=34262681. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T01:30:01+00:00, last15m_closed_end=2026-10-25T01:30+00:00, prior8high=0.073400, depth_time=2026-10-25T01:30:14+00:00, book20_bid_proxy_usdt=51281, book20_ask_proxy_usdt=60730, funding_indicative=-0.001995, next_funding_utc=2026-10-25T02:00:00+00:00, funding_cycle_h=1, 24h_change=-20.96%, turnover=13319790. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
