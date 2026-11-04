# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T10:30:14Z**
- feed_generated_utc: 2026-11-04T10:30:16+00:00
- source_sha256: `1144a776acab55cbe8d801298225678db55f41e33d49e3afef68a8177c4a7bb7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T10:30+00:00, close=78591.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T10:00+00:00, close=78377.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T08:00+00:00, close=78117.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.033310|-38.09|-29.90|-39.28|10755108|3.00|
|AKE_USDT|0.002913|-29.90|-86.21|-31.09|12629792|3.43|
|TRUMPOFFICIAL_USDT|1.476000|-8.20|-12.55|-9.39|10630057|6.77|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.033310|0.032150|0.033310|0.83|N|Y/Y|Y/N|N|N|
|AKE_USDT|0.002913|0.002807|0.002911|1.67|N|Y/Y|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.476000|1.463000|1.476000|0.74|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T10:30:02+00:00, last15m_closed_end=2026-11-04T10:30+00:00, prior8high=0.036110, depth_time=2026-11-04T10:30:08+00:00, book20_bid_proxy_usdt=31407, book20_ask_proxy_usdt=34112, funding_indicative=0.000053, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-38.09%, turnover=10755108. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T10:30:02+00:00, last15m_closed_end=2026-11-04T10:30+00:00, prior8high=0.003107, depth_time=2026-11-04T10:30:10+00:00, book20_bid_proxy_usdt=74717, book20_ask_proxy_usdt=109976, funding_indicative=0.000050, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-29.90%, turnover=12629792. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T10:30:02+00:00, last15m_closed_end=2026-11-04T10:30+00:00, prior8high=1.526000, depth_time=2026-11-04T10:30:10+00:00, book20_bid_proxy_usdt=2958240, book20_ask_proxy_usdt=2121345, funding_indicative=-0.000106, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.20%, turnover=10630057. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
