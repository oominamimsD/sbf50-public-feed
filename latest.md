# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T15:30:19Z**
- feed_generated_utc: 2026-11-09T15:30:21+00:00
- source_sha256: `09e4f41c2ab62494d692ecc1ac3d5ebb12a40ff6fe38743b01e864d348fe0d7b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T15:30+00:00, close=75059.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T15:00+00:00, close=74871.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-09T12:00+00:00, close=74345.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001485|-24.16|27.50|-22.90|5939513|0.67|
|AKE_USDT|0.004690|-12.45|-48.79|-11.19|8931206|4.26|
|ASTER_USDT|0.644800|-5.14|-7.80|-3.88|6507324|1.55|
|ETH_USDT|2129.460000|-4.98|-6.01|-3.72|1713709300|0.05|
|XRP_USDT|1.101800|-4.67|-11.84|-3.41|294304458|1.81|
|TRUMPOFFICIAL_USDT|1.134000|-4.62|-33.91|-3.36|6358404|8.81|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004690|0.004671|0.004691|1.38|N|Y/Y|N/Y|Y|N|
|ASTER_USDT|0.644800|0.637600|0.644500|23.78|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2129.460000|2113.380000|2129.260000|2.57|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001485|0.001470|0.001485|0.55|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.134000|1.113000|1.134000|0.75|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.101800|1.090100|1.101800|1.47|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T15:30:02+00:00, last15m_closed_end=2026-11-09T15:30+00:00, prior8high=0.004890, depth_time=2026-11-09T15:30:09+00:00, book20_bid_proxy_usdt=39405, book20_ask_proxy_usdt=38671, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.45%, turnover=8931206. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T15:30:02+00:00, last15m_closed_end=2026-11-09T15:30+00:00, prior8high=0.642800, depth_time=2026-11-09T15:30:09+00:00, book20_bid_proxy_usdt=679015, book20_ask_proxy_usdt=568874, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.14%, turnover=6507324. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T15:30:02+00:00, last15m_closed_end=2026-11-09T15:30+00:00, prior8high=2137.760000, depth_time=2026-11-09T15:30:13+00:00, book20_bid_proxy_usdt=3131501, book20_ask_proxy_usdt=2090958, funding_indicative=0.000011, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.98%, turnover=1713709300. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T15:30:02+00:00, last15m_closed_end=2026-11-09T15:30+00:00, prior8high=0.001538, depth_time=2026-11-09T15:30:06+00:00, book20_bid_proxy_usdt=16012, book20_ask_proxy_usdt=19034, funding_indicative=-0.000280, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-24.16%, turnover=5939513. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T15:30:02+00:00, last15m_closed_end=2026-11-09T15:30+00:00, prior8high=1.139000, depth_time=2026-11-09T15:30:13+00:00, book20_bid_proxy_usdt=2377918, book20_ask_proxy_usdt=2776185, funding_indicative=0.000033, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.62%, turnover=6358404. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T15:30:02+00:00, last15m_closed_end=2026-11-09T15:30+00:00, prior8high=1.106500, depth_time=2026-11-09T15:30:15+00:00, book20_bid_proxy_usdt=2724756, book20_ask_proxy_usdt=2341098, funding_indicative=0.000076, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.67%, turnover=294304458. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
