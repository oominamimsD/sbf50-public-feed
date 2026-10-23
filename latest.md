# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T07:15:23Z**
- feed_generated_utc: 2026-10-23T07:15:25+00:00
- source_sha256: `5a0b68087b0483993414f781440cb37d50b46ae3b80c78f41a1abc8187fd5c33`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T07:15+00:00, close=81770, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T07:00+00:00, close=81851.5, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T04:00+00:00, close=81863.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.427600|-5.16|10.87|-5.30|9881124|0.29|
|SILVER_USDT|54.060000|-2.17|-5.39|-2.31|339347186|1.85|
|STRK_USDT|0.053400|-1.76|-44.58|-1.90|10463069|1.87|
|TIA_USDT|0.560300|-1.42|-7.00|-1.56|23745564|1.78|
|QNT_USDT|188.920000|-0.93|-9.13|-1.07|48826002|0.53|
|XAU_USDT|4024.110000|-0.87|-3.17|-1.01|659361690|0.03|
|XAUT_USDT|4019.110000|-0.86|-3.03|-1.00|262729506|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|LIT_USDT|3.427600|3.409600|3.427600|0.45|N|Y/Y|N/N|Y|N|
|QNT_USDT|188.920000|187.970000|188.920000|1.14|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|54.060000|53.860000|54.060000|2.30|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.053400|0.052400|0.053420|1.27|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.560300|0.556900|0.560300|0.53|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4019.110000|4010.140000|4019.110000|1.57|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4024.110000|4013.320000|4024.110000|0.88|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- LIT_USDT: quote_utc=2026-10-23T07:15:00+00:00, last15m_closed_end=2026-10-23T07:15+00:00, prior8high=3.474800, depth_time=2026-10-23T07:15:08+00:00, book20_bid_proxy_usdt=20519, book20_ask_proxy_usdt=21442, funding_indicative=-0.000008, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.16%, turnover=9881124. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T07:14:59+00:00, last15m_closed_end=2026-10-23T07:15+00:00, prior8high=190.340000, depth_time=2026-10-23T07:15:18+00:00, book20_bid_proxy_usdt=79584, book20_ask_proxy_usdt=117294, funding_indicative=-0.000127, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.93%, turnover=48826002. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T07:14:59+00:00, last15m_closed_end=2026-10-23T07:15+00:00, prior8high=54.680000, depth_time=2026-10-23T07:15:09+00:00, book20_bid_proxy_usdt=35430216, book20_ask_proxy_usdt=28114032, funding_indicative=0.000143, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.17%, turnover=339347186. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T07:15:00+00:00, last15m_closed_end=2026-10-23T07:15+00:00, prior8high=0.053240, depth_time=2026-10-23T07:15:13+00:00, book20_bid_proxy_usdt=727062, book20_ask_proxy_usdt=723481, funding_indicative=-0.000027, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.76%, turnover=10463069. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T07:14:59+00:00, last15m_closed_end=2026-10-23T07:15+00:00, prior8high=0.562000, depth_time=2026-10-23T07:15:14+00:00, book20_bid_proxy_usdt=326810, book20_ask_proxy_usdt=270731, funding_indicative=-0.000038, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.42%, turnover=23745564. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T07:14:59+00:00, last15m_closed_end=2026-10-23T07:15+00:00, prior8high=4032.400000, depth_time=2026-10-23T07:15:22+00:00, book20_bid_proxy_usdt=303423, book20_ask_proxy_usdt=96505, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.86%, turnover=262729506. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T07:14:59+00:00, last15m_closed_end=2026-10-23T07:15+00:00, prior8high=4036.730000, depth_time=2026-10-23T07:15:20+00:00, book20_bid_proxy_usdt=2127531, book20_ask_proxy_usdt=2147288, funding_indicative=0.000101, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.87%, turnover=659361690. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
