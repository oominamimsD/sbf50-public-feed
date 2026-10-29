# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T13:30:27Z**
- feed_generated_utc: 2026-10-29T13:30:30+00:00
- source_sha256: `a6511aaaf4523e3567000810933db0df473744467604b3b089cf72267eb880da`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T13:30+00:00, close=80229.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-29T13:00+00:00, close=80026.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-29T12:00+00:00, close=80133.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.042240|-32.16|-63.63|-31.79|33744797|2.37|
|EVAA_USDT|1.217000|-18.04|115.93|-17.67|19862731|6.57|
|DASH_USDT|50.350000|-5.07|-5.48|-4.70|14511835|1.99|
|BCH_USDT|279.630000|-4.54|-3.46|-4.17|5008885|5.00|
|NEAR_USDT|4.487000|-3.06|-16.67|-2.69|107115345|2.23|
|WLD_USDT|0.421800|-2.54|-26.46|-2.17|79064137|2.37|
|SILVER_USDT|52.460000|-2.25|-9.01|-1.88|494169660|1.91|
|HBAR_USDT|0.074470|-1.89|-13.34|-1.52|15445942|1.34|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|279.630000|278.330000|279.630000|3.04|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|50.350000|49.890000|50.350000|4.27|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.217000|1.203900|1.214600|0.60|N|Y/Y|N/N|Y|N|
|HBAR_USDT|0.074470|0.073220|0.074470|1.18|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.487000|4.381000|4.485000|1.22|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.042240|0.039240|0.042250|0.66|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|52.460000|52.350000|52.440000|3.89|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.421800|0.416800|0.421700|0.91|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-10-29T13:30:02+00:00, last15m_closed_end=2026-10-29T13:30+00:00, prior8high=281.260000, depth_time=2026-10-29T13:30:16+00:00, book20_bid_proxy_usdt=89305, book20_ask_proxy_usdt=84774, funding_indicative=0.000045, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.54%, turnover=5008885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-29T13:30:02+00:00, last15m_closed_end=2026-10-29T13:30+00:00, prior8high=50.760000, depth_time=2026-10-29T13:30:11+00:00, book20_bid_proxy_usdt=632772, book20_ask_proxy_usdt=698472, funding_indicative=0.000019, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.07%, turnover=14511835. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-29T13:30:01+00:00, last15m_closed_end=2026-10-29T13:30+00:00, prior8high=1.285900, depth_time=2026-10-29T13:30:11+00:00, book20_bid_proxy_usdt=6758, book20_ask_proxy_usdt=24054, funding_indicative=0.000167, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-18.04%, turnover=19862731. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-29T13:30:02+00:00, last15m_closed_end=2026-10-29T13:30+00:00, prior8high=0.074410, depth_time=2026-10-29T13:30:24+00:00, book20_bid_proxy_usdt=516929, book20_ask_proxy_usdt=915740, funding_indicative=0.000100, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.89%, turnover=15445942. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-29T13:30:01+00:00, last15m_closed_end=2026-10-29T13:30+00:00, prior8high=4.497000, depth_time=2026-10-29T13:30:18+00:00, book20_bid_proxy_usdt=2442811, book20_ask_proxy_usdt=3430063, funding_indicative=0.000074, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.06%, turnover=107115345. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-29T13:30:01+00:00, last15m_closed_end=2026-10-29T13:30+00:00, prior8high=0.045070, depth_time=2026-10-29T13:30:07+00:00, book20_bid_proxy_usdt=35135, book20_ask_proxy_usdt=35916, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-32.16%, turnover=33744797. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-29T13:30:01+00:00, last15m_closed_end=2026-10-29T13:30+00:00, prior8high=53.140000, depth_time=2026-10-29T13:30:23+00:00, book20_bid_proxy_usdt=47019349, book20_ask_proxy_usdt=47639494, funding_indicative=0.000088, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.25%, turnover=494169660. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-29T13:30:01+00:00, last15m_closed_end=2026-10-29T13:30+00:00, prior8high=0.424500, depth_time=2026-10-29T13:30:20+00:00, book20_bid_proxy_usdt=3263886, book20_ask_proxy_usdt=3015753, funding_indicative=0.000046, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=79064137. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
