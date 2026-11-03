# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T22:15:14Z**
- feed_generated_utc: 2026-11-03T22:15:15+00:00
- source_sha256: `2646248402b533f772e5f4f1ba389660ecfd65501026535f4404154621f1a933`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T22:15+00:00, close=77791.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T22:00+00:00, close=77870.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T20:00+00:00, close=77586.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003961|-4.69|-81.24|-4.85|13630885|2.52|
|EVAA_USDT|1.456600|-3.94|108.47|-4.10|5220186|0.69|
|QNT_USDT|193.390000|-1.03|-2.27|-1.19|57524656|0.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003961|0.003851|0.003961|0.48|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.456600|1.427900|1.456600|0.59|N|Y/Y|N/N|Y|N|
|QNT_USDT|193.390000|190.330000|193.390000|0.87|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T22:15:03+00:00, last15m_closed_end=2026-11-03T22:15+00:00, prior8high=0.004140, depth_time=2026-11-03T22:15:07+00:00, book20_bid_proxy_usdt=18315, book20_ask_proxy_usdt=33185, funding_indicative=-0.000590, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.69%, turnover=13630885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-11-03T22:15:03+00:00, last15m_closed_end=2026-11-03T22:15+00:00, prior8high=1.486000, depth_time=2026-11-03T22:15:10+00:00, book20_bid_proxy_usdt=21937, book20_ask_proxy_usdt=8005, funding_indicative=0.000050, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.94%, turnover=5220186. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T22:15:03+00:00, last15m_closed_end=2026-11-03T22:15+00:00, prior8high=193.640000, depth_time=2026-11-03T22:15:12+00:00, book20_bid_proxy_usdt=77932, book20_ask_proxy_usdt=68732, funding_indicative=0.000064, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.03%, turnover=57524656. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
