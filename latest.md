# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T23:15:16Z**
- feed_generated_utc: 2026-10-24T23:15:19+00:00
- source_sha256: `5c07290a4e4dab2eb3c7246e41b15e1546cc16cb6846a1f6c334acdc5a63ab96`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T23:15+00:00, close=80576.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T23:00+00:00, close=80571.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T20:00+00:00, close=80455.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.085110|-12.85|75.41|-13.86|11630295|2.35|
|IRYS_USDT|0.043150|-6.29|238.16|-7.30|33835379|9.27|
|STRK_USDT|0.046440|-0.62|-29.79|-1.63|8316727|2.15|
|DOT_USDT|1.038500|-0.05|-7.06|-1.06|11276017|0.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.085110|0.083640|0.085460|0.55|N|Y/Y|N/N|Y|N|
|DOT_USDT|1.038500|1.033000|1.038500|0.50|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.043150|0.042610|0.043270|1.01|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.046440|0.046170|0.046440|1.35|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-24T23:15:04+00:00, last15m_closed_end=2026-10-24T23:15+00:00, prior8high=0.092260, depth_time=2026-10-24T23:15:08+00:00, book20_bid_proxy_usdt=19907, book20_ask_proxy_usdt=17704, funding_indicative=-0.008790, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-12.85%, turnover=11630295. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-24T23:15:04+00:00, last15m_closed_end=2026-10-24T23:15+00:00, prior8high=1.040400, depth_time=2026-10-24T23:15:15+00:00, book20_bid_proxy_usdt=266412, book20_ask_proxy_usdt=428305, funding_indicative=-0.000105, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.05%, turnover=11276017. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-24T23:15:03+00:00, last15m_closed_end=2026-10-24T23:15+00:00, prior8high=0.045580, depth_time=2026-10-24T23:15:10+00:00, book20_bid_proxy_usdt=48268, book20_ask_proxy_usdt=64706, funding_indicative=0.000012, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=1, 24h_change=-6.29%, turnover=33835379. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-24T23:15:04+00:00, last15m_closed_end=2026-10-24T23:15+00:00, prior8high=0.046670, depth_time=2026-10-24T23:15:13+00:00, book20_bid_proxy_usdt=998666, book20_ask_proxy_usdt=845350, funding_indicative=0.000022, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.62%, turnover=8316727. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
