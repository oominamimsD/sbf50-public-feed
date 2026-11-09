# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T14:30:22Z**
- feed_generated_utc: 2026-11-09T14:30:24+00:00
- source_sha256: `dd9b506853825e68309c984408da6dcf6e0a63405c74f1cd6a07e71d4279027e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T14:30+00:00, close=74596.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T14:00+00:00, close=74694.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T12:00+00:00, close=74345.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001521|-22.31|30.62|-20.41|6104642|0.66|
|AKE_USDT|0.004733|-11.64|-48.32|-9.74|9017394|2.11|
|ASTER_USDT|0.640000|-5.85|-8.49|-3.95|5764636|3.13|
|TRUMPOFFICIAL_USDT|1.121000|-5.71|-34.67|-3.81|6397154|8.92|
|ETH_USDT|2121.200000|-5.35|-6.38|-3.45|1615543364|0.05|
|XRP_USDT|1.096000|-5.17|-12.31|-3.27|287786670|0.91|
|HYPE_USDT|74.227000|-4.13|-15.35|-2.23|50279086|0.14|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004733|0.004635|0.004733|0.46|N|Y/Y|N/Y|Y|N|
|ASTER_USDT|0.640000|0.635700|0.640000|1.94|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2121.200000|2115.100000|2121.350000|0.62|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|74.227000|73.090000|74.227000|5.11|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001521|0.001470|0.001521|1.06|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.121000|1.125000|1.121000|1.57|Y|Y/Y|Y/Y|Y|Y|
|XRP_USDT|1.096000|1.086000|1.096000|0.51|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T14:30:01+00:00, last15m_closed_end=2026-11-09T14:30+00:00, prior8high=0.004952, depth_time=2026-11-09T14:30:09+00:00, book20_bid_proxy_usdt=48515, book20_ask_proxy_usdt=57749, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.64%, turnover=9017394. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T14:30:01+00:00, last15m_closed_end=2026-11-09T14:30+00:00, prior8high=0.643800, depth_time=2026-11-09T14:30:07+00:00, book20_bid_proxy_usdt=683128, book20_ask_proxy_usdt=691054, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.85%, turnover=5764636. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T14:30:01+00:00, last15m_closed_end=2026-11-09T14:30+00:00, prior8high=2131.940000, depth_time=2026-11-09T14:30:16+00:00, book20_bid_proxy_usdt=2386504, book20_ask_proxy_usdt=7270346, funding_indicative=-0.000004, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.35%, turnover=1615543364. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T14:30:01+00:00, last15m_closed_end=2026-11-09T14:30+00:00, prior8high=74.040000, depth_time=2026-11-09T14:30:21+00:00, book20_bid_proxy_usdt=88739, book20_ask_proxy_usdt=125453, funding_indicative=0.000039, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.13%, turnover=50279086. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T14:30:01+00:00, last15m_closed_end=2026-11-09T14:30+00:00, prior8high=0.001521, depth_time=2026-11-09T14:30:07+00:00, book20_bid_proxy_usdt=10878, book20_ask_proxy_usdt=12372, funding_indicative=-0.000024, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-22.31%, turnover=6104642. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T14:30:01+00:00, last15m_closed_end=2026-11-09T14:30+00:00, prior8high=1.148000, depth_time=2026-11-09T14:30:14+00:00, book20_bid_proxy_usdt=2310206, book20_ask_proxy_usdt=2662623, funding_indicative=0.000035, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.71%, turnover=6397154. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T14:30:01+00:00, last15m_closed_end=2026-11-09T14:30+00:00, prior8high=1.110100, depth_time=2026-11-09T14:30:19+00:00, book20_bid_proxy_usdt=2169461, book20_ask_proxy_usdt=3329372, funding_indicative=0.000086, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.17%, turnover=287786670. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
