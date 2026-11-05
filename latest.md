# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T19:45:13Z**
- feed_generated_utc: 2026-11-05T19:45:14+00:00
- source_sha256: `219378872c52b524f3d7ace5733a6872c6d422a22fb4795a27d0a2d30d22ba8b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T19:45+00:00, close=76385, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T19:00+00:00, close=76066.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T16:00+00:00, close=76013.2, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002257|-12.51|-89.28|-13.02|18609545|4.44|
|FLUID_USDT|2.415000|-4.62|17.00|-5.13|8824748|4.14|
|XMR_USDT|610.260000|-0.81|1.02|-1.32|5187932|3.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002257|0.001878|0.002260|0.36|N|Y/Y|Y/Y|Y|N|
|FLUID_USDT|2.415000|2.359000|2.415000|0.50|N|Y/Y|N/N|Y|N|
|XMR_USDT|610.260000|608.810000|609.920000|0.57|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T19:45:01+00:00, last15m_closed_end=2026-11-05T19:45+00:00, prior8high=0.002857, depth_time=2026-11-05T19:45:07+00:00, book20_bid_proxy_usdt=32817, book20_ask_proxy_usdt=31082, funding_indicative=-0.009693, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-12.51%, turnover=18609545. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T19:45:01+00:00, last15m_closed_end=2026-11-05T19:45+00:00, prior8high=2.446000, depth_time=2026-11-05T19:45:08+00:00, book20_bid_proxy_usdt=186798, book20_ask_proxy_usdt=168238, funding_indicative=0.000112, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.62%, turnover=8824748. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-05T19:45:01+00:00, last15m_closed_end=2026-11-05T19:45+00:00, prior8high=617.170000, depth_time=2026-11-05T19:45:12+00:00, book20_bid_proxy_usdt=22615, book20_ask_proxy_usdt=26844, funding_indicative=0.000855, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.81%, turnover=5187932. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
