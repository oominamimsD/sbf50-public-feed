# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T11:30:29Z**
- feed_generated_utc: 2026-10-20T11:30:31+00:00
- source_sha256: `977708d1c440f847fa5397cfc59900df0584904f8deae303d7a71f06bc70aa14`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T11:30+00:00, close=81440.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T11:00+00:00, close=81518.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T08:00+00:00, close=81519.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.068255|-21.58|309.64|-21.00|9239129|2.50|
|NEAR_USDT|4.669000|-4.79|-15.85|-4.21|170600269|4.28|
|SAND_USDT|0.056890|-3.80|-8.37|-3.22|5367847|1.76|
|ARB_USDT|0.189370|-3.19|0.47|-2.61|96279823|0.53|
|ATOM_USDT|1.724000|-2.92|-5.68|-2.34|5044821|5.80|
|UNI_USDT|7.127000|-2.20|-3.92|-1.62|10055741|1.40|
|TAO_USDT|262.920000|-2.00|-8.16|-1.42|57609470|1.14|
|LTC_USDT|58.560000|-1.95|-6.98|-1.37|12912321|3.42|
|AVAX_USDT|9.401000|-1.68|-11.98|-1.10|141424186|2.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.068255|0.066520|0.068255|0.38|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.189370|0.188610|0.189560|4.69|N|Y/Y|N/N|Y|N|
|ATOM_USDT|1.724000|1.711000|1.724000|0.17|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.401000|9.384000|9.401000|1.16|N|Y/Y|Y/Y|Y|N|
|LTC_USDT|58.560000|58.770000|58.560000|6.41|Y|Y/Y|Y/N|Y|N|
|NEAR_USDT|4.669000|4.654000|4.675000|4.66|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.056890|0.056320|0.056890|0.90|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|262.920000|261.790000|262.810000|0.97|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.127000|7.093000|7.127000|0.88|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T11:30:01+00:00, last15m_closed_end=2026-10-20T11:30+00:00, prior8high=0.072192, depth_time=2026-10-20T11:30:07+00:00, book20_bid_proxy_usdt=5923, book20_ask_proxy_usdt=8501, funding_indicative=0.000082, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-21.58%, turnover=9239129. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T11:30:01+00:00, last15m_closed_end=2026-10-20T11:30+00:00, prior8high=0.190520, depth_time=2026-10-20T11:30:15+00:00, book20_bid_proxy_usdt=62416, book20_ask_proxy_usdt=59867, funding_indicative=0.000100, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.19%, turnover=96279823. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-10-20T11:30:02+00:00, last15m_closed_end=2026-10-20T11:30+00:00, prior8high=1.729000, depth_time=2026-10-20T11:30:17+00:00, book20_bid_proxy_usdt=1556206, book20_ask_proxy_usdt=1604558, funding_indicative=0.000079, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.92%, turnover=5044821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-20T11:30:01+00:00, last15m_closed_end=2026-10-20T11:30+00:00, prior8high=9.461000, depth_time=2026-10-20T11:30:27+00:00, book20_bid_proxy_usdt=933584, book20_ask_proxy_usdt=1045300, funding_indicative=0.000000, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.68%, turnover=141424186. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-20T11:30:01+00:00, last15m_closed_end=2026-10-20T11:30+00:00, prior8high=59.200000, depth_time=2026-10-20T11:30:25+00:00, book20_bid_proxy_usdt=1261532, book20_ask_proxy_usdt=1160656, funding_indicative=0.000100, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.95%, turnover=12912321. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T11:30:01+00:00, last15m_closed_end=2026-10-20T11:30+00:00, prior8high=4.731000, depth_time=2026-10-20T11:30:11+00:00, book20_bid_proxy_usdt=3213352, book20_ask_proxy_usdt=3001865, funding_indicative=0.000071, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.79%, turnover=170600269. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T11:30:02+00:00, last15m_closed_end=2026-10-20T11:30+00:00, prior8high=0.056980, depth_time=2026-10-20T11:30:13+00:00, book20_bid_proxy_usdt=942560, book20_ask_proxy_usdt=990720, funding_indicative=-0.001826, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.80%, turnover=5367847. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T11:30:01+00:00, last15m_closed_end=2026-10-20T11:30+00:00, prior8high=264.330000, depth_time=2026-10-20T11:30:23+00:00, book20_bid_proxy_usdt=136610, book20_ask_proxy_usdt=164977, funding_indicative=0.000041, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.00%, turnover=57609470. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T11:30:02+00:00, last15m_closed_end=2026-10-20T11:30+00:00, prior8high=7.169000, depth_time=2026-10-20T11:30:21+00:00, book20_bid_proxy_usdt=1875679, book20_ask_proxy_usdt=1850194, funding_indicative=0.000074, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=10055741. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
