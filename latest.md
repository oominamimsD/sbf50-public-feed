# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T16:00:14Z**
- feed_generated_utc: 2026-11-06T16:00:15+00:00
- source_sha256: `a8a1e23ffde0a40e7813ef28aa7b1db702faa041f8b9f00392f85301da06226d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T16:00+00:00, close=75832.8, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T16:00+00:00, close=75832.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T16:00+00:00, close=75832.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.003035|-14.19|-47.07|-14.61|5454821|9.90|
|BTW_USDT|1.127200|-6.07|-6.02|-6.49|8539532|6.21|
|XPL_USDT|0.057500|-0.70|-26.11|-1.12|7354609|1.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.127200|1.131500|1.127200|1.08|N|Y/N|N/N|Y|N|
|JCT_USDT|0.003035|0.003308|0.003035|2.67|Y|Y/Y|Y/Y|Y|Y|
|XPL_USDT|0.057500|0.057110|0.057500|0.92|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-11-06T16:00:00+00:00, last15m_closed_end=2026-11-06T16:00+00:00, prior8high=1.317300, depth_time=2026-11-06T16:00:10+00:00, book20_bid_proxy_usdt=13072, book20_ask_proxy_usdt=10837, funding_indicative=0.000050, next_funding_utc=2026-11-06T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.07%, turnover=8539532. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-06T16:00:00+00:00, last15m_closed_end=2026-11-06T16:00+00:00, prior8high=0.003840, depth_time=2026-11-06T16:00:08+00:00, book20_bid_proxy_usdt=56087, book20_ask_proxy_usdt=52314, funding_indicative=0.000050, next_funding_utc=2026-11-06T20:00:00+00:00, funding_cycle_h=4, 24h_change=-14.19%, turnover=5454821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T16:00:00+00:00, last15m_closed_end=2026-11-06T16:00+00:00, prior8high=0.058620, depth_time=2026-11-06T16:00:13+00:00, book20_bid_proxy_usdt=539305, book20_ask_proxy_usdt=400882, funding_indicative=0.000050, next_funding_utc=2026-11-06T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.70%, turnover=7354609. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
