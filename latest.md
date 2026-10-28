# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T06:00:14Z**
- feed_generated_utc: 2026-10-28T06:00:17+00:00
- source_sha256: `0759c8ec9b3197590dd60ba75e98e33f8b5968f855a172b31693e0204b5ddf68`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T06:00+00:00, close=80865.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T06:00+00:00, close=80865.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T04:00+00:00, close=81110.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.021510|-27.24|-30.81|-27.65|5603898|4.65|
|NIL_USDT|0.084410|-7.21|-5.00|-7.62|6036830|5.92|
|BULLA_USDT|0.066820|-3.29|-5.09|-3.70|11062452|3.00|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.021510|0.021404|0.021510|1.55|N|Y/Y|Y/Y|N|N|
|BULLA_USDT|0.066820|0.065550|0.066820|0.86|N|Y/Y|Y/Y|N|N|
|NIL_USDT|0.084410|0.081520|0.084410|3.08|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T06:00:02+00:00, last15m_closed_end=2026-10-28T06:00+00:00, prior8high=0.022485, depth_time=2026-10-28T06:00:07+00:00, book20_bid_proxy_usdt=6131, book20_ask_proxy_usdt=2434, funding_indicative=0.000050, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-27.24%, turnover=5603898. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-28T06:00:02+00:00, last15m_closed_end=2026-10-28T06:00+00:00, prior8high=0.095000, depth_time=2026-10-28T06:00:13+00:00, book20_bid_proxy_usdt=141086, book20_ask_proxy_usdt=6277, funding_indicative=-0.002062, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.29%, turnover=11062452. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-28T06:00:02+00:00, last15m_closed_end=2026-10-28T06:00+00:00, prior8high=0.085080, depth_time=2026-10-28T06:00:11+00:00, book20_bid_proxy_usdt=13200, book20_ask_proxy_usdt=4436, funding_indicative=-0.000402, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.21%, turnover=6036830. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
