# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T08:00:15Z**
- feed_generated_utc: 2026-11-04T08:00:17+00:00
- source_sha256: `2bda850ad28ddf6742d8e2702beb2046ab8312ee61d52333c428924787ec4cd3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T08:00+00:00, close=78117.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T08:00+00:00, close=78117.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T08:00+00:00, close=78117.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.036100|-30.69|-24.03|-31.27|10518926|5.54|
|AKE_USDT|0.003083|-24.96|-85.40|-25.54|11830541|3.25|
|TRUMPOFFICIAL_USDT|1.503000|-6.41|-10.95|-6.99|9079769|6.65|
|Q_USDT|0.027860|-1.45|-56.18|-2.03|7274497|7.18|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.036100|0.036850|0.036100|2.49|Y|Y/Y|Y/N|N|N|
|AKE_USDT|0.003083|0.003052|0.003081|0.35|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.027860|0.027590|0.027860|0.43|N|Y/Y|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.503000|1.502000|1.503000|0.43|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T08:00:01+00:00, last15m_closed_end=2026-11-04T08:00+00:00, prior8high=0.038670, depth_time=2026-11-04T08:00:06+00:00, book20_bid_proxy_usdt=18516, book20_ask_proxy_usdt=39883, funding_indicative=0.000092, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-30.69%, turnover=10518926. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T08:00:02+00:00, last15m_closed_end=2026-11-04T08:00+00:00, prior8high=0.003323, depth_time=2026-11-04T08:00:10+00:00, book20_bid_proxy_usdt=33027, book20_ask_proxy_usdt=52425, funding_indicative=0.000050, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-24.96%, turnover=11830541. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T08:00:02+00:00, last15m_closed_end=2026-11-04T08:00+00:00, prior8high=0.028570, depth_time=2026-11-04T08:00:14+00:00, book20_bid_proxy_usdt=61361, book20_ask_proxy_usdt=47934, funding_indicative=-0.000390, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.45%, turnover=7274497. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T08:00:02+00:00, last15m_closed_end=2026-11-04T08:00+00:00, prior8high=1.536000, depth_time=2026-11-04T08:00:12+00:00, book20_bid_proxy_usdt=2134886, book20_ask_proxy_usdt=2215408, funding_indicative=-0.000063, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.41%, turnover=9079769. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
