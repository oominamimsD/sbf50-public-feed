# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T21:45:20Z**
- feed_generated_utc: 2026-10-24T21:45:23+00:00
- source_sha256: `45875d2bd6b2e6195617e2ab4e551c5184e306dffebb3e55a75fa49ae9acce1e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T21:45+00:00, close=80322.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-24T21:00+00:00, close=80489.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T20:00+00:00, close=80455.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.057170|-15.17|84.71|-15.87|12632615|5.25|
|BIRB_USDT|0.089730|-8.12|84.93|-8.82|11775525|6.69|
|IRYS_USDT|0.044210|-3.99|246.47|-4.69|38206596|4.53|
|STRK_USDT|0.046550|-0.38|-29.62|-1.08|9229766|2.15|
|DOT_USDT|1.035700|-0.32|-7.31|-1.02|12455476|0.97|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.089730|0.090100|0.089730|0.65|N|Y/Y|N/N|Y|N|
|DOT_USDT|1.035700|1.033000|1.035700|0.78|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.044210|0.043660|0.044200|0.59|N|Y/Y|Y/N|Y|N|
|ORDER_USDT|0.057170|0.056100|0.057370|0.62|N|N/N|N/N|Y|N|
|STRK_USDT|0.046550|0.046250|0.046550|1.38|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-24T21:45:03+00:00, last15m_closed_end=2026-10-24T21:45+00:00, prior8high=0.094440, depth_time=2026-10-24T21:45:11+00:00, book20_bid_proxy_usdt=24952, book20_ask_proxy_usdt=23178, funding_indicative=-0.008451, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.12%, turnover=11775525. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-24T21:45:00+00:00, last15m_closed_end=2026-10-24T21:45+00:00, prior8high=1.047500, depth_time=2026-10-24T21:45:18+00:00, book20_bid_proxy_usdt=335697, book20_ask_proxy_usdt=295478, funding_indicative=-0.000085, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.32%, turnover=12455476. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-24T21:45:03+00:00, last15m_closed_end=2026-10-24T21:45+00:00, prior8high=0.045710, depth_time=2026-10-24T21:45:14+00:00, book20_bid_proxy_usdt=50003, book20_ask_proxy_usdt=65086, funding_indicative=0.000012, next_funding_utc=2026-10-24T22:00:00+00:00, funding_cycle_h=1, 24h_change=-3.99%, turnover=38206596. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-24T21:45:03+00:00, last15m_closed_end=2026-10-24T21:45+00:00, prior8high=0.064800, depth_time=2026-10-24T21:45:08+00:00, book20_bid_proxy_usdt=59403, book20_ask_proxy_usdt=76608, funding_indicative=-0.001208, next_funding_utc=2026-10-24T22:00:00+00:00, funding_cycle_h=1, 24h_change=-15.17%, turnover=12632615. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-24T21:45:00+00:00, last15m_closed_end=2026-10-24T21:45+00:00, prior8high=0.047580, depth_time=2026-10-24T21:45:16+00:00, book20_bid_proxy_usdt=1034439, book20_ask_proxy_usdt=905911, funding_indicative=0.000026, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.38%, turnover=9229766. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
