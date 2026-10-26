# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T06:30:44Z**
- feed_generated_utc: 2026-10-26T06:30:48+00:00
- source_sha256: `2fb92a57a4c925f06e485af70b46c8c30651db767c7107c7eba7aeb22f4c03f2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T06:30+00:00, close=79931.2, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T06:00+00:00, close=80234.1, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T04:00+00:00, close=79565.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.031470|-18.13|157.95|-17.31|13692649|3.17|
|APR_USDT|0.035200|-14.79|29.22|-13.97|10430834|2.84|
|T_USDT|0.004844|-10.01|3.01|-9.19|5806242|4.13|
|WLD_USDT|0.438400|-3.98|-7.95|-3.16|71950108|2.28|
|DOT_USDT|1.004000|-3.38|-6.11|-2.56|11296183|1.99|
|XMR_USDT|588.010000|-3.16|0.94|-2.34|6383093|0.34|
|TIA_USDT|0.521500|-2.90|-15.60|-2.08|17964043|1.92|
|PUMPFUN_USDT|0.004168|-2.73|-0.64|-1.91|16646184|2.40|
|LIT_USDT|3.094800|-2.63|5.61|-1.81|6088593|0.32|
|BTW_USDT|1.615900|-2.59|-29.90|-1.77|12592247|6.81|
|DASH_USDT|51.110000|-2.48|6.74|-1.66|12158692|1.96|
|STRK_USDT|0.044620|-2.44|-27.51|-1.62|9291411|4.48|
|INJ_USDT|7.539000|-2.14|-7.16|-1.32|25599379|1.33|
|APT_USDT|0.687200|-2.06|-10.59|-1.24|6199808|1.45|
|NEAR_USDT|4.457000|-1.91|-5.93|-1.09|131712502|2.24|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.035200|0.034230|0.035200|0.48|N|Y/Y|N/N|Y|N|
|APT_USDT|0.687200|0.691900|0.687200|3.95|Y|Y/Y|Y/Y|Y|Y|
|BTW_USDT|1.615900|1.620600|1.616100|0.92|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|51.110000|50.560000|51.090000|0.80|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.004000|1.004200|1.003200|1.87|Y|Y/Y|Y/Y|Y|Y|
|INJ_USDT|7.539000|7.567000|7.539000|1.06|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.031470|0.030290|0.031470|1.77|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.094800|3.000300|3.094800|0.88|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.457000|4.466000|4.453000|0.92|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004168|0.004146|0.004168|0.83|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044620|0.044630|0.044620|2.88|Y|Y/Y|Y/Y|Y|Y|
|TIA_USDT|0.521500|0.519000|0.521500|0.43|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004844|0.004814|0.004844|0.30|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.438400|0.437400|0.438400|0.90|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|588.010000|587.680000|588.010000|0.13|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T06:30:01+00:00, last15m_closed_end=2026-10-26T06:30+00:00, prior8high=0.037240, depth_time=2026-10-26T06:30:10+00:00, book20_bid_proxy_usdt=73643, book20_ask_proxy_usdt=75577, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.79%, turnover=10430834. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-26T06:30:01+00:00, last15m_closed_end=2026-10-26T06:30+00:00, prior8high=0.705000, depth_time=2026-10-26T06:30:41+00:00, book20_bid_proxy_usdt=148396, book20_ask_proxy_usdt=185396, funding_indicative=-0.000039, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.06%, turnover=6199808. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T06:30:01+00:00, last15m_closed_end=2026-10-26T06:30+00:00, prior8high=1.667700, depth_time=2026-10-26T06:30:31+00:00, book20_bid_proxy_usdt=6458, book20_ask_proxy_usdt=16163, funding_indicative=-0.003896, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.59%, turnover=12592247. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T06:30:01+00:00, last15m_closed_end=2026-10-26T06:30+00:00, prior8high=51.450000, depth_time=2026-10-26T06:30:33+00:00, book20_bid_proxy_usdt=679388, book20_ask_proxy_usdt=691986, funding_indicative=0.000055, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.48%, turnover=12158692. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T06:30:01+00:00, last15m_closed_end=2026-10-26T06:30+00:00, prior8high=1.024300, depth_time=2026-10-26T06:30:18+00:00, book20_bid_proxy_usdt=337087, book20_ask_proxy_usdt=313877, funding_indicative=-0.000052, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.38%, turnover=11296183. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-26T06:30:01+00:00, last15m_closed_end=2026-10-26T06:30+00:00, prior8high=7.718000, depth_time=2026-10-26T06:30:38+00:00, book20_bid_proxy_usdt=701089, book20_ask_proxy_usdt=297667, funding_indicative=0.000098, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.14%, turnover=25599379. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T06:30:01+00:00, last15m_closed_end=2026-10-26T06:30+00:00, prior8high=0.036520, depth_time=2026-10-26T06:30:08+00:00, book20_bid_proxy_usdt=138337, book20_ask_proxy_usdt=69889, funding_indicative=-0.000450, next_funding_utc=2026-10-26T07:00:00+00:00, funding_cycle_h=1, 24h_change=-18.13%, turnover=13692649. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T06:30:01+00:00, last15m_closed_end=2026-10-26T06:30+00:00, prior8high=3.113700, depth_time=2026-10-26T06:30:28+00:00, book20_bid_proxy_usdt=22301, book20_ask_proxy_usdt=41720, funding_indicative=0.000033, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.63%, turnover=6088593. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T06:30:01+00:00, last15m_closed_end=2026-10-26T06:30+00:00, prior8high=4.541000, depth_time=2026-10-26T06:30:43+00:00, book20_bid_proxy_usdt=2766473, book20_ask_proxy_usdt=4355159, funding_indicative=0.000079, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=131712502. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T06:30:01+00:00, last15m_closed_end=2026-10-26T06:30+00:00, prior8high=0.004233, depth_time=2026-10-26T06:30:26+00:00, book20_bid_proxy_usdt=2264326, book20_ask_proxy_usdt=1903710, funding_indicative=-0.000008, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.73%, turnover=16646184. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T06:30:01+00:00, last15m_closed_end=2026-10-26T06:30+00:00, prior8high=0.045380, depth_time=2026-10-26T06:30:36+00:00, book20_bid_proxy_usdt=918275, book20_ask_proxy_usdt=599687, funding_indicative=0.000008, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.44%, turnover=9291411. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-26T06:30:01+00:00, last15m_closed_end=2026-10-26T06:30+00:00, prior8high=0.536500, depth_time=2026-10-26T06:30:23+00:00, book20_bid_proxy_usdt=290550, book20_ask_proxy_usdt=307452, funding_indicative=-0.000061, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.90%, turnover=17964043. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T06:30:01+00:00, last15m_closed_end=2026-10-26T06:30+00:00, prior8high=0.004966, depth_time=2026-10-26T06:30:09+00:00, book20_bid_proxy_usdt=64529, book20_ask_proxy_usdt=62032, funding_indicative=-0.000764, next_funding_utc=2026-10-26T07:00:00+00:00, funding_cycle_h=1, 24h_change=-10.01%, turnover=5806242. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T06:30:01+00:00, last15m_closed_end=2026-10-26T06:30+00:00, prior8high=0.446600, depth_time=2026-10-26T06:30:15+00:00, book20_bid_proxy_usdt=2130206, book20_ask_proxy_usdt=2406401, funding_indicative=-0.000039, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.98%, turnover=71950108. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T06:30:01+00:00, last15m_closed_end=2026-10-26T06:30+00:00, prior8high=595.240000, depth_time=2026-10-26T06:30:21+00:00, book20_bid_proxy_usdt=14079, book20_ask_proxy_usdt=19554, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=6383093. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
