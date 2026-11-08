# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T00:45:10Z**
- feed_generated_utc: 2026-11-08T00:45:11+00:00
- source_sha256: `78ae6acfd4a2fc6b3ccccd35047393dfd091cc0da41930eab913ba2de757b387`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T00:45+00:00, close=75729.2, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T00:00+00:00, close=75836.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T00:00+00:00, close=75836.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|QNT_USDT|195.650000|-1.60|-2.68|-1.60|43890005|0.51|
|PEPE_USDT|0.000005|-1.18|-2.87|-1.18|40092384|1.45|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|PEPE_USDT|0.000005|0.000005|0.000005|0.69|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.650000|194.800000|195.650000|1.20|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- PEPE_USDT: quote_utc=2026-11-08T00:45:00+00:00, last15m_closed_end=2026-11-08T00:45+00:00, prior8high=0.000005, depth_time=2026-11-08T00:45:08+00:00, book20_bid_proxy_usdt=55878, book20_ask_proxy_usdt=24186, funding_indicative=0.000085, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.18%, turnover=40092384. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T00:45:00+00:00, last15m_closed_end=2026-11-08T00:45+00:00, prior8high=196.770000, depth_time=2026-11-08T00:45:05+00:00, book20_bid_proxy_usdt=84848, book20_ask_proxy_usdt=66861, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=43890005. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
