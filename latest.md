# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T23:45:33Z**
- feed_generated_utc: 2026-10-17T23:45:35+00:00
- source_sha256: `e0722d368d3e377a525ecbb36576579a304327dcb710f6bcfa96af3b15815ff1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T23:45+00:00, close=81331.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T23:00+00:00, close=81327, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T20:00+00:00, close=81575.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.168300|-9.12|69.82|-9.13|14739139|5.94|
|DNA_USDT|0.257100|-5.51|UNKNOWN|-5.52|6084329|7.78|
|EIGEN_USDT|0.249600|-2.61|5.94|-2.62|10818596|4.01|
|QNT_USDT|195.220000|-2.58|-20.36|-2.59|66778245|0.51|
|STRK_USDT|0.064740|-2.13|-30.70|-2.14|16253656|1.54|
|FILECOIN_USDT|1.064700|-2.08|-5.59|-2.09|21549794|0.94|
|TIA_USDT|0.645200|-1.94|25.76|-1.95|75836775|1.55|
|PUMPFUN_USDT|0.004332|-1.81|-24.33|-1.82|26882864|2.31|
|XPL_USDT|0.078710|-1.77|-9.27|-1.78|5012091|3.81|
|ARB_USDT|0.181080|-1.54|-2.99|-1.55|31103950|0.55|
|ZEC_USDT|1125.640000|-1.37|-8.61|-1.38|1172314841|0.09|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.181080|0.176600|0.181080|0.71|N|Y/Y|Y/Y|Y|N|
|DNA_USDT|0.257100|0.245300|0.257100|0.22|N|Y/Y|?|Y|N|
|EIGEN_USDT|0.249600|0.241300|0.249800|2.71|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|1.064700|1.038400|1.064700|0.63|N|Y/Y|Y/Y|Y|N|
|ICNT_USDT|0.168300|0.163200|0.168300|0.28|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004332|0.004262|0.004332|1.27|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.220000|190.470000|195.220000|1.15|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.064740|0.063090|0.064710|0.23|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.645200|0.634700|0.645200|0.33|N|Y/Y|N/N|Y|N|
|XPL_USDT|0.078710|0.076690|0.078690|0.67|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1125.640000|1098.000000|1126.420000|0.53|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-17T23:45:02+00:00, last15m_closed_end=2026-10-17T23:45+00:00, prior8high=0.181720, depth_time=2026-10-17T23:45:29+00:00, book20_bid_proxy_usdt=62494, book20_ask_proxy_usdt=165176, funding_indicative=0.000048, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=31103950. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-17T23:45:02+00:00, last15m_closed_end=2026-10-17T23:45+00:00, prior8high=0.260000, depth_time=2026-10-17T23:45:09+00:00, book20_bid_proxy_usdt=57778, book20_ask_proxy_usdt=80178, funding_indicative=-0.001563, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.51%, turnover=6084329. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-17T23:45:02+00:00, last15m_closed_end=2026-10-17T23:45+00:00, prior8high=0.250600, depth_time=2026-10-17T23:45:12+00:00, book20_bid_proxy_usdt=499875, book20_ask_proxy_usdt=438751, funding_indicative=0.000010, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.61%, turnover=10818596. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T23:45:02+00:00, last15m_closed_end=2026-10-17T23:45+00:00, prior8high=1.070900, depth_time=2026-10-17T23:45:19+00:00, book20_bid_proxy_usdt=471235, book20_ask_proxy_usdt=447243, funding_indicative=-0.000045, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.08%, turnover=21549794. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-17T23:45:02+00:00, last15m_closed_end=2026-10-17T23:45+00:00, prior8high=0.181500, depth_time=2026-10-17T23:45:07+00:00, book20_bid_proxy_usdt=184208, book20_ask_proxy_usdt=176827, funding_indicative=-0.000194, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.12%, turnover=14739139. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-17T23:45:02+00:00, last15m_closed_end=2026-10-17T23:45+00:00, prior8high=0.004372, depth_time=2026-10-17T23:45:24+00:00, book20_bid_proxy_usdt=1447565, book20_ask_proxy_usdt=1989702, funding_indicative=0.000024, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.81%, turnover=26882864. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-17T23:45:02+00:00, last15m_closed_end=2026-10-17T23:45+00:00, prior8high=196.940000, depth_time=2026-10-17T23:45:15+00:00, book20_bid_proxy_usdt=61265, book20_ask_proxy_usdt=81220, funding_indicative=-0.000048, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.58%, turnover=66778245. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T23:45:02+00:00, last15m_closed_end=2026-10-17T23:45+00:00, prior8high=0.065060, depth_time=2026-10-17T23:45:17+00:00, book20_bid_proxy_usdt=537184, book20_ask_proxy_usdt=295322, funding_indicative=0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.13%, turnover=16253656. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-17T23:45:02+00:00, last15m_closed_end=2026-10-17T23:45+00:00, prior8high=0.652100, depth_time=2026-10-17T23:45:21+00:00, book20_bid_proxy_usdt=155402, book20_ask_proxy_usdt=167390, funding_indicative=-0.000013, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.94%, turnover=75836775. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-17T23:45:03+00:00, last15m_closed_end=2026-10-17T23:45+00:00, prior8high=0.078900, depth_time=2026-10-17T23:45:26+00:00, book20_bid_proxy_usdt=312112, book20_ask_proxy_usdt=470747, funding_indicative=0.000041, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.77%, turnover=5012091. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T23:45:02+00:00, last15m_closed_end=2026-10-17T23:45+00:00, prior8high=1131.360000, depth_time=2026-10-17T23:45:31+00:00, book20_bid_proxy_usdt=392714, book20_ask_proxy_usdt=87482, funding_indicative=0.000043, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.37%, turnover=1172314841. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
