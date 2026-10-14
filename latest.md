# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T06:15:18Z**
- feed_generated_utc: 2026-10-14T06:15:20+00:00
- source_sha256: `5c2aafe408f0dcc75e2f8df771d0c5f02e52a0faabebb1e9b34ad7069ee6199b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T06:15+00:00, close=83547, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T06:00+00:00, close=83434.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T04:00+00:00, close=83663.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.081140|-6.66|55.47|-6.87|30345984|1.23|
|MAGIC_USDT|0.112490|-5.19|65.13|-5.40|5454406|2.67|
|W_USDT|0.016141|-3.93|11.22|-4.14|7022961|3.72|
|TIA_USDT|0.555200|-3.82|16.56|-4.03|44763272|1.80|
|UNI_USDT|7.348000|-2.95|-15.19|-3.16|19758388|1.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.112490|0.111620|0.112490|1.73|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.081140|0.080450|0.081100|3.45|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.555200|0.547400|0.555200|1.43|N|Y/Y|N/N|N|N|
|UNI_USDT|7.348000|7.259000|7.348000|0.72|N|Y/Y|Y/N|N|N|
|W_USDT|0.016141|0.015960|0.016141|2.27|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T06:15:00+00:00, last15m_closed_end=2026-10-14T06:15+00:00, prior8high=0.115610, depth_time=2026-10-14T06:15:08+00:00, book20_bid_proxy_usdt=172504, book20_ask_proxy_usdt=169692, funding_indicative=-0.000087, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.19%, turnover=5454406. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T06:15:00+00:00, last15m_closed_end=2026-10-14T06:15+00:00, prior8high=0.085530, depth_time=2026-10-14T06:15:07+00:00, book20_bid_proxy_usdt=164877, book20_ask_proxy_usdt=210275, funding_indicative=0.000050, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.66%, turnover=30345984. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T06:15:00+00:00, last15m_closed_end=2026-10-14T06:15+00:00, prior8high=0.581500, depth_time=2026-10-14T06:15:14+00:00, book20_bid_proxy_usdt=108573, book20_ask_proxy_usdt=255665, funding_indicative=-0.000010, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.82%, turnover=44763272. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T06:15:00+00:00, last15m_closed_end=2026-10-14T06:15+00:00, prior8high=7.510000, depth_time=2026-10-14T06:15:17+00:00, book20_bid_proxy_usdt=1727348, book20_ask_proxy_usdt=2062227, funding_indicative=0.000100, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.95%, turnover=19758388. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T06:15:00+00:00, last15m_closed_end=2026-10-14T06:15+00:00, prior8high=0.016644, depth_time=2026-10-14T06:15:12+00:00, book20_bid_proxy_usdt=44739, book20_ask_proxy_usdt=32629, funding_indicative=-0.000141, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.93%, turnover=7022961. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
