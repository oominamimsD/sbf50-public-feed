# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T07:00:30Z**
- feed_generated_utc: 2026-10-13T07:00:32+00:00
- source_sha256: `c6a849fef63aa9dd8b7ec077d4f1e40771a35d0126e397e9b0e97c8ea2852d07`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T07:00+00:00, close=83732.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T07:00+00:00, close=83732.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T04:00+00:00, close=83297.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOS_USDT|0.229100|-22.70|7.55|-23.97|9312912|4.37|
|W_USDT|0.019469|-19.42|37.65|-20.69|32500745|8.22|
|ZRO_USDT|2.095700|-10.69|2.44|-11.96|27675194|1.43|
|STRK_USDT|0.087360|-6.34|67.64|-7.61|61981536|1.14|
|PUMPFUN_USDT|0.005106|-5.89|-19.40|-7.16|31025475|1.96|
|LIT_USDT|3.433000|-5.15|-9.70|-6.42|10224052|0.29|
|RLC_USDT|0.951900|-3.71|73.70|-4.98|6597582|4.20|
|HBAR_USDT|0.088160|-2.58|-12.45|-3.85|22074972|1.13|
|PONS_USDT|0.288900|-1.96|-24.66|-3.23|6194737|3.46|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.229100|0.227700|0.229100|0.61|N|Y/Y|Y/N|N|N|
|HBAR_USDT|0.088160|0.087550|0.088150|1.16|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.433000|3.414900|3.433000|1.86|N|Y/Y|Y/Y|N|N|
|PONS_USDT|0.288900|0.282200|0.289100|1.70|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005106|0.005057|0.005106|4.21|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.951900|0.947800|0.951400|1.16|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.087360|0.085720|0.087360|0.46|N|Y/Y|Y/Y|N|N|
|W_USDT|0.019469|0.019044|0.019469|0.67|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.095700|2.087100|2.095700|0.32|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T07:00:01+00:00, last15m_closed_end=2026-10-13T07:00+00:00, prior8high=0.251000, depth_time=2026-10-13T07:00:08+00:00, book20_bid_proxy_usdt=96359, book20_ask_proxy_usdt=96634, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-22.70%, turnover=9312912. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-13T07:00:01+00:00, last15m_closed_end=2026-10-13T07:00+00:00, prior8high=0.088580, depth_time=2026-10-13T07:00:27+00:00, book20_bid_proxy_usdt=346092, book20_ask_proxy_usdt=780866, funding_indicative=-0.000010, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.58%, turnover=22074972. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T07:00:02+00:00, last15m_closed_end=2026-10-13T07:00+00:00, prior8high=3.476600, depth_time=2026-10-13T07:00:18+00:00, book20_bid_proxy_usdt=26410, book20_ask_proxy_usdt=22113, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.15%, turnover=10224052. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-13T07:00:01+00:00, last15m_closed_end=2026-10-13T07:00+00:00, prior8high=0.291800, depth_time=2026-10-13T07:00:29+00:00, book20_bid_proxy_usdt=213608, book20_ask_proxy_usdt=209972, funding_indicative=0.000071, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.96%, turnover=6194737. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T07:00:01+00:00, last15m_closed_end=2026-10-13T07:00+00:00, prior8high=0.005119, depth_time=2026-10-13T07:00:18+00:00, book20_bid_proxy_usdt=1635456, book20_ask_proxy_usdt=1310462, funding_indicative=0.000022, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.89%, turnover=31025475. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T07:00:01+00:00, last15m_closed_end=2026-10-13T07:00+00:00, prior8high=0.964300, depth_time=2026-10-13T07:00:23+00:00, book20_bid_proxy_usdt=98778, book20_ask_proxy_usdt=49110, funding_indicative=-0.000624, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.71%, turnover=6597582. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T07:00:01+00:00, last15m_closed_end=2026-10-13T07:00+00:00, prior8high=0.088840, depth_time=2026-10-13T07:00:15+00:00, book20_bid_proxy_usdt=165380, book20_ask_proxy_usdt=168715, funding_indicative=0.000015, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.34%, turnover=61981536. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T07:00:01+00:00, last15m_closed_end=2026-10-13T07:00+00:00, prior8high=0.019841, depth_time=2026-10-13T07:00:10+00:00, book20_bid_proxy_usdt=22741, book20_ask_proxy_usdt=17559, funding_indicative=-0.000502, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-19.42%, turnover=32500745. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T07:00:01+00:00, last15m_closed_end=2026-10-13T07:00+00:00, prior8high=2.149200, depth_time=2026-10-13T07:00:13+00:00, book20_bid_proxy_usdt=88319, book20_ask_proxy_usdt=91482, funding_indicative=0.000010, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.69%, turnover=27675194. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
