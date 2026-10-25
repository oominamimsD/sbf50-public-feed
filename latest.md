# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T05:15:17Z**
- feed_generated_utc: 2026-10-25T05:15:19+00:00
- source_sha256: `3f323355796889d819d7cbf4a37312f21be5e21a43c4e12756aab5db851c2755`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T05:15+00:00, close=80868.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T05:00+00:00, close=80894.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T04:00+00:00, close=80826.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.083330|-14.67|71.74|-16.05|7682638|2.40|
|IRYS_USDT|0.040150|-12.81|214.65|-14.19|33715649|4.98|
|ORDER_USDT|0.058840|-12.70|90.11|-14.08|13667550|1.70|
|DOT_USDT|1.039300|0.01|-6.98|-1.37|11482801|0.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.083330|0.074510|0.083310|1.10|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.039300|1.038900|1.039300|1.65|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.040150|0.037220|0.040390|1.06|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.058840|0.052230|0.058840|1.80|N|N/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T05:15:01+00:00, last15m_closed_end=2026-10-25T05:15+00:00, prior8high=0.091370, depth_time=2026-10-25T05:15:08+00:00, book20_bid_proxy_usdt=6567, book20_ask_proxy_usdt=14858, funding_indicative=-0.010401, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.67%, turnover=7682638. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T05:15:01+00:00, last15m_closed_end=2026-10-25T05:15+00:00, prior8high=1.044800, depth_time=2026-10-25T05:15:16+00:00, book20_bid_proxy_usdt=310038, book20_ask_proxy_usdt=319293, funding_indicative=-0.000126, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=0.01%, turnover=11482801. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T05:15:01+00:00, last15m_closed_end=2026-10-25T05:15+00:00, prior8high=0.049460, depth_time=2026-10-25T05:15:11+00:00, book20_bid_proxy_usdt=41713, book20_ask_proxy_usdt=42295, funding_indicative=-0.000901, next_funding_utc=2026-10-25T06:00:00+00:00, funding_cycle_h=1, 24h_change=-12.81%, turnover=33715649. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T05:15:01+00:00, last15m_closed_end=2026-10-25T05:15+00:00, prior8high=0.063890, depth_time=2026-10-25T05:15:14+00:00, book20_bid_proxy_usdt=55022, book20_ask_proxy_usdt=51983, funding_indicative=-0.001284, next_funding_utc=2026-10-25T06:00:00+00:00, funding_cycle_h=1, 24h_change=-12.70%, turnover=13667550. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
