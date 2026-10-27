# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T21:00:14Z**
- feed_generated_utc: 2026-10-27T21:00:16+00:00
- source_sha256: `3f87b237dd95789c3aa0d7ecf6f9e97705366ed5019f93bcf365e7791092f70e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T21:00+00:00, close=80753.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T21:00+00:00, close=80753.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T20:00+00:00, close=80778.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.022441|-24.09|-27.82|-24.36|5188093|0.45|
|Q_USDT|0.054020|-18.13|-55.99|-18.40|51054407|1.29|
|IRYS_USDT|0.024480|-3.27|88.01|-3.54|5587393|4.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.022441|0.022407|0.022441|0.16|N|Y/Y|Y/Y|N|N|
|IRYS_USDT|0.024480|0.024420|0.024480|1.48|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.054020|0.051125|0.054020|0.59|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-27T21:00:01+00:00, last15m_closed_end=2026-10-27T21:00+00:00, prior8high=0.023222, depth_time=2026-10-27T21:00:06+00:00, book20_bid_proxy_usdt=3548, book20_ask_proxy_usdt=3281, funding_indicative=0.000050, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-24.09%, turnover=5188093. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T21:00:01+00:00, last15m_closed_end=2026-10-27T21:00+00:00, prior8high=0.024830, depth_time=2026-10-27T21:00:12+00:00, book20_bid_proxy_usdt=115218, book20_ask_proxy_usdt=90489, funding_indicative=-0.000456, next_funding_utc=2026-10-27T22:00:00+00:00, funding_cycle_h=1, 24h_change=-3.27%, turnover=5587393. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-27T21:00:00+00:00, last15m_closed_end=2026-10-27T21:00+00:00, prior8high=0.055947, depth_time=2026-10-27T21:00:10+00:00, book20_bid_proxy_usdt=3127, book20_ask_proxy_usdt=2270, funding_indicative=0.000027, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-18.13%, turnover=51054407. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
