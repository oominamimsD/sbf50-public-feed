# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T17:00:43Z**
- feed_generated_utc: 2026-11-10T17:00:45+00:00
- source_sha256: `02f6c79147ec259e80f9bbe21dc4ac9310885fa0747e798ff598f84a1dc4efc4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 22; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T17:00+00:00, close=72844.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T17:00+00:00, close=72844.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T16:00+00:00, close=73180.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.005365|-11.01|28.41|-10.56|22892054|7.45|
|PIEVERSE_USDT|1.846100|-8.88|57.06|-8.43|9542440|3.78|
|ZEC_USDT|1010.410000|-7.58|-16.06|-7.13|2301799129|0.10|
|PEPE_USDT|0.000005|-6.81|5.84|-6.36|71293082|0.19|
|NEAR_USDT|3.488000|-6.28|-9.61|-5.83|35622713|2.87|
|PUMPFUN_USDT|0.003357|-5.78|-21.32|-5.33|9124623|2.98|
|UNI_USDT|6.696000|-5.22|-8.93|-4.77|25149005|1.49|
|INJ_USDT|7.786000|-4.85|6.20|-4.40|16105204|1.28|
|DASH_USDT|43.000000|-4.74|-6.80|-4.29|13436535|2.33|
|TIA_USDT|0.415400|-4.37|-4.68|-3.92|9174084|2.41|
|WLD_USDT|0.305500|-3.90|-17.89|-3.45|28630489|3.27|
|SUI_USDT|0.805800|-3.87|-10.29|-3.42|40616715|1.24|
|HYPE_USDT|70.847000|-3.75|-18.89|-3.30|40732421|0.14|
|DOGE_USDT|0.067050|-3.37|-11.16|-2.92|79796179|1.49|
|DOT_USDT|0.833800|-3.32|-11.54|-2.87|8479996|4.80|
|QNT_USDT|177.880000|-2.84|-8.97|-2.39|39755261|0.56|
|ARB_USDT|0.157020|-2.70|-1.78|-2.25|39026080|0.64|
|HBAR_USDT|0.065310|-2.40|-6.73|-1.95|8832059|1.53|
|ANTHROPIC_USDT|1287.480000|-2.28|-23.08|-1.83|7649052|6.21|
|AVAX_USDT|8.188000|-2.26|-4.50|-1.81|35929295|1.22|
|FILECOIN_USDT|0.741100|-2.02|-16.14|-1.57|5083769|2.70|
|ONDO_USDT|0.359600|-1.69|-7.60|-1.24|14767696|2.78|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|43.000000|43.240000|43.010000|1.30|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.067050|0.066660|0.067050|0.88|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.833800|0.830900|0.833800|2.27|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|70.847000|71.053000|70.847000|1.37|Y|Y/Y|Y/Y|Y|Y|
|INJ_USDT|7.786000|7.696000|7.784000|0.99|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005365|0.004969|0.005365|0.57|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.488000|3.474000|3.488000|1.23|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.83|N|Y/N|N/N|Y|N|
|PIEVERSE_USDT|1.846100|1.871300|1.851800|3.75|Y|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003357|0.003343|0.003357|1.18|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.805800|0.800900|0.805800|0.87|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.415400|0.417100|0.415500|2.71|Y|Y/Y|Y/Y|Y|Y|
|UNI_USDT|6.696000|6.656000|6.696000|1.15|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.305500|0.303000|0.305500|0.55|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1010.410000|1005.620000|1010.370000|1.76|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-11-10T17:00:02+00:00, last15m_closed_end=2026-11-10T17:00+00:00, prior8high=47.390000, depth_time=2026-11-10T17:00:26+00:00, book20_bid_proxy_usdt=619684, book20_ask_proxy_usdt=369056, funding_indicative=-0.000022, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.74%, turnover=13436535. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-10T17:00:01+00:00, last15m_closed_end=2026-11-10T17:00+00:00, prior8high=0.069850, depth_time=2026-11-10T17:00:40+00:00, book20_bid_proxy_usdt=3551325, book20_ask_proxy_usdt=3847492, funding_indicative=-0.000019, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.37%, turnover=79796179. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T17:00:01+00:00, last15m_closed_end=2026-11-10T17:00+00:00, prior8high=0.868700, depth_time=2026-11-10T17:00:41+00:00, book20_bid_proxy_usdt=291101, book20_ask_proxy_usdt=627171, funding_indicative=0.000005, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.32%, turnover=8479996. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T17:00:01+00:00, last15m_closed_end=2026-11-10T17:00+00:00, prior8high=74.288000, depth_time=2026-11-10T17:00:38+00:00, book20_bid_proxy_usdt=51167, book20_ask_proxy_usdt=71251, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.75%, turnover=40732421. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-10T17:00:01+00:00, last15m_closed_end=2026-11-10T17:00+00:00, prior8high=8.247000, depth_time=2026-11-10T17:00:24+00:00, book20_bid_proxy_usdt=182292, book20_ask_proxy_usdt=260703, funding_indicative=0.000255, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.85%, turnover=16105204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T17:00:01+00:00, last15m_closed_end=2026-11-10T17:00+00:00, prior8high=0.007529, depth_time=2026-11-10T17:00:06+00:00, book20_bid_proxy_usdt=35493, book20_ask_proxy_usdt=31720, funding_indicative=0.000054, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-11.01%, turnover=22892054. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-10T17:00:01+00:00, last15m_closed_end=2026-11-10T17:00+00:00, prior8high=3.760000, depth_time=2026-11-10T17:00:16+00:00, book20_bid_proxy_usdt=2393443, book20_ask_proxy_usdt=3963928, funding_indicative=0.000100, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-6.28%, turnover=35622713. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-10T17:00:01+00:00, last15m_closed_end=2026-11-10T17:00+00:00, prior8high=0.000006, depth_time=2026-11-10T17:00:14+00:00, book20_bid_proxy_usdt=33084, book20_ask_proxy_usdt=23878, funding_indicative=0.000100, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-6.81%, turnover=71293082. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T17:00:01+00:00, last15m_closed_end=2026-11-10T17:00+00:00, prior8high=2.075800, depth_time=2026-11-10T17:00:08+00:00, book20_bid_proxy_usdt=20410, book20_ask_proxy_usdt=14010, funding_indicative=0.000271, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.88%, turnover=9542440. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T17:00:01+00:00, last15m_closed_end=2026-11-10T17:00+00:00, prior8high=0.003613, depth_time=2026-11-10T17:00:19+00:00, book20_bid_proxy_usdt=2814338, book20_ask_proxy_usdt=4310639, funding_indicative=-0.000012, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.78%, turnover=9124623. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-10T17:00:01+00:00, last15m_closed_end=2026-11-10T17:00+00:00, prior8high=0.846000, depth_time=2026-11-10T17:00:34+00:00, book20_bid_proxy_usdt=909598, book20_ask_proxy_usdt=1277438, funding_indicative=-0.000045, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.87%, turnover=40616715. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-10T17:00:02+00:00, last15m_closed_end=2026-11-10T17:00+00:00, prior8high=0.438000, depth_time=2026-11-10T17:00:29+00:00, book20_bid_proxy_usdt=214218, book20_ask_proxy_usdt=492824, funding_indicative=0.000031, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.37%, turnover=9174084. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T17:00:01+00:00, last15m_closed_end=2026-11-10T17:00+00:00, prior8high=7.157000, depth_time=2026-11-10T17:00:21+00:00, book20_bid_proxy_usdt=1662504, book20_ask_proxy_usdt=1625076, funding_indicative=0.000093, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.22%, turnover=25149005. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-10T17:00:01+00:00, last15m_closed_end=2026-11-10T17:00+00:00, prior8high=0.321300, depth_time=2026-11-10T17:00:30+00:00, book20_bid_proxy_usdt=4941884, book20_ask_proxy_usdt=5059079, funding_indicative=0.000013, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.90%, turnover=28630489. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T17:00:01+00:00, last15m_closed_end=2026-11-10T17:00+00:00, prior8high=1198.440000, depth_time=2026-11-10T17:00:12+00:00, book20_bid_proxy_usdt=334181, book20_ask_proxy_usdt=158337, funding_indicative=-0.000003, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-7.58%, turnover=2301799129. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
