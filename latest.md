# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T08:45:15Z**
- feed_generated_utc: 2026-11-04T08:45:17+00:00
- source_sha256: `80b0a6ca8e5b6ce5a485b5b0dd101b0e137c4ae9ec7b93b6b2c604a906538ba0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T08:45+00:00, close=78398.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T08:00+00:00, close=78117.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T08:00+00:00, close=78117.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.034630|-35.64|-27.12|-36.58|10721885|2.89|
|AKE_USDT|0.003007|-27.64|-85.76|-28.58|12092839|3.33|
|TRUMPOFFICIAL_USDT|1.496000|-6.96|-11.37|-7.90|10164323|6.69|
|Q_USDT|0.027910|-0.92|-56.10|-1.86|7344533|3.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.034630|0.035230|0.034630|2.01|Y|Y/Y|Y/N|N|N|
|AKE_USDT|0.003007|0.003002|0.003007|1.07|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.027910|0.027670|0.027910|0.72|N|Y/Y|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.496000|1.502000|1.496000|3.79|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T08:45:02+00:00, last15m_closed_end=2026-11-04T08:45+00:00, prior8high=0.038390, depth_time=2026-11-04T08:45:07+00:00, book20_bid_proxy_usdt=41973, book20_ask_proxy_usdt=41491, funding_indicative=0.000053, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-35.64%, turnover=10721885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T08:45:03+00:00, last15m_closed_end=2026-11-04T08:45+00:00, prior8high=0.003323, depth_time=2026-11-04T08:45:10+00:00, book20_bid_proxy_usdt=100790, book20_ask_proxy_usdt=62355, funding_indicative=0.000050, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-27.64%, turnover=12092839. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T08:45:03+00:00, last15m_closed_end=2026-11-04T08:45+00:00, prior8high=0.028570, depth_time=2026-11-04T08:45:14+00:00, book20_bid_proxy_usdt=86756, book20_ask_proxy_usdt=44684, funding_indicative=-0.000450, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.92%, turnover=7344533. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T08:45:03+00:00, last15m_closed_end=2026-11-04T08:45+00:00, prior8high=1.531000, depth_time=2026-11-04T08:45:11+00:00, book20_bid_proxy_usdt=2692582, book20_ask_proxy_usdt=2899300, funding_indicative=-0.000061, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.96%, turnover=10164323. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
