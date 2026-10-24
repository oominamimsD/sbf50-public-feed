# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T18:45:16Z**
- feed_generated_utc: 2026-10-24T18:45:19+00:00
- source_sha256: `4659a6f98fbedf1adc7b4746a23f195fad3ac8a51ba71ca0d47e1d17d3179fd7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T18:45+00:00, close=80323.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T18:00+00:00, close=80238.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T16:00+00:00, close=79763.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.057970|-13.99|87.30|-14.69|12107252|1.73|
|BIRB_USDT|0.089750|-8.09|84.97|-8.79|11917431|1.11|
|IRYS_USDT|0.044530|-3.30|248.98|-4.00|65656725|6.74|
|BR_USDT|0.464700|-0.42|23.72|-1.12|5266513|6.46|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.089750|0.091630|0.089980|1.58|Y|Y/Y|N/N|Y|N|
|BR_USDT|0.464700|0.461700|0.464700|0.20|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.044530|0.046940|0.044550|1.68|Y|Y/Y|Y/N|Y|N|
|ORDER_USDT|0.057970|0.065140|0.057390|0.87|N|N/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-24T18:45:02+00:00, last15m_closed_end=2026-10-24T18:45+00:00, prior8high=0.096610, depth_time=2026-10-24T18:45:10+00:00, book20_bid_proxy_usdt=11680, book20_ask_proxy_usdt=17728, funding_indicative=-0.007730, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.09%, turnover=11917431. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-24T18:45:03+00:00, last15m_closed_end=2026-10-24T18:45+00:00, prior8high=0.479200, depth_time=2026-10-24T18:45:15+00:00, book20_bid_proxy_usdt=31462, book20_ask_proxy_usdt=34337, funding_indicative=0.000050, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.42%, turnover=5266513. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-24T18:45:02+00:00, last15m_closed_end=2026-10-24T18:45+00:00, prior8high=0.051840, depth_time=2026-10-24T18:45:13+00:00, book20_bid_proxy_usdt=55451, book20_ask_proxy_usdt=46692, funding_indicative=0.000012, next_funding_utc=2026-10-24T19:00:00+00:00, funding_cycle_h=1, 24h_change=-3.30%, turnover=65656725. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-24T18:45:02+00:00, last15m_closed_end=2026-10-24T18:45+00:00, prior8high=0.074180, depth_time=2026-10-24T18:45:08+00:00, book20_bid_proxy_usdt=51583, book20_ask_proxy_usdt=32707, funding_indicative=-0.002974, next_funding_utc=2026-10-24T19:00:00+00:00, funding_cycle_h=1, 24h_change=-13.99%, turnover=12107252. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
