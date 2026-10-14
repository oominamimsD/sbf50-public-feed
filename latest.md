# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T18:00:33Z**
- feed_generated_utc: 2026-10-14T18:00:35+00:00
- source_sha256: `c02971a74f52bca94b690e996d85f6b67311c7352e56d4652ba2c39d585bf16b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T18:00+00:00, close=81556.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T18:00+00:00, close=81556.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T16:00+00:00, close=81600.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.105100|-11.50|70.27|-11.45|58467442|1.90|
|S_USDT|0.052590|-5.31|32.00|-5.26|7555034|1.90|
|ETHFI_USDT|0.617100|-2.55|-12.91|-2.50|5209330|1.62|
|BAT_USDT|0.169990|-2.53|71.43|-2.48|36316900|1.18|
|PUMPFUN_USDT|0.004741|-2.20|-24.39|-2.15|20465190|2.11|
|STRK_USDT|0.075750|-1.85|53.15|-1.80|24414931|1.32|
|INJ_USDT|7.702000|-1.73|5.37|-1.68|44712402|1.30|
|AAVE_USDT|154.410000|-1.49|-10.10|-1.44|23199585|0.65|
|TIA_USDT|0.540200|-1.44|21.85|-1.39|29403248|1.85|
|SILVER_USDT|55.690000|-1.22|-7.12|-1.17|387136323|1.80|
|FET_USDT|0.205600|-1.20|-9.22|-1.15|8461086|4.86|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.410000|155.830000|154.410000|1.71|Y|Y/Y|Y/Y|Y|Y|
|BAT_USDT|0.169990|0.170490|0.170000|0.52|N|Y/Y|N/N|Y|N|
|BTW_USDT|2.105100|2.152200|2.111400|1.77|Y|Y/Y|N/N|Y|N|
|ETHFI_USDT|0.617100|0.619600|0.617100|0.86|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.205600|0.202700|0.205600|1.34|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.702000|7.587000|7.702000|0.41|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.004741|0.004659|0.004741|0.38|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|55.690000|55.580000|55.690000|0.68|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.075750|0.075190|0.075730|0.61|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.052590|0.052320|0.052590|0.35|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.540200|0.528700|0.540200|0.40|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-14T18:00:02+00:00, last15m_closed_end=2026-10-14T18:00+00:00, prior8high=158.400000, depth_time=2026-10-14T18:00:25+00:00, book20_bid_proxy_usdt=273165, book20_ask_proxy_usdt=717319, funding_indicative=0.000061, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.49%, turnover=23199585. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-14T18:00:02+00:00, last15m_closed_end=2026-10-14T18:00+00:00, prior8high=0.176560, depth_time=2026-10-14T18:00:15+00:00, book20_bid_proxy_usdt=36556, book20_ask_proxy_usdt=38584, funding_indicative=0.000044, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=36316900. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-14T18:00:02+00:00, last15m_closed_end=2026-10-14T18:00+00:00, prior8high=2.425200, depth_time=2026-10-14T18:00:08+00:00, book20_bid_proxy_usdt=16108, book20_ask_proxy_usdt=11673, funding_indicative=-0.000004, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-11.50%, turnover=58467442. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-14T18:00:03+00:00, last15m_closed_end=2026-10-14T18:00+00:00, prior8high=0.632400, depth_time=2026-10-14T18:00:12+00:00, book20_bid_proxy_usdt=259069, book20_ask_proxy_usdt=284833, funding_indicative=-0.000046, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.55%, turnover=5209330. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T18:00:02+00:00, last15m_closed_end=2026-10-14T18:00+00:00, prior8high=0.208600, depth_time=2026-10-14T18:00:31+00:00, book20_bid_proxy_usdt=1274130, book20_ask_proxy_usdt=1189619, funding_indicative=-0.000056, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=8461086. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-14T18:00:02+00:00, last15m_closed_end=2026-10-14T18:00+00:00, prior8high=7.746000, depth_time=2026-10-14T18:00:22+00:00, book20_bid_proxy_usdt=222123, book20_ask_proxy_usdt=219424, funding_indicative=0.000022, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=44712402. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-14T18:00:02+00:00, last15m_closed_end=2026-10-14T18:00+00:00, prior8high=0.004810, depth_time=2026-10-14T18:00:17+00:00, book20_bid_proxy_usdt=1243117, book20_ask_proxy_usdt=1601413, funding_indicative=0.000050, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.20%, turnover=20465190. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T18:00:02+00:00, last15m_closed_end=2026-10-14T18:00+00:00, prior8high=56.030000, depth_time=2026-10-14T18:00:29+00:00, book20_bid_proxy_usdt=52100936, book20_ask_proxy_usdt=55454083, funding_indicative=0.000151, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.22%, turnover=387136323. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T18:00:02+00:00, last15m_closed_end=2026-10-14T18:00+00:00, prior8high=0.078370, depth_time=2026-10-14T18:00:20+00:00, book20_bid_proxy_usdt=266450, book20_ask_proxy_usdt=353826, funding_indicative=0.000039, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.85%, turnover=24414931. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T18:00:02+00:00, last15m_closed_end=2026-10-14T18:00+00:00, prior8high=0.055570, depth_time=2026-10-14T18:00:10+00:00, book20_bid_proxy_usdt=166782, book20_ask_proxy_usdt=183588, funding_indicative=-0.000049, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.31%, turnover=7555034. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T18:00:02+00:00, last15m_closed_end=2026-10-14T18:00+00:00, prior8high=0.542300, depth_time=2026-10-14T18:00:27+00:00, book20_bid_proxy_usdt=197211, book20_ask_proxy_usdt=166064, funding_indicative=-0.000096, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.44%, turnover=29403248. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
