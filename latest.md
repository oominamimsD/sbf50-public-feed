# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T20:15:12Z**
- feed_generated_utc: 2026-11-05T20:15:13+00:00
- source_sha256: `6834947910e9f7cd1dc84558f7eca73252b12e1d57a6035e44400e29c201db41`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T20:15+00:00, close=76099.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T20:00+00:00, close=76344.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T20:00+00:00, close=76344.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002015|-21.89|-90.43|-22.00|19168812|9.88|
|FLUID_USDT|2.376000|-6.16|15.11|-6.27|8577616|4.21|
|BCH_USDT|276.500000|-0.93|-4.08|-1.04|10194406|2.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002015|0.001878|0.002065|1.44|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|276.500000|272.300000|276.630000|0.19|N|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.376000|2.359000|2.376000|0.36|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T20:15:01+00:00, last15m_closed_end=2026-11-05T20:15+00:00, prior8high=0.002495, depth_time=2026-11-05T20:15:06+00:00, book20_bid_proxy_usdt=24700, book20_ask_proxy_usdt=27735, funding_indicative=-0.007197, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-21.89%, turnover=19168812. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-05T20:15:02+00:00, last15m_closed_end=2026-11-05T20:15+00:00, prior8high=278.250000, depth_time=2026-11-05T20:15:11+00:00, book20_bid_proxy_usdt=49426, book20_ask_proxy_usdt=51840, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.93%, turnover=10194406. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T20:15:01+00:00, last15m_closed_end=2026-11-05T20:15+00:00, prior8high=2.446000, depth_time=2026-11-05T20:15:07+00:00, book20_bid_proxy_usdt=201986, book20_ask_proxy_usdt=179068, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.16%, turnover=8577616. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
