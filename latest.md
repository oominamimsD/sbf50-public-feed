# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T00:30:39Z**
- feed_generated_utc: 2026-11-04T00:30:41+00:00
- source_sha256: `ae075b19322a283431a190029eb810fc389e159ecd418866f254dd5bd4fed546`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T00:30+00:00, close=77204, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-04T00:00+00:00, close=77441.6, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T00:00+00:00, close=77441.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003878|-6.68|-81.64|-6.08|13611149|2.58|
|STRK_USDT|0.041980|-4.87|-8.97|-4.27|5301719|2.38|
|HYPE_USDT|83.633000|-4.25|5.25|-3.65|65960942|0.12|
|TRUMPOFFICIAL_USDT|1.543000|-4.04|-8.59|-3.44|6053345|6.48|
|XPL_USDT|0.062360|-2.63|-15.52|-2.03|7299495|1.60|
|XLM_USDT|0.160460|-2.62|-5.17|-2.02|34374299|0.62|
|QNT_USDT|190.560000|-2.48|-3.70|-1.88|59436085|1.05|
|TAO_USDT|222.340000|-2.27|-11.48|-1.67|32188262|1.35|
|OP_USDT|0.107950|-2.24|-3.02|-1.64|8981217|0.93|
|LINK_USDT|10.919000|-2.10|-4.64|-1.50|159271552|0.92|
|TIA_USDT|0.427200|-1.97|-20.31|-1.37|12768633|2.34|
|AAVE_USDT|126.190000|-1.75|-4.88|-1.15|20628333|0.79|
|SOL_USDT|92.090000|-1.73|-8.74|-1.13|470470415|1.09|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|126.190000|126.660000|126.190000|15.11|Y|Y/Y|Y/Y|Y|Y|
|AKE_USDT|0.003878|0.003887|0.003878|1.14|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|83.633000|84.824000|83.633000|4.64|Y|Y/N|Y/Y|Y|N|
|LINK_USDT|10.919000|10.988000|10.922000|3.61|Y|Y/Y|Y/Y|Y|Y|
|OP_USDT|0.107950|0.108900|0.107950|4.47|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|190.560000|191.930000|190.560000|1.89|Y|Y/Y|Y/Y|Y|Y|
|SOL_USDT|92.090000|92.550000|92.090000|4.44|Y|Y/N|Y/Y|Y|N|
|STRK_USDT|0.041980|0.042170|0.041980|3.95|Y|Y/N|Y/N|Y|N|
|TAO_USDT|222.340000|225.330000|222.340000|6.98|Y|Y/N|Y/Y|Y|N|
|TIA_USDT|0.427200|0.431800|0.427200|7.24|Y|Y/Y|Y/Y|Y|Y|
|TRUMPOFFICIAL_USDT|1.543000|1.580000|1.543000|12.67|Y|Y/Y|Y/Y|Y|Y|
|XLM_USDT|0.160460|0.161500|0.160470|9.64|Y|Y/Y|Y/Y|Y|Y|
|XPL_USDT|0.062360|0.062610|0.062360|8.06|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-04T00:30:01+00:00, last15m_closed_end=2026-11-04T00:30+00:00, prior8high=128.110000, depth_time=2026-11-04T00:30:33+00:00, book20_bid_proxy_usdt=247865, book20_ask_proxy_usdt=266644, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.75%, turnover=20628333. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T00:30:01+00:00, last15m_closed_end=2026-11-04T00:30+00:00, prior8high=0.004047, depth_time=2026-11-04T00:30:08+00:00, book20_bid_proxy_usdt=27051, book20_ask_proxy_usdt=45047, funding_indicative=-0.000858, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.68%, turnover=13611149. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-04T00:30:01+00:00, last15m_closed_end=2026-11-04T00:30+00:00, prior8high=85.946000, depth_time=2026-11-04T00:30:13+00:00, book20_bid_proxy_usdt=82561, book20_ask_proxy_usdt=53381, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.25%, turnover=65960942. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-04T00:30:01+00:00, last15m_closed_end=2026-11-04T00:30+00:00, prior8high=11.152000, depth_time=2026-11-04T00:30:29+00:00, book20_bid_proxy_usdt=381320, book20_ask_proxy_usdt=369412, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=159271552. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-04T00:30:01+00:00, last15m_closed_end=2026-11-04T00:30+00:00, prior8high=0.110510, depth_time=2026-11-04T00:30:28+00:00, book20_bid_proxy_usdt=58266, book20_ask_proxy_usdt=102151, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.24%, turnover=8981217. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-04T00:30:01+00:00, last15m_closed_end=2026-11-04T00:30+00:00, prior8high=193.800000, depth_time=2026-11-04T00:30:22+00:00, book20_bid_proxy_usdt=43924, book20_ask_proxy_usdt=61317, funding_indicative=0.000008, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.48%, turnover=59436085. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-04T00:30:01+00:00, last15m_closed_end=2026-11-04T00:30+00:00, prior8high=93.660000, depth_time=2026-11-04T00:30:38+00:00, book20_bid_proxy_usdt=13167281, book20_ask_proxy_usdt=13114939, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=470470415. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-11-04T00:30:01+00:00, last15m_closed_end=2026-11-04T00:30+00:00, prior8high=0.042890, depth_time=2026-11-04T00:30:11+00:00, book20_bid_proxy_usdt=295038, book20_ask_proxy_usdt=311297, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.87%, turnover=5301719. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-04T00:30:01+00:00, last15m_closed_end=2026-11-04T00:30+00:00, prior8high=227.970000, depth_time=2026-11-04T00:30:25+00:00, book20_bid_proxy_usdt=111225, book20_ask_proxy_usdt=389360, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.27%, turnover=32188262. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-04T00:30:01+00:00, last15m_closed_end=2026-11-04T00:30+00:00, prior8high=0.439200, depth_time=2026-11-04T00:30:32+00:00, book20_bid_proxy_usdt=256547, book20_ask_proxy_usdt=322658, funding_indicative=-0.000007, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.97%, turnover=12768633. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T00:30:01+00:00, last15m_closed_end=2026-11-04T00:30+00:00, prior8high=1.602000, depth_time=2026-11-04T00:30:15+00:00, book20_bid_proxy_usdt=1944579, book20_ask_proxy_usdt=1987652, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.04%, turnover=6053345. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-04T00:30:01+00:00, last15m_closed_end=2026-11-04T00:30+00:00, prior8high=0.163590, depth_time=2026-11-04T00:30:20+00:00, book20_bid_proxy_usdt=148262, book20_ask_proxy_usdt=152714, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.62%, turnover=34374299. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-04T00:30:01+00:00, last15m_closed_end=2026-11-04T00:30+00:00, prior8high=0.064550, depth_time=2026-11-04T00:30:17+00:00, book20_bid_proxy_usdt=367227, book20_ask_proxy_usdt=457470, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.63%, turnover=7299495. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
