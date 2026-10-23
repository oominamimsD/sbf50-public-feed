# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T06:30:23Z**
- feed_generated_utc: 2026-10-23T06:30:24+00:00
- source_sha256: `d8f7cdd33e585041bf3bf9c129698b05274e11427b6f50d53f46dfa162ababd0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T06:30+00:00, close=81816.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T06:00+00:00, close=81812.9, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T04:00+00:00, close=81863.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004223|-8.35|112.74|-8.55|8486962|7.11|
|LIT_USDT|3.417600|-5.43|10.55|-5.63|10149689|0.29|
|STRK_USDT|0.052870|-2.74|-45.13|-2.94|10679386|3.78|
|SILVER_USDT|54.240000|-1.84|-5.07|-2.04|345208171|1.84|
|TIA_USDT|0.559200|-1.61|-7.18|-1.81|23760062|1.79|
|XAU_USDT|4024.110000|-0.87|-3.17|-1.07|682881458|0.03|
|XAUT_USDT|4019.880000|-0.84|-3.01|-1.04|266849981|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.004223|0.004130|0.004224|0.73|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.417600|3.410200|3.417600|1.90|N|Y/Y|N/N|Y|N|
|SILVER_USDT|54.240000|53.720000|54.240000|1.67|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052870|0.052610|0.052880|1.39|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.559200|0.556900|0.559200|0.63|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4019.880000|4008.190000|4019.880000|0.93|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4024.110000|4010.840000|4024.110000|0.61|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-10-23T06:30:01+00:00, last15m_closed_end=2026-10-23T06:30+00:00, prior8high=0.004429, depth_time=2026-10-23T06:30:06+00:00, book20_bid_proxy_usdt=42417, book20_ask_proxy_usdt=27244, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.35%, turnover=8486962. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T06:30:01+00:00, last15m_closed_end=2026-10-23T06:30+00:00, prior8high=3.493400, depth_time=2026-10-23T06:30:09+00:00, book20_bid_proxy_usdt=19642, book20_ask_proxy_usdt=19117, funding_indicative=0.000022, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.43%, turnover=10149689. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T06:30:01+00:00, last15m_closed_end=2026-10-23T06:30+00:00, prior8high=54.680000, depth_time=2026-10-23T06:30:14+00:00, book20_bid_proxy_usdt=37244870, book20_ask_proxy_usdt=27806596, funding_indicative=0.000122, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.84%, turnover=345208171. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T06:30:01+00:00, last15m_closed_end=2026-10-23T06:30+00:00, prior8high=0.053360, depth_time=2026-10-23T06:30:11+00:00, book20_bid_proxy_usdt=788206, book20_ask_proxy_usdt=632317, funding_indicative=-0.000019, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.74%, turnover=10679386. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T06:30:01+00:00, last15m_closed_end=2026-10-23T06:30+00:00, prior8high=0.561900, depth_time=2026-10-23T06:30:16+00:00, book20_bid_proxy_usdt=421136, book20_ask_proxy_usdt=378200, funding_indicative=-0.000033, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.61%, turnover=23760062. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T06:30:01+00:00, last15m_closed_end=2026-10-23T06:30+00:00, prior8high=4032.400000, depth_time=2026-10-23T06:30:20+00:00, book20_bid_proxy_usdt=145124, book20_ask_proxy_usdt=77353, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.84%, turnover=266849981. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T06:30:00+00:00, last15m_closed_end=2026-10-23T06:30+00:00, prior8high=4036.730000, depth_time=2026-10-23T06:30:19+00:00, book20_bid_proxy_usdt=3192535, book20_ask_proxy_usdt=450201, funding_indicative=0.000088, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.87%, turnover=682881458. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
