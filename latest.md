# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T16:45:14Z**
- feed_generated_utc: 2026-10-16T16:45:15+00:00
- source_sha256: `1bee8272fa8829a332ab5d16edb11001e4948c22fc7c3ccaad7d2f8d89aedf7c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T16:45+00:00, close=81520, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T16:00+00:00, close=81322.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T16:00+00:00, close=81322.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1171.280000|-1.40|-3.86|-1.65|1546737869|0.09|
|OP_USDT|0.138200|-1.28|12.15|-1.53|15468247|0.72|
|ZRO_USDT|2.076300|-1.18|1.93|-1.43|15605816|1.44|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|OP_USDT|0.138200|0.137910|0.138170|1.45|N|N/N|N/N|Y|N|
|ZEC_USDT|1171.280000|1177.240000|1171.240000|1.62|Y|Y/Y|Y/N|Y|N|
|ZRO_USDT|2.076300|2.082500|2.076300|2.14|Y|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- OP_USDT: quote_utc=2026-10-16T16:45:01+00:00, last15m_closed_end=2026-10-16T16:45+00:00, prior8high=0.142960, depth_time=2026-10-16T16:45:10+00:00, book20_bid_proxy_usdt=28364, book20_ask_proxy_usdt=44263, funding_indicative=0.000056, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=15468247. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T16:45:01+00:00, last15m_closed_end=2026-10-16T16:45+00:00, prior8high=1227.350000, depth_time=2026-10-16T16:45:07+00:00, book20_bid_proxy_usdt=436479, book20_ask_proxy_usdt=230481, funding_indicative=0.000014, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.40%, turnover=1546737869. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-16T16:45:01+00:00, last15m_closed_end=2026-10-16T16:45+00:00, prior8high=2.187000, depth_time=2026-10-16T16:45:13+00:00, book20_bid_proxy_usdt=58312, book20_ask_proxy_usdt=46153, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.18%, turnover=15605816. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
