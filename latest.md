# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T12:00:21Z**
- feed_generated_utc: 2026-11-08T12:00:22+00:00
- source_sha256: `f9844a3f4b2ea624275d29b1ffb7ac187146d5cfb0aeca3c1286a9555098aa0b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T12:00+00:00, close=75944.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T12:00+00:00, close=75944.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T12:00+00:00, close=75944.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001907|-5.50|62.44|-5.53|25189583|1.05|
|TIA_USDT|0.426000|-3.40|-13.07|-3.43|6671144|2.35|
|ENA_USDT|0.154890|-3.34|-20.16|-3.37|29224178|0.65|
|WLD_USDT|0.329300|-2.11|-18.57|-2.14|22336287|3.04|
|LINK_USDT|10.781000|-1.13|-6.82|-1.16|61678559|1.85|
|ADA_USDT|0.180600|-1.09|-6.71|-1.12|9534850|5.54|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.180600|0.179200|0.180600|0.92|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.154890|0.152210|0.154890|1.66|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.781000|10.718000|10.781000|0.86|N|N/Y|Y/Y|Y|N|
|ONE_USDT|0.001907|0.001872|0.001907|0.45|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.426000|0.422800|0.426000|1.21|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.329300|0.326800|0.329300|0.31|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-08T12:00:00+00:00, last15m_closed_end=2026-11-08T12:00+00:00, prior8high=0.180900, depth_time=2026-11-08T12:00:20+00:00, book20_bid_proxy_usdt=8337962, book20_ask_proxy_usdt=9256694, funding_indicative=-0.000046, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.09%, turnover=9534850. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T12:00:00+00:00, last15m_closed_end=2026-11-08T12:00+00:00, prior8high=0.155490, depth_time=2026-11-08T12:00:12+00:00, book20_bid_proxy_usdt=213551, book20_ask_proxy_usdt=306586, funding_indicative=0.000026, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.34%, turnover=29224178. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T12:00:00+00:00, last15m_closed_end=2026-11-08T12:00+00:00, prior8high=10.807000, depth_time=2026-11-08T12:00:15+00:00, book20_bid_proxy_usdt=528470, book20_ask_proxy_usdt=323878, funding_indicative=0.000023, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=61678559. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T12:00:00+00:00, last15m_closed_end=2026-11-08T12:00+00:00, prior8high=0.002227, depth_time=2026-11-08T12:00:07+00:00, book20_bid_proxy_usdt=14406, book20_ask_proxy_usdt=11180, funding_indicative=-0.001396, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.50%, turnover=25189583. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T12:00:00+00:00, last15m_closed_end=2026-11-08T12:00+00:00, prior8high=0.427700, depth_time=2026-11-08T12:00:09+00:00, book20_bid_proxy_usdt=311360, book20_ask_proxy_usdt=405261, funding_indicative=-0.000016, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.40%, turnover=6671144. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T12:00:00+00:00, last15m_closed_end=2026-11-08T12:00+00:00, prior8high=0.330100, depth_time=2026-11-08T12:00:14+00:00, book20_bid_proxy_usdt=3884778, book20_ask_proxy_usdt=4006304, funding_indicative=-0.000028, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.11%, turnover=22336287. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
