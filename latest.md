# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T18:15:18Z**
- feed_generated_utc: 2026-10-17T18:15:20+00:00
- source_sha256: `8808c6f0e58f3f8dd040d72aa7de71e9773bb06073e5ab03ac4e65de9ddd3cd7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T18:15+00:00, close=81474.5, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T18:00+00:00, close=81340.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T16:00+00:00, close=81315.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DNA_USDT|0.263500|-3.16|UNKNOWN|-3.35|7281018|3.80|
|EIGEN_USDT|0.250800|-2.14|6.45|-2.33|9290366|3.99|
|FILECOIN_USDT|1.066700|-1.90|-5.41|-2.09|24279280|1.88|
|ARB_USDT|0.182000|-1.04|-2.50|-1.23|26592373|0.55|
|ZEC_USDT|1131.820000|-0.83|-8.11|-1.02|1080280383|0.71|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.182000|0.180230|0.182000|0.46|N|Y/Y|Y/Y|Y|N|
|DNA_USDT|0.263500|0.254400|0.263500|0.37|N|Y/Y|?|Y|N|
|EIGEN_USDT|0.250800|0.247500|0.250800|1.15|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|1.066700|1.059300|1.066900|0.69|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1131.820000|1111.380000|1131.820000|1.04|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-17T18:14:59+00:00, last15m_closed_end=2026-10-17T18:15+00:00, prior8high=0.184280, depth_time=2026-10-17T18:15:14+00:00, book20_bid_proxy_usdt=64096, book20_ask_proxy_usdt=102996, funding_indicative=-0.000029, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.04%, turnover=26592373. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-17T18:14:59+00:00, last15m_closed_end=2026-10-17T18:15+00:00, prior8high=0.275100, depth_time=2026-10-17T18:15:06+00:00, book20_bid_proxy_usdt=67568, book20_ask_proxy_usdt=89117, funding_indicative=-0.001477, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.16%, turnover=7281018. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-17T18:14:59+00:00, last15m_closed_end=2026-10-17T18:15+00:00, prior8high=0.257800, depth_time=2026-10-17T18:15:08+00:00, book20_bid_proxy_usdt=473470, book20_ask_proxy_usdt=556026, funding_indicative=0.000050, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.14%, turnover=9290366. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T18:14:59+00:00, last15m_closed_end=2026-10-17T18:15+00:00, prior8high=1.095600, depth_time=2026-10-17T18:15:12+00:00, book20_bid_proxy_usdt=486335, book20_ask_proxy_usdt=723114, funding_indicative=-0.000094, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=24279280. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T18:14:59+00:00, last15m_closed_end=2026-10-17T18:15+00:00, prior8high=1147.410000, depth_time=2026-10-17T18:15:17+00:00, book20_bid_proxy_usdt=901300, book20_ask_proxy_usdt=426471, funding_indicative=0.000054, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.83%, turnover=1080280383. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
