# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T21:15:19Z**
- feed_generated_utc: 2026-11-05T21:15:20+00:00
- source_sha256: `198d39a5c03ef332c84558f7949231d223d4349a7cd32719a024d42009d27e4d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T21:15+00:00, close=76032.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T21:00+00:00, close=76205.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T20:00+00:00, close=76344.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002164|-16.12|-89.72|-16.14|19459739|4.62|
|FLUID_USDT|2.386000|-5.76|15.60|-5.78|8279552|4.19|
|BCH_USDT|273.590000|-1.98|-5.09|-2.00|10173434|2.56|
|XRP_USDT|1.222900|-1.74|-6.61|-1.76|426112076|0.82|
|QNT_USDT|188.520000|-1.72|-5.14|-1.74|42507780|1.06|
|HYPE_USDT|77.797000|-1.14|-17.17|-1.16|88309501|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002164|0.002009|0.002164|0.31|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|273.590000|274.410000|273.590000|1.52|Y|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.386000|2.355000|2.386000|0.90|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.797000|77.613000|77.797000|0.44|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|188.520000|187.630000|188.520000|1.25|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.222900|1.228700|1.222900|1.77|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T21:15:00+00:00, last15m_closed_end=2026-11-05T21:15+00:00, prior8high=0.002495, depth_time=2026-11-05T21:15:06+00:00, book20_bid_proxy_usdt=23868, book20_ask_proxy_usdt=35729, funding_indicative=-0.003284, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-16.12%, turnover=19459739. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-05T21:15:00+00:00, last15m_closed_end=2026-11-05T21:15+00:00, prior8high=278.650000, depth_time=2026-11-05T21:15:11+00:00, book20_bid_proxy_usdt=52593, book20_ask_proxy_usdt=70479, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.98%, turnover=10173434. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T21:14:59+00:00, last15m_closed_end=2026-11-05T21:15+00:00, prior8high=2.424000, depth_time=2026-11-05T21:15:09+00:00, book20_bid_proxy_usdt=173631, book20_ask_proxy_usdt=186838, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.76%, turnover=8279552. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T21:15:00+00:00, last15m_closed_end=2026-11-05T21:15+00:00, prior8high=78.939000, depth_time=2026-11-05T21:15:18+00:00, book20_bid_proxy_usdt=206022, book20_ask_proxy_usdt=93559, funding_indicative=0.000050, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.14%, turnover=88309501. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-05T21:15:00+00:00, last15m_closed_end=2026-11-05T21:15+00:00, prior8high=193.570000, depth_time=2026-11-05T21:15:16+00:00, book20_bid_proxy_usdt=65754, book20_ask_proxy_usdt=67720, funding_indicative=0.000008, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=42507780. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-05T21:14:59+00:00, last15m_closed_end=2026-11-05T21:15+00:00, prior8high=1.245300, depth_time=2026-11-05T21:15:14+00:00, book20_bid_proxy_usdt=2851901, book20_ask_proxy_usdt=3507010, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=426112076. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
