# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T07:45:29Z**
- feed_generated_utc: 2026-10-27T07:45:32+00:00
- source_sha256: `40d8d3a4891cdf4a6d82e1e2e42072dde517de4f459717a3e560b73a7b4f24ed`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T07:45+00:00, close=79620.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T07:00+00:00, close=79629.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T04:00+00:00, close=79790.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.026510|-3.87|115.87|-2.91|8148118|3.77|
|AAVE_USDT|131.660000|-3.70|-10.56|-2.74|24726319|0.76|
|PUMPFUN_USDT|0.004170|-3.65|-6.41|-2.69|21402639|2.40|
|NEAR_USDT|4.439000|-2.93|-9.48|-1.97|95864650|2.25|
|DOT_USDT|0.994600|-2.73|-13.27|-1.77|10844120|1.00|
|AVAX_USDT|8.771000|-2.51|-8.27|-1.55|43226789|1.14|
|FILECOIN_USDT|0.898400|-2.42|-11.22|-1.46|6172838|1.11|
|SILVER_USDT|52.990000|-2.28|-7.63|-1.32|258690084|1.89|
|SOL_USDT|99.740000|-2.06|-4.17|-1.10|713620795|1.00|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|131.660000|131.060000|131.650000|0.72|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.771000|8.656000|8.771000|0.09|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.994600|0.984100|0.994600|1.26|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.898400|0.888900|0.898300|3.01|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.026510|0.026480|0.026510|0.68|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.439000|4.405000|4.438000|1.13|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004170|0.004131|0.004170|0.93|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|52.990000|52.800000|52.990000|0.93|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|99.740000|99.380000|99.730000|0.59|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T07:45:03+00:00, last15m_closed_end=2026-10-27T07:45+00:00, prior8high=132.600000, depth_time=2026-10-27T07:45:11+00:00, book20_bid_proxy_usdt=387722, book20_ask_proxy_usdt=795545, funding_indicative=0.000067, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.70%, turnover=24726319. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T07:45:03+00:00, last15m_closed_end=2026-10-27T07:45+00:00, prior8high=8.786000, depth_time=2026-10-27T07:45:19+00:00, book20_bid_proxy_usdt=1948997, book20_ask_proxy_usdt=1663801, funding_indicative=-0.000084, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.51%, turnover=43226789. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T07:45:03+00:00, last15m_closed_end=2026-10-27T07:45+00:00, prior8high=0.992700, depth_time=2026-10-27T07:45:19+00:00, book20_bid_proxy_usdt=360353, book20_ask_proxy_usdt=533001, funding_indicative=-0.000033, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.73%, turnover=10844120. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T07:45:03+00:00, last15m_closed_end=2026-10-27T07:45+00:00, prior8high=0.899300, depth_time=2026-10-27T07:45:18+00:00, book20_bid_proxy_usdt=1012004, book20_ask_proxy_usdt=1511886, funding_indicative=0.000008, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.42%, turnover=6172838. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T07:45:03+00:00, last15m_closed_end=2026-10-27T07:45+00:00, prior8high=0.029940, depth_time=2026-10-27T07:45:08+00:00, book20_bid_proxy_usdt=119011, book20_ask_proxy_usdt=79611, funding_indicative=-0.000609, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=1, 24h_change=-3.87%, turnover=8148118. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T07:45:03+00:00, last15m_closed_end=2026-10-27T07:45+00:00, prior8high=4.459000, depth_time=2026-10-27T07:45:16+00:00, book20_bid_proxy_usdt=4118763, book20_ask_proxy_usdt=4333570, funding_indicative=0.000065, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.93%, turnover=95864650. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T07:45:03+00:00, last15m_closed_end=2026-10-27T07:45+00:00, prior8high=0.004181, depth_time=2026-10-27T07:45:12+00:00, book20_bid_proxy_usdt=1895880, book20_ask_proxy_usdt=2239530, funding_indicative=0.000024, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.65%, turnover=21402639. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-27T07:45:03+00:00, last15m_closed_end=2026-10-27T07:45+00:00, prior8high=53.550000, depth_time=2026-10-27T07:45:26+00:00, book20_bid_proxy_usdt=54119521, book20_ask_proxy_usdt=41143764, funding_indicative=0.000108, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.28%, turnover=258690084. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-27T07:45:03+00:00, last15m_closed_end=2026-10-27T07:45+00:00, prior8high=100.260000, depth_time=2026-10-27T07:45:28+00:00, book20_bid_proxy_usdt=17116170, book20_ask_proxy_usdt=22031122, funding_indicative=0.000037, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.06%, turnover=713620795. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
