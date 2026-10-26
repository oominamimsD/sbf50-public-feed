# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T07:00:28Z**
- feed_generated_utc: 2026-10-26T07:00:32+00:00
- source_sha256: `bf48c2e6ff89153cfb3878d548665c94235be9fc00a1606b30132e020e101c80`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T07:00+00:00, close=80093.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T07:00+00:00, close=80093.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T04:00+00:00, close=79565.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|APR_USDT|0.034520|-15.22|26.72|-14.59|9169332|5.79|
|T_USDT|0.004813|-11.73|2.36|-11.10|5520567|2.08|
|IRYS_USDT|0.031400|-10.84|157.37|-10.21|13116663|3.18|
|BTW_USDT|1.605800|-3.84|-30.34|-3.21|10920283|0.62|
|XMR_USDT|585.140000|-3.64|0.45|-3.01|6155298|0.17|
|DASH_USDT|51.180000|-3.45|6.89|-2.82|11788103|3.91|
|WLD_USDT|0.439200|-2.87|-7.78|-2.24|68145279|2.28|
|DOT_USDT|1.006800|-2.52|-5.85|-1.89|10433351|0.99|
|INJ_USDT|7.556000|-1.74|-6.95|-1.11|25278221|2.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.034520|0.034230|0.034520|1.69|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.605800|1.578900|1.605800|0.81|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|51.180000|50.820000|51.180000|0.37|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.006800|1.002800|1.006900|1.02|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.556000|7.533000|7.556000|0.33|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.031400|0.030290|0.031400|0.82|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004813|0.004788|0.004813|0.26|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.439200|0.436400|0.439200|0.66|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|585.140000|585.460000|585.410000|1.21|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T07:00:00+00:00, last15m_closed_end=2026-10-26T07:00+00:00, prior8high=0.037240, depth_time=2026-10-26T07:00:08+00:00, book20_bid_proxy_usdt=41846, book20_ask_proxy_usdt=43638, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.22%, turnover=9169332. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T07:00:01+00:00, last15m_closed_end=2026-10-26T07:00+00:00, prior8high=1.667700, depth_time=2026-10-26T07:00:14+00:00, book20_bid_proxy_usdt=14892, book20_ask_proxy_usdt=10421, funding_indicative=-0.004036, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.84%, turnover=10920283. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T07:00:01+00:00, last15m_closed_end=2026-10-26T07:00+00:00, prior8high=51.450000, depth_time=2026-10-26T07:00:20+00:00, book20_bid_proxy_usdt=775196, book20_ask_proxy_usdt=734958, funding_indicative=0.000071, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.45%, turnover=11788103. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T07:00:01+00:00, last15m_closed_end=2026-10-26T07:00+00:00, prior8high=1.022500, depth_time=2026-10-26T07:00:24+00:00, book20_bid_proxy_usdt=239191, book20_ask_proxy_usdt=402582, funding_indicative=-0.000108, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.52%, turnover=10433351. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-26T07:00:01+00:00, last15m_closed_end=2026-10-26T07:00+00:00, prior8high=7.718000, depth_time=2026-10-26T07:00:27+00:00, book20_bid_proxy_usdt=237475, book20_ask_proxy_usdt=330315, funding_indicative=0.000080, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=25278221. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T07:00:00+00:00, last15m_closed_end=2026-10-26T07:00+00:00, prior8high=0.035550, depth_time=2026-10-26T07:00:12+00:00, book20_bid_proxy_usdt=118104, book20_ask_proxy_usdt=77940, funding_indicative=-0.000607, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=1, 24h_change=-10.84%, turnover=13116663. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T07:00:00+00:00, last15m_closed_end=2026-10-26T07:00+00:00, prior8high=0.004917, depth_time=2026-10-26T07:00:05+00:00, book20_bid_proxy_usdt=76966, book20_ask_proxy_usdt=99950, funding_indicative=-0.000674, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=1, 24h_change=-11.73%, turnover=5520567. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T07:00:00+00:00, last15m_closed_end=2026-10-26T07:00+00:00, prior8high=0.446600, depth_time=2026-10-26T07:00:23+00:00, book20_bid_proxy_usdt=2372769, book20_ask_proxy_usdt=2967383, funding_indicative=-0.000055, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.87%, turnover=68145279. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T07:00:01+00:00, last15m_closed_end=2026-10-26T07:00+00:00, prior8high=593.530000, depth_time=2026-10-26T07:00:18+00:00, book20_bid_proxy_usdt=16294, book20_ask_proxy_usdt=21222, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.64%, turnover=6155298. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
