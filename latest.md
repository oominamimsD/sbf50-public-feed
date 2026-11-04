# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T08:30:17Z**
- feed_generated_utc: 2026-11-04T08:30:19+00:00
- source_sha256: `0f4ff8bdf18f922eca629a46d8e616b135340ebca7dd7a09144bfe17363166f6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T08:30+00:00, close=78353.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T08:00+00:00, close=78117.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T08:00+00:00, close=78117.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.035300|-34.39|-25.71|-35.27|10645541|5.66|
|AKE_USDT|0.003018|-27.38|-85.71|-28.26|11983451|3.31|
|TRUMPOFFICIAL_USDT|1.503000|-6.52|-10.95|-7.40|9825479|6.66|
|Q_USDT|0.027900|-0.95|-56.12|-1.83|7329026|3.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.035300|0.035540|0.035340|1.96|Y|Y/Y|Y/N|N|N|
|AKE_USDT|0.003018|0.003003|0.003018|0.49|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.027900|0.027670|0.027900|0.75|N|Y/Y|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.503000|1.502000|1.503000|4.73|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T08:30:03+00:00, last15m_closed_end=2026-11-04T08:30+00:00, prior8high=0.038520, depth_time=2026-11-04T08:30:09+00:00, book20_bid_proxy_usdt=27486, book20_ask_proxy_usdt=36278, funding_indicative=0.000053, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-34.39%, turnover=10645541. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T08:30:03+00:00, last15m_closed_end=2026-11-04T08:30+00:00, prior8high=0.003323, depth_time=2026-11-04T08:30:11+00:00, book20_bid_proxy_usdt=139055, book20_ask_proxy_usdt=67914, funding_indicative=0.000050, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-27.38%, turnover=11983451. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T08:30:03+00:00, last15m_closed_end=2026-11-04T08:30+00:00, prior8high=0.028570, depth_time=2026-11-04T08:30:16+00:00, book20_bid_proxy_usdt=54779, book20_ask_proxy_usdt=38427, funding_indicative=-0.000447, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.95%, turnover=7329026. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T08:30:03+00:00, last15m_closed_end=2026-11-04T08:30+00:00, prior8high=1.531000, depth_time=2026-11-04T08:30:13+00:00, book20_bid_proxy_usdt=2813931, book20_ask_proxy_usdt=2423880, funding_indicative=-0.000046, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.52%, turnover=9825479. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
