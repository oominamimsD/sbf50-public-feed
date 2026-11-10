# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T06:30:31Z**
- feed_generated_utc: 2026-11-10T06:30:33+00:00
- source_sha256: `6f9e03cac25b99bb3d9fbe0e3651cb08952236603c686192b284633e1022dd40`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T06:30+00:00, close=74662.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T06:00+00:00, close=74787.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T04:00+00:00, close=74537.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002534|-48.25|-53.94|-47.13|15376838|3.95|
|JCT_USDT|0.006613|-34.72|53.18|-33.60|26054597|1.50|
|ARB_USDT|0.172000|-6.54|7.95|-5.42|34242859|0.58|
|ZEC_USDT|1149.380000|-6.22|-8.35|-5.10|2424005137|0.09|
|AAVE_USDT|125.940000|-5.55|-3.53|-4.43|13483676|0.79|
|QNT_USDT|190.630000|-4.70|-5.83|-3.58|35411811|1.57|
|DASH_USDT|45.820000|-3.77|-2.92|-2.65|13798036|2.18|
|DOT_USDT|0.857700|-3.72|-8.17|-2.60|10485172|1.17|
|PUMPFUN_USDT|0.003578|-2.82|-12.81|-1.70|7548971|2.80|
|SOL_USDT|85.980000|-2.17|-8.05|-1.05|670485115|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|125.940000|125.220000|125.950000|7.28|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.002534|0.002443|0.002534|0.67|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.172000|0.170290|0.172000|1.67|N|Y/Y|N/N|Y|N|
|DASH_USDT|45.820000|45.630000|45.820000|0.65|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.857700|0.848100|0.857700|1.67|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.006613|0.006725|0.006614|1.48|Y|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003578|0.003559|0.003578|0.53|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|190.630000|190.000000|190.690000|0.93|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|85.980000|85.780000|86.020000|3.94|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1149.380000|1146.050000|1149.810000|1.02|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T06:30:01+00:00, last15m_closed_end=2026-11-10T06:30+00:00, prior8high=128.320000, depth_time=2026-11-10T06:30:18+00:00, book20_bid_proxy_usdt=602511, book20_ask_proxy_usdt=266074, funding_indicative=0.000029, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.55%, turnover=13483676. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T06:30:01+00:00, last15m_closed_end=2026-11-10T06:30+00:00, prior8high=0.002790, depth_time=2026-11-10T06:30:08+00:00, book20_bid_proxy_usdt=39298, book20_ask_proxy_usdt=68115, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-48.25%, turnover=15376838. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T06:30:01+00:00, last15m_closed_end=2026-11-10T06:30+00:00, prior8high=0.173110, depth_time=2026-11-10T06:30:11+00:00, book20_bid_proxy_usdt=61702, book20_ask_proxy_usdt=52621, funding_indicative=-0.000024, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.54%, turnover=34242859. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T06:30:01+00:00, last15m_closed_end=2026-11-10T06:30+00:00, prior8high=46.350000, depth_time=2026-11-10T06:30:18+00:00, book20_bid_proxy_usdt=936207, book20_ask_proxy_usdt=469935, funding_indicative=0.000031, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.77%, turnover=13798036. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T06:30:01+00:00, last15m_closed_end=2026-11-10T06:30+00:00, prior8high=0.858800, depth_time=2026-11-10T06:30:25+00:00, book20_bid_proxy_usdt=569589, book20_ask_proxy_usdt=575945, funding_indicative=0.000041, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.72%, turnover=10485172. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T06:30:01+00:00, last15m_closed_end=2026-11-10T06:30+00:00, prior8high=0.008180, depth_time=2026-11-10T06:30:10+00:00, book20_bid_proxy_usdt=35155, book20_ask_proxy_usdt=25001, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-34.72%, turnover=26054597. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T06:30:01+00:00, last15m_closed_end=2026-11-10T06:30+00:00, prior8high=0.003603, depth_time=2026-11-10T06:30:27+00:00, book20_bid_proxy_usdt=2940682, book20_ask_proxy_usdt=3167606, funding_indicative=0.000006, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.82%, turnover=7548971. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T06:30:01+00:00, last15m_closed_end=2026-11-10T06:30+00:00, prior8high=192.660000, depth_time=2026-11-10T06:30:18+00:00, book20_bid_proxy_usdt=67888, book20_ask_proxy_usdt=99191, funding_indicative=-0.000152, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.70%, turnover=35411811. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T06:30:01+00:00, last15m_closed_end=2026-11-10T06:30+00:00, prior8high=86.580000, depth_time=2026-11-10T06:30:29+00:00, book20_bid_proxy_usdt=19448686, book20_ask_proxy_usdt=18425829, funding_indicative=0.000037, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=670485115. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T06:30:01+00:00, last15m_closed_end=2026-11-10T06:30+00:00, prior8high=1165.460000, depth_time=2026-11-10T06:30:15+00:00, book20_bid_proxy_usdt=115809, book20_ask_proxy_usdt=621834, funding_indicative=0.000073, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.22%, turnover=2424005137. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
