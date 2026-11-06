# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T10:00:18Z**
- feed_generated_utc: 2026-11-06T10:00:19+00:00
- source_sha256: `1bfd29159d5e7bb7680e2f7c970829bf6803bfd36d1bef1c3defc6b16a7de15a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T10:00+00:00, close=76151.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T10:00+00:00, close=76151.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T08:00+00:00, close=75573.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BCH_USDT|268.960000|-3.64|-6.70|-3.82|7602645|2.98|
|XRP_USDT|1.199400|-3.63|-8.40|-3.81|483313100|0.83|
|XPL_USDT|0.057700|-1.50|-26.89|-1.68|12203310|1.73|
|QNT_USDT|188.950000|-1.49|-4.92|-1.67|36806914|0.53|
|HYPE_USDT|77.897000|-1.02|-17.07|-1.20|83831604|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|268.960000|263.610000|268.960000|2.12|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|77.897000|77.194000|77.897000|0.56|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|188.950000|188.140000|188.950000|0.62|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057700|0.057030|0.057700|0.21|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.199400|1.180700|1.199200|0.47|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T09:59:59+00:00, last15m_closed_end=2026-11-06T10:00+00:00, prior8high=269.100000, depth_time=2026-11-06T10:00:07+00:00, book20_bid_proxy_usdt=45680, book20_ask_proxy_usdt=48294, funding_indicative=-0.000029, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.64%, turnover=7602645. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-06T09:59:59+00:00, last15m_closed_end=2026-11-06T10:00+00:00, prior8high=78.516000, depth_time=2026-11-06T10:00:16+00:00, book20_bid_proxy_usdt=62197, book20_ask_proxy_usdt=93467, funding_indicative=0.000050, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.02%, turnover=83831604. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T09:59:59+00:00, last15m_closed_end=2026-11-06T10:00+00:00, prior8high=190.420000, depth_time=2026-11-06T10:00:14+00:00, book20_bid_proxy_usdt=71331, book20_ask_proxy_usdt=96999, funding_indicative=0.000033, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.49%, turnover=36806914. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T09:59:59+00:00, last15m_closed_end=2026-11-06T10:00+00:00, prior8high=0.057950, depth_time=2026-11-06T10:00:12+00:00, book20_bid_proxy_usdt=545046, book20_ask_proxy_usdt=403301, funding_indicative=0.000050, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.50%, turnover=12203310. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T09:59:59+00:00, last15m_closed_end=2026-11-06T10:00+00:00, prior8high=1.201000, depth_time=2026-11-06T10:00:10+00:00, book20_bid_proxy_usdt=3354560, book20_ask_proxy_usdt=4981080, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.63%, turnover=483313100. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
