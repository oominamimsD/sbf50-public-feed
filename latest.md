# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T04:00:33Z**
- feed_generated_utc: 2026-10-23T04:00:35+00:00
- source_sha256: `20e78ae32bb3967501c878ae899035197f7d00c536babc771551e66663b6ad4c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T04:00+00:00, close=81863.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T04:00+00:00, close=81863.9, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T04:00+00:00, close=81863.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004192|-16.32|111.18|-16.58|9035325|7.15|
|LIT_USDT|3.488700|-4.16|12.85|-4.42|10490018|0.29|
|STRK_USDT|0.053220|-3.13|-44.76|-3.39|11796136|1.88|
|SILVER_USDT|54.020000|-2.24|-5.46|-2.50|350961291|1.85|
|TIA_USDT|0.563600|-2.10|-6.45|-2.36|22733938|3.55|
|QNT_USDT|189.330000|-1.85|-8.93|-2.11|51842391|0.53|
|XMR_USDT|611.000000|-1.53|12.32|-1.79|26484796|0.16|
|PUMPFUN_USDT|0.004647|-1.14|2.67|-1.40|38465990|2.15|
|XAU_USDT|4024.380000|-1.05|-3.16|-1.31|728353466|0.03|
|XAUT_USDT|4022.860000|-0.96|-2.94|-1.22|277434915|0.07|
|XPT_USDT|1574.290000|-0.74|-2.86|-1.00|5002294|0.19|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.004192|0.004170|0.004192|2.76|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.488700|3.420300|3.488700|1.00|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004647|0.004596|0.004647|0.17|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|189.330000|188.320000|189.330000|0.98|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|54.020000|53.570000|54.030000|0.76|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.053220|0.052540|0.053220|0.96|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.563600|0.558400|0.563600|0.50|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4022.860000|3994.260000|4022.860000|0.41|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4024.380000|3989.000000|4024.380000|0.36|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|611.000000|607.030000|611.000000|0.68|N|Y/Y|N/Y|Y|N|
|XPT_USDT|1574.290000|1559.300000|1574.290000|13.46|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-10-23T04:00:01+00:00, last15m_closed_end=2026-10-23T04:00+00:00, prior8high=0.004440, depth_time=2026-10-23T04:00:08+00:00, book20_bid_proxy_usdt=31903, book20_ask_proxy_usdt=27707, funding_indicative=0.000052, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.32%, turnover=9035325. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T04:00:02+00:00, last15m_closed_end=2026-10-23T04:00+00:00, prior8high=3.544400, depth_time=2026-10-23T04:00:10+00:00, book20_bid_proxy_usdt=20690, book20_ask_proxy_usdt=25250, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.16%, turnover=10490018. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T04:00:02+00:00, last15m_closed_end=2026-10-23T04:00+00:00, prior8high=0.004691, depth_time=2026-10-23T04:00:25+00:00, book20_bid_proxy_usdt=2070066, book20_ask_proxy_usdt=1058099, funding_indicative=0.000013, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.14%, turnover=38465990. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T04:00:02+00:00, last15m_closed_end=2026-10-23T04:00+00:00, prior8high=191.220000, depth_time=2026-10-23T04:00:20+00:00, book20_bid_proxy_usdt=47466, book20_ask_proxy_usdt=73835, funding_indicative=-0.000152, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=51842391. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T04:00:01+00:00, last15m_closed_end=2026-10-23T04:00+00:00, prior8high=54.440000, depth_time=2026-10-23T04:00:15+00:00, book20_bid_proxy_usdt=29783205, book20_ask_proxy_usdt=37740648, funding_indicative=0.000092, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.24%, turnover=350961291. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T04:00:02+00:00, last15m_closed_end=2026-10-23T04:00+00:00, prior8high=0.053500, depth_time=2026-10-23T04:00:12+00:00, book20_bid_proxy_usdt=698893, book20_ask_proxy_usdt=563073, funding_indicative=0.000016, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.13%, turnover=11796136. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T04:00:02+00:00, last15m_closed_end=2026-10-23T04:00+00:00, prior8high=0.567500, depth_time=2026-10-23T04:00:18+00:00, book20_bid_proxy_usdt=304305, book20_ask_proxy_usdt=242719, funding_indicative=0.000002, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.10%, turnover=22733938. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T04:00:01+00:00, last15m_closed_end=2026-10-23T04:00+00:00, prior8high=4030.690000, depth_time=2026-10-23T04:00:30+00:00, book20_bid_proxy_usdt=110734, book20_ask_proxy_usdt=486018, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.96%, turnover=277434915. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T04:00:01+00:00, last15m_closed_end=2026-10-23T04:00+00:00, prior8high=4032.600000, depth_time=2026-10-23T04:00:27+00:00, book20_bid_proxy_usdt=135271, book20_ask_proxy_usdt=1940602, funding_indicative=0.000081, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.05%, turnover=728353466. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-23T04:00:01+00:00, last15m_closed_end=2026-10-23T04:00+00:00, prior8high=615.760000, depth_time=2026-10-23T04:00:22+00:00, book20_bid_proxy_usdt=26119, book20_ask_proxy_usdt=12141, funding_indicative=0.000100, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=26484796. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPT_USDT: quote_utc=2026-10-23T04:00:02+00:00, last15m_closed_end=2026-10-23T04:00+00:00, prior8high=1580.400000, depth_time=2026-10-23T04:00:30+00:00, book20_bid_proxy_usdt=378194, book20_ask_proxy_usdt=98169, funding_indicative=0.000000, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.74%, turnover=5002294. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
