# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T04:45:18Z**
- feed_generated_utc: 2026-11-06T04:45:19+00:00
- source_sha256: `96cbd4d35cfcb5fbf238d9faf3349d0d06eaa80237ec42c510df208e10d110ac`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T04:45+00:00, close=75738, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T04:00+00:00, close=75880.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T04:00+00:00, close=75880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ELSA_USDT|0.078250|-3.57|4.75|-3.19|6723373|7.67|
|FLUID_USDT|2.447000|-3.35|18.55|-2.97|6757733|4.09|
|XRP_USDT|1.204400|-3.22|-8.02|-2.84|431526599|0.83|
|XPL_USDT|0.057110|-2.50|-27.64|-2.12|12593133|3.50|
|ZRO_USDT|1.583000|-2.41|-10.27|-2.03|7429391|0.63|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ELSA_USDT|0.078250|0.077150|0.078250|0.28|N|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.447000|2.411000|2.447000|0.64|N|Y/Y|N/N|Y|N|
|XPL_USDT|0.057110|0.056370|0.057110|0.70|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.204400|1.199900|1.204200|1.04|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.583000|1.572400|1.583000|1.22|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ELSA_USDT: quote_utc=2026-11-06T04:45:01+00:00, last15m_closed_end=2026-11-06T04:45+00:00, prior8high=0.080920, depth_time=2026-11-06T04:45:07+00:00, book20_bid_proxy_usdt=23111, book20_ask_proxy_usdt=23720, funding_indicative=0.000109, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.57%, turnover=6723373. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T04:45:01+00:00, last15m_closed_end=2026-11-06T04:45+00:00, prior8high=2.468000, depth_time=2026-11-06T04:45:05+00:00, book20_bid_proxy_usdt=168336, book20_ask_proxy_usdt=146081, funding_indicative=0.000272, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.35%, turnover=6757733. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T04:45:01+00:00, last15m_closed_end=2026-11-06T04:45+00:00, prior8high=0.057930, depth_time=2026-11-06T04:45:15+00:00, book20_bid_proxy_usdt=377807, book20_ask_proxy_usdt=476960, funding_indicative=0.000050, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.50%, turnover=12593133. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T04:45:01+00:00, last15m_closed_end=2026-11-06T04:45+00:00, prior8high=1.220300, depth_time=2026-11-06T04:45:12+00:00, book20_bid_proxy_usdt=4023485, book20_ask_proxy_usdt=3515285, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.22%, turnover=431526599. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-06T04:45:01+00:00, last15m_closed_end=2026-11-06T04:45+00:00, prior8high=1.616700, depth_time=2026-11-06T04:45:16+00:00, book20_bid_proxy_usdt=90754, book20_ask_proxy_usdt=73595, funding_indicative=0.000050, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.41%, turnover=7429391. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
