# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T11:15:27Z**
- feed_generated_utc: 2026-10-20T11:15:30+00:00
- source_sha256: `66c3fb4db9299ba1f4906ee7b5a835d2c42b743875698e7505df99d6b6cfe189`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T11:15+00:00, close=81569.8, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T11:00+00:00, close=81518.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T08:00+00:00, close=81519.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.068290|-21.54|309.85|-21.12|9201444|2.93|
|NEAR_USDT|4.675000|-4.66|-15.75|-4.24|165942457|2.14|
|SAND_USDT|0.056900|-3.78|-8.35|-3.36|5351356|3.51|
|ARB_USDT|0.189300|-3.23|0.44|-2.81|94062150|0.53|
|ATOM_USDT|1.727000|-2.75|-5.52|-2.33|5039629|5.79|
|TAO_USDT|263.560000|-1.76|-7.93|-1.34|57034796|1.14|
|UNI_USDT|7.163000|-1.71|-3.43|-1.29|9999674|1.40|
|AVAX_USDT|9.420000|-1.48|-11.80|-1.06|139848096|1.06|
|LTC_USDT|58.850000|-1.47|-6.52|-1.05|12584299|1.70|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.068290|0.066732|0.068297|0.87|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.189300|0.188610|0.189280|0.74|N|Y/Y|N/N|Y|N|
|ATOM_USDT|1.727000|1.711000|1.726000|0.22|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.420000|9.384000|9.420000|0.99|N|Y/Y|Y/Y|Y|N|
|LTC_USDT|58.850000|58.850000|58.880000|4.02|N|Y/Y|Y/N|Y|N|
|NEAR_USDT|4.675000|4.654000|4.675000|1.17|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.056900|0.056320|0.056900|0.84|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|263.560000|261.790000|263.640000|0.85|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.163000|7.093000|7.162000|2.05|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T11:15:03+00:00, last15m_closed_end=2026-10-20T11:15+00:00, prior8high=0.072535, depth_time=2026-10-20T11:15:08+00:00, book20_bid_proxy_usdt=7420, book20_ask_proxy_usdt=6994, funding_indicative=0.000062, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-21.54%, turnover=9201444. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T11:15:03+00:00, last15m_closed_end=2026-10-20T11:15+00:00, prior8high=0.190590, depth_time=2026-10-20T11:15:15+00:00, book20_bid_proxy_usdt=58897, book20_ask_proxy_usdt=60358, funding_indicative=0.000100, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.23%, turnover=94062150. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-10-20T11:15:03+00:00, last15m_closed_end=2026-10-20T11:15+00:00, prior8high=1.731000, depth_time=2026-10-20T11:15:15+00:00, book20_bid_proxy_usdt=1455849, book20_ask_proxy_usdt=1618999, funding_indicative=0.000074, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.75%, turnover=5039629. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-20T11:15:03+00:00, last15m_closed_end=2026-10-20T11:15+00:00, prior8high=9.469000, depth_time=2026-10-20T11:15:24+00:00, book20_bid_proxy_usdt=1194310, book20_ask_proxy_usdt=994857, funding_indicative=0.000002, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=139848096. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-20T11:15:03+00:00, last15m_closed_end=2026-10-20T11:15+00:00, prior8high=59.200000, depth_time=2026-10-20T11:15:27+00:00, book20_bid_proxy_usdt=868410, book20_ask_proxy_usdt=817245, funding_indicative=0.000100, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=12584299. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T11:15:03+00:00, last15m_closed_end=2026-10-20T11:15+00:00, prior8high=4.756000, depth_time=2026-10-20T11:15:10+00:00, book20_bid_proxy_usdt=4327308, book20_ask_proxy_usdt=1999409, funding_indicative=0.000075, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.66%, turnover=165942457. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T11:15:04+00:00, last15m_closed_end=2026-10-20T11:15+00:00, prior8high=0.056980, depth_time=2026-10-20T11:15:11+00:00, book20_bid_proxy_usdt=894934, book20_ask_proxy_usdt=1246412, funding_indicative=-0.001763, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.78%, turnover=5351356. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T11:15:03+00:00, last15m_closed_end=2026-10-20T11:15+00:00, prior8high=263.930000, depth_time=2026-10-20T11:15:19+00:00, book20_bid_proxy_usdt=105332, book20_ask_proxy_usdt=105012, funding_indicative=0.000044, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.76%, turnover=57034796. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T11:15:03+00:00, last15m_closed_end=2026-10-20T11:15+00:00, prior8high=7.157000, depth_time=2026-10-20T11:15:20+00:00, book20_bid_proxy_usdt=1289004, book20_ask_proxy_usdt=2120541, funding_indicative=0.000080, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=9999674. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
