# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T05:45:16Z**
- feed_generated_utc: 2026-11-06T05:45:17+00:00
- source_sha256: `c91a44c233175712acf145c33ee9e2b4f73485d7ab174b50e5fc944576a536e2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T05:45+00:00, close=75590.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T05:00+00:00, close=75744, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T04:00+00:00, close=75880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ELSA_USDT|0.076810|-5.34|2.82|-4.79|6238106|3.91|
|FLUID_USDT|2.432000|-3.94|17.82|-3.39|6434842|4.11|
|XRP_USDT|1.199000|-3.66|-8.43|-3.11|438249253|0.83|
|XPL_USDT|0.057080|-2.56|-27.68|-2.01|12518359|1.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ELSA_USDT|0.076810|0.076350|0.076810|0.21|N|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.432000|2.409000|2.432000|0.59|N|Y/Y|N/N|Y|N|
|XPL_USDT|0.057080|0.056370|0.057080|1.06|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.199000|1.194200|1.198900|1.45|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ELSA_USDT: quote_utc=2026-11-06T05:44:59+00:00, last15m_closed_end=2026-11-06T05:45+00:00, prior8high=0.078830, depth_time=2026-11-06T05:45:04+00:00, book20_bid_proxy_usdt=22497, book20_ask_proxy_usdt=30244, funding_indicative=0.000074, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.34%, turnover=6238106. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T05:44:59+00:00, last15m_closed_end=2026-11-06T05:45+00:00, prior8high=2.456000, depth_time=2026-11-06T05:45:10+00:00, book20_bid_proxy_usdt=232810, book20_ask_proxy_usdt=166161, funding_indicative=0.000258, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.94%, turnover=6434842. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T05:45:00+00:00, last15m_closed_end=2026-11-06T05:45+00:00, prior8high=0.057540, depth_time=2026-11-06T05:45:14+00:00, book20_bid_proxy_usdt=383752, book20_ask_proxy_usdt=448365, funding_indicative=0.000050, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.56%, turnover=12518359. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T05:44:59+00:00, last15m_closed_end=2026-11-06T05:45+00:00, prior8high=1.209400, depth_time=2026-11-06T05:45:12+00:00, book20_bid_proxy_usdt=4246803, book20_ask_proxy_usdt=3838359, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.66%, turnover=438249253. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
