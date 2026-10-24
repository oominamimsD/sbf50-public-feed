# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T21:30:17Z**
- feed_generated_utc: 2026-10-24T21:30:20+00:00
- source_sha256: `04107b6e024f028742366c02d40e8456621db931cb165771db648e11352783f7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T21:30+00:00, close=80435.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T21:00+00:00, close=80489.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T20:00+00:00, close=80455.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.057560|-14.59|85.97|-15.43|12595450|6.94|
|BIRB_USDT|0.091400|-6.40|88.37|-7.24|11765826|6.56|
|IRYS_USDT|0.044560|-3.23|249.21|-4.07|38116275|2.25|
|STRK_USDT|0.046430|-0.64|-29.81|-1.48|9148669|2.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.091400|0.090940|0.091400|1.01|N|Y/Y|N/N|Y|N|
|IRYS_USDT|0.044560|0.042300|0.044520|0.80|N|Y/Y|Y/N|Y|N|
|ORDER_USDT|0.057560|0.056100|0.057690|0.63|N|N/N|N/N|Y|N|
|STRK_USDT|0.046430|0.046250|0.046430|0.88|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-24T21:30:01+00:00, last15m_closed_end=2026-10-24T21:30+00:00, prior8high=0.094440, depth_time=2026-10-24T21:30:11+00:00, book20_bid_proxy_usdt=21673, book20_ask_proxy_usdt=30445, funding_indicative=-0.008274, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.40%, turnover=11765826. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-24T21:30:01+00:00, last15m_closed_end=2026-10-24T21:30+00:00, prior8high=0.045710, depth_time=2026-10-24T21:30:13+00:00, book20_bid_proxy_usdt=61718, book20_ask_proxy_usdt=50168, funding_indicative=0.000012, next_funding_utc=2026-10-24T22:00:00+00:00, funding_cycle_h=1, 24h_change=-3.23%, turnover=38116275. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-24T21:30:01+00:00, last15m_closed_end=2026-10-24T21:30+00:00, prior8high=0.064800, depth_time=2026-10-24T21:30:09+00:00, book20_bid_proxy_usdt=71161, book20_ask_proxy_usdt=61890, funding_indicative=-0.001359, next_funding_utc=2026-10-24T22:00:00+00:00, funding_cycle_h=1, 24h_change=-14.59%, turnover=12595450. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-24T21:30:01+00:00, last15m_closed_end=2026-10-24T21:30+00:00, prior8high=0.047580, depth_time=2026-10-24T21:30:16+00:00, book20_bid_proxy_usdt=985362, book20_ask_proxy_usdt=845374, funding_indicative=0.000019, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.64%, turnover=9148669. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
