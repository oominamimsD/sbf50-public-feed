# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T23:30:15Z**
- feed_generated_utc: 2026-10-24T23:30:17+00:00
- source_sha256: `d02f3b01f62bb9c6d8a7e34f95f6fc07c8780da6b0bd2068d45a785d5b000d55`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T23:30+00:00, close=80591.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T23:00+00:00, close=80571.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T20:00+00:00, close=80455.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.085910|-12.03|77.06|-13.06|11646518|5.83|
|IRYS_USDT|0.042000|-8.79|229.15|-9.82|34005464|2.38|
|STRK_USDT|0.046500|-0.49|-29.70|-1.52|8356315|2.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.085910|0.083640|0.086090|1.20|N|Y/Y|N/N|Y|N|
|IRYS_USDT|0.042000|0.042610|0.042000|1.22|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.046500|0.046170|0.046500|0.71|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-24T23:30:02+00:00, last15m_closed_end=2026-10-24T23:30+00:00, prior8high=0.092050, depth_time=2026-10-24T23:30:09+00:00, book20_bid_proxy_usdt=17898, book20_ask_proxy_usdt=18048, funding_indicative=-0.008865, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-12.03%, turnover=11646518. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-24T23:30:01+00:00, last15m_closed_end=2026-10-24T23:30+00:00, prior8high=0.045580, depth_time=2026-10-24T23:30:11+00:00, book20_bid_proxy_usdt=80390, book20_ask_proxy_usdt=81555, funding_indicative=0.000002, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=1, 24h_change=-8.79%, turnover=34005464. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-24T23:30:02+00:00, last15m_closed_end=2026-10-24T23:30+00:00, prior8high=0.046670, depth_time=2026-10-24T23:30:13+00:00, book20_bid_proxy_usdt=1014946, book20_ask_proxy_usdt=863180, funding_indicative=0.000021, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.49%, turnover=8356315. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
