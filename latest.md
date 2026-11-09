# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T14:15:30Z**
- feed_generated_utc: 2026-11-09T14:15:31+00:00
- source_sha256: `0fa03b8a6c9319b63a8907b47f1737bdae6c215b319f3b84b02a1aeb1cb21b30`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T14:15+00:00, close=74553.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T14:00+00:00, close=74694.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T12:00+00:00, close=74345.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001478|-24.51|26.92|-22.56|6045703|0.68|
|AKE_USDT|0.004697|-12.32|-48.72|-10.37|8957372|2.13|
|ASTER_USDT|0.640400|-5.79|-8.43|-3.84|5726112|1.56|
|ETH_USDT|2120.110000|-5.39|-6.42|-3.44|1609359589|0.05|
|XRP_USDT|1.093400|-5.39|-12.52|-3.44|286271361|0.92|
|TRUMPOFFICIAL_USDT|1.127000|-5.21|-34.32|-3.26|6348358|8.88|
|HYPE_USDT|73.766000|-4.73|-15.87|-2.78|48455970|0.14|
|ZEC_USDT|1215.690000|-4.32|-1.79|-2.37|2280319175|0.33|
|NEAR_USDT|3.549000|-4.10|-18.05|-2.15|47210285|2.82|
|SOL_USDT|86.840000|-3.16|-8.35|-1.21|748525463|1.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004697|0.004635|0.004697|0.50|N|Y/Y|N/Y|Y|N|
|ASTER_USDT|0.640400|0.633600|0.640400|0.79|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2120.110000|2112.200000|2120.400000|1.81|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.766000|73.047000|73.766000|1.53|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.549000|3.508000|3.549000|1.94|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001478|0.001470|0.001477|1.38|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.840000|86.040000|86.840000|0.80|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.127000|1.128000|1.127000|0.48|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.093400|1.079300|1.093400|0.73|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1215.690000|1205.390000|1216.000000|0.91|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T14:15:02+00:00, last15m_closed_end=2026-11-09T14:15+00:00, prior8high=0.005589, depth_time=2026-11-09T14:15:09+00:00, book20_bid_proxy_usdt=44741, book20_ask_proxy_usdt=35783, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.32%, turnover=8957372. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T14:15:02+00:00, last15m_closed_end=2026-11-09T14:15+00:00, prior8high=0.643800, depth_time=2026-11-09T14:15:06+00:00, book20_bid_proxy_usdt=577331, book20_ask_proxy_usdt=638026, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.79%, turnover=5726112. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T14:15:02+00:00, last15m_closed_end=2026-11-09T14:15+00:00, prior8high=2131.940000, depth_time=2026-11-09T14:15:13+00:00, book20_bid_proxy_usdt=3234336, book20_ask_proxy_usdt=2405649, funding_indicative=-0.000007, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.39%, turnover=1609359589. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T14:15:02+00:00, last15m_closed_end=2026-11-09T14:15+00:00, prior8high=74.040000, depth_time=2026-11-09T14:15:20+00:00, book20_bid_proxy_usdt=111343, book20_ask_proxy_usdt=57441, funding_indicative=0.000035, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.73%, turnover=48455970. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T14:15:02+00:00, last15m_closed_end=2026-11-09T14:15+00:00, prior8high=3.587000, depth_time=2026-11-09T14:15:24+00:00, book20_bid_proxy_usdt=2844684, book20_ask_proxy_usdt=2545256, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.10%, turnover=47210285. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T14:15:02+00:00, last15m_closed_end=2026-11-09T14:15+00:00, prior8high=0.001521, depth_time=2026-11-09T14:15:06+00:00, book20_bid_proxy_usdt=41646, book20_ask_proxy_usdt=17021, funding_indicative=-0.000004, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-24.51%, turnover=6045703. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T14:15:02+00:00, last15m_closed_end=2026-11-09T14:15+00:00, prior8high=87.100000, depth_time=2026-11-09T14:15:29+00:00, book20_bid_proxy_usdt=18845322, book20_ask_proxy_usdt=20848822, funding_indicative=0.000026, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=748525463. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T14:15:02+00:00, last15m_closed_end=2026-11-09T14:15+00:00, prior8high=1.148000, depth_time=2026-11-09T14:15:17+00:00, book20_bid_proxy_usdt=2249614, book20_ask_proxy_usdt=3032167, funding_indicative=0.000026, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.21%, turnover=6348358. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T14:15:02+00:00, last15m_closed_end=2026-11-09T14:15+00:00, prior8high=1.110100, depth_time=2026-11-09T14:15:15+00:00, book20_bid_proxy_usdt=2624483, book20_ask_proxy_usdt=3031944, funding_indicative=0.000084, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.39%, turnover=286271361. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T14:15:02+00:00, last15m_closed_end=2026-11-09T14:15+00:00, prior8high=1228.080000, depth_time=2026-11-09T14:15:24+00:00, book20_bid_proxy_usdt=165128, book20_ask_proxy_usdt=246514, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.32%, turnover=2280319175. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
