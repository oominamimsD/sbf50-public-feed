# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T11:00:47Z**
- feed_generated_utc: 2026-10-25T11:00:51+00:00
- source_sha256: `8871047d291c5a691b3a22548b66248eb282a6fff7cc7382f29f6801762c24cd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T11:00+00:00, close=80246.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T11:00+00:00, close=80246.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T08:00+00:00, close=80645, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.049610|-26.39|60.29|-27.01|9609236|2.02|
|IRYS_USDT|0.034750|-24.53|172.33|-25.15|29023312|2.88|
|BTW_USDT|1.653300|-5.05|-27.14|-5.67|11202840|1.81|
|WLD_USDT|0.444000|-3.89|-10.41|-4.51|92621047|2.25|
|STRK_USDT|0.045150|-3.38|-31.74|-4.00|8888200|2.21|
|PENGU_USDT|0.007347|-2.68|-1.42|-3.30|5546880|2.72|
|DOT_USDT|1.017300|-2.09|-8.95|-2.71|11652835|0.98|
|SUI_USDT|0.910000|-1.62|-7.31|-2.24|66887956|1.10|
|APT_USDT|0.690900|-1.56|-13.36|-2.18|5773909|1.45|
|TIA_USDT|0.526200|-1.46|-20.03|-2.08|20795141|1.90|
|LINK_USDT|11.309000|-1.31|-5.01|-1.93|46406351|0.88|
|SEI_USDT|0.052350|-1.00|-15.57|-1.62|7758432|1.91|
|OP_USDT|0.109930|-0.91|-14.78|-1.53|5921394|1.82|
|ARB_USDT|0.164240|-0.90|-10.70|-1.52|15545907|0.61|
|XLM_USDT|0.168460|-0.59|-4.84|-1.21|11339391|0.59|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.690900|0.687600|0.690800|1.65|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164240|0.163130|0.164200|1.00|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.653300|1.610600|1.650100|0.76|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.017300|1.011600|1.016100|0.87|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.034750|0.034520|0.034770|1.46|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.309000|11.255000|11.309000|0.94|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.109930|0.109150|0.109930|1.09|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.049610|0.048370|0.049550|1.24|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007347|0.007294|0.007347|0.94|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052350|0.051870|0.052380|0.97|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045150|0.045060|0.045140|2.77|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.910000|0.903500|0.909500|0.88|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.526200|0.521500|0.526200|1.18|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.444000|0.431900|0.444100|0.72|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.168460|0.167730|0.168460|0.81|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-25T11:00:03+00:00, last15m_closed_end=2026-10-25T11:00+00:00, prior8high=0.695500, depth_time=2026-10-25T11:00:30+00:00, book20_bid_proxy_usdt=123725, book20_ask_proxy_usdt=155788, funding_indicative=-0.000106, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.56%, turnover=5773909. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-25T11:00:03+00:00, last15m_closed_end=2026-10-25T11:00+00:00, prior8high=0.164850, depth_time=2026-10-25T11:00:44+00:00, book20_bid_proxy_usdt=100769, book20_ask_proxy_usdt=71881, funding_indicative=0.000065, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.90%, turnover=15545907. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T11:00:03+00:00, last15m_closed_end=2026-10-25T11:00+00:00, prior8high=1.675400, depth_time=2026-10-25T11:00:13+00:00, book20_bid_proxy_usdt=3633, book20_ask_proxy_usdt=8597, funding_indicative=-0.018840, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.05%, turnover=11202840. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T11:00:03+00:00, last15m_closed_end=2026-10-25T11:00+00:00, prior8high=1.026000, depth_time=2026-10-25T11:00:25+00:00, book20_bid_proxy_usdt=133938, book20_ask_proxy_usdt=267910, funding_indicative=-0.000043, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=11652835. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T11:00:03+00:00, last15m_closed_end=2026-10-25T11:00+00:00, prior8high=0.037450, depth_time=2026-10-25T11:00:11+00:00, book20_bid_proxy_usdt=56693, book20_ask_proxy_usdt=61228, funding_indicative=-0.000954, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=1, 24h_change=-24.53%, turnover=29023312. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-25T11:00:03+00:00, last15m_closed_end=2026-10-25T11:00+00:00, prior8high=11.354000, depth_time=2026-10-25T11:00:36+00:00, book20_bid_proxy_usdt=470755, book20_ask_proxy_usdt=464118, funding_indicative=0.000001, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=46406351. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-25T11:00:03+00:00, last15m_closed_end=2026-10-25T11:00+00:00, prior8high=0.110600, depth_time=2026-10-25T11:00:41+00:00, book20_bid_proxy_usdt=66720, book20_ask_proxy_usdt=107034, funding_indicative=0.000021, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.91%, turnover=5921394. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T11:00:03+00:00, last15m_closed_end=2026-10-25T11:00+00:00, prior8high=0.053130, depth_time=2026-10-25T11:00:09+00:00, book20_bid_proxy_usdt=82337, book20_ask_proxy_usdt=79380, funding_indicative=-0.001628, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=1, 24h_change=-26.39%, turnover=9609236. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T11:00:03+00:00, last15m_closed_end=2026-10-25T11:00+00:00, prior8high=0.007408, depth_time=2026-10-25T11:00:23+00:00, book20_bid_proxy_usdt=300622, book20_ask_proxy_usdt=237560, funding_indicative=-0.000072, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.68%, turnover=5546880. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T11:00:03+00:00, last15m_closed_end=2026-10-25T11:00+00:00, prior8high=0.052480, depth_time=2026-10-25T11:00:38+00:00, book20_bid_proxy_usdt=103007, book20_ask_proxy_usdt=371495, funding_indicative=-0.000119, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=7758432. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T11:00:03+00:00, last15m_closed_end=2026-10-25T11:00+00:00, prior8high=0.045770, depth_time=2026-10-25T11:00:19+00:00, book20_bid_proxy_usdt=848912, book20_ask_proxy_usdt=814275, funding_indicative=0.000050, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.38%, turnover=8888200. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T11:00:03+00:00, last15m_closed_end=2026-10-25T11:00+00:00, prior8high=0.915200, depth_time=2026-10-25T11:00:28+00:00, book20_bid_proxy_usdt=460522, book20_ask_proxy_usdt=1240314, funding_indicative=-0.000009, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.62%, turnover=66887956. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-25T11:00:03+00:00, last15m_closed_end=2026-10-25T11:00+00:00, prior8high=0.535500, depth_time=2026-10-25T11:00:33+00:00, book20_bid_proxy_usdt=377774, book20_ask_proxy_usdt=410820, funding_indicative=0.000002, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.46%, turnover=20795141. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-25T11:00:03+00:00, last15m_closed_end=2026-10-25T11:00+00:00, prior8high=0.457400, depth_time=2026-10-25T11:00:17+00:00, book20_bid_proxy_usdt=2005516, book20_ask_proxy_usdt=2186176, funding_indicative=0.000008, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.89%, turnover=92621047. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-25T11:00:03+00:00, last15m_closed_end=2026-10-25T11:00+00:00, prior8high=0.169120, depth_time=2026-10-25T11:00:45+00:00, book20_bid_proxy_usdt=129662, book20_ask_proxy_usdt=152963, funding_indicative=0.000015, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.59%, turnover=11339391. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
