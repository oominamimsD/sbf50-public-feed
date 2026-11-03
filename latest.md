# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T18:45:14Z**
- feed_generated_utc: 2026-11-03T18:45:16+00:00
- source_sha256: `bdb78c544feea0d44e1f1db4a47344e8c80b376142739c04d10104ded3aa7f57`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T18:45+00:00, close=77703.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T18:00+00:00, close=77626.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T16:00+00:00, close=77664.3, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003931|-5.41|-81.39|-5.45|13286955|5.10|
|TRUMPOFFICIAL_USDT|1.578000|-1.86|-6.51|-1.90|6584303|6.34|
|QNT_USDT|192.250000|-1.62|-2.85|-1.66|57132792|1.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003931|0.003806|0.003928|3.20|N|Y/Y|Y/Y|N|N|
|QNT_USDT|192.250000|192.330000|192.270000|0.87|N|Y/Y|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.578000|1.579000|1.578000|0.56|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T18:45:03+00:00, last15m_closed_end=2026-11-03T18:45+00:00, prior8high=0.004095, depth_time=2026-11-03T18:45:08+00:00, book20_bid_proxy_usdt=36218, book20_ask_proxy_usdt=30717, funding_indicative=-0.000752, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.41%, turnover=13286955. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T18:45:04+00:00, last15m_closed_end=2026-11-03T18:45+00:00, prior8high=195.800000, depth_time=2026-11-03T18:45:14+00:00, book20_bid_proxy_usdt=75788, book20_ask_proxy_usdt=75872, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.62%, turnover=57132792. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T18:45:00+00:00, last15m_closed_end=2026-11-03T18:45+00:00, prior8high=1.599000, depth_time=2026-11-03T18:45:08+00:00, book20_bid_proxy_usdt=1884169, book20_ask_proxy_usdt=2369123, funding_indicative=0.000030, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.86%, turnover=6584303. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
