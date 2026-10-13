# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T06:30:33Z**
- feed_generated_utc: 2026-10-13T06:30:36+00:00
- source_sha256: `825d0d6855f2deb237177ded9e4e940c61605f032260acd1ad64542547b1f3a2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T06:30+00:00, close=83678.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T06:00+00:00, close=83646.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T04:00+00:00, close=83297.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOS_USDT|0.231300|-20.10|8.59|-21.30|9297968|4.32|
|W_USDT|0.019634|-18.39|38.82|-19.59|34360027|8.66|
|RSR_USDT|0.002112|-10.12|24.16|-11.32|17614840|9.47|
|ZRO_USDT|2.094300|-7.37|2.38|-8.57|29568275|0.48|
|LIT_USDT|3.459800|-4.56|-9.00|-5.76|10609158|0.29|
|STRK_USDT|0.086620|-4.46|66.22|-5.66|64148220|2.31|
|PUMPFUN_USDT|0.005103|-3.88|-19.44|-5.08|31428399|1.96|
|ICP_USDT|3.181000|-3.45|-8.22|-4.65|17078115|3.14|
|RLC_USDT|0.959900|-2.90|75.16|-4.10|6886499|1.04|
|HBAR_USDT|0.088140|-2.60|-12.47|-3.80|22208492|1.13|
|PONS_USDT|0.290100|-1.56|-24.35|-2.76|6299984|3.45|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.231300|0.227700|0.231300|0.84|N|Y/Y|Y/N|N|N|
|HBAR_USDT|0.088140|0.087470|0.088160|0.96|N|Y/Y|Y/Y|N|N|
|ICP_USDT|3.181000|3.155000|3.182000|0.31|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.459800|3.427200|3.460000|0.49|N|Y/Y|Y/Y|N|N|
|PONS_USDT|0.290100|0.281700|0.290200|0.98|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005103|0.005031|0.005104|0.41|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.959900|0.939400|0.959800|0.55|N|Y/Y|Y/Y|N|N|
|RSR_USDT|0.002112|0.002015|0.002110|0.15|N|Y/Y|N/N|N|N|
|STRK_USDT|0.086620|0.084670|0.086540|0.91|N|Y/Y|Y/Y|N|N|
|W_USDT|0.019634|0.019044|0.019634|1.09|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.094300|2.096100|2.094300|1.32|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T06:30:02+00:00, last15m_closed_end=2026-10-13T06:30+00:00, prior8high=0.251000, depth_time=2026-10-13T06:30:08+00:00, book20_bid_proxy_usdt=79503, book20_ask_proxy_usdt=60218, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-20.10%, turnover=9297968. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-13T06:30:03+00:00, last15m_closed_end=2026-10-13T06:30+00:00, prior8high=0.088580, depth_time=2026-10-13T06:30:30+00:00, book20_bid_proxy_usdt=366789, book20_ask_proxy_usdt=664839, funding_indicative=-0.000004, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.60%, turnover=22208492. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-13T06:30:03+00:00, last15m_closed_end=2026-10-13T06:30+00:00, prior8high=3.205000, depth_time=2026-10-13T06:30:24+00:00, book20_bid_proxy_usdt=707024, book20_ask_proxy_usdt=708434, funding_indicative=-0.000020, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.45%, turnover=17078115. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T06:30:03+00:00, last15m_closed_end=2026-10-13T06:30+00:00, prior8high=3.476600, depth_time=2026-10-13T06:30:18+00:00, book20_bid_proxy_usdt=18606, book20_ask_proxy_usdt=29652, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.56%, turnover=10609158. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-13T06:30:03+00:00, last15m_closed_end=2026-10-13T06:30+00:00, prior8high=0.291600, depth_time=2026-10-13T06:30:32+00:00, book20_bid_proxy_usdt=222742, book20_ask_proxy_usdt=180763, funding_indicative=0.000091, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.56%, turnover=6299984. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T06:30:03+00:00, last15m_closed_end=2026-10-13T06:30+00:00, prior8high=0.005113, depth_time=2026-10-13T06:30:22+00:00, book20_bid_proxy_usdt=1872704, book20_ask_proxy_usdt=1427860, funding_indicative=0.000035, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.88%, turnover=31428399. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T06:30:03+00:00, last15m_closed_end=2026-10-13T06:30+00:00, prior8high=0.964300, depth_time=2026-10-13T06:30:27+00:00, book20_bid_proxy_usdt=62100, book20_ask_proxy_usdt=49649, funding_indicative=-0.000594, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.90%, turnover=6886499. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RSR_USDT: quote_utc=2026-10-13T06:30:02+00:00, last15m_closed_end=2026-10-13T06:30+00:00, prior8high=0.002194, depth_time=2026-10-13T06:30:11+00:00, book20_bid_proxy_usdt=165782, book20_ask_proxy_usdt=241668, funding_indicative=-0.008456, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-10.12%, turnover=17614840. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T06:30:02+00:00, last15m_closed_end=2026-10-13T06:30+00:00, prior8high=0.089670, depth_time=2026-10-13T06:30:19+00:00, book20_bid_proxy_usdt=135672, book20_ask_proxy_usdt=177902, funding_indicative=0.000026, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.46%, turnover=64148220. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T06:30:02+00:00, last15m_closed_end=2026-10-13T06:30+00:00, prior8high=0.019641, depth_time=2026-10-13T06:30:11+00:00, book20_bid_proxy_usdt=11264, book20_ask_proxy_usdt=28500, funding_indicative=-0.000491, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-18.39%, turnover=34360027. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T06:30:03+00:00, last15m_closed_end=2026-10-13T06:30+00:00, prior8high=2.149200, depth_time=2026-10-13T06:30:16+00:00, book20_bid_proxy_usdt=28354, book20_ask_proxy_usdt=58722, funding_indicative=0.000028, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.37%, turnover=29568275. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
