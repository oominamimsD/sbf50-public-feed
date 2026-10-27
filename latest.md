# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T00:45:13Z**
- feed_generated_utc: 2026-10-27T00:45:15+00:00
- source_sha256: `d86d50edd13b3083456d35f7fa6ff3fd48aebd1386aae2e352671e58cd8672b1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T00:45+00:00, close=80243.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T00:00+00:00, close=80115.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T00:00+00:00, close=80115.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.626000|-4.75|-14.51|-4.56|5394101|0.61|
|NEAR_USDT|4.492000|-1.77|-8.40|-1.58|112028443|2.23|
|DOT_USDT|1.008500|-1.37|-12.05|-1.18|10600498|0.99|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.008500|0.999000|1.008800|1.16|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.492000|4.422000|4.492000|0.82|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.626000|1.610100|1.626000|2.29|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-27T00:44:59+00:00, last15m_closed_end=2026-10-27T00:45+00:00, prior8high=1.013800, depth_time=2026-10-27T00:45:12+00:00, book20_bid_proxy_usdt=354557, book20_ask_proxy_usdt=526121, funding_indicative=-0.000049, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.37%, turnover=10600498. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T00:44:59+00:00, last15m_closed_end=2026-10-27T00:45+00:00, prior8high=4.536000, depth_time=2026-10-27T00:45:09+00:00, book20_bid_proxy_usdt=4572436, book20_ask_proxy_usdt=3067256, funding_indicative=-0.000119, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=112028443. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T00:45:00+00:00, last15m_closed_end=2026-10-27T00:45+00:00, prior8high=1.647700, depth_time=2026-10-27T00:45:07+00:00, book20_bid_proxy_usdt=51047, book20_ask_proxy_usdt=28422, funding_indicative=-0.000277, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.75%, turnover=5394101. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
