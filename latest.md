# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T12:30:22Z**
- feed_generated_utc: 2026-10-19T12:30:24+00:00
- source_sha256: `138a1f65a82ef8388712efd7dc8c4610795cf237f6c6b35a249dc3c1b81060f1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T12:30+00:00, close=82525.6, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-19T12:00+00:00, close=82317.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T12:00+00:00, close=82317.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.993700|-13.52|18.51|-15.23|21245480|0.50|
|STRK_USDT|0.058300|-5.29|-51.11|-7.00|18190186|1.72|
|HBAR_USDT|0.083500|-2.65|-10.96|-4.36|40798567|1.20|
|TIA_USDT|0.605700|-1.97|2.88|-3.68|49456292|1.65|
|SEI_USDT|0.059950|-0.48|-15.43|-2.19|9193897|1.67|
|XAUT_USDT|4160.090000|0.29|-0.70|-1.42|93851798|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.993700|1.978100|1.993700|1.92|N|Y/Y|Y/Y|N|N|
|HBAR_USDT|0.083500|0.082730|0.083500|1.33|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.059950|0.059210|0.059950|0.85|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.058300|0.057600|0.058300|1.14|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.605700|0.602400|0.605700|0.90|N|Y/Y|Y/Y|N|N|
|XAUT_USDT|4160.090000|4154.090000|4160.090000|1.06|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T12:30:01+00:00, last15m_closed_end=2026-10-19T12:30+00:00, prior8high=2.239100, depth_time=2026-10-19T12:30:08+00:00, book20_bid_proxy_usdt=8149, book20_ask_proxy_usdt=14527, funding_indicative=-0.000757, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.52%, turnover=21245480. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T12:30:01+00:00, last15m_closed_end=2026-10-19T12:30+00:00, prior8high=0.084010, depth_time=2026-10-19T12:30:12+00:00, book20_bid_proxy_usdt=371263, book20_ask_proxy_usdt=426428, funding_indicative=0.000000, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.65%, turnover=40798567. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-19T12:30:01+00:00, last15m_closed_end=2026-10-19T12:30+00:00, prior8high=0.060390, depth_time=2026-10-19T12:30:17+00:00, book20_bid_proxy_usdt=184035, book20_ask_proxy_usdt=245396, funding_indicative=0.000019, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.48%, turnover=9193897. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T12:30:01+00:00, last15m_closed_end=2026-10-19T12:30+00:00, prior8high=0.060310, depth_time=2026-10-19T12:30:07+00:00, book20_bid_proxy_usdt=716353, book20_ask_proxy_usdt=598010, funding_indicative=0.000050, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.29%, turnover=18190186. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T12:30:01+00:00, last15m_closed_end=2026-10-19T12:30+00:00, prior8high=0.614900, depth_time=2026-10-19T12:30:15+00:00, book20_bid_proxy_usdt=260981, book20_ask_proxy_usdt=162998, funding_indicative=0.000001, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.97%, turnover=49456292. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-19T12:30:01+00:00, last15m_closed_end=2026-10-19T12:30+00:00, prior8high=4169.510000, depth_time=2026-10-19T12:30:19+00:00, book20_bid_proxy_usdt=94394, book20_ask_proxy_usdt=225007, funding_indicative=0.000006, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=4, 24h_change=0.29%, turnover=93851798. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
