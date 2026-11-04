# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T06:15:13Z**
- feed_generated_utc: 2026-11-04T06:15:15+00:00
- source_sha256: `fc9225a47e6826a6f54a4bc6410ce9285f728836ea084a23925e9f87dc71454c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T06:15+00:00, close=77759.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T06:00+00:00, close=77721.7, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-04T04:00+00:00, close=76468.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.038530|-28.39|-18.91|-28.51|11072887|5.20|
|AKE_USDT|0.003230|-22.28|-84.71|-22.40|12518987|3.09|
|TRUMPOFFICIAL_USDT|1.514000|-5.84|-10.30|-5.96|8409748|6.61|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.038530|0.036380|0.038520|1.40|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.003230|0.002979|0.003230|1.00|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.514000|1.494000|1.514000|0.47|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T06:15:00+00:00, last15m_closed_end=2026-11-04T06:15+00:00, prior8high=0.038590, depth_time=2026-11-04T06:15:07+00:00, book20_bid_proxy_usdt=27437, book20_ask_proxy_usdt=32814, funding_indicative=0.000168, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-28.39%, turnover=11072887. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T06:15:00+00:00, last15m_closed_end=2026-11-04T06:15+00:00, prior8high=0.003654, depth_time=2026-11-04T06:15:10+00:00, book20_bid_proxy_usdt=47374, book20_ask_proxy_usdt=37863, funding_indicative=0.000054, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-22.28%, turnover=12518987. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T06:15:01+00:00, last15m_closed_end=2026-11-04T06:15+00:00, prior8high=1.536000, depth_time=2026-11-04T06:15:07+00:00, book20_bid_proxy_usdt=1947965, book20_ask_proxy_usdt=2862971, funding_indicative=-0.000126, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.84%, turnover=8409748. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
