# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T06:15:22Z**
- feed_generated_utc: 2026-10-23T06:15:24+00:00
- source_sha256: `e266e202d3d00e7d74dca4343f008f81eb08ec8edb7db67cd7ef4c36d43c8f96`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T06:15+00:00, close=81878.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T06:00+00:00, close=81812.9, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T04:00+00:00, close=81863.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.428900|-5.12|10.91|-5.40|10022356|0.29|
|STRK_USDT|0.053050|-2.40|-44.94|-2.68|10590754|1.88|
|SILVER_USDT|54.360000|-1.62|-4.86|-1.90|341882511|1.84|
|TIA_USDT|0.559800|-1.51|-7.08|-1.79|23577640|5.36|
|XAU_USDT|4027.200000|-0.80|-3.10|-1.08|679212681|0.03|
|XAUT_USDT|4023.330000|-0.76|-2.93|-1.04|265573493|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|LIT_USDT|3.428900|3.422100|3.428900|1.48|N|Y/Y|N/N|Y|N|
|SILVER_USDT|54.360000|53.720000|54.360000|0.75|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.053050|0.052690|0.053050|2.45|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.559800|0.556900|0.559600|1.23|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4023.330000|4008.190000|4023.330000|1.13|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4027.200000|4010.840000|4027.200000|0.51|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- LIT_USDT: quote_utc=2026-10-23T06:14:59+00:00, last15m_closed_end=2026-10-23T06:15+00:00, prior8high=3.493400, depth_time=2026-10-23T06:15:08+00:00, book20_bid_proxy_usdt=26303, book20_ask_proxy_usdt=31362, funding_indicative=0.000031, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.12%, turnover=10022356. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T06:14:59+00:00, last15m_closed_end=2026-10-23T06:15+00:00, prior8high=54.680000, depth_time=2026-10-23T06:15:14+00:00, book20_bid_proxy_usdt=33095149, book20_ask_proxy_usdt=30851017, funding_indicative=0.000122, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.62%, turnover=341882511. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T06:14:59+00:00, last15m_closed_end=2026-10-23T06:15+00:00, prior8high=0.053360, depth_time=2026-10-23T06:15:11+00:00, book20_bid_proxy_usdt=504325, book20_ask_proxy_usdt=705680, funding_indicative=-0.000013, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.40%, turnover=10590754. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T06:14:59+00:00, last15m_closed_end=2026-10-23T06:15+00:00, prior8high=0.564900, depth_time=2026-10-23T06:15:16+00:00, book20_bid_proxy_usdt=397806, book20_ask_proxy_usdt=359699, funding_indicative=-0.000022, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.51%, turnover=23577640. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T06:14:59+00:00, last15m_closed_end=2026-10-23T06:15+00:00, prior8high=4032.400000, depth_time=2026-10-23T06:15:21+00:00, book20_bid_proxy_usdt=138012, book20_ask_proxy_usdt=103410, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.76%, turnover=265573493. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T06:14:59+00:00, last15m_closed_end=2026-10-23T06:15+00:00, prior8high=4036.730000, depth_time=2026-10-23T06:15:18+00:00, book20_bid_proxy_usdt=3432750, book20_ask_proxy_usdt=736345, funding_indicative=0.000088, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.80%, turnover=679212681. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
