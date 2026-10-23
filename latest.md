# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T14:00:34Z**
- feed_generated_utc: 2026-10-23T14:00:37+00:00
- source_sha256: `aecb30ff3d6af75f2c0d277ed9b2a1a1e9e734f1b23d2b32bc1a8551f05ba8fb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T14:00+00:00, close=81969.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T14:00+00:00, close=81969.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-23T12:00+00:00, close=81696.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|MAGMA_USDT|0.419120|-16.51|77.25|-16.90|6372590|5.73|
|LIT_USDT|3.365800|-6.87|8.87|-7.26|8779092|0.30|
|QNT_USDT|182.280000|-4.42|-12.32|-4.81|57892552|0.55|
|TIA_USDT|0.548700|-3.46|-8.92|-3.85|25009054|1.82|
|STRK_USDT|0.052850|-2.77|-45.15|-3.16|12249452|1.89|
|SILVER_USDT|54.180000|-1.95|-5.18|-2.34|347512946|1.85|
|OP_USDT|0.118500|-1.12|-14.66|-1.51|6386889|1.69|
|PUMPFUN_USDT|0.004640|-0.83|2.51|-1.22|39859296|2.15|
|XAU_USDT|4031.120000|-0.70|-3.00|-1.09|599943314|0.03|
|XAUT_USDT|4025.560000|-0.70|-2.88|-1.09|234073430|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|LIT_USDT|3.365800|3.317600|3.365800|1.19|N|Y/Y|Y/Y|Y|N|
|MAGMA_USDT|0.419120|0.419990|0.419120|1.08|N|Y/Y|N/N|Y|N|
|OP_USDT|0.118500|0.117120|0.118500|1.29|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004640|0.004564|0.004644|0.55|N|N/Y|Y/Y|Y|N|
|QNT_USDT|182.280000|180.210000|182.220000|0.59|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|54.180000|53.830000|54.180000|5.74|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052850|0.051660|0.052850|0.98|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.548700|0.543400|0.548700|0.68|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4025.560000|4024.150000|4025.090000|3.69|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4031.120000|4030.250000|4031.120000|1.96|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- LIT_USDT: quote_utc=2026-10-23T13:59:59+00:00, last15m_closed_end=2026-10-23T14:00+00:00, prior8high=3.406000, depth_time=2026-10-23T14:00:10+00:00, book20_bid_proxy_usdt=17158, book20_ask_proxy_usdt=26516, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.87%, turnover=8779092. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGMA_USDT: quote_utc=2026-10-23T13:59:59+00:00, last15m_closed_end=2026-10-23T14:00+00:00, prior8high=0.462420, depth_time=2026-10-23T14:00:09+00:00, book20_bid_proxy_usdt=6363, book20_ask_proxy_usdt=6835, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-16.51%, turnover=6372590. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T13:59:59+00:00, last15m_closed_end=2026-10-23T14:00+00:00, prior8high=0.118580, depth_time=2026-10-23T14:00:25+00:00, book20_bid_proxy_usdt=63398, book20_ask_proxy_usdt=82958, funding_indicative=-0.000001, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=6386889. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T13:59:59+00:00, last15m_closed_end=2026-10-23T14:00+00:00, prior8high=0.004674, depth_time=2026-10-23T14:00:28+00:00, book20_bid_proxy_usdt=1210699, book20_ask_proxy_usdt=1832827, funding_indicative=0.000014, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.83%, turnover=39859296. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T13:59:59+00:00, last15m_closed_end=2026-10-23T14:00+00:00, prior8high=183.550000, depth_time=2026-10-23T14:00:15+00:00, book20_bid_proxy_usdt=52275, book20_ask_proxy_usdt=62043, funding_indicative=-0.000185, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.42%, turnover=57892552. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T13:59:59+00:00, last15m_closed_end=2026-10-23T14:00+00:00, prior8high=54.150000, depth_time=2026-10-23T14:00:23+00:00, book20_bid_proxy_usdt=30788528, book20_ask_proxy_usdt=28775680, funding_indicative=0.000077, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.95%, turnover=347512946. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T13:59:59+00:00, last15m_closed_end=2026-10-23T14:00+00:00, prior8high=0.053770, depth_time=2026-10-23T14:00:20+00:00, book20_bid_proxy_usdt=665186, book20_ask_proxy_usdt=553634, funding_indicative=-0.000024, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.77%, turnover=12249452. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T13:59:59+00:00, last15m_closed_end=2026-10-23T14:00+00:00, prior8high=0.552300, depth_time=2026-10-23T14:00:17+00:00, book20_bid_proxy_usdt=308149, book20_ask_proxy_usdt=331069, funding_indicative=-0.000007, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.46%, turnover=25009054. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T13:59:59+00:00, last15m_closed_end=2026-10-23T14:00+00:00, prior8high=4035.760000, depth_time=2026-10-23T14:00:34+00:00, book20_bid_proxy_usdt=102233, book20_ask_proxy_usdt=104376, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.70%, turnover=234073430. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T13:59:59+00:00, last15m_closed_end=2026-10-23T14:00+00:00, prior8high=4042.750000, depth_time=2026-10-23T14:00:31+00:00, book20_bid_proxy_usdt=2841443, book20_ask_proxy_usdt=1242883, funding_indicative=0.000168, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.70%, turnover=599943314. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
