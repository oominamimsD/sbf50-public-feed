# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T23:00:12Z**
- feed_generated_utc: 2026-11-09T23:00:14+00:00
- source_sha256: `7cd6eff2b48dbd1ffbfc06928c227839484c0e1188e314723d49a8d18f569438`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T23:00+00:00, close=75256.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T23:00+00:00, close=75256.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-09T20:00+00:00, close=74856.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1174.120000|-4.20|-6.37|-3.88|2532172264|0.09|
|DOT_USDT|0.858400|-3.09|-8.10|-2.77|11186577|1.17|
|QNT_USDT|195.610000|-2.16|-3.37|-1.84|40657501|0.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|0.858400|0.856000|0.858400|1.40|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.610000|194.440000|195.610000|1.60|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1174.120000|1162.360000|1174.120000|0.72|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-11-09T23:00:00+00:00, last15m_closed_end=2026-11-09T23:00+00:00, prior8high=0.867700, depth_time=2026-11-09T23:00:09+00:00, book20_bid_proxy_usdt=760870, book20_ask_proxy_usdt=344702, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.09%, turnover=11186577. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-09T23:00:00+00:00, last15m_closed_end=2026-11-09T23:00+00:00, prior8high=196.800000, depth_time=2026-11-09T23:00:11+00:00, book20_bid_proxy_usdt=62087, book20_ask_proxy_usdt=48750, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=40657501. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T22:59:59+00:00, last15m_closed_end=2026-11-09T23:00+00:00, prior8high=1184.660000, depth_time=2026-11-09T23:00:07+00:00, book20_bid_proxy_usdt=141375, book20_ask_proxy_usdt=110666, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.20%, turnover=2532172264. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
