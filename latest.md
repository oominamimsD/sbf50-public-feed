# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T08:45:13Z**
- feed_generated_utc: 2026-11-06T08:45:14+00:00
- source_sha256: `2cacc4a460b93613e32cdadcb55e48bedd125bb1eee5c32db9c217e72400c1f1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T08:45+00:00, close=75676.8, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T08:00+00:00, close=75573.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T08:00+00:00, close=75573.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BCH_USDT|266.140000|-4.65|-7.68|-4.21|7700912|2.63|
|FLUID_USDT|2.421000|-4.38|17.29|-3.94|5062307|4.13|
|XRP_USDT|1.190100|-4.37|-9.11|-3.93|473927670|0.84|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|266.140000|261.500000|266.140000|2.97|N|Y/Y|Y/Y|Y|N|
|FLUID_USDT|2.421000|2.384000|2.421000|0.16|N|Y/Y|N/N|Y|N|
|XRP_USDT|1.190100|1.177100|1.190100|0.81|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T08:45:00+00:00, last15m_closed_end=2026-11-06T08:45+00:00, prior8high=277.780000, depth_time=2026-11-06T08:45:07+00:00, book20_bid_proxy_usdt=40731, book20_ask_proxy_usdt=105321, funding_indicative=-0.000001, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.65%, turnover=7700912. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T08:45:00+00:00, last15m_closed_end=2026-11-06T08:45+00:00, prior8high=2.459000, depth_time=2026-11-06T08:45:03+00:00, book20_bid_proxy_usdt=231816, book20_ask_proxy_usdt=160258, funding_indicative=0.000059, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.38%, turnover=5062307. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T08:45:00+00:00, last15m_closed_end=2026-11-06T08:45+00:00, prior8high=1.199400, depth_time=2026-11-06T08:45:12+00:00, book20_bid_proxy_usdt=3270255, book20_ask_proxy_usdt=3767328, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.37%, turnover=473927670. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
