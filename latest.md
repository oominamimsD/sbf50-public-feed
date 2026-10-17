# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T21:15:15Z**
- feed_generated_utc: 2026-10-17T21:15:17+00:00
- source_sha256: `a3ad5133215c6217c35da18fc856776bf8afeadbf4e1d99719c0b46283f622eb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T21:15+00:00, close=81622.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T21:00+00:00, close=81610.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-17T20:00+00:00, close=81575.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DNA_USDT|0.261100|-4.04|UNKNOWN|-4.41|6421608|7.66|
|STRK_USDT|0.064870|-1.93|-30.56|-2.30|15475795|1.54|
|EIGEN_USDT|0.253100|-1.24|7.42|-1.61|9931118|3.95|
|QNT_USDT|198.740000|-0.83|-18.92|-1.20|60355343|0.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DNA_USDT|0.261100|0.249000|0.261100|0.92|N|Y/Y|?|Y|N|
|EIGEN_USDT|0.253100|0.252800|0.253100|1.65|N|Y/Y|N/N|Y|N|
|QNT_USDT|198.740000|198.420000|198.740000|0.74|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.064870|0.064770|0.064860|0.71|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DNA_USDT: quote_utc=2026-10-17T21:15:00+00:00, last15m_closed_end=2026-10-17T21:15+00:00, prior8high=0.260200, depth_time=2026-10-17T21:15:07+00:00, book20_bid_proxy_usdt=89505, book20_ask_proxy_usdt=88341, funding_indicative=-0.001120, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.04%, turnover=6421608. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-17T21:15:00+00:00, last15m_closed_end=2026-10-17T21:15+00:00, prior8high=0.256500, depth_time=2026-10-17T21:15:11+00:00, book20_bid_proxy_usdt=447333, book20_ask_proxy_usdt=343753, funding_indicative=0.000001, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.24%, turnover=9931118. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-17T21:15:00+00:00, last15m_closed_end=2026-10-17T21:15+00:00, prior8high=200.680000, depth_time=2026-10-17T21:15:15+00:00, book20_bid_proxy_usdt=70126, book20_ask_proxy_usdt=47003, funding_indicative=-0.000017, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.83%, turnover=60355343. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T21:15:00+00:00, last15m_closed_end=2026-10-17T21:15+00:00, prior8high=0.066320, depth_time=2026-10-17T21:15:10+00:00, book20_bid_proxy_usdt=751072, book20_ask_proxy_usdt=150296, funding_indicative=0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.93%, turnover=15475795. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
