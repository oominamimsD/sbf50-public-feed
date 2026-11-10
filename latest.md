# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T21:00:37Z**
- feed_generated_utc: 2026-11-10T21:00:38+00:00
- source_sha256: `35385ae751a40a91d9a2dc689cc5ac90e5df7df8c7ac20f0a2caa7279da942a6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T21:00+00:00, close=73756.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T21:00+00:00, close=73756.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T20:00+00:00, close=73437.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.809800|-10.67|53.97|-11.45|7080804|0.55|
|DASH_USDT|42.810000|-8.03|-7.21|-8.81|13295319|2.34|
|ZEC_USDT|1051.160000|-3.85|-12.68|-4.63|2345046112|0.10|
|AKE_USDT|0.002814|-3.43|-32.29|-4.21|15989636|3.56|
|VVV_USDT|19.296000|-2.62|-13.70|-3.40|5138236|0.52|
|UNI_USDT|6.680000|-2.19|-9.15|-2.97|29939198|1.50|
|ARB_USDT|0.159160|-1.37|-0.45|-2.15|34851025|1.26|
|ANTHROPIC_USDT|1299.930000|-1.33|-22.34|-2.11|8135558|0.23|
|DOT_USDT|0.836000|-0.67|-11.30|-1.45|8915658|1.20|
|ENA_USDT|0.148320|-0.58|-13.85|-1.36|30905749|0.67|
|ONDO_USDT|0.363800|-0.54|-6.52|-1.32|15127378|2.75|
|WLD_USDT|0.306700|-0.45|-17.57|-1.23|29945682|3.26|
|XAU_USDT|4038.190000|-0.27|2.35|-1.05|535362131|0.03|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002814|0.002791|0.002814|0.56|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1299.930000|1285.250000|1299.930000|0.07|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.159160|0.158120|0.159160|1.27|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|42.810000|42.550000|42.810000|0.45|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.836000|0.831500|0.836000|0.13|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.148320|0.147450|0.148510|0.70|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.363800|0.358400|0.363800|0.83|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.809800|1.782100|1.809800|1.07|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.680000|6.649000|6.680000|0.80|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.296000|19.012000|19.296000|0.96|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.306700|0.304400|0.306700|0.59|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4038.190000|4031.330000|4038.190000|0.66|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1051.160000|1020.790000|1051.160000|0.90|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T20:59:59+00:00, last15m_closed_end=2026-11-10T21:00+00:00, prior8high=0.002911, depth_time=2026-11-10T21:00:11+00:00, book20_bid_proxy_usdt=50168, book20_ask_proxy_usdt=42783, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.43%, turnover=15989636. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-10T20:59:59+00:00, last15m_closed_end=2026-11-10T21:00+00:00, prior8high=1303.870000, depth_time=2026-11-10T21:00:23+00:00, book20_bid_proxy_usdt=2967, book20_ask_proxy_usdt=4987, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.33%, turnover=8135558. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T20:59:59+00:00, last15m_closed_end=2026-11-10T21:00+00:00, prior8high=0.160720, depth_time=2026-11-10T21:00:21+00:00, book20_bid_proxy_usdt=52336, book20_ask_proxy_usdt=65902, funding_indicative=-0.000203, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.37%, turnover=34851025. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T21:00:00+00:00, last15m_closed_end=2026-11-10T21:00+00:00, prior8high=43.620000, depth_time=2026-11-10T21:00:09+00:00, book20_bid_proxy_usdt=741889, book20_ask_proxy_usdt=615487, funding_indicative=-0.000177, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-8.03%, turnover=13295319. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T20:59:59+00:00, last15m_closed_end=2026-11-10T21:00+00:00, prior8high=0.843100, depth_time=2026-11-10T21:00:25+00:00, book20_bid_proxy_usdt=429895, book20_ask_proxy_usdt=406625, funding_indicative=0.000016, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.67%, turnover=8915658. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-10T20:59:59+00:00, last15m_closed_end=2026-11-10T21:00+00:00, prior8high=0.150490, depth_time=2026-11-10T21:00:28+00:00, book20_bid_proxy_usdt=145681, book20_ask_proxy_usdt=177376, funding_indicative=0.000049, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.58%, turnover=30905749. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-10T20:59:59+00:00, last15m_closed_end=2026-11-10T21:00+00:00, prior8high=0.366300, depth_time=2026-11-10T21:00:30+00:00, book20_bid_proxy_usdt=2172398, book20_ask_proxy_usdt=2412501, funding_indicative=0.000000, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.54%, turnover=15127378. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T20:59:59+00:00, last15m_closed_end=2026-11-10T21:00+00:00, prior8high=1.864700, depth_time=2026-11-10T21:00:05+00:00, book20_bid_proxy_usdt=17767, book20_ask_proxy_usdt=10902, funding_indicative=0.000177, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.67%, turnover=7080804. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T20:59:59+00:00, last15m_closed_end=2026-11-10T21:00+00:00, prior8high=6.774000, depth_time=2026-11-10T21:00:15+00:00, book20_bid_proxy_usdt=1988938, book20_ask_proxy_usdt=3185554, funding_indicative=-0.000012, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.19%, turnover=29939198. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-10T21:00:00+00:00, last15m_closed_end=2026-11-10T21:00+00:00, prior8high=19.396000, depth_time=2026-11-10T21:00:16+00:00, book20_bid_proxy_usdt=18473, book20_ask_proxy_usdt=30321, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.62%, turnover=5138236. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-10T20:59:59+00:00, last15m_closed_end=2026-11-10T21:00+00:00, prior8high=0.310100, depth_time=2026-11-10T21:00:32+00:00, book20_bid_proxy_usdt=4826151, book20_ask_proxy_usdt=5758302, funding_indicative=-0.000001, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.45%, turnover=29945682. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-11-10T20:59:59+00:00, last15m_closed_end=2026-11-10T21:00+00:00, prior8high=4043.650000, depth_time=2026-11-10T21:00:36+00:00, book20_bid_proxy_usdt=2615230, book20_ask_proxy_usdt=1157752, funding_indicative=0.000095, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.27%, turnover=535362131. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T20:59:59+00:00, last15m_closed_end=2026-11-10T21:00+00:00, prior8high=1051.410000, depth_time=2026-11-10T21:00:12+00:00, book20_bid_proxy_usdt=78646, book20_ask_proxy_usdt=216930, funding_indicative=0.000020, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.85%, turnover=2345046112. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
