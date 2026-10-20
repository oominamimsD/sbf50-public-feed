# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T11:45:31Z**
- feed_generated_utc: 2026-10-20T11:45:34+00:00
- source_sha256: `c43730babedc1bb796044fbdac828ff95a1b4e7e4ca875d343fe7075db5046bf`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T11:45+00:00, close=81542.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T11:00+00:00, close=81518.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T08:00+00:00, close=81519.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.067400|-22.56|304.51|-22.11|9280873|0.15|
|NEAR_USDT|4.678000|-4.60|-15.69|-4.15|173785252|2.14|
|SAND_USDT|0.056740|-4.05|-8.61|-3.60|5372570|1.76|
|ARB_USDT|0.189380|-3.19|0.48|-2.74|97103941|0.53|
|ATOM_USDT|1.727000|-2.75|-5.52|-2.30|5066918|5.79|
|UNI_USDT|7.132000|-2.14|-3.85|-1.69|10107703|1.40|
|LTC_USDT|58.500000|-2.05|-7.08|-1.60|13148153|3.42|
|TAO_USDT|263.740000|-1.69|-7.87|-1.24|58068261|1.14|
|STRK_USDT|0.055730|-1.50|-38.53|-1.05|18629195|1.79|
|AVAX_USDT|9.420000|-1.48|-11.80|-1.03|142702910|1.06|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.067400|0.066520|0.067547|0.43|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.189380|0.188340|0.189380|1.54|N|Y/Y|N/N|Y|N|
|ATOM_USDT|1.727000|1.711000|1.727000|0.71|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.420000|9.384000|9.420000|0.94|N|Y/Y|Y/Y|Y|N|
|LTC_USDT|58.500000|58.460000|58.500000|4.60|N|Y/Y|Y/N|Y|N|
|NEAR_USDT|4.678000|4.630000|4.678000|3.17|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.056740|0.056320|0.056750|0.29|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.055730|0.055640|0.055730|1.82|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|263.740000|261.790000|263.750000|0.78|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.132000|7.093000|7.133000|1.01|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T11:45:01+00:00, last15m_closed_end=2026-10-20T11:45+00:00, prior8high=0.072028, depth_time=2026-10-20T11:45:08+00:00, book20_bid_proxy_usdt=5873, book20_ask_proxy_usdt=8185, funding_indicative=0.000077, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-22.56%, turnover=9280873. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T11:45:01+00:00, last15m_closed_end=2026-10-20T11:45+00:00, prior8high=0.190320, depth_time=2026-10-20T11:45:15+00:00, book20_bid_proxy_usdt=100666, book20_ask_proxy_usdt=52493, funding_indicative=0.000100, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.19%, turnover=97103941. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-10-20T11:45:01+00:00, last15m_closed_end=2026-10-20T11:45+00:00, prior8high=1.729000, depth_time=2026-10-20T11:45:18+00:00, book20_bid_proxy_usdt=1796903, book20_ask_proxy_usdt=1253500, funding_indicative=0.000084, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.75%, turnover=5066918. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-20T11:45:01+00:00, last15m_closed_end=2026-10-20T11:45+00:00, prior8high=9.452000, depth_time=2026-10-20T11:45:29+00:00, book20_bid_proxy_usdt=1307852, book20_ask_proxy_usdt=1131210, funding_indicative=-0.000003, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=142702910. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-20T11:45:01+00:00, last15m_closed_end=2026-10-20T11:45+00:00, prior8high=59.150000, depth_time=2026-10-20T11:45:22+00:00, book20_bid_proxy_usdt=1539100, book20_ask_proxy_usdt=1480122, funding_indicative=0.000100, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=13148153. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T11:45:01+00:00, last15m_closed_end=2026-10-20T11:45+00:00, prior8high=4.721000, depth_time=2026-10-20T11:45:10+00:00, book20_bid_proxy_usdt=2739312, book20_ask_proxy_usdt=1788956, funding_indicative=0.000066, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.60%, turnover=173785252. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T11:45:01+00:00, last15m_closed_end=2026-10-20T11:45+00:00, prior8high=0.057080, depth_time=2026-10-20T11:45:08+00:00, book20_bid_proxy_usdt=745485, book20_ask_proxy_usdt=894747, funding_indicative=-0.001857, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.05%, turnover=5372570. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-20T11:45:01+00:00, last15m_closed_end=2026-10-20T11:45+00:00, prior8high=0.056500, depth_time=2026-10-20T11:45:26+00:00, book20_bid_proxy_usdt=657830, book20_ask_proxy_usdt=607866, funding_indicative=0.000030, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.50%, turnover=18629195. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T11:45:01+00:00, last15m_closed_end=2026-10-20T11:45+00:00, prior8high=264.330000, depth_time=2026-10-20T11:45:25+00:00, book20_bid_proxy_usdt=156053, book20_ask_proxy_usdt=54817, funding_indicative=0.000042, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.69%, turnover=58068261. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T11:45:01+00:00, last15m_closed_end=2026-10-20T11:45+00:00, prior8high=7.169000, depth_time=2026-10-20T11:45:20+00:00, book20_bid_proxy_usdt=1894586, book20_ask_proxy_usdt=1887097, funding_indicative=0.000070, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.14%, turnover=10107703. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
