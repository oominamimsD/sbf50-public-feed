# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T09:30:50Z**
- feed_generated_utc: 2026-10-25T09:30:54+00:00
- source_sha256: `b95c25aa00c825f10954a2b4f0eba9b1193a2bb00b771f5dfb1fda70a737693f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T09:30+00:00, close=80153.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T09:00+00:00, close=80374.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T08:00+00:00, close=80645, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.034960|-24.08|173.98|-24.56|33273000|2.86|
|ORDER_USDT|0.051350|-23.81|65.91|-24.29|13495648|3.90|
|BTW_USDT|1.640800|-5.77|-27.69|-6.25|11632188|3.05|
|WLD_USDT|0.444500|-3.78|-10.31|-4.26|95548519|2.25|
|STRK_USDT|0.045260|-3.14|-31.57|-3.62|9261059|2.21|
|AKE_USDT|0.028597|-2.16|-1.26|-2.64|5711241|0.35|
|SUI_USDT|0.907200|-1.92|-7.59|-2.40|68858654|1.10|
|DOT_USDT|1.021700|-1.67|-8.56|-2.15|12511663|0.98|
|APT_USDT|0.692200|-1.38|-13.20|-1.86|6010220|1.45|
|PENGU_USDT|0.007342|-1.35|-1.48|-1.83|5783345|1.36|
|SEI_USDT|0.052220|-1.24|-15.78|-1.72|7843063|1.92|
|ARB_USDT|0.163810|-1.16|-10.93|-1.64|15576944|0.61|
|ONDO_USDT|0.398300|-0.77|-9.39|-1.25|15346340|2.51|
|LINK_USDT|11.295000|-0.76|-5.13|-1.24|49975916|0.89|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.028597|0.028638|0.028597|1.27|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.692200|0.689400|0.692200|0.72|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.163810|0.163510|0.163810|2.95|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.640800|1.640900|1.640800|1.10|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.021700|1.014400|1.021700|5.28|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.034960|0.034620|0.034940|0.94|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.295000|11.276000|11.295000|1.45|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.398300|0.397400|0.398300|1.38|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.051350|0.048370|0.051450|1.75|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007342|0.007314|0.007343|2.41|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052220|0.051960|0.052220|1.20|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045260|0.045070|0.045260|1.03|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.907200|0.908000|0.907200|2.23|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.444500|0.431900|0.444500|2.53|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-25T09:30:00+00:00, last15m_closed_end=2026-10-25T09:30+00:00, prior8high=0.029381, depth_time=2026-10-25T09:30:26+00:00, book20_bid_proxy_usdt=11062, book20_ask_proxy_usdt=17997, funding_indicative=0.000050, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.16%, turnover=5711241. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-25T09:30:00+00:00, last15m_closed_end=2026-10-25T09:30+00:00, prior8high=0.703200, depth_time=2026-10-25T09:30:34+00:00, book20_bid_proxy_usdt=157913, book20_ask_proxy_usdt=158054, funding_indicative=-0.000062, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.38%, turnover=6010220. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-25T09:30:00+00:00, last15m_closed_end=2026-10-25T09:30+00:00, prior8high=0.166810, depth_time=2026-10-25T09:30:44+00:00, book20_bid_proxy_usdt=79617, book20_ask_proxy_usdt=90934, funding_indicative=0.000044, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=15576944. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T09:30:00+00:00, last15m_closed_end=2026-10-25T09:30+00:00, prior8high=1.751100, depth_time=2026-10-25T09:30:15+00:00, book20_bid_proxy_usdt=60850, book20_ask_proxy_usdt=13794, funding_indicative=-0.014340, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.77%, turnover=11632188. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T09:30:00+00:00, last15m_closed_end=2026-10-25T09:30+00:00, prior8high=1.032000, depth_time=2026-10-25T09:30:32+00:00, book20_bid_proxy_usdt=222903, book20_ask_proxy_usdt=395619, funding_indicative=-0.000033, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.67%, turnover=12511663. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T09:30:00+00:00, last15m_closed_end=2026-10-25T09:30+00:00, prior8high=0.040010, depth_time=2026-10-25T09:30:10+00:00, book20_bid_proxy_usdt=71310, book20_ask_proxy_usdt=60736, funding_indicative=-0.001559, next_funding_utc=2026-10-25T10:00:00+00:00, funding_cycle_h=1, 24h_change=-24.08%, turnover=33273000. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-25T09:30:00+00:00, last15m_closed_end=2026-10-25T09:30+00:00, prior8high=11.417000, depth_time=2026-10-25T09:30:50+00:00, book20_bid_proxy_usdt=442921, book20_ask_proxy_usdt=506044, funding_indicative=0.000041, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.76%, turnover=49975916. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-25T09:30:00+00:00, last15m_closed_end=2026-10-25T09:30+00:00, prior8high=0.405500, depth_time=2026-10-25T09:30:47+00:00, book20_bid_proxy_usdt=3109013, book20_ask_proxy_usdt=2971042, funding_indicative=0.000047, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.77%, turnover=15346340. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T09:30:00+00:00, last15m_closed_end=2026-10-25T09:30+00:00, prior8high=0.055570, depth_time=2026-10-25T09:30:14+00:00, book20_bid_proxy_usdt=79175, book20_ask_proxy_usdt=74428, funding_indicative=-0.001113, next_funding_utc=2026-10-25T10:00:00+00:00, funding_cycle_h=1, 24h_change=-23.81%, turnover=13495648. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T09:30:01+00:00, last15m_closed_end=2026-10-25T09:30+00:00, prior8high=0.007475, depth_time=2026-10-25T09:30:37+00:00, book20_bid_proxy_usdt=198939, book20_ask_proxy_usdt=323730, funding_indicative=-0.000077, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.35%, turnover=5783345. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T09:30:01+00:00, last15m_closed_end=2026-10-25T09:30+00:00, prior8high=0.052970, depth_time=2026-10-25T09:30:41+00:00, book20_bid_proxy_usdt=184228, book20_ask_proxy_usdt=383207, funding_indicative=-0.000095, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.24%, turnover=7843063. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T09:30:01+00:00, last15m_closed_end=2026-10-25T09:30+00:00, prior8high=0.046630, depth_time=2026-10-25T09:30:24+00:00, book20_bid_proxy_usdt=732884, book20_ask_proxy_usdt=717968, funding_indicative=0.000044, next_funding_utc=2026-10-25T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.14%, turnover=9261059. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T09:30:00+00:00, last15m_closed_end=2026-10-25T09:30+00:00, prior8high=0.921100, depth_time=2026-10-25T09:30:28+00:00, book20_bid_proxy_usdt=1108207, book20_ask_proxy_usdt=1506718, funding_indicative=0.000042, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.92%, turnover=68858654. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-25T09:30:00+00:00, last15m_closed_end=2026-10-25T09:30+00:00, prior8high=0.466600, depth_time=2026-10-25T09:30:19+00:00, book20_bid_proxy_usdt=1719544, book20_ask_proxy_usdt=2465425, funding_indicative=0.000004, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.78%, turnover=95548519. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
