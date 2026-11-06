# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T04:15:20Z**
- feed_generated_utc: 2026-11-06T04:15:21+00:00
- source_sha256: `9d38466911affcb0af02aa0aa5c626679f5549d550a4addd4df941b11a0abce6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T04:15+00:00, close=75705.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T04:00+00:00, close=75880.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T04:00+00:00, close=75880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ELSA_USDT|0.077900|-4.00|4.28|-3.59|6716398|7.70|
|FLUID_USDT|2.437000|-3.75|18.07|-3.34|6746613|4.10|
|XRP_USDT|1.204800|-3.19|-7.99|-2.78|425160043|0.83|
|XPL_USDT|0.056900|-2.86|-27.91|-2.45|12520126|1.76|
|ZRO_USDT|1.582300|-2.45|-10.31|-2.04|7327326|0.63|
|HYPE_USDT|77.413000|-1.63|-17.58|-1.22|84576830|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ELSA_USDT|0.077900|0.077150|0.077900|0.53|N|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.437000|2.398000|2.437000|2.62|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.413000|77.142000|77.413000|0.64|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.056900|0.056370|0.056900|1.22|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.204800|1.201500|1.205400|1.81|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.582300|1.576600|1.582300|5.35|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ELSA_USDT: quote_utc=2026-11-06T04:15:03+00:00, last15m_closed_end=2026-11-06T04:15+00:00, prior8high=0.082400, depth_time=2026-11-06T04:15:06+00:00, book20_bid_proxy_usdt=25976, book20_ask_proxy_usdt=20704, funding_indicative=0.000067, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.00%, turnover=6716398. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T04:15:03+00:00, last15m_closed_end=2026-11-06T04:15+00:00, prior8high=2.468000, depth_time=2026-11-06T04:15:06+00:00, book20_bid_proxy_usdt=306836, book20_ask_proxy_usdt=227128, funding_indicative=0.000094, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.75%, turnover=6746613. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-06T04:15:03+00:00, last15m_closed_end=2026-11-06T04:15+00:00, prior8high=78.260000, depth_time=2026-11-06T04:15:19+00:00, book20_bid_proxy_usdt=255785, book20_ask_proxy_usdt=98629, funding_indicative=0.000050, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.63%, turnover=84576830. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T04:14:59+00:00, last15m_closed_end=2026-11-06T04:15+00:00, prior8high=0.058050, depth_time=2026-11-06T04:15:14+00:00, book20_bid_proxy_usdt=412082, book20_ask_proxy_usdt=457728, funding_indicative=0.000050, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.86%, turnover=12520126. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T04:15:03+00:00, last15m_closed_end=2026-11-06T04:15+00:00, prior8high=1.222500, depth_time=2026-11-06T04:15:12+00:00, book20_bid_proxy_usdt=4613800, book20_ask_proxy_usdt=2851025, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.19%, turnover=425160043. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-06T04:14:59+00:00, last15m_closed_end=2026-11-06T04:15+00:00, prior8high=1.616700, depth_time=2026-11-06T04:15:16+00:00, book20_bid_proxy_usdt=57176, book20_ask_proxy_usdt=37991, funding_indicative=0.000050, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.45%, turnover=7327326. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
