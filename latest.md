# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T15:45:21Z**
- feed_generated_utc: 2026-10-25T15:45:24+00:00
- source_sha256: `2311eb909804c8f95d67006c7d4213b630756711c3f98936ff546e12c717f4cf`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T15:45+00:00, close=80633.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T15:00+00:00, close=80618, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T12:00+00:00, close=80542.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.047500|-29.52|53.47|-30.60|5045081|6.32|
|IRYS_USDT|0.038400|-16.61|200.94|-17.69|24557691|5.21|
|BTW_USDT|1.662300|-4.53|-26.75|-5.61|11971098|3.01|
|SUI_USDT|0.917300|-0.83|-6.56|-1.91|65149314|1.09|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.662300|1.650000|1.662300|0.73|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.038400|0.034410|0.038260|1.16|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.047500|0.045840|0.047500|0.51|N|Y/Y|N/N|Y|N|
|SUI_USDT|0.917300|0.907500|0.917300|2.89|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-25T15:45:04+00:00, last15m_closed_end=2026-10-25T15:45+00:00, prior8high=1.701000, depth_time=2026-10-25T15:45:18+00:00, book20_bid_proxy_usdt=25404, book20_ask_proxy_usdt=14129, funding_indicative=-0.009658, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.53%, turnover=11971098. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T15:45:04+00:00, last15m_closed_end=2026-10-25T15:45+00:00, prior8high=0.040280, depth_time=2026-10-25T15:45:15+00:00, book20_bid_proxy_usdt=59672, book20_ask_proxy_usdt=28084, funding_indicative=-0.000192, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=1, 24h_change=-16.61%, turnover=24557691. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T15:45:04+00:00, last15m_closed_end=2026-10-25T15:45+00:00, prior8high=0.048570, depth_time=2026-10-25T15:45:09+00:00, book20_bid_proxy_usdt=83990, book20_ask_proxy_usdt=128432, funding_indicative=-0.000981, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=1, 24h_change=-29.52%, turnover=5045081. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T15:45:04+00:00, last15m_closed_end=2026-10-25T15:45+00:00, prior8high=0.917900, depth_time=2026-10-25T15:45:21+00:00, book20_bid_proxy_usdt=1104712, book20_ask_proxy_usdt=1203320, funding_indicative=-0.000015, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.83%, turnover=65149314. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
