# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T08:45:14Z**
- feed_generated_utc: 2026-10-16T08:45:16+00:00
- source_sha256: `6c9f18a9feb70ea60292da4befd97cea1edf4329cd0cdf863b3d4b4b12408001`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T08:45+00:00, close=82285.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T08:00+00:00, close=82258.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T08:00+00:00, close=82258.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.079040|-17.97|31.38|-17.87|47947240|1.26|
|RLC_USDT|0.869200|-5.09|18.56|-4.99|5016287|1.15|
|NIL_USDT|0.083520|-3.86|-3.54|-3.76|8435928|3.59|
|AKE_USDT|0.030538|-3.37|5.21|-3.27|21332697|1.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.030538|0.028483|0.030512|2.47|N|Y/Y|N/N|Y|N|
|NIL_USDT|0.083520|0.082730|0.083520|1.64|N|Y/Y|Y/N|Y|N|
|RLC_USDT|0.869200|0.859900|0.869200|0.25|N|N/N|Y/Y|Y|N|
|STRK_USDT|0.079040|0.078350|0.079000|1.61|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T08:45:01+00:00, last15m_closed_end=2026-10-16T08:45+00:00, prior8high=0.031053, depth_time=2026-10-16T08:45:13+00:00, book20_bid_proxy_usdt=13762, book20_ask_proxy_usdt=15579, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.37%, turnover=21332697. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T08:45:01+00:00, last15m_closed_end=2026-10-16T08:45+00:00, prior8high=0.086860, depth_time=2026-10-16T08:45:11+00:00, book20_bid_proxy_usdt=36549, book20_ask_proxy_usdt=29512, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.86%, turnover=8435928. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-16T08:45:01+00:00, last15m_closed_end=2026-10-16T08:45+00:00, prior8high=0.886600, depth_time=2026-10-16T08:45:05+00:00, book20_bid_proxy_usdt=70481, book20_ask_proxy_usdt=80362, funding_indicative=-0.000557, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.09%, turnover=5016287. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T08:45:01+00:00, last15m_closed_end=2026-10-16T08:45+00:00, prior8high=0.083550, depth_time=2026-10-16T08:45:06+00:00, book20_bid_proxy_usdt=286907, book20_ask_proxy_usdt=312963, funding_indicative=-0.000019, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-17.97%, turnover=47947240. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
