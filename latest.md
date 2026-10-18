# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T23:15:12Z**
- feed_generated_utc: 2026-10-18T23:15:14+00:00
- source_sha256: `b82b03e3f5537ccd2032b22581ebeb29ba8c790d743e90c045bd77f2cf49c280`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T23:15+00:00, close=81735.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T23:00+00:00, close=81727.3, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T20:00+00:00, close=80844.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.061350|-9.15|246.90|-9.88|9994365|3.43|
|STRK_USDT|0.059790|-2.87|-49.87|-3.60|15753529|1.67|
|SAND_USDT|0.058250|-0.86|-12.32|-1.59|33951934|1.72|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.061350|0.061280|0.061358|1.24|N|Y/Y|N/N|Y|N|
|SAND_USDT|0.058250|0.056220|0.058210|0.25|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.059790|0.058490|0.059790|0.94|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-18T23:15:01+00:00, last15m_closed_end=2026-10-18T23:15+00:00, prior8high=0.064900, depth_time=2026-10-18T23:15:07+00:00, book20_bid_proxy_usdt=2766, book20_ask_proxy_usdt=9443, funding_indicative=0.000237, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.15%, turnover=9994365. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T23:15:01+00:00, last15m_closed_end=2026-10-18T23:15+00:00, prior8high=0.058220, depth_time=2026-10-18T23:15:10+00:00, book20_bid_proxy_usdt=508772, book20_ask_proxy_usdt=649186, funding_indicative=-0.002454, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.86%, turnover=33951934. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T23:15:01+00:00, last15m_closed_end=2026-10-18T23:15+00:00, prior8high=0.061020, depth_time=2026-10-18T23:15:09+00:00, book20_bid_proxy_usdt=532209, book20_ask_proxy_usdt=387168, funding_indicative=0.000050, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.87%, turnover=15753529. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
