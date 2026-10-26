# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T05:30:29Z**
- feed_generated_utc: 2026-10-26T05:30:32+00:00
- source_sha256: `2b20d7339d87aafedcd768590b846f030c8e81b43b7466e0a2f7dc86ec2f6627`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T05:30+00:00, close=80133.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T05:00+00:00, close=80102.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T04:00+00:00, close=79565.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|APR_USDT|0.035470|-14.13|30.21|-13.56|11525771|5.64|
|IRYS_USDT|0.034480|-10.30|182.62|-9.73|14163492|2.90|
|T_USDT|0.004875|-9.43|3.67|-8.86|5952718|2.05|
|LIT_USDT|3.063400|-3.61|4.53|-3.04|6163173|0.33|
|XMR_USDT|590.140000|-2.81|1.31|-2.24|6836872|0.17|
|DASH_USDT|50.950000|-2.78|6.41|-2.21|13539511|1.96|
|WLD_USDT|0.444700|-2.60|-6.63|-2.03|73660648|2.25|
|DOT_USDT|1.018000|-2.04|-4.80|-1.47|11172078|1.97|
|PUMPFUN_USDT|0.004200|-1.98|0.11|-1.41|17454712|2.38|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.035470|0.033880|0.035610|1.00|N|Y/Y|N/N|Y|N|
|DASH_USDT|50.950000|50.050000|50.950000|0.95|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.018000|1.011600|1.018000|0.68|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.034480|0.034260|0.034450|1.89|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.063400|3.000300|3.063400|0.39|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004200|0.004111|0.004200|0.37|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004875|0.004831|0.004875|0.57|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.444700|0.434800|0.444700|0.95|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|590.140000|588.910000|590.130000|1.06|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T05:30:02+00:00, last15m_closed_end=2026-10-26T05:30+00:00, prior8high=0.036370, depth_time=2026-10-26T05:30:07+00:00, book20_bid_proxy_usdt=47164, book20_ask_proxy_usdt=52409, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.13%, turnover=11525771. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T05:30:03+00:00, last15m_closed_end=2026-10-26T05:30+00:00, prior8high=51.450000, depth_time=2026-10-26T05:30:17+00:00, book20_bid_proxy_usdt=744227, book20_ask_proxy_usdt=560979, funding_indicative=0.000057, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.78%, turnover=13539511. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T05:30:03+00:00, last15m_closed_end=2026-10-26T05:30+00:00, prior8high=1.024300, depth_time=2026-10-26T05:30:23+00:00, book20_bid_proxy_usdt=183065, book20_ask_proxy_usdt=207178, funding_indicative=-0.000003, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=11172078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T05:30:03+00:00, last15m_closed_end=2026-10-26T05:30+00:00, prior8high=0.038620, depth_time=2026-10-26T05:30:10+00:00, book20_bid_proxy_usdt=56470, book20_ask_proxy_usdt=69944, funding_indicative=-0.000568, next_funding_utc=2026-10-26T06:00:00+00:00, funding_cycle_h=1, 24h_change=-10.30%, turnover=14163492. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T05:30:03+00:00, last15m_closed_end=2026-10-26T05:30+00:00, prior8high=3.118800, depth_time=2026-10-26T05:30:14+00:00, book20_bid_proxy_usdt=14533, book20_ask_proxy_usdt=24036, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.61%, turnover=6163173. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T05:30:03+00:00, last15m_closed_end=2026-10-26T05:30+00:00, prior8high=0.004219, depth_time=2026-10-26T05:30:26+00:00, book20_bid_proxy_usdt=1948509, book20_ask_proxy_usdt=1547699, funding_indicative=0.000033, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.98%, turnover=17454712. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T05:30:03+00:00, last15m_closed_end=2026-10-26T05:30+00:00, prior8high=0.004979, depth_time=2026-10-26T05:30:13+00:00, book20_bid_proxy_usdt=45682, book20_ask_proxy_usdt=61964, funding_indicative=-0.000840, next_funding_utc=2026-10-26T06:00:00+00:00, funding_cycle_h=1, 24h_change=-9.43%, turnover=5952718. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T05:30:03+00:00, last15m_closed_end=2026-10-26T05:30+00:00, prior8high=0.446600, depth_time=2026-10-26T05:30:23+00:00, book20_bid_proxy_usdt=3024374, book20_ask_proxy_usdt=2545338, funding_indicative=0.000007, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.60%, turnover=73660648. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T05:30:03+00:00, last15m_closed_end=2026-10-26T05:30+00:00, prior8high=596.010000, depth_time=2026-10-26T05:30:12+00:00, book20_bid_proxy_usdt=19541, book20_ask_proxy_usdt=14767, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.81%, turnover=6836872. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
