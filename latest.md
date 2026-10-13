# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T07:45:31Z**
- feed_generated_utc: 2026-10-13T07:45:34+00:00
- source_sha256: `d43352e3467afb934990b57d173362d60b162e521e019c7f2e9d44758e120185`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T07:45+00:00, close=83810.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T07:00+00:00, close=83732.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T04:00+00:00, close=83297.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOS_USDT|0.231300|-20.10|8.59|-21.46|9366071|8.65|
|W_USDT|0.019419|-19.28|37.30|-20.64|32706771|7.21|
|NEAR_USDT|5.234000|-5.67|4.22|-7.03|279512423|1.91|
|ZRO_USDT|2.132900|-5.66|4.26|-7.02|27957040|0.94|
|STRK_USDT|0.086000|-5.15|65.03|-6.51|62943493|1.16|
|LIT_USDT|3.440600|-5.09|-9.50|-6.45|10468115|0.29|
|RLC_USDT|0.938700|-5.04|71.29|-6.40|6959200|2.13|
|PUMPFUN_USDT|0.005089|-4.14|-19.66|-5.50|31919100|1.97|
|HBAR_USDT|0.088050|-2.70|-12.56|-4.06|22499520|1.14|
|PONS_USDT|0.292200|-0.84|-23.80|-2.20|6280685|3.42|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.231300|0.227700|0.231300|1.37|N|Y/Y|Y/N|N|N|
|HBAR_USDT|0.088050|0.087450|0.088070|1.39|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.440600|3.407500|3.440600|4.62|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|5.234000|5.151000|5.234000|2.20|N|Y/Y|Y/Y|N|N|
|PONS_USDT|0.292200|0.287500|0.292200|1.51|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005089|0.005044|0.005089|2.42|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.938700|0.926700|0.938700|6.29|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.086000|0.083010|0.086000|0.84|N|Y/Y|Y/Y|N|N|
|W_USDT|0.019419|0.019044|0.019419|0.71|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.132900|2.075100|2.132900|2.10|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T07:44:59+00:00, last15m_closed_end=2026-10-13T07:45+00:00, prior8high=0.236700, depth_time=2026-10-13T07:45:08+00:00, book20_bid_proxy_usdt=90186, book20_ask_proxy_usdt=68551, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-20.10%, turnover=9366071. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-13T07:44:59+00:00, last15m_closed_end=2026-10-13T07:45+00:00, prior8high=0.088280, depth_time=2026-10-13T07:45:28+00:00, book20_bid_proxy_usdt=454831, book20_ask_proxy_usdt=762902, funding_indicative=-0.000013, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.70%, turnover=22499520. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T07:45:00+00:00, last15m_closed_end=2026-10-13T07:45+00:00, prior8high=3.467500, depth_time=2026-10-13T07:45:19+00:00, book20_bid_proxy_usdt=23808, book20_ask_proxy_usdt=20191, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.09%, turnover=10468115. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-13T07:44:59+00:00, last15m_closed_end=2026-10-13T07:45+00:00, prior8high=5.340000, depth_time=2026-10-13T07:45:13+00:00, book20_bid_proxy_usdt=2747331, book20_ask_proxy_usdt=2036698, funding_indicative=-0.000043, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.67%, turnover=279512423. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-13T07:44:59+00:00, last15m_closed_end=2026-10-13T07:45+00:00, prior8high=0.292500, depth_time=2026-10-13T07:45:31+00:00, book20_bid_proxy_usdt=222698, book20_ask_proxy_usdt=218131, funding_indicative=0.000064, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.84%, turnover=6280685. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T07:44:59+00:00, last15m_closed_end=2026-10-13T07:45+00:00, prior8high=0.005124, depth_time=2026-10-13T07:45:26+00:00, book20_bid_proxy_usdt=1134834, book20_ask_proxy_usdt=1576648, funding_indicative=0.000013, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.14%, turnover=31919100. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T07:44:59+00:00, last15m_closed_end=2026-10-13T07:45+00:00, prior8high=0.963200, depth_time=2026-10-13T07:45:23+00:00, book20_bid_proxy_usdt=53929, book20_ask_proxy_usdt=48414, funding_indicative=-0.000792, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.04%, turnover=6959200. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T07:44:59+00:00, last15m_closed_end=2026-10-13T07:45+00:00, prior8high=0.088540, depth_time=2026-10-13T07:45:18+00:00, book20_bid_proxy_usdt=166795, book20_ask_proxy_usdt=249523, funding_indicative=0.000013, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.15%, turnover=62943493. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T07:44:59+00:00, last15m_closed_end=2026-10-13T07:45+00:00, prior8high=0.019841, depth_time=2026-10-13T07:45:10+00:00, book20_bid_proxy_usdt=23821, book20_ask_proxy_usdt=40167, funding_indicative=-0.000519, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-19.28%, turnover=32706771. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T07:44:59+00:00, last15m_closed_end=2026-10-13T07:45+00:00, prior8high=2.149200, depth_time=2026-10-13T07:45:15+00:00, book20_bid_proxy_usdt=61682, book20_ask_proxy_usdt=25586, funding_indicative=-0.000033, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.66%, turnover=27957040. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
