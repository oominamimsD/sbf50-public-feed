# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T20:15:11Z**
- feed_generated_utc: 2026-10-24T20:15:14+00:00
- source_sha256: `6e829ef578e7f050b07b529ef4c96a3d6d9acc4281d567439009c9e08de90467`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T20:15+00:00, close=80527.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T20:00+00:00, close=80455.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T20:00+00:00, close=80455.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.093790|-3.96|93.30|-4.91|11819081|3.20|
|IRYS_USDT|0.044420|-3.53|248.11|-4.48|44305236|2.25|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.093790|0.088740|0.093790|1.53|N|Y/Y|N/N|Y|N|
|IRYS_USDT|0.044420|0.042300|0.044420|0.65|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-24T20:14:59+00:00, last15m_closed_end=2026-10-24T20:15+00:00, prior8high=0.095690, depth_time=2026-10-24T20:15:08+00:00, book20_bid_proxy_usdt=27554, book20_ask_proxy_usdt=16796, funding_indicative=-0.007606, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.96%, turnover=11819081. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-24T20:14:59+00:00, last15m_closed_end=2026-10-24T20:15+00:00, prior8high=0.050880, depth_time=2026-10-24T20:15:10+00:00, book20_bid_proxy_usdt=41529, book20_ask_proxy_usdt=74868, funding_indicative=0.000012, next_funding_utc=2026-10-24T21:00:00+00:00, funding_cycle_h=1, 24h_change=-3.53%, turnover=44305236. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
