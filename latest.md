# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T02:15:23Z**
- feed_generated_utc: 2026-10-21T02:15:25+00:00
- source_sha256: `5e79712c5c6282d955153d9d74223058fd7ca3528bb739b954765d91c280aaaf`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T02:15+00:00, close=82750, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T02:00+00:00, close=82965.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T00:00+00:00, close=82984.8, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.187490|-13.10|5.69|-13.30|10380910|0.53|
|XMR_USDT|580.850000|-6.34|10.02|-6.54|19912351|0.17|
|BR_USDT|0.627660|-3.53|44.95|-3.73|36104181|3.03|
|AGT_USDT|0.063542|-1.68|292.79|-1.88|7104521|2.99|
|TIA_USDT|0.613700|-1.44|6.30|-1.64|49565848|1.63|
|PHA_USDT|0.057040|-1.34|3.65|-1.54|9395465|1.75|
|SEI_USDT|0.061070|-0.90|-2.08|-1.10|6120555|3.27|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.063542|0.060101|0.063542|0.65|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.187490|0.188210|0.187490|0.96|N|Y/Y|N/N|N|N|
|BR_USDT|0.627660|0.614910|0.627300|0.88|N|Y/Y|N/N|N|N|
|PHA_USDT|0.057040|0.056840|0.057040|2.23|N|Y/Y|N/N|N|N|
|SEI_USDT|0.061070|0.060900|0.061070|0.76|N|N/N|Y/Y|N|N|
|TIA_USDT|0.613700|0.605800|0.613700|1.33|N|Y/Y|Y/Y|N|N|
|XMR_USDT|580.850000|572.610000|580.850000|0.83|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T02:14:59+00:00, last15m_closed_end=2026-10-21T02:15+00:00, prior8high=0.069341, depth_time=2026-10-21T02:15:14+00:00, book20_bid_proxy_usdt=7131, book20_ask_proxy_usdt=5276, funding_indicative=0.000049, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=7104521. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T02:14:59+00:00, last15m_closed_end=2026-10-21T02:15+00:00, prior8high=0.194560, depth_time=2026-10-21T02:15:07+00:00, book20_bid_proxy_usdt=29634, book20_ask_proxy_usdt=23979, funding_indicative=0.000058, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-13.10%, turnover=10380910. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T02:14:59+00:00, last15m_closed_end=2026-10-21T02:15+00:00, prior8high=0.664000, depth_time=2026-10-21T02:15:12+00:00, book20_bid_proxy_usdt=2508, book20_ask_proxy_usdt=3033, funding_indicative=0.000007, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.53%, turnover=36104181. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T02:14:59+00:00, last15m_closed_end=2026-10-21T02:15+00:00, prior8high=0.058080, depth_time=2026-10-21T02:15:19+00:00, book20_bid_proxy_usdt=53108, book20_ask_proxy_usdt=92788, funding_indicative=-0.000047, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.34%, turnover=9395465. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-21T02:14:59+00:00, last15m_closed_end=2026-10-21T02:15+00:00, prior8high=0.061880, depth_time=2026-10-21T02:15:22+00:00, book20_bid_proxy_usdt=268854, book20_ask_proxy_usdt=223751, funding_indicative=-0.000072, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.90%, turnover=6120555. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T02:14:59+00:00, last15m_closed_end=2026-10-21T02:15+00:00, prior8high=0.625200, depth_time=2026-10-21T02:15:17+00:00, book20_bid_proxy_usdt=214817, book20_ask_proxy_usdt=241735, funding_indicative=-0.000053, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.44%, turnover=49565848. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T02:14:59+00:00, last15m_closed_end=2026-10-21T02:15+00:00, prior8high=601.630000, depth_time=2026-10-21T02:15:10+00:00, book20_bid_proxy_usdt=16125, book20_ask_proxy_usdt=6965, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.34%, turnover=19912351. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
