# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T05:30:26Z**
- feed_generated_utc: 2026-10-21T05:30:28+00:00
- source_sha256: `031ffdc89b077d1e581052c420fc12e203d3a751c525bb5de8d838a7108ca81f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T05:30+00:00, close=82854.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T05:00+00:00, close=82776.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T04:00+00:00, close=82699, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.183590|-14.91|3.50|-15.24|10812985|1.63|
|BR_USDT|0.585530|-10.01|35.22|-10.34|34458904|1.20|
|XMR_USDT|581.430000|-6.25|10.13|-6.58|21135542|0.86|
|AGT_USDT|0.061462|-4.90|279.93|-5.23|6618685|1.79|
|PHA_USDT|0.056100|-2.97|1.94|-3.30|7620722|1.78|
|Q_USDT|0.119228|-2.87|189.90|-3.20|5072336|1.93|
|TIA_USDT|0.613800|-1.42|6.32|-1.75|47460165|1.63|
|SEI_USDT|0.061060|-0.92|-2.10|-1.25|6243199|1.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.061462|0.060783|0.061462|0.89|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.183590|0.184440|0.183590|1.40|Y|Y/Y|Y/N|N|N|
|BR_USDT|0.585530|0.580600|0.585530|0.98|N|Y/Y|N/N|N|N|
|PHA_USDT|0.056100|0.056320|0.056100|1.87|Y|Y/Y|N/N|N|N|
|Q_USDT|0.119228|0.114853|0.119228|1.50|N|Y/Y|N/N|N|N|
|SEI_USDT|0.061060|0.060870|0.061060|2.13|N|Y/N|N/Y|N|N|
|TIA_USDT|0.613800|0.608800|0.613800|0.53|N|Y/Y|Y/Y|N|N|
|XMR_USDT|581.430000|571.180000|581.430000|1.08|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T05:29:59+00:00, last15m_closed_end=2026-10-21T05:30+00:00, prior8high=0.064103, depth_time=2026-10-21T05:30:12+00:00, book20_bid_proxy_usdt=12734, book20_ask_proxy_usdt=8394, funding_indicative=0.000047, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.90%, turnover=6618685. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T05:29:59+00:00, last15m_closed_end=2026-10-21T05:30+00:00, prior8high=0.187530, depth_time=2026-10-21T05:30:07+00:00, book20_bid_proxy_usdt=30404, book20_ask_proxy_usdt=26188, funding_indicative=-0.000065, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-14.91%, turnover=10812985. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T05:29:59+00:00, last15m_closed_end=2026-10-21T05:30+00:00, prior8high=0.624180, depth_time=2026-10-21T05:30:10+00:00, book20_bid_proxy_usdt=3756, book20_ask_proxy_usdt=3480, funding_indicative=0.000050, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.01%, turnover=34458904. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T05:29:59+00:00, last15m_closed_end=2026-10-21T05:30+00:00, prior8high=0.058590, depth_time=2026-10-21T05:30:18+00:00, book20_bid_proxy_usdt=36697, book20_ask_proxy_usdt=68790, funding_indicative=-0.000024, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.97%, turnover=7620722. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T05:29:59+00:00, last15m_closed_end=2026-10-21T05:30+00:00, prior8high=0.125002, depth_time=2026-10-21T05:30:20+00:00, book20_bid_proxy_usdt=13509, book20_ask_proxy_usdt=13658, funding_indicative=-0.000127, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.87%, turnover=5072336. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-21T05:29:59+00:00, last15m_closed_end=2026-10-21T05:30+00:00, prior8high=0.061440, depth_time=2026-10-21T05:30:25+00:00, book20_bid_proxy_usdt=266364, book20_ask_proxy_usdt=194442, funding_indicative=-0.000047, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.92%, turnover=6243199. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T05:29:59+00:00, last15m_closed_end=2026-10-21T05:30+00:00, prior8high=0.621800, depth_time=2026-10-21T05:30:23+00:00, book20_bid_proxy_usdt=255824, book20_ask_proxy_usdt=213336, funding_indicative=-0.000089, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.42%, turnover=47460165. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T05:29:59+00:00, last15m_closed_end=2026-10-21T05:30+00:00, prior8high=581.000000, depth_time=2026-10-21T05:30:11+00:00, book20_bid_proxy_usdt=11911, book20_ask_proxy_usdt=16682, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.25%, turnover=21135542. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
