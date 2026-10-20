# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T10:30:30Z**
- feed_generated_utc: 2026-10-20T10:30:33+00:00
- source_sha256: `123227352d1327d8cedb3e0959ec57e718ef96f917b80da622115f53a6a6f819`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T10:30+00:00, close=81578.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T10:00+00:00, close=81450, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T08:00+00:00, close=81519.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.069707|-19.91|318.35|-19.50|9565293|1.29|
|Q_USDT|0.116150|-7.80|277.22|-7.39|6446076|1.98|
|NEAR_USDT|4.687000|-4.42|-15.53|-4.01|171364914|2.13|
|SAND_USDT|0.056650|-4.21|-8.76|-3.80|5548752|3.53|
|ATOM_USDT|1.717000|-3.32|-6.07|-2.91|5202137|5.82|
|ARB_USDT|0.189810|-2.97|0.71|-2.56|95988535|0.53|
|UNI_USDT|7.140000|-2.03|-3.74|-1.62|10299155|1.40|
|TAO_USDT|263.200000|-1.90|-8.06|-1.49|59822014|1.14|
|AVAX_USDT|9.419000|-1.49|-11.81|-1.08|143125270|1.06|
|SEI_USDT|0.059760|-1.49|-9.95|-1.08|6126069|1.67|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.069707|0.066550|0.069753|0.27|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.189810|0.188800|0.189810|0.63|N|Y/Y|N/N|Y|N|
|ATOM_USDT|1.717000|1.711000|1.718000|0.15|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.419000|9.402000|9.419000|0.76|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.687000|4.685000|4.687000|1.53|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.116150|0.115360|0.116490|0.41|N|Y/Y|N/N|Y|N|
|SAND_USDT|0.056650|0.056320|0.056650|0.56|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.059760|0.059410|0.059760|1.84|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|263.200000|261.790000|263.200000|1.29|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.140000|7.093000|7.141000|0.72|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T10:30:02+00:00, last15m_closed_end=2026-10-20T10:30+00:00, prior8high=0.075266, depth_time=2026-10-20T10:30:06+00:00, book20_bid_proxy_usdt=4663, book20_ask_proxy_usdt=7412, funding_indicative=0.000047, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-19.91%, turnover=9565293. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T10:30:02+00:00, last15m_closed_end=2026-10-20T10:30+00:00, prior8high=0.191210, depth_time=2026-10-20T10:30:20+00:00, book20_bid_proxy_usdt=59047, book20_ask_proxy_usdt=70274, funding_indicative=0.000097, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.97%, turnover=95988535. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-10-20T10:30:03+00:00, last15m_closed_end=2026-10-20T10:30+00:00, prior8high=1.737000, depth_time=2026-10-20T10:30:17+00:00, book20_bid_proxy_usdt=1477139, book20_ask_proxy_usdt=1102354, funding_indicative=0.000062, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.32%, turnover=5202137. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-20T10:30:02+00:00, last15m_closed_end=2026-10-20T10:30+00:00, prior8high=9.507000, depth_time=2026-10-20T10:30:27+00:00, book20_bid_proxy_usdt=1052873, book20_ask_proxy_usdt=1103403, funding_indicative=0.000006, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.49%, turnover=143125270. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T10:30:02+00:00, last15m_closed_end=2026-10-20T10:30+00:00, prior8high=4.761000, depth_time=2026-10-20T10:30:13+00:00, book20_bid_proxy_usdt=4772603, book20_ask_proxy_usdt=3634719, funding_indicative=0.000070, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.42%, turnover=171364914. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T10:30:02+00:00, last15m_closed_end=2026-10-20T10:30+00:00, prior8high=0.129136, depth_time=2026-10-20T10:30:11+00:00, book20_bid_proxy_usdt=18964, book20_ask_proxy_usdt=14585, funding_indicative=0.000021, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.80%, turnover=6446076. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T10:30:03+00:00, last15m_closed_end=2026-10-20T10:30+00:00, prior8high=0.056960, depth_time=2026-10-20T10:30:15+00:00, book20_bid_proxy_usdt=746503, book20_ask_proxy_usdt=820863, funding_indicative=-0.001653, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.21%, turnover=5548752. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-20T10:30:03+00:00, last15m_closed_end=2026-10-20T10:30+00:00, prior8high=0.060050, depth_time=2026-10-20T10:30:29+00:00, book20_bid_proxy_usdt=290472, book20_ask_proxy_usdt=207109, funding_indicative=-0.000011, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.49%, turnover=6126069. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T10:30:02+00:00, last15m_closed_end=2026-10-20T10:30+00:00, prior8high=264.140000, depth_time=2026-10-20T10:30:24+00:00, book20_bid_proxy_usdt=199344, book20_ask_proxy_usdt=49508, funding_indicative=0.000049, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.90%, turnover=59822014. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T10:30:03+00:00, last15m_closed_end=2026-10-20T10:30+00:00, prior8high=7.180000, depth_time=2026-10-20T10:30:21+00:00, book20_bid_proxy_usdt=1932496, book20_ask_proxy_usdt=2570431, funding_indicative=0.000077, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.03%, turnover=10299155. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
