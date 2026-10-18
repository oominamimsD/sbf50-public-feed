# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T19:15:29Z**
- feed_generated_utc: 2026-10-18T19:15:32+00:00
- source_sha256: `9d832ca91efcdd4740bb4057cfa6712d1717ffd2e06ddb95cb481c4fa3c4f18d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T19:15+00:00, close=81119.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T19:00+00:00, close=81155.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T16:00+00:00, close=81137.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.169030|-3.62|1.43|-3.60|8068071|2.96|
|STRK_USDT|0.059470|-3.39|-50.13|-3.37|15534876|1.68|
|HBAR_USDT|0.083700|-2.42|-10.74|-2.40|44074644|1.20|
|PUMPFUN_USDT|0.004118|-1.83|-28.69|-1.81|28594250|4.86|
|TIA_USDT|0.607900|-1.61|3.26|-1.59|53317528|1.65|
|WLD_USDT|0.468800|-1.57|-19.06|-1.55|74794867|2.13|
|QNT_USDT|186.730000|-1.31|-23.10|-1.29|62560789|2.68|
|XPL_USDT|0.074950|-1.30|-16.02|-1.28|6594049|1.33|
|FET_USDT|0.185000|-1.28|-22.17|-1.26|8667103|5.41|
|OP_USDT|0.121770|-1.08|-15.51|-1.06|8606164|2.46|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.169030|0.169070|0.169030|1.92|Y|Y/Y|Y/Y|Y|Y|
|FET_USDT|0.185000|0.184900|0.185000|0.56|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.083700|0.083890|0.083700|1.26|N|Y/Y|N/N|Y|N|
|OP_USDT|0.121770|0.121610|0.121770|0.58|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004118|0.004107|0.004119|0.32|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|186.730000|187.160000|186.770000|1.06|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.059470|0.058820|0.059470|0.28|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.607900|0.607400|0.608000|0.90|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.468800|0.468000|0.468800|1.05|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.074950|0.075040|0.074950|1.22|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-18T19:15:00+00:00, last15m_closed_end=2026-10-18T19:15+00:00, prior8high=0.172800, depth_time=2026-10-18T19:15:06+00:00, book20_bid_proxy_usdt=23052, book20_ask_proxy_usdt=29253, funding_indicative=0.000035, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.62%, turnover=8068071. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-18T19:15:00+00:00, last15m_closed_end=2026-10-18T19:15+00:00, prior8high=0.188200, depth_time=2026-10-18T19:15:26+00:00, book20_bid_proxy_usdt=1650911, book20_ask_proxy_usdt=1527184, funding_indicative=0.000017, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=8667103. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-18T19:15:00+00:00, last15m_closed_end=2026-10-18T19:15+00:00, prior8high=0.086160, depth_time=2026-10-18T19:15:12+00:00, book20_bid_proxy_usdt=514520, book20_ask_proxy_usdt=933620, funding_indicative=0.000039, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.42%, turnover=44074644. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T19:15:00+00:00, last15m_closed_end=2026-10-18T19:15+00:00, prior8high=0.123840, depth_time=2026-10-18T19:15:28+00:00, book20_bid_proxy_usdt=81214, book20_ask_proxy_usdt=96584, funding_indicative=-0.000112, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.08%, turnover=8606164. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T19:15:00+00:00, last15m_closed_end=2026-10-18T19:15+00:00, prior8high=0.004143, depth_time=2026-10-18T19:15:14+00:00, book20_bid_proxy_usdt=2520955, book20_ask_proxy_usdt=2008440, funding_indicative=0.000043, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.83%, turnover=28594250. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T19:15:00+00:00, last15m_closed_end=2026-10-18T19:15+00:00, prior8high=190.570000, depth_time=2026-10-18T19:15:22+00:00, book20_bid_proxy_usdt=62793, book20_ask_proxy_usdt=72646, funding_indicative=0.000000, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=62560789. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T19:15:00+00:00, last15m_closed_end=2026-10-18T19:15+00:00, prior8high=0.060810, depth_time=2026-10-18T19:15:10+00:00, book20_bid_proxy_usdt=746735, book20_ask_proxy_usdt=282665, funding_indicative=0.000050, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.39%, turnover=15534876. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T19:15:00+00:00, last15m_closed_end=2026-10-18T19:15+00:00, prior8high=0.625200, depth_time=2026-10-18T19:15:17+00:00, book20_bid_proxy_usdt=263818, book20_ask_proxy_usdt=155901, funding_indicative=0.000014, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.61%, turnover=53317528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T19:15:00+00:00, last15m_closed_end=2026-10-18T19:15+00:00, prior8high=0.480000, depth_time=2026-10-18T19:15:18+00:00, book20_bid_proxy_usdt=2364606, book20_ask_proxy_usdt=1834124, funding_indicative=-0.000230, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.57%, turnover=74794867. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T19:15:00+00:00, last15m_closed_end=2026-10-18T19:15+00:00, prior8high=0.076130, depth_time=2026-10-18T19:15:23+00:00, book20_bid_proxy_usdt=644005, book20_ask_proxy_usdt=572856, funding_indicative=-0.000006, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.30%, turnover=6594049. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
