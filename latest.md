# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T12:30:24Z**
- feed_generated_utc: 2026-10-20T12:30:26+00:00
- source_sha256: `bd146d35cc6068d7be3902dc4812311e6b75e113c5d08f24802dcd67dcede7c9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1201; contracts: 1193; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T12:30+00:00, close=81524.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T12:00+00:00, close=81467.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T12:00+00:00, close=81467.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.067610|-22.32|305.77|-21.85|8802018|3.70|
|SAND_USDT|0.056690|-4.14|-8.69|-3.67|5401752|1.76|
|NEAR_USDT|4.708000|-3.99|-15.15|-3.52|168222712|2.12|
|ARB_USDT|0.189150|-3.31|0.36|-2.84|97676589|0.53|
|LTC_USDT|58.720000|-1.69|-6.73|-1.22|13094828|1.70|
|UNI_USDT|7.167000|-1.66|-3.38|-1.19|9835967|1.40|
|TAO_USDT|264.200000|-1.52|-7.71|-1.05|59996063|1.14|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.067610|0.066520|0.067610|0.50|N|Y/Y|Y/N|Y|N|
|ARB_USDT|0.189150|0.187860|0.189150|0.99|N|Y/Y|Y/N|Y|N|
|LTC_USDT|58.720000|58.250000|58.720000|2.32|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.708000|4.630000|4.708000|2.75|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.056690|0.056510|0.056690|2.16|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|264.200000|262.530000|264.200000|3.36|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.167000|7.106000|7.167000|3.10|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T12:30:00+00:00, last15m_closed_end=2026-10-20T12:30+00:00, prior8high=0.070454, depth_time=2026-10-20T12:30:09+00:00, book20_bid_proxy_usdt=4913, book20_ask_proxy_usdt=4974, funding_indicative=0.000054, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-22.32%, turnover=8802018. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T12:30:00+00:00, last15m_closed_end=2026-10-20T12:30+00:00, prior8high=0.190320, depth_time=2026-10-20T12:30:16+00:00, book20_bid_proxy_usdt=29746, book20_ask_proxy_usdt=69705, funding_indicative=0.000094, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.31%, turnover=97676589. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-20T12:30:00+00:00, last15m_closed_end=2026-10-20T12:30+00:00, prior8high=59.130000, depth_time=2026-10-20T12:30:15+00:00, book20_bid_proxy_usdt=1306826, book20_ask_proxy_usdt=977787, funding_indicative=0.000100, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.69%, turnover=13094828. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T12:30:00+00:00, last15m_closed_end=2026-10-20T12:30+00:00, prior8high=4.708000, depth_time=2026-10-20T12:30:14+00:00, book20_bid_proxy_usdt=2789766, book20_ask_proxy_usdt=1948562, funding_indicative=0.000041, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.99%, turnover=168222712. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T12:30:00+00:00, last15m_closed_end=2026-10-20T12:30+00:00, prior8high=0.057080, depth_time=2026-10-20T12:30:10+00:00, book20_bid_proxy_usdt=583555, book20_ask_proxy_usdt=680602, funding_indicative=-0.001830, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.14%, turnover=5401752. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T12:30:00+00:00, last15m_closed_end=2026-10-20T12:30+00:00, prior8high=264.440000, depth_time=2026-10-20T12:30:23+00:00, book20_bid_proxy_usdt=66423, book20_ask_proxy_usdt=20903, funding_indicative=0.000042, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.52%, turnover=59996063. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T12:30:00+00:00, last15m_closed_end=2026-10-20T12:30+00:00, prior8high=7.169000, depth_time=2026-10-20T12:30:18+00:00, book20_bid_proxy_usdt=1203334, book20_ask_proxy_usdt=1762745, funding_indicative=0.000040, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.66%, turnover=9835967. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
