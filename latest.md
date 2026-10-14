# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T17:15:15Z**
- feed_generated_utc: 2026-10-14T17:15:16+00:00
- source_sha256: `510d85ed43cb7822f450d818518ac2f059ee4c309b3b0f11297fcaa2fad8a9a1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T17:15+00:00, close=81912.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T17:00+00:00, close=81967.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T16:00+00:00, close=81600.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.162900|-9.07|74.94|-9.45|56756586|2.77|
|S_USDT|0.053510|-2.33|34.31|-2.71|8018876|3.74|
|STRK_USDT|0.076470|-0.91|54.60|-1.29|24814674|1.31|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.162900|2.219300|2.166900|1.29|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.076470|0.076280|0.076540|0.81|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.053510|0.053450|0.053510|0.50|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-14T17:15:02+00:00, last15m_closed_end=2026-10-14T17:15+00:00, prior8high=2.461700, depth_time=2026-10-14T17:15:08+00:00, book20_bid_proxy_usdt=11035, book20_ask_proxy_usdt=19067, funding_indicative=-0.000011, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.07%, turnover=56756586. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T17:15:02+00:00, last15m_closed_end=2026-10-14T17:15+00:00, prior8high=0.079670, depth_time=2026-10-14T17:15:14+00:00, book20_bid_proxy_usdt=177031, book20_ask_proxy_usdt=277485, funding_indicative=0.000035, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.91%, turnover=24814674. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T17:15:02+00:00, last15m_closed_end=2026-10-14T17:15+00:00, prior8high=0.055930, depth_time=2026-10-14T17:15:11+00:00, book20_bid_proxy_usdt=154676, book20_ask_proxy_usdt=147630, funding_indicative=-0.000032, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.33%, turnover=8018876. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
