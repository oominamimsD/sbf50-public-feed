# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-22T01:30:40Z**
- feed_generated_utc: 2026-10-22T01:30:43+00:00
- source_sha256: `f27eb989b6150959df7a5440a3ca0a3b964cd1820a792d9d3af6ec32e98d949a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-22T01:30+00:00, close=84302.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-22T01:00+00:00, close=84159, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-22T00:00+00:00, close=84050, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IOST_USDT|0.000925|-36.80|15.60|-36.57|15265764|1.08|
|DOOD_USDT|0.002280|-19.83|60.78|-19.60|9043952|4.39|
|AKE_USDT|0.023298|-12.70|-9.98|-12.47|11013548|1.72|
|BR_USDT|0.474320|-12.41|16.32|-12.18|14456571|2.11|
|STRK_USDT|0.057880|-6.59|-25.00|-6.36|24179543|1.73|
|ZRO_USDT|1.970700|-6.03|4.05|-5.80|7429947|0.51|
|TIA_USDT|0.605900|-4.20|13.57|-3.97|38037953|3.30|
|AVAX_USDT|9.701000|-2.16|-1.18|-1.93|158911712|2.06|
|DOT_USDT|1.156100|-2.01|2.81|-1.78|17085547|0.86|
|HBAR_USDT|0.084260|-1.95|0.30|-1.72|13896236|1.19|
|ICP_USDT|2.908000|-1.95|-2.96|-1.72|5758188|3.44|
|FET_USDT|0.196800|-1.89|-3.48|-1.66|7768869|5.08|
|AAVE_USDT|155.650000|-1.80|-0.15|-1.57|132665157|0.64|
|INJ_USDT|8.600000|-1.80|12.58|-1.57|48647038|1.16|
|DOGE_USDT|0.082000|-1.73|0.02|-1.50|82605652|1.22|
|OP_USDT|0.129680|-1.68|-6.25|-1.45|6736880|0.77|
|LDO_USDT|0.408700|-1.56|0.71|-1.33|5178614|2.45|
|TAO_USDT|273.220000|-1.55|1.96|-1.32|60644916|1.10|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|155.650000|154.590000|155.650000|0.82|N|Y/Y|N/N|N|N|
|AKE_USDT|0.023298|0.023372|0.023298|0.35|N|Y/Y|Y/Y|N|N|
|AVAX_USDT|9.701000|9.630000|9.702000|0.81|N|Y/Y|Y/N|N|N|
|BR_USDT|0.474320|0.469940|0.474320|0.56|N|Y/Y|Y/Y|N|N|
|DOGE_USDT|0.082000|0.081690|0.082000|0.68|N|Y/Y|N/N|N|N|
|DOOD_USDT|0.002280|0.002157|0.002280|0.60|N|Y/Y|N/N|N|N|
|DOT_USDT|1.156100|1.139000|1.156100|0.33|N|Y/Y|Y/N|N|N|
|FET_USDT|0.196800|0.195000|0.196800|0.32|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084260|0.083560|0.084260|1.38|N|Y/Y|Y/N|N|N|
|ICP_USDT|2.908000|2.880000|2.909000|0.18|N|Y/Y|Y/N|N|N|
|INJ_USDT|8.600000|8.544000|8.600000|0.17|N|Y/Y|Y/Y|N|N|
|IOST_USDT|0.000925|0.000912|0.000925|0.43|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.057880|0.056630|0.057880|0.46|N|Y/Y|Y/N|N|N|
|TIA_USDT|0.605900|0.595900|0.605900|0.65|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.970700|1.935400|1.970700|1.54|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-22T01:30:01+00:00, last15m_closed_end=2026-10-22T01:30+00:00, prior8high=156.090000, depth_time=2026-10-22T01:30:34+00:00, book20_bid_proxy_usdt=339762, book20_ask_proxy_usdt=298067, funding_indicative=-0.000010, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.80%, turnover=132665157. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-22T01:30:01+00:00, last15m_closed_end=2026-10-22T01:30+00:00, prior8high=0.024607, depth_time=2026-10-22T01:30:11+00:00, book20_bid_proxy_usdt=15317, book20_ask_proxy_usdt=12954, funding_indicative=0.000050, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.70%, turnover=11013548. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-22T01:30:01+00:00, last15m_closed_end=2026-10-22T01:30+00:00, prior8high=9.717000, depth_time=2026-10-22T01:30:22+00:00, book20_bid_proxy_usdt=910204, book20_ask_proxy_usdt=932267, funding_indicative=-0.000023, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=158911712. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-22T01:30:01+00:00, last15m_closed_end=2026-10-22T01:30+00:00, prior8high=0.491340, depth_time=2026-10-22T01:30:14+00:00, book20_bid_proxy_usdt=3565, book20_ask_proxy_usdt=2424, funding_indicative=-0.000209, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.41%, turnover=14456571. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-10-22T01:30:01+00:00, last15m_closed_end=2026-10-22T01:30+00:00, prior8high=0.082150, depth_time=2026-10-22T01:30:39+00:00, book20_bid_proxy_usdt=3219156, book20_ask_proxy_usdt=3915439, funding_indicative=0.000015, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=82605652. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-22T01:30:00+00:00, last15m_closed_end=2026-10-22T01:30+00:00, prior8high=0.002454, depth_time=2026-10-22T01:30:09+00:00, book20_bid_proxy_usdt=175902, book20_ask_proxy_usdt=195885, funding_indicative=-0.000486, next_funding_utc=2026-10-22T02:00:00+00:00, funding_cycle_h=1, 24h_change=-19.83%, turnover=9043952. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-22T01:30:01+00:00, last15m_closed_end=2026-10-22T01:30+00:00, prior8high=1.159800, depth_time=2026-10-22T01:30:25+00:00, book20_bid_proxy_usdt=328051, book20_ask_proxy_usdt=242363, funding_indicative=-0.000148, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.01%, turnover=17085547. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-22T01:30:01+00:00, last15m_closed_end=2026-10-22T01:30+00:00, prior8high=0.197200, depth_time=2026-10-22T01:30:32+00:00, book20_bid_proxy_usdt=1677900, book20_ask_proxy_usdt=1175400, funding_indicative=0.000100, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.89%, turnover=7768869. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-22T01:30:01+00:00, last15m_closed_end=2026-10-22T01:30+00:00, prior8high=0.084510, depth_time=2026-10-22T01:30:27+00:00, book20_bid_proxy_usdt=1024032, book20_ask_proxy_usdt=895454, funding_indicative=-0.000013, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.95%, turnover=13896236. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-22T01:30:01+00:00, last15m_closed_end=2026-10-22T01:30+00:00, prior8high=2.917000, depth_time=2026-10-22T01:30:29+00:00, book20_bid_proxy_usdt=1101190, book20_ask_proxy_usdt=794200, funding_indicative=0.000062, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.95%, turnover=5758188. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-22T01:30:01+00:00, last15m_closed_end=2026-10-22T01:30+00:00, prior8high=8.661000, depth_time=2026-10-22T01:30:36+00:00, book20_bid_proxy_usdt=324563, book20_ask_proxy_usdt=166099, funding_indicative=0.000198, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.80%, turnover=48647038. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IOST_USDT: quote_utc=2026-10-22T01:30:00+00:00, last15m_closed_end=2026-10-22T01:30+00:00, prior8high=0.001188, depth_time=2026-10-22T01:30:06+00:00, book20_bid_proxy_usdt=10780, book20_ask_proxy_usdt=19400, funding_indicative=-0.003800, next_funding_utc=2026-10-22T02:00:00+00:00, funding_cycle_h=1, 24h_change=-36.80%, turnover=15265764. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-22T01:30:01+00:00, last15m_closed_end=2026-10-22T01:30+00:00, prior8high=0.058160, depth_time=2026-10-22T01:30:16+00:00, book20_bid_proxy_usdt=671871, book20_ask_proxy_usdt=612395, funding_indicative=-0.000014, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.59%, turnover=24179543. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-22T01:30:01+00:00, last15m_closed_end=2026-10-22T01:30+00:00, prior8high=0.609000, depth_time=2026-10-22T01:30:20+00:00, book20_bid_proxy_usdt=187311, book20_ask_proxy_usdt=576718, funding_indicative=-0.000149, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.20%, turnover=38037953. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-22T01:30:01+00:00, last15m_closed_end=2026-10-22T01:30+00:00, prior8high=1.979800, depth_time=2026-10-22T01:30:17+00:00, book20_bid_proxy_usdt=40173, book20_ask_proxy_usdt=32140, funding_indicative=0.000036, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.03%, turnover=7429947. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
