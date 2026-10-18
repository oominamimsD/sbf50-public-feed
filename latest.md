# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T19:00:24Z**
- feed_generated_utc: 2026-10-18T19:00:26+00:00
- source_sha256: `97ede945bb8ee9818967414fe90865a72460549e66e20515acc53057c31c301b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T19:00+00:00, close=81155.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T19:00+00:00, close=81155.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T16:00+00:00, close=81137.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.169360|-3.43|1.63|-3.44|8885092|1.77|
|STRK_USDT|0.059480|-3.37|-50.12|-3.38|16329482|1.68|
|PUMPFUN_USDT|0.004125|-1.66|-28.57|-1.67|29735856|2.42|
|HBAR_USDT|0.084370|-1.64|-10.03|-1.65|43937711|1.19|
|TIA_USDT|0.609400|-1.37|3.51|-1.38|55282167|1.64|
|WLD_USDT|0.470300|-1.25|-18.80|-1.26|75638975|2.13|
|FET_USDT|0.185500|-1.01|-21.96|-1.02|8986909|5.39|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.169360|0.169070|0.169330|0.30|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.185500|0.184900|0.185500|0.20|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.084370|0.083890|0.084370|0.57|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004125|0.004107|0.004124|0.38|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.059480|0.058820|0.059480|0.64|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.609400|0.607400|0.609400|0.53|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.470300|0.468000|0.470300|0.30|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-18T18:59:58+00:00, last15m_closed_end=2026-10-18T19:00+00:00, prior8high=0.172860, depth_time=2026-10-18T19:00:07+00:00, book20_bid_proxy_usdt=23406, book20_ask_proxy_usdt=23156, funding_indicative=0.000029, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.43%, turnover=8885092. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-18T18:59:58+00:00, last15m_closed_end=2026-10-18T19:00+00:00, prior8high=0.188200, depth_time=2026-10-18T19:00:21+00:00, book20_bid_proxy_usdt=1997080, book20_ask_proxy_usdt=1269069, funding_indicative=0.000004, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.01%, turnover=8986909. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-18T18:59:58+00:00, last15m_closed_end=2026-10-18T19:00+00:00, prior8high=0.086220, depth_time=2026-10-18T19:00:16+00:00, book20_bid_proxy_usdt=777181, book20_ask_proxy_usdt=1079646, funding_indicative=0.000038, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=43937711. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T18:59:58+00:00, last15m_closed_end=2026-10-18T19:00+00:00, prior8high=0.004143, depth_time=2026-10-18T19:00:13+00:00, book20_bid_proxy_usdt=2609750, book20_ask_proxy_usdt=1954734, funding_indicative=0.000050, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.66%, turnover=29735856. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T18:59:58+00:00, last15m_closed_end=2026-10-18T19:00+00:00, prior8high=0.060810, depth_time=2026-10-18T19:00:10+00:00, book20_bid_proxy_usdt=593086, book20_ask_proxy_usdt=397725, funding_indicative=0.000050, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.37%, turnover=16329482. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T18:59:58+00:00, last15m_closed_end=2026-10-18T19:00+00:00, prior8high=0.625200, depth_time=2026-10-18T19:00:17+00:00, book20_bid_proxy_usdt=306439, book20_ask_proxy_usdt=211693, funding_indicative=0.000013, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.37%, turnover=55282167. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T18:59:58+00:00, last15m_closed_end=2026-10-18T19:00+00:00, prior8high=0.480000, depth_time=2026-10-18T19:00:19+00:00, book20_bid_proxy_usdt=2356412, book20_ask_proxy_usdt=2331944, funding_indicative=-0.000212, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=75638975. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
