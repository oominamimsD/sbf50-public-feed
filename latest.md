# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T01:45:19Z**
- feed_generated_utc: 2026-10-21T01:45:21+00:00
- source_sha256: `76b04097ea651ec13fd1d861fcf46c6caa83aac439573847fd435205d2f98cf3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T01:45+00:00, close=82946, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T01:00+00:00, close=82991, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T00:00+00:00, close=82984.8, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.190780|-11.58|7.55|-12.02|10352000|0.52|
|XMR_USDT|588.010000|-5.19|11.38|-5.63|19756894|2.21|
|AGT_USDT|0.063449|-1.82|292.21|-2.26|7320411|7.89|
|TIA_USDT|0.616800|-0.94|6.84|-1.38|48930573|1.62|
|PHA_USDT|0.057290|-0.91|4.10|-1.35|9849746|3.49|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.063449|0.055541|0.063449|0.49|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.190780|0.189610|0.190940|1.70|N|Y/Y|N/N|N|N|
|PHA_USDT|0.057290|0.056840|0.057290|0.60|N|Y/Y|N/N|N|N|
|TIA_USDT|0.616800|0.605800|0.616800|2.18|N|Y/Y|Y/Y|N|N|
|XMR_USDT|588.010000|572.610000|587.970000|7.96|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T01:44:59+00:00, last15m_closed_end=2026-10-21T01:45+00:00, prior8high=0.069341, depth_time=2026-10-21T01:45:13+00:00, book20_bid_proxy_usdt=7482, book20_ask_proxy_usdt=6931, funding_indicative=0.000058, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.82%, turnover=7320411. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T01:44:59+00:00, last15m_closed_end=2026-10-21T01:45+00:00, prior8high=0.195840, depth_time=2026-10-21T01:45:08+00:00, book20_bid_proxy_usdt=19728, book20_ask_proxy_usdt=25428, funding_indicative=0.000078, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-11.58%, turnover=10352000. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T01:44:59+00:00, last15m_closed_end=2026-10-21T01:45+00:00, prior8high=0.058370, depth_time=2026-10-21T01:45:18+00:00, book20_bid_proxy_usdt=81978, book20_ask_proxy_usdt=79744, funding_indicative=-0.000042, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.91%, turnover=9849746. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T01:44:59+00:00, last15m_closed_end=2026-10-21T01:45+00:00, prior8high=0.625200, depth_time=2026-10-21T01:45:15+00:00, book20_bid_proxy_usdt=161753, book20_ask_proxy_usdt=191719, funding_indicative=-0.000046, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.94%, turnover=48930573. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T01:44:59+00:00, last15m_closed_end=2026-10-21T01:45+00:00, prior8high=605.900000, depth_time=2026-10-21T01:45:11+00:00, book20_bid_proxy_usdt=15303, book20_ask_proxy_usdt=14784, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.19%, turnover=19756894. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
