# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T06:45:15Z**
- feed_generated_utc: 2026-11-06T06:45:16+00:00
- source_sha256: `76649dcd3a0280f1d873cc877023ffc3736d18c0532495483e44771146feda2e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T06:45+00:00, close=75694.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T06:00+00:00, close=75669.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T04:00+00:00, close=75880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|XRP_USDT|1.194200|-4.04|-8.80|-3.63|445064027|0.84|
|BCH_USDT|268.900000|-3.66|-6.72|-3.25|7404884|0.74|
|FLUID_USDT|2.454000|-3.08|18.89|-2.67|6239934|4.08|
|XPL_USDT|0.057310|-2.16|-27.39|-1.75|12462150|1.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|268.900000|273.870000|268.900000|29.11|Y|Y/Y|Y/Y|Y|Y|
|FLUID_USDT|2.454000|2.409000|2.454000|1.76|N|Y/Y|N/N|Y|N|
|XPL_USDT|0.057310|0.056460|0.057310|0.90|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.194200|1.188800|1.194200|0.43|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T06:45:00+00:00, last15m_closed_end=2026-11-06T06:45+00:00, prior8high=277.120000, depth_time=2026-11-06T06:45:10+00:00, book20_bid_proxy_usdt=65467, book20_ask_proxy_usdt=75471, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.66%, turnover=7404884. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T06:45:00+00:00, last15m_closed_end=2026-11-06T06:45+00:00, prior8high=2.456000, depth_time=2026-11-06T06:45:08+00:00, book20_bid_proxy_usdt=202785, book20_ask_proxy_usdt=149638, funding_indicative=0.000295, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.08%, turnover=6239934. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T06:45:00+00:00, last15m_closed_end=2026-11-06T06:45+00:00, prior8high=0.057540, depth_time=2026-11-06T06:45:14+00:00, book20_bid_proxy_usdt=413479, book20_ask_proxy_usdt=389106, funding_indicative=0.000050, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.16%, turnover=12462150. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T06:44:59+00:00, last15m_closed_end=2026-11-06T06:45+00:00, prior8high=1.207300, depth_time=2026-11-06T06:45:06+00:00, book20_bid_proxy_usdt=3618212, book20_ask_proxy_usdt=4225203, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.04%, turnover=445064027. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
