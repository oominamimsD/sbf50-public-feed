# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T11:00:15Z**
- feed_generated_utc: 2026-10-16T11:00:17+00:00
- source_sha256: `512291e10a20f396fed725e4919c05e85417c6b8a645eb9a7da8ae5e2f0ac8ff`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T11:00+00:00, close=82175.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T11:00+00:00, close=82175.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T08:00+00:00, close=82258.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.076330|-10.28|26.87|-10.04|39601980|2.62|
|NIL_USDT|0.082830|-7.01|-4.34|-6.77|5673597|1.21|
|AKE_USDT|0.030067|-4.86|3.59|-4.62|19176088|1.33|
|BTW_USDT|1.847500|-4.25|33.07|-4.01|20524334|3.79|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.030067|0.029790|0.030092|0.76|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.847500|1.849400|1.847500|0.99|N|Y/Y|Y/Y|Y|N|
|NIL_USDT|0.082830|0.081680|0.082830|1.65|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.076330|0.076540|0.076330|2.37|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T11:00:01+00:00, last15m_closed_end=2026-10-16T11:00+00:00, prior8high=0.031827, depth_time=2026-10-16T11:00:12+00:00, book20_bid_proxy_usdt=13482, book20_ask_proxy_usdt=15986, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.86%, turnover=19176088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-16T11:00:01+00:00, last15m_closed_end=2026-10-16T11:00+00:00, prior8high=2.088200, depth_time=2026-10-16T11:00:15+00:00, book20_bid_proxy_usdt=8133, book20_ask_proxy_usdt=12770, funding_indicative=-0.000746, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.25%, turnover=20524334. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T11:00:01+00:00, last15m_closed_end=2026-10-16T11:00+00:00, prior8high=0.084570, depth_time=2026-10-16T11:00:08+00:00, book20_bid_proxy_usdt=24758, book20_ask_proxy_usdt=22281, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.01%, turnover=5673597. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T11:00:01+00:00, last15m_closed_end=2026-10-16T11:00+00:00, prior8high=0.079390, depth_time=2026-10-16T11:00:07+00:00, book20_bid_proxy_usdt=378267, book20_ask_proxy_usdt=498202, funding_indicative=0.000037, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.28%, turnover=39601980. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
