# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T13:45:17Z**
- feed_generated_utc: 2026-11-04T13:45:18+00:00
- source_sha256: `84464c9a7b537d7e5600719fb84a7317e15602e6df7329cf404d98779366216f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T13:45+00:00, close=78355.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T13:00+00:00, close=78272, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T12:00+00:00, close=78453.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.033490|-37.76|-29.52|-38.66|9584269|2.98|
|AKE_USDT|0.002924|-29.64|-86.15|-30.54|14482011|3.42|
|HOT_USDT|0.000474|-11.97|37.20|-12.87|6025193|4.22|
|TRUMPOFFICIAL_USDT|1.424000|-11.44|-15.63|-12.34|12876834|7.02|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.033490|0.032170|0.033490|1.02|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.002924|0.002758|0.002934|0.73|N|Y/Y|Y/Y|N|N|
|HOT_USDT|0.000474|0.000472|0.000474|0.41|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.424000|1.407000|1.424000|0.89|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T13:45:01+00:00, last15m_closed_end=2026-11-04T13:45+00:00, prior8high=0.034410, depth_time=2026-11-04T13:45:08+00:00, book20_bid_proxy_usdt=29548, book20_ask_proxy_usdt=54557, funding_indicative=0.000053, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-37.76%, turnover=9584269. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T13:45:02+00:00, last15m_closed_end=2026-11-04T13:45+00:00, prior8high=0.003257, depth_time=2026-11-04T13:45:11+00:00, book20_bid_proxy_usdt=34426, book20_ask_proxy_usdt=69288, funding_indicative=-0.000062, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-29.64%, turnover=14482011. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-04T13:45:02+00:00, last15m_closed_end=2026-11-04T13:45+00:00, prior8high=0.000500, depth_time=2026-11-04T13:45:14+00:00, book20_bid_proxy_usdt=83949, book20_ask_proxy_usdt=120314, funding_indicative=-0.000117, next_funding_utc=2026-11-04T14:00:00+00:00, funding_cycle_h=1, 24h_change=-11.97%, turnover=6025193. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T13:45:02+00:00, last15m_closed_end=2026-11-04T13:45+00:00, prior8high=1.490000, depth_time=2026-11-04T13:45:15+00:00, book20_bid_proxy_usdt=2410330, book20_ask_proxy_usdt=2259076, funding_indicative=-0.000374, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.44%, turnover=12876834. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
