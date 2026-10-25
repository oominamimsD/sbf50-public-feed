# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T18:15:11Z**
- feed_generated_utc: 2026-10-25T18:15:13+00:00
- source_sha256: `f53aaf5c3df7a95eb31bab1080a7a54a4a5188caacee5f6e33be2c7a72a6ea54`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T18:15+00:00, close=80669.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T18:00+00:00, close=80762.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T16:00+00:00, close=80602.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.036470|-5.12|198.93|-5.20|21856117|2.74|
|XMR_USDT|601.200000|-0.99|3.21|-1.07|6950589|0.83|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|IRYS_USDT|0.036470|0.035970|0.036420|0.61|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|601.200000|601.040000|601.210000|0.31|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- IRYS_USDT: quote_utc=2026-10-25T18:15:01+00:00, last15m_closed_end=2026-10-25T18:15+00:00, prior8high=0.039980, depth_time=2026-10-25T18:15:07+00:00, book20_bid_proxy_usdt=40462, book20_ask_proxy_usdt=66937, funding_indicative=-0.000035, next_funding_utc=2026-10-25T19:00:00+00:00, funding_cycle_h=1, 24h_change=-5.12%, turnover=21856117. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-25T18:15:01+00:00, last15m_closed_end=2026-10-25T18:15+00:00, prior8high=607.760000, depth_time=2026-10-25T18:15:09+00:00, book20_bid_proxy_usdt=15717, book20_ask_proxy_usdt=14106, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.99%, turnover=6950589. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
