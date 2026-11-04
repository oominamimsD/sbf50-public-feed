# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T15:45:17Z**
- feed_generated_utc: 2026-11-04T15:45:19+00:00
- source_sha256: `f32f3fdff5b90f7685486f842e9c60c38c0f00b428bcfdca9da63c71bbcbf835`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T15:45+00:00, close=80256.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T15:00+00:00, close=79318.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T12:00+00:00, close=78453.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.036300|-32.54|-23.61|-35.82|7146074|5.51|
|AKE_USDT|0.002824|-32.05|-86.63|-35.33|16285719|3.53|
|TRUMPOFFICIAL_USDT|1.433000|-10.88|-15.10|-14.16|15000080|6.99|
|Q_USDT|0.028310|0.49|-55.47|-2.79|7182152|3.54|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.036300|0.033240|0.036310|0.60|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.002824|0.002910|0.002813|3.63|Y|Y/Y|Y/Y|N|Y|
|Q_USDT|0.028310|0.028520|0.028310|3.02|Y|N/N|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.433000|1.404000|1.433000|0.63|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T15:45:03+00:00, last15m_closed_end=2026-11-04T15:45+00:00, prior8high=0.037650, depth_time=2026-11-04T15:45:08+00:00, book20_bid_proxy_usdt=18866, book20_ask_proxy_usdt=36667, funding_indicative=0.000053, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-32.54%, turnover=7146074. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T15:45:03+00:00, last15m_closed_end=2026-11-04T15:45+00:00, prior8high=0.003487, depth_time=2026-11-04T15:45:11+00:00, book20_bid_proxy_usdt=43046, book20_ask_proxy_usdt=32050, funding_indicative=-0.000188, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-32.05%, turnover=16285719. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T15:45:03+00:00, last15m_closed_end=2026-11-04T15:45+00:00, prior8high=0.029920, depth_time=2026-11-04T15:45:15+00:00, book20_bid_proxy_usdt=61101, book20_ask_proxy_usdt=75766, funding_indicative=-0.000083, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=0.49%, turnover=7182152. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T15:45:03+00:00, last15m_closed_end=2026-11-04T15:45+00:00, prior8high=1.465000, depth_time=2026-11-04T15:45:14+00:00, book20_bid_proxy_usdt=1987023, book20_ask_proxy_usdt=2219606, funding_indicative=-0.000356, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.88%, turnover=15000080. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
