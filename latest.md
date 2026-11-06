# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T14:15:18Z**
- feed_generated_utc: 2026-11-06T14:15:20+00:00
- source_sha256: `79b0ac6bb8094c2d939024aae8d875e4ac45fb57000e491a5a9f5c2bcb0bade0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T14:15+00:00, close=75571.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T14:00+00:00, close=75866.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T12:00+00:00, close=76114.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|XRP_USDT|1.180300|-5.16|-9.86|-4.58|479212825|0.85|
|BCH_USDT|264.690000|-5.16|-8.18|-4.58|6819591|2.27|
|ANTHROPIC_USDT|1424.350000|-4.92|-20.88|-4.34|5967160|1.48|
|XPL_USDT|0.057430|-1.96|-27.23|-1.38|11797530|1.74|
|QNT_USDT|188.130000|-1.92|-5.33|-1.34|38051630|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1424.350000|1397.580000|1424.350000|4.07|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|264.690000|265.100000|264.690000|0.28|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|188.130000|188.210000|188.130000|8.83|Y|Y/Y|Y/Y|Y|Y|
|XPL_USDT|0.057430|0.057230|0.057430|2.66|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.180300|1.177800|1.180700|1.24|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-06T14:15:01+00:00, last15m_closed_end=2026-11-06T14:15+00:00, prior8high=1510.080000, depth_time=2026-11-06T14:15:13+00:00, book20_bid_proxy_usdt=6902, book20_ask_proxy_usdt=35526, funding_indicative=0.000050, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.92%, turnover=5967160. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-06T14:15:01+00:00, last15m_closed_end=2026-11-06T14:15+00:00, prior8high=271.890000, depth_time=2026-11-06T14:15:09+00:00, book20_bid_proxy_usdt=45979, book20_ask_proxy_usdt=70973, funding_indicative=-0.000046, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.16%, turnover=6819591. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T14:15:01+00:00, last15m_closed_end=2026-11-06T14:15+00:00, prior8high=192.700000, depth_time=2026-11-06T14:15:17+00:00, book20_bid_proxy_usdt=48118, book20_ask_proxy_usdt=169559, funding_indicative=-0.000015, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.92%, turnover=38051630. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T14:15:01+00:00, last15m_closed_end=2026-11-06T14:15+00:00, prior8high=0.058510, depth_time=2026-11-06T14:15:10+00:00, book20_bid_proxy_usdt=477464, book20_ask_proxy_usdt=399255, funding_indicative=0.000050, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.96%, turnover=11797530. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T14:15:01+00:00, last15m_closed_end=2026-11-06T14:15+00:00, prior8high=1.202300, depth_time=2026-11-06T14:15:08+00:00, book20_bid_proxy_usdt=3597594, book20_ask_proxy_usdt=2557500, funding_indicative=0.000090, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.16%, turnover=479212825. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
