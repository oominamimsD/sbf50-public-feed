# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T21:45:38Z**
- feed_generated_utc: 2026-11-10T21:45:39+00:00
- source_sha256: `56827dcd677af8c5701abf31fe74a5942c9d9ec0a5d882ba5b9dc66d2d673a34`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T21:45+00:00, close=73837.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T21:00+00:00, close=73756.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T20:00+00:00, close=73437.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.213190|-15.04|58.52|-15.92|48755954|4.22|
|PIEVERSE_USDT|1.838500|-9.25|56.41|-10.13|6152204|2.72|
|DASH_USDT|43.200000|-4.29|-6.37|-5.17|13842872|2.31|
|AKE_USDT|0.002803|-3.80|-32.55|-4.68|15799993|3.57|
|ZEC_USDT|1061.510000|-2.91|-11.82|-3.79|2288281079|0.09|
|UNI_USDT|6.712000|-1.72|-8.71|-2.60|30357277|2.98|
|ARB_USDT|0.158610|-1.71|-0.79|-2.59|34570825|0.63|
|ANTHROPIC_USDT|1304.050000|-1.02|-22.09|-1.90|8425044|3.37|
|JUP_USDT|0.250900|-0.90|0.72|-1.78|5557763|3.99|
|DOT_USDT|0.838900|-0.33|-11.00|-1.21|8998198|3.58|
|XAU_USDT|4037.810000|-0.28|2.35|-1.16|521100819|0.03|
|XAUT_USDT|4020.570000|-0.21|2.31|-1.09|113598493|0.07|
|WLD_USDT|0.307500|-0.19|-17.36|-1.07|29558463|3.25|
|PEPE_USDT|0.000005|-0.16|7.15|-1.04|72352943|0.38|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002803|0.002755|0.002803|0.32|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1304.050000|1292.100000|1304.050000|6.70|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.158610|0.158120|0.158610|0.52|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.200000|42.550000|43.200000|0.98|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.838900|0.831500|0.838900|0.18|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.213190|0.202000|0.213170|0.69|N|Y/N|N/N|Y|N|
|JUP_USDT|0.250900|0.251600|0.250900|0.72|N|N/N|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.96|N|Y/N|N/N|Y|N|
|PIEVERSE_USDT|1.838500|1.782100|1.838500|0.37|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.712000|6.649000|6.712000|0.68|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.307500|0.304400|0.307500|0.25|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4020.570000|4015.640000|4020.570000|0.75|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4037.810000|4031.330000|4037.810000|1.42|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1061.510000|1020.790000|1061.510000|1.07|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T21:44:59+00:00, last15m_closed_end=2026-11-10T21:45+00:00, prior8high=0.002911, depth_time=2026-11-10T21:45:13+00:00, book20_bid_proxy_usdt=44854, book20_ask_proxy_usdt=49111, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.80%, turnover=15799993. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-10T21:44:59+00:00, last15m_closed_end=2026-11-10T21:45+00:00, prior8high=1308.680000, depth_time=2026-11-10T21:45:23+00:00, book20_bid_proxy_usdt=27523, book20_ask_proxy_usdt=23693, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.02%, turnover=8425044. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T21:44:59+00:00, last15m_closed_end=2026-11-10T21:45+00:00, prior8high=0.160720, depth_time=2026-11-10T21:45:20+00:00, book20_bid_proxy_usdt=66784, book20_ask_proxy_usdt=70979, funding_indicative=-0.000229, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=34570825. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T21:45:00+00:00, last15m_closed_end=2026-11-10T21:45+00:00, prior8high=43.110000, depth_time=2026-11-10T21:45:09+00:00, book20_bid_proxy_usdt=546921, book20_ask_proxy_usdt=758116, funding_indicative=-0.000199, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.29%, turnover=13842872. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T21:45:00+00:00, last15m_closed_end=2026-11-10T21:45+00:00, prior8high=0.842400, depth_time=2026-11-10T21:45:27+00:00, book20_bid_proxy_usdt=561961, book20_ask_proxy_usdt=485346, funding_indicative=0.000083, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.33%, turnover=8998198. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-10T21:44:59+00:00, last15m_closed_end=2026-11-10T21:45+00:00, prior8high=0.285840, depth_time=2026-11-10T21:45:07+00:00, book20_bid_proxy_usdt=7843, book20_ask_proxy_usdt=9581, funding_indicative=-0.020000, next_funding_utc=2026-11-10T22:00:00+00:00, funding_cycle_h=1, 24h_change=-15.04%, turnover=48755954. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-11-10T21:45:00+00:00, last15m_closed_end=2026-11-10T21:45+00:00, prior8high=0.257600, depth_time=2026-11-10T21:45:25+00:00, book20_bid_proxy_usdt=367947, book20_ask_proxy_usdt=492310, funding_indicative=-0.000027, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.90%, turnover=5557763. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-10T21:44:59+00:00, last15m_closed_end=2026-11-10T21:45+00:00, prior8high=0.000005, depth_time=2026-11-10T21:45:36+00:00, book20_bid_proxy_usdt=36010, book20_ask_proxy_usdt=34819, funding_indicative=0.000048, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.16%, turnover=72352943. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T21:44:59+00:00, last15m_closed_end=2026-11-10T21:45+00:00, prior8high=1.851500, depth_time=2026-11-10T21:45:08+00:00, book20_bid_proxy_usdt=17431, book20_ask_proxy_usdt=19905, funding_indicative=0.000156, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.25%, turnover=6152204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T21:45:00+00:00, last15m_closed_end=2026-11-10T21:45+00:00, prior8high=6.774000, depth_time=2026-11-10T21:45:18+00:00, book20_bid_proxy_usdt=1806590, book20_ask_proxy_usdt=2469953, funding_indicative=-0.000031, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=30357277. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-10T21:44:59+00:00, last15m_closed_end=2026-11-10T21:45+00:00, prior8high=0.310100, depth_time=2026-11-10T21:45:33+00:00, book20_bid_proxy_usdt=5457815, book20_ask_proxy_usdt=5771014, funding_indicative=-0.000022, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.19%, turnover=29558463. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-11-10T21:44:59+00:00, last15m_closed_end=2026-11-10T21:45+00:00, prior8high=4026.090000, depth_time=2026-11-10T21:45:29+00:00, book20_bid_proxy_usdt=160200, book20_ask_proxy_usdt=220239, funding_indicative=0.000080, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.21%, turnover=113598493. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-11-10T21:44:59+00:00, last15m_closed_end=2026-11-10T21:45+00:00, prior8high=4043.650000, depth_time=2026-11-10T21:45:29+00:00, book20_bid_proxy_usdt=618921, book20_ask_proxy_usdt=1267861, funding_indicative=0.000106, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.28%, turnover=521100819. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T21:44:59+00:00, last15m_closed_end=2026-11-10T21:45+00:00, prior8high=1062.220000, depth_time=2026-11-10T21:45:16+00:00, book20_bid_proxy_usdt=146514, book20_ask_proxy_usdt=129612, funding_indicative=0.000012, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=2288281079. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
