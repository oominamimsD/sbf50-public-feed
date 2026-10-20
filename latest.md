# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T01:30:13Z**
- feed_generated_utc: 2026-10-20T01:30:15+00:00
- source_sha256: `9120de3955ba7c93eba347c42ab5aac0f242ad9e43efc6e590630c9963effc75`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T01:30+00:00, close=81428, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T01:00+00:00, close=81700.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T00:00+00:00, close=81903.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|SAND_USDT|0.057720|-2.40|-7.03|-1.82|8856773|1.73|
|ZRO_USDT|1.862800|-2.06|-17.61|-1.48|7810467|0.54|
|NEAR_USDT|4.826000|-1.59|-13.02|-1.01|170373422|4.14|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NEAR_USDT|4.826000|4.785000|4.825000|0.63|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.057720|0.057130|0.057720|4.75|N|Y/Y|N/Y|Y|N|
|ZRO_USDT|1.862800|1.833600|1.864500|0.75|N|Y/N|N/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- NEAR_USDT: quote_utc=2026-10-20T01:30:01+00:00, last15m_closed_end=2026-10-20T01:30+00:00, prior8high=4.939000, depth_time=2026-10-20T01:30:12+00:00, book20_bid_proxy_usdt=3354971, book20_ask_proxy_usdt=2260947, funding_indicative=0.000030, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=170373422. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T01:30:01+00:00, last15m_closed_end=2026-10-20T01:30+00:00, prior8high=0.059370, depth_time=2026-10-20T01:30:07+00:00, book20_bid_proxy_usdt=337588, book20_ask_proxy_usdt=697305, funding_indicative=-0.002375, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.40%, turnover=8856773. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T01:30:01+00:00, last15m_closed_end=2026-10-20T01:30+00:00, prior8high=1.924500, depth_time=2026-10-20T01:30:09+00:00, book20_bid_proxy_usdt=36340, book20_ask_proxy_usdt=55026, funding_indicative=0.000050, next_funding_utc=2026-10-20T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.06%, turnover=7810467. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
