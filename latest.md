# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T18:30:12Z**
- feed_generated_utc: 2026-10-27T18:30:15+00:00
- source_sha256: `8a8a60866e5d0245466cf803251f2fd9c2a5d67c5ad53fc3985ed2a144c74cfd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T18:30+00:00, close=80584.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T18:00+00:00, close=80476.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T16:00+00:00, close=80529.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.054796|-13.82|-55.36|-13.88|59761622|3.47|
|IRYS_USDT|0.024640|-1.08|89.24|-1.14|5911434|8.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|IRYS_USDT|0.024640|0.024340|0.024640|0.58|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.054796|0.052960|0.054789|0.51|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- IRYS_USDT: quote_utc=2026-10-27T18:29:59+00:00, last15m_closed_end=2026-10-27T18:30+00:00, prior8high=0.025120, depth_time=2026-10-27T18:30:10+00:00, book20_bid_proxy_usdt=93381, book20_ask_proxy_usdt=87388, funding_indicative=-0.000318, next_funding_utc=2026-10-27T19:00:00+00:00, funding_cycle_h=1, 24h_change=-1.08%, turnover=5911434. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-27T18:29:59+00:00, last15m_closed_end=2026-10-27T18:30+00:00, prior8high=0.064262, depth_time=2026-10-27T18:30:08+00:00, book20_bid_proxy_usdt=1722, book20_ask_proxy_usdt=2223, funding_indicative=0.000050, next_funding_utc=2026-10-27T20:00:00+00:00, funding_cycle_h=4, 24h_change=-13.82%, turnover=59761622. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
