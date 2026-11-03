# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T13:45:21Z**
- feed_generated_utc: 2026-11-03T13:45:23+00:00
- source_sha256: `e3006b064731985d278ba9d26bbd7ab4dd302c06e306f72d20c3c049e170c664`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T13:45+00:00, close=77579.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T13:00+00:00, close=77400, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T12:00+00:00, close=77085.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.004199|-23.68|-86.35|-23.80|12440927|2.38|
|BTW_USDT|0.978100|-10.82|-18.19|-10.94|9453722|2.05|
|XPL_USDT|0.065010|-6.56|-12.49|-6.68|11699306|1.54|
|NEAR_USDT|3.895000|-2.86|-14.82|-2.98|83095691|2.57|
|TIA_USDT|0.444600|-2.69|-17.00|-2.81|13753883|2.25|
|ENA_USDT|0.172050|-1.70|-18.21|-1.82|73222945|0.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004199|0.004233|0.004196|2.97|Y|Y/Y|Y/Y|Y|Y|
|BTW_USDT|0.978100|0.922800|0.978100|0.38|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.172050|0.170200|0.172110|2.23|N|N/Y|Y/Y|Y|N|
|NEAR_USDT|3.895000|3.829000|3.895000|5.47|N|N/Y|Y/Y|Y|N|
|TIA_USDT|0.444600|0.438600|0.444500|2.01|N|N/Y|Y/Y|Y|N|
|XPL_USDT|0.065010|0.064160|0.065010|2.32|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T13:45:01+00:00, last15m_closed_end=2026-11-03T13:45+00:00, prior8high=0.004562, depth_time=2026-11-03T13:45:08+00:00, book20_bid_proxy_usdt=37220, book20_ask_proxy_usdt=46806, funding_indicative=-0.001494, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-23.68%, turnover=12440927. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-03T13:45:01+00:00, last15m_closed_end=2026-11-03T13:45+00:00, prior8high=1.032400, depth_time=2026-11-03T13:45:10+00:00, book20_bid_proxy_usdt=11558, book20_ask_proxy_usdt=24137, funding_indicative=-0.000012, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.82%, turnover=9453722. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-03T13:45:01+00:00, last15m_closed_end=2026-11-03T13:45+00:00, prior8high=0.173500, depth_time=2026-11-03T13:45:20+00:00, book20_bid_proxy_usdt=210785, book20_ask_proxy_usdt=147124, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.70%, turnover=73222945. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T13:45:01+00:00, last15m_closed_end=2026-11-03T13:45+00:00, prior8high=3.928000, depth_time=2026-11-03T13:45:15+00:00, book20_bid_proxy_usdt=1322672, book20_ask_proxy_usdt=441408, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.86%, turnover=83095691. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T13:45:01+00:00, last15m_closed_end=2026-11-03T13:45+00:00, prior8high=0.449000, depth_time=2026-11-03T13:45:17+00:00, book20_bid_proxy_usdt=341222, book20_ask_proxy_usdt=406872, funding_indicative=-0.000001, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.69%, turnover=13753883. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T13:45:01+00:00, last15m_closed_end=2026-11-03T13:45+00:00, prior8high=0.065540, depth_time=2026-11-03T13:45:12+00:00, book20_bid_proxy_usdt=430150, book20_ask_proxy_usdt=361924, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.56%, turnover=11699306. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
