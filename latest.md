# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T06:15:32Z**
- feed_generated_utc: 2026-10-26T06:15:36+00:00
- source_sha256: `6334ddbb144bad0aa060b88a7812a38fc25831101a28cf19db02bbe96703dac4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T06:15+00:00, close=80064.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T06:00+00:00, close=80234.1, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T04:00+00:00, close=79565.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.032320|-15.92|164.91|-15.25|13523275|3.10|
|APR_USDT|0.036100|-12.61|32.52|-11.94|10415448|2.77|
|T_USDT|0.004855|-9.80|3.25|-9.13|5804897|2.06|
|WLD_USDT|0.437400|-4.20|-8.16|-3.53|71568983|2.29|
|TIA_USDT|0.519900|-3.20|-15.86|-2.53|17922806|3.85|
|DOT_USDT|1.006700|-3.12|-5.86|-2.45|11170568|0.99|
|XMR_USDT|588.840000|-3.03|1.08|-2.36|6377748|0.17|
|DASH_USDT|51.030000|-2.63|6.57|-1.96|12105493|1.96|
|LIT_USDT|3.102700|-2.38|5.87|-1.71|6042861|0.32|
|PUMPFUN_USDT|0.004184|-2.35|-0.26|-1.68|16574599|2.39|
|STRK_USDT|0.044910|-1.81|-27.04|-1.14|9181804|2.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.036100|0.034230|0.036100|1.14|N|Y/Y|N/N|Y|N|
|DASH_USDT|51.030000|50.340000|51.030000|0.36|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.006700|1.011600|1.006700|3.63|Y|Y/Y|Y/Y|Y|Y|
|IRYS_USDT|0.032320|0.032740|0.032320|3.18|Y|Y/Y|Y/Y|Y|Y|
|LIT_USDT|3.102700|3.000300|3.102700|0.68|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004184|0.004146|0.004184|0.97|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044910|0.044630|0.044910|0.37|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.519900|0.527400|0.519900|2.07|Y|Y/Y|Y/Y|Y|Y|
|T_USDT|0.004855|0.004814|0.004855|0.30|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.437400|0.438900|0.437400|1.94|Y|Y/Y|Y/Y|Y|Y|
|XMR_USDT|588.840000|589.000000|588.840000|0.85|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T06:15:00+00:00, last15m_closed_end=2026-10-26T06:15+00:00, prior8high=0.037190, depth_time=2026-10-26T06:15:10+00:00, book20_bid_proxy_usdt=72236, book20_ask_proxy_usdt=55289, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-12.61%, turnover=10415448. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T06:15:01+00:00, last15m_closed_end=2026-10-26T06:15+00:00, prior8high=51.450000, depth_time=2026-10-26T06:15:24+00:00, book20_bid_proxy_usdt=728993, book20_ask_proxy_usdt=635422, funding_indicative=0.000058, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.63%, turnover=12105493. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T06:15:01+00:00, last15m_closed_end=2026-10-26T06:15+00:00, prior8high=1.024300, depth_time=2026-10-26T06:15:19+00:00, book20_bid_proxy_usdt=541402, book20_ask_proxy_usdt=389535, funding_indicative=-0.000069, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.12%, turnover=11170568. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T06:15:00+00:00, last15m_closed_end=2026-10-26T06:15+00:00, prior8high=0.036520, depth_time=2026-10-26T06:15:08+00:00, book20_bid_proxy_usdt=98477, book20_ask_proxy_usdt=114923, funding_indicative=-0.000341, next_funding_utc=2026-10-26T07:00:00+00:00, funding_cycle_h=1, 24h_change=-15.92%, turnover=13523275. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T06:15:01+00:00, last15m_closed_end=2026-10-26T06:15+00:00, prior8high=3.105500, depth_time=2026-10-26T06:15:27+00:00, book20_bid_proxy_usdt=20032, book20_ask_proxy_usdt=19776, funding_indicative=0.000042, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.38%, turnover=6042861. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T06:15:01+00:00, last15m_closed_end=2026-10-26T06:15+00:00, prior8high=0.004231, depth_time=2026-10-26T06:15:28+00:00, book20_bid_proxy_usdt=1937357, book20_ask_proxy_usdt=2434493, funding_indicative=0.000001, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=16574599. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T06:15:01+00:00, last15m_closed_end=2026-10-26T06:15+00:00, prior8high=0.045380, depth_time=2026-10-26T06:15:32+00:00, book20_bid_proxy_usdt=1198768, book20_ask_proxy_usdt=684290, funding_indicative=0.000023, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.81%, turnover=9181804. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-26T06:15:01+00:00, last15m_closed_end=2026-10-26T06:15+00:00, prior8high=0.536500, depth_time=2026-10-26T06:15:17+00:00, book20_bid_proxy_usdt=261312, book20_ask_proxy_usdt=426344, funding_indicative=-0.000055, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.20%, turnover=17922806. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T06:15:00+00:00, last15m_closed_end=2026-10-26T06:15+00:00, prior8high=0.004976, depth_time=2026-10-26T06:15:12+00:00, book20_bid_proxy_usdt=48382, book20_ask_proxy_usdt=90525, funding_indicative=-0.000757, next_funding_utc=2026-10-26T07:00:00+00:00, funding_cycle_h=1, 24h_change=-9.80%, turnover=5804897. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T06:15:00+00:00, last15m_closed_end=2026-10-26T06:15+00:00, prior8high=0.446600, depth_time=2026-10-26T06:15:15+00:00, book20_bid_proxy_usdt=3004663, book20_ask_proxy_usdt=2349479, funding_indicative=-0.000036, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.20%, turnover=71568983. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T06:15:01+00:00, last15m_closed_end=2026-10-26T06:15+00:00, prior8high=595.240000, depth_time=2026-10-26T06:15:21+00:00, book20_bid_proxy_usdt=36446, book20_ask_proxy_usdt=28529, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.03%, turnover=6377748. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
