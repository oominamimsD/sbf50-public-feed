# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T07:30:26Z**
- feed_generated_utc: 2026-11-10T07:30:27+00:00
- source_sha256: `5803cb7bb70c04355397de63b915acdf9f63eaa737c65d8017429ac4cc918909`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T07:30+00:00, close=74776.4, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T07:00+00:00, close=74627.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T04:00+00:00, close=74537.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002529|-48.35|-54.03|-47.38|15370944|3.95|
|JCT_USDT|0.006214|-38.66|43.94|-37.69|25609956|1.61|
|ARB_USDT|0.168500|-8.44|5.75|-7.47|35956340|0.59|
|ZEC_USDT|1151.440000|-6.06|-8.18|-5.09|2380338868|0.09|
|QNT_USDT|191.150000|-4.44|-5.58|-3.47|34537341|1.05|
|AAVE_USDT|127.520000|-4.37|-2.32|-3.40|13155937|0.78|
|DASH_USDT|45.680000|-4.07|-3.22|-3.10|12336878|2.19|
|DOT_USDT|0.859500|-3.52|-7.98|-2.55|8790263|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|127.520000|125.050000|127.520000|0.82|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.002529|0.002443|0.002529|0.53|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.168500|0.167760|0.168500|2.12|N|Y/Y|N/N|Y|N|
|DASH_USDT|45.680000|45.630000|45.670000|1.40|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.859500|0.852000|0.859600|0.11|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.006214|0.006357|0.006197|1.22|N|Y/Y|N/N|Y|N|
|QNT_USDT|191.150000|189.670000|191.150000|0.86|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1151.440000|1144.770000|1151.520000|0.71|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T07:30:03+00:00, last15m_closed_end=2026-11-10T07:30+00:00, prior8high=127.600000, depth_time=2026-11-10T07:30:18+00:00, book20_bid_proxy_usdt=387613, book20_ask_proxy_usdt=437875, funding_indicative=0.000058, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.37%, turnover=13155937. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T07:30:03+00:00, last15m_closed_end=2026-11-10T07:30+00:00, prior8high=0.002556, depth_time=2026-11-10T07:30:06+00:00, book20_bid_proxy_usdt=43029, book20_ask_proxy_usdt=69393, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-48.35%, turnover=15370944. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T07:30:03+00:00, last15m_closed_end=2026-11-10T07:30+00:00, prior8high=0.173110, depth_time=2026-11-10T07:30:13+00:00, book20_bid_proxy_usdt=63705, book20_ask_proxy_usdt=94658, funding_indicative=-0.000046, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-8.44%, turnover=35956340. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T07:30:03+00:00, last15m_closed_end=2026-11-10T07:30+00:00, prior8high=46.200000, depth_time=2026-11-10T07:30:23+00:00, book20_bid_proxy_usdt=912970, book20_ask_proxy_usdt=667588, funding_indicative=0.000038, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.07%, turnover=12336878. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T07:30:03+00:00, last15m_closed_end=2026-11-10T07:30+00:00, prior8high=0.860700, depth_time=2026-11-10T07:30:25+00:00, book20_bid_proxy_usdt=690400, book20_ask_proxy_usdt=769081, funding_indicative=0.000006, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.52%, turnover=8790263. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T07:30:03+00:00, last15m_closed_end=2026-11-10T07:30+00:00, prior8high=0.007663, depth_time=2026-11-10T07:30:10+00:00, book20_bid_proxy_usdt=37365, book20_ask_proxy_usdt=44902, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-38.66%, turnover=25609956. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T07:30:03+00:00, last15m_closed_end=2026-11-10T07:30+00:00, prior8high=192.230000, depth_time=2026-11-10T07:30:16+00:00, book20_bid_proxy_usdt=46846, book20_ask_proxy_usdt=81135, funding_indicative=-0.000127, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.44%, turnover=34537341. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T07:30:03+00:00, last15m_closed_end=2026-11-10T07:30+00:00, prior8high=1165.460000, depth_time=2026-11-10T07:30:14+00:00, book20_bid_proxy_usdt=382635, book20_ask_proxy_usdt=183219, funding_indicative=0.000055, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.06%, turnover=2380338868. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
