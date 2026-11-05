# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T05:00:33Z**
- feed_generated_utc: 2026-11-05T05:00:35+00:00
- source_sha256: `260cf3ce13fc5a75090fee2d9df84690c52490ba9d18ae80e7a67d2305ddbc60`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T05:00+00:00, close=80490.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T05:00+00:00, close=80490.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T04:00+00:00, close=80514.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRUMPOFFICIAL_USDT|1.256000|-11.79|-26.50|-12.06|26848781|7.98|
|IDOL_USDT|0.020798|-11.37|140.24|-11.64|5677337|8.65|
|CLANKER_USDT|16.850000|-9.45|26.12|-9.72|20347956|5.94|
|AKE_USDT|0.002545|-9.43|-87.33|-9.70|16659470|3.93|
|BTW_USDT|1.016500|-7.50|-41.51|-7.77|5820076|0.98|
|VVV_USDT|21.633000|-6.56|-9.16|-6.83|5347927|1.39|
|WLD_USDT|0.374100|-4.59|-13.56|-4.86|71112580|2.67|
|OP_USDT|0.110230|-3.47|-0.76|-3.74|10419469|1.81|
|PEPE_USDT|0.000005|-3.32|3.10|-3.59|140358453|0.20|
|HYPE_USDT|83.843000|-2.40|4.99|-2.67|85530854|0.12|
|ZRO_USDT|1.821700|-2.30|6.40|-2.57|10024667|0.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002545|0.002354|0.002544|0.72|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.016500|1.015700|1.016500|0.81|N|Y/Y|Y/Y|N|N|
|CLANKER_USDT|16.850000|16.230000|16.850000|0.35|N|Y/Y|N/N|N|N|
|HYPE_USDT|83.843000|83.085000|83.843000|0.73|N|Y/Y|Y/Y|N|N|
|IDOL_USDT|0.020798|0.020300|0.020798|1.05|N|Y/Y|N/N|N|N|
|OP_USDT|0.110230|0.109650|0.110230|1.05|N|Y/Y|Y/Y|N|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.41|N|Y/N|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.256000|1.247000|1.256000|0.46|N|Y/Y|Y/Y|N|N|
|VVV_USDT|21.633000|21.380000|21.633000|2.26|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.374100|0.372200|0.374100|0.82|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.821700|1.810200|1.821700|0.34|N|Y/Y|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T04:59:59+00:00, last15m_closed_end=2026-11-05T05:00+00:00, prior8high=0.002599, depth_time=2026-11-05T05:00:14+00:00, book20_bid_proxy_usdt=48626, book20_ask_proxy_usdt=38110, funding_indicative=-0.000537, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.43%, turnover=16659470. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-05T04:59:59+00:00, last15m_closed_end=2026-11-05T05:00+00:00, prior8high=1.061500, depth_time=2026-11-05T05:00:16+00:00, book20_bid_proxy_usdt=23491, book20_ask_proxy_usdt=33432, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.50%, turnover=5820076. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLANKER_USDT: quote_utc=2026-11-05T04:59:59+00:00, last15m_closed_end=2026-11-05T05:00+00:00, prior8high=17.050000, depth_time=2026-11-05T05:00:11+00:00, book20_bid_proxy_usdt=153946, book20_ask_proxy_usdt=179995, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.45%, turnover=20347956. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T04:59:59+00:00, last15m_closed_end=2026-11-05T05:00+00:00, prior8high=84.572000, depth_time=2026-11-05T05:00:30+00:00, book20_bid_proxy_usdt=58468, book20_ask_proxy_usdt=319338, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.40%, turnover=85530854. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-05T04:59:59+00:00, last15m_closed_end=2026-11-05T05:00+00:00, prior8high=0.021620, depth_time=2026-11-05T05:00:09+00:00, book20_bid_proxy_usdt=5229, book20_ask_proxy_usdt=11033, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.37%, turnover=5677337. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-05T04:59:59+00:00, last15m_closed_end=2026-11-05T05:00+00:00, prior8high=0.111820, depth_time=2026-11-05T05:00:25+00:00, book20_bid_proxy_usdt=111774, book20_ask_proxy_usdt=67494, funding_indicative=0.000052, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.47%, turnover=10419469. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-05T04:59:59+00:00, last15m_closed_end=2026-11-05T05:00+00:00, prior8high=0.000005, depth_time=2026-11-05T05:00:28+00:00, book20_bid_proxy_usdt=60727, book20_ask_proxy_usdt=60964, funding_indicative=0.000100, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.32%, turnover=140358453. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T04:59:59+00:00, last15m_closed_end=2026-11-05T05:00+00:00, prior8high=1.290000, depth_time=2026-11-05T05:00:05+00:00, book20_bid_proxy_usdt=1448473, book20_ask_proxy_usdt=1197058, funding_indicative=-0.000345, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.79%, turnover=26848781. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-05T04:59:59+00:00, last15m_closed_end=2026-11-05T05:00+00:00, prior8high=22.117000, depth_time=2026-11-05T05:00:19+00:00, book20_bid_proxy_usdt=35007, book20_ask_proxy_usdt=31288, funding_indicative=-0.000183, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.56%, turnover=5347927. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T04:59:59+00:00, last15m_closed_end=2026-11-05T05:00+00:00, prior8high=0.380500, depth_time=2026-11-05T05:00:22+00:00, book20_bid_proxy_usdt=3470600, book20_ask_proxy_usdt=2034450, funding_indicative=-0.000344, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.59%, turnover=71112580. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T04:59:59+00:00, last15m_closed_end=2026-11-05T05:00+00:00, prior8high=1.861000, depth_time=2026-11-05T05:00:29+00:00, book20_bid_proxy_usdt=92002, book20_ask_proxy_usdt=28807, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.30%, turnover=10024667. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
