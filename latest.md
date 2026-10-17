# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T02:45:42Z**
- feed_generated_utc: 2026-10-17T02:45:45+00:00
- source_sha256: `1692d9befcbf0b15724f73eab8b17fa2f2d40383e23bb8a5eb6845b68309b505`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T02:45+00:00, close=81434.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T02:00+00:00, close=81511.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T00:00+00:00, close=81578.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.945000|-7.43|-4.50|-7.56|15869349|0.51|
|RIVER_USDT|1.076000|-4.44|-8.96|-4.57|5407940|9.29|
|STRK_USDT|0.070990|-4.00|-5.73|-4.13|21892375|1.41|
|ZEC_USDT|1142.260000|-3.85|-6.24|-3.98|1398954445|0.09|
|ARB_USDT|0.188180|-3.46|4.08|-3.59|33007390|0.53|
|BAT_USDT|0.198210|-3.32|62.92|-3.45|15170856|0.50|
|TAO_USDT|273.500000|-2.53|-0.42|-2.66|80282448|1.10|
|APT_USDT|0.837500|-2.17|4.62|-2.30|12690274|1.19|
|FET_USDT|0.195300|-2.15|-10.00|-2.28|11521140|5.12|
|INJ_USDT|8.786000|-2.13|26.80|-2.26|113654791|1.14|
|SUI_USDT|1.003400|-1.67|-5.12|-1.80|97839938|1.00|
|AAVE_USDT|154.800000|-1.57|-8.85|-1.70|31015194|1.29|
|ENA_USDT|0.197050|-1.44|-8.59|-1.57|40839882|0.51|
|ICP_USDT|2.994000|-1.44|-0.82|-1.57|9137392|3.34|
|ONDO_USDT|0.451000|-1.33|-6.06|-1.46|28822906|2.22|
|AVAX_USDT|9.953000|-1.28|-2.34|-1.41|124974404|1.00|
|FARTCOIN_USDT|0.152730|-1.28|-6.51|-1.41|7159824|0.66|
|SEI_USDT|0.063590|-1.10|-2.88|-1.23|19200504|1.57|
|QNT_USDT|199.720000|-0.90|-19.92|-1.03|66140388|0.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.800000|153.940000|154.790000|0.84|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.837500|0.833600|0.837500|1.02|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.188180|0.188400|0.188180|9.70|Y|Y/Y|N/N|Y|N|
|BAT_USDT|0.198210|0.195700|0.198210|0.84|N|N/Y|N/N|Y|N|
|ENA_USDT|0.197050|0.196360|0.197050|0.65|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.195300|0.194100|0.195300|0.55|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.994000|2.986000|2.994000|5.06|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.786000|8.619000|8.785000|1.17|N|N/Y|N/N|Y|N|
|ONDO_USDT|0.451000|0.448400|0.451100|0.54|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.076000|1.075000|1.078000|0.15|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.070990|0.071710|0.070990|7.07|Y|Y/Y|Y/Y|Y|Y|
|SUI_USDT|1.003400|1.001200|1.003400|0.75|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|273.500000|273.080000|273.500000|0.71|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1142.260000|1141.130000|1142.260000|1.21|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.945000|1.938500|1.945000|0.78|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T02:45:01+00:00, last15m_closed_end=2026-10-17T02:45+00:00, prior8high=155.480000, depth_time=2026-10-17T02:45:35+00:00, book20_bid_proxy_usdt=256091, book20_ask_proxy_usdt=282963, funding_indicative=0.000055, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.57%, turnover=31015194. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T02:45:01+00:00, last15m_closed_end=2026-10-17T02:45+00:00, prior8high=0.848700, depth_time=2026-10-17T02:45:24+00:00, book20_bid_proxy_usdt=158247, book20_ask_proxy_usdt=146873, funding_indicative=0.000052, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=12690274. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T02:45:01+00:00, last15m_closed_end=2026-10-17T02:45+00:00, prior8high=0.190730, depth_time=2026-10-17T02:45:17+00:00, book20_bid_proxy_usdt=52894, book20_ask_proxy_usdt=65646, funding_indicative=-0.000093, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.46%, turnover=33007390. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-17T02:45:01+00:00, last15m_closed_end=2026-10-17T02:45+00:00, prior8high=0.201540, depth_time=2026-10-17T02:45:19+00:00, book20_bid_proxy_usdt=26493, book20_ask_proxy_usdt=25271, funding_indicative=-0.000014, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.32%, turnover=15170856. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-17T02:45:01+00:00, last15m_closed_end=2026-10-17T02:45+00:00, prior8high=0.198780, depth_time=2026-10-17T02:45:36+00:00, book20_bid_proxy_usdt=197135, book20_ask_proxy_usdt=259675, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.44%, turnover=40839882. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T02:45:01+00:00, last15m_closed_end=2026-10-17T02:45+00:00, prior8high=0.197800, depth_time=2026-10-17T02:45:27+00:00, book20_bid_proxy_usdt=1726984, book20_ask_proxy_usdt=1097523, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.15%, turnover=11521140. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-17T02:45:01+00:00, last15m_closed_end=2026-10-17T02:45+00:00, prior8high=3.023000, depth_time=2026-10-17T02:45:39+00:00, book20_bid_proxy_usdt=1010484, book20_ask_proxy_usdt=869910, funding_indicative=0.000087, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=9137392. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-17T02:45:01+00:00, last15m_closed_end=2026-10-17T02:45+00:00, prior8high=8.886000, depth_time=2026-10-17T02:45:30+00:00, book20_bid_proxy_usdt=249806, book20_ask_proxy_usdt=228800, funding_indicative=0.000099, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=113654791. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-17T02:45:01+00:00, last15m_closed_end=2026-10-17T02:45+00:00, prior8high=0.453000, depth_time=2026-10-17T02:45:41+00:00, book20_bid_proxy_usdt=2284533, book20_ask_proxy_usdt=1967710, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.33%, turnover=28822906. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T02:45:01+00:00, last15m_closed_end=2026-10-17T02:45+00:00, prior8high=1.093000, depth_time=2026-10-17T02:45:10+00:00, book20_bid_proxy_usdt=492533, book20_ask_proxy_usdt=495877, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.44%, turnover=5407940. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T02:45:01+00:00, last15m_closed_end=2026-10-17T02:45+00:00, prior8high=0.074750, depth_time=2026-10-17T02:45:12+00:00, book20_bid_proxy_usdt=200539, book20_ask_proxy_usdt=521040, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.00%, turnover=21892375. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T02:45:01+00:00, last15m_closed_end=2026-10-17T02:45+00:00, prior8high=1.010300, depth_time=2026-10-17T02:45:32+00:00, book20_bid_proxy_usdt=1036257, book20_ask_proxy_usdt=1373465, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.67%, turnover=97839938. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T02:45:01+00:00, last15m_closed_end=2026-10-17T02:45+00:00, prior8high=275.750000, depth_time=2026-10-17T02:45:22+00:00, book20_bid_proxy_usdt=94362, book20_ask_proxy_usdt=124480, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.53%, turnover=80282448. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T02:45:01+00:00, last15m_closed_end=2026-10-17T02:45+00:00, prior8high=1157.920000, depth_time=2026-10-17T02:45:15+00:00, book20_bid_proxy_usdt=414416, book20_ask_proxy_usdt=209201, funding_indicative=0.000075, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.85%, turnover=1398954445. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T02:45:01+00:00, last15m_closed_end=2026-10-17T02:45+00:00, prior8high=1.978100, depth_time=2026-10-17T02:45:07+00:00, book20_bid_proxy_usdt=36307, book20_ask_proxy_usdt=33907, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.43%, turnover=15869349. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
