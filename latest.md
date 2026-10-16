# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T22:45:42Z**
- feed_generated_utc: 2026-10-16T22:45:44+00:00
- source_sha256: `1a2b78e00f61d5f908b8713ccc9c1613db7e61bed8cd5edacf1d9f347bb6aa8f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T22:45+00:00, close=81721.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T22:00+00:00, close=81648.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T20:00+00:00, close=81561.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.196310|-4.25|61.35|-4.74|18377901|0.51|
|ZEC_USDT|1143.170000|-3.77|-6.17|-4.26|1441204240|0.09|
|INJ_USDT|8.681000|-3.30|25.28|-3.79|117548591|1.15|
|RIVER_USDT|1.094000|-2.84|-7.44|-3.33|5697225|9.14|
|FILECOIN_USDT|1.134800|-2.74|6.05|-3.23|23343847|0.88|
|ZRO_USDT|2.045000|-2.67|0.40|-3.16|16057830|3.42|
|TAO_USDT|273.800000|-2.43|-0.31|-2.92|82386111|1.09|
|APT_USDT|0.835500|-2.40|4.37|-2.89|12438222|1.20|
|OP_USDT|0.136830|-2.26|11.04|-2.75|14780941|0.73|
|ARB_USDT|0.191280|-1.87|5.79|-2.36|32659415|0.52|
|AAVE_USDT|154.950000|-1.48|-8.76|-1.97|31930323|0.65|
|DOT_USDT|1.156700|-1.20|-2.63|-1.69|21926684|0.86|
|ICP_USDT|3.006000|-1.05|-0.43|-1.54|8849593|3.33|
|STRK_USDT|0.073180|-1.04|-2.82|-1.53|21929585|1.37|
|AVAX_USDT|9.983000|-0.99|-2.05|-1.48|128201002|1.00|
|ENA_USDT|0.198330|-0.80|-8.00|-1.29|40965334|0.50|
|HBAR_USDT|0.083510|-0.71|-8.08|-1.20|20869321|1.20|
|LTC_USDT|59.550000|-0.51|-6.36|-1.00|9917869|3.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.950000|153.830000|154.930000|1.17|N|Y/Y|Y/N|Y|N|
|APT_USDT|0.835500|0.833500|0.835500|0.17|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.191280|0.190740|0.191280|0.72|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.983000|9.920000|9.983000|0.32|N|Y/Y|Y/N|Y|N|
|BAT_USDT|0.196310|0.195230|0.196310|0.96|N|N/Y|N/N|Y|N|
|DOT_USDT|1.156700|1.145400|1.156700|0.59|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|1.134800|1.120000|1.134800|0.26|N|Y/Y|N/N|Y|N|
|ICP_USDT|3.006000|2.984000|3.006000|0.70|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.681000|8.469000|8.681000|0.60|N|Y/Y|N/N|Y|N|
|OP_USDT|0.136830|0.135200|0.136830|2.11|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.094000|1.082000|1.095000|0.24|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.073180|0.072170|0.073180|0.36|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|273.800000|270.100000|273.790000|0.16|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1143.170000|1134.590000|1142.940000|0.54|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|2.045000|2.027800|2.045000|0.64|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-16T22:45:01+00:00, last15m_closed_end=2026-10-16T22:45+00:00, prior8high=156.200000, depth_time=2026-10-16T22:45:30+00:00, book20_bid_proxy_usdt=283229, book20_ask_proxy_usdt=327295, funding_indicative=0.000066, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=31930323. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-16T22:45:01+00:00, last15m_closed_end=2026-10-16T22:45+00:00, prior8high=0.848000, depth_time=2026-10-16T22:45:23+00:00, book20_bid_proxy_usdt=156964, book20_ask_proxy_usdt=135568, funding_indicative=0.000059, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.40%, turnover=12438222. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-16T22:45:01+00:00, last15m_closed_end=2026-10-16T22:45+00:00, prior8high=0.193380, depth_time=2026-10-16T22:45:29+00:00, book20_bid_proxy_usdt=85053, book20_ask_proxy_usdt=67590, funding_indicative=-0.000103, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.87%, turnover=32659415. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-16T22:45:01+00:00, last15m_closed_end=2026-10-16T22:45+00:00, prior8high=10.024000, depth_time=2026-10-16T22:45:41+00:00, book20_bid_proxy_usdt=836279, book20_ask_proxy_usdt=631825, funding_indicative=-0.000005, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.99%, turnover=128201002. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-16T22:45:00+00:00, last15m_closed_end=2026-10-16T22:45+00:00, prior8high=0.202830, depth_time=2026-10-16T22:45:07+00:00, book20_bid_proxy_usdt=18410, book20_ask_proxy_usdt=32680, funding_indicative=-0.000106, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.25%, turnover=18377901. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-16T22:45:01+00:00, last15m_closed_end=2026-10-16T22:45+00:00, prior8high=1.162700, depth_time=2026-10-16T22:45:33+00:00, book20_bid_proxy_usdt=268828, book20_ask_proxy_usdt=351400, funding_indicative=0.000047, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=21926684. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-16T22:45:01+00:00, last15m_closed_end=2026-10-16T22:45+00:00, prior8high=1.143200, depth_time=2026-10-16T22:45:16+00:00, book20_bid_proxy_usdt=584981, book20_ask_proxy_usdt=353518, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.74%, turnover=23343847. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-16T22:45:01+00:00, last15m_closed_end=2026-10-16T22:45+00:00, prior8high=3.019000, depth_time=2026-10-16T22:45:36+00:00, book20_bid_proxy_usdt=943248, book20_ask_proxy_usdt=916140, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.05%, turnover=8849593. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-16T22:45:01+00:00, last15m_closed_end=2026-10-16T22:45+00:00, prior8high=8.696000, depth_time=2026-10-16T22:45:12+00:00, book20_bid_proxy_usdt=224689, book20_ask_proxy_usdt=247167, funding_indicative=-0.000073, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.30%, turnover=117548591. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-16T22:45:01+00:00, last15m_closed_end=2026-10-16T22:45+00:00, prior8high=0.137470, depth_time=2026-10-16T22:45:24+00:00, book20_bid_proxy_usdt=58841, book20_ask_proxy_usdt=45042, funding_indicative=0.000063, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=14780941. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-16T22:45:01+00:00, last15m_closed_end=2026-10-16T22:45+00:00, prior8high=1.112000, depth_time=2026-10-16T22:45:13+00:00, book20_bid_proxy_usdt=612166, book20_ask_proxy_usdt=274362, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.84%, turnover=5697225. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T22:45:01+00:00, last15m_closed_end=2026-10-16T22:45+00:00, prior8high=0.073820, depth_time=2026-10-16T22:45:39+00:00, book20_bid_proxy_usdt=312128, book20_ask_proxy_usdt=266003, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.04%, turnover=21929585. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-16T22:45:01+00:00, last15m_closed_end=2026-10-16T22:45+00:00, prior8high=275.700000, depth_time=2026-10-16T22:45:21+00:00, book20_bid_proxy_usdt=101143, book20_ask_proxy_usdt=122955, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.43%, turnover=82386111. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T22:45:00+00:00, last15m_closed_end=2026-10-16T22:45+00:00, prior8high=1153.300000, depth_time=2026-10-16T22:45:10+00:00, book20_bid_proxy_usdt=448654, book20_ask_proxy_usdt=157391, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.77%, turnover=1441204240. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-16T22:45:01+00:00, last15m_closed_end=2026-10-16T22:45+00:00, prior8high=2.113300, depth_time=2026-10-16T22:45:19+00:00, book20_bid_proxy_usdt=72559, book20_ask_proxy_usdt=62265, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.67%, turnover=16057830. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
