# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T09:45:32Z**
- feed_generated_utc: 2026-11-10T09:45:33+00:00
- source_sha256: `337c3c11d3d68bbda1850c16f91be6d76f39a7c8ea9822a9dae566e4214615c6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T09:45+00:00, close=74389.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T09:00+00:00, close=74699.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T08:00+00:00, close=74805.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002466|-49.64|-55.17|-48.19|15391284|4.06|
|JCT_USDT|0.005617|-44.55|30.11|-43.10|25479764|7.13|
|ARB_USDT|0.167670|-8.89|5.23|-7.44|37662193|0.60|
|ZEC_USDT|1142.910000|-6.75|-8.86|-5.30|2329104084|0.09|
|AAVE_USDT|125.710000|-5.72|-3.71|-4.27|12489308|0.80|
|QNT_USDT|188.920000|-5.55|-6.68|-4.10|33408203|0.53|
|DOT_USDT|0.852400|-4.32|-8.74|-2.87|8299221|1.17|
|PUMPFUN_USDT|0.003543|-3.77|-13.66|-2.32|7533973|2.82|
|DASH_USDT|46.190000|-3.00|-2.13|-1.55|10664023|4.33|
|SOL_USDT|85.460000|-2.76|-8.60|-1.31|639616952|1.17|
|INJ_USDT|7.953000|-2.73|13.46|-1.28|16362976|1.26|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|125.710000|124.500000|125.660000|0.74|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002466|0.002412|0.002466|1.03|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.167670|0.166250|0.167670|1.84|N|Y/Y|Y/N|Y|N|
|DASH_USDT|46.190000|45.390000|46.190000|2.04|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.852400|0.846200|0.852400|2.34|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.953000|7.862000|7.954000|1.44|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005617|0.005560|0.005647|1.74|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003543|0.003516|0.003542|8.77|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|188.920000|187.970000|188.960000|0.89|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|85.460000|84.880000|85.420000|0.33|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1142.910000|1134.630000|1141.740000|0.65|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T09:45:02+00:00, last15m_closed_end=2026-11-10T09:45+00:00, prior8high=127.890000, depth_time=2026-11-10T09:45:16+00:00, book20_bid_proxy_usdt=377134, book20_ask_proxy_usdt=386052, funding_indicative=0.000049, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.72%, turnover=12489308. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T09:45:02+00:00, last15m_closed_end=2026-11-10T09:45+00:00, prior8high=0.002555, depth_time=2026-11-10T09:45:07+00:00, book20_bid_proxy_usdt=71118, book20_ask_proxy_usdt=49635, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-49.64%, turnover=15391284. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T09:45:02+00:00, last15m_closed_end=2026-11-10T09:45+00:00, prior8high=0.169380, depth_time=2026-11-10T09:45:11+00:00, book20_bid_proxy_usdt=47970, book20_ask_proxy_usdt=61274, funding_indicative=-0.000147, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.89%, turnover=37662193. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T09:45:02+00:00, last15m_closed_end=2026-11-10T09:45+00:00, prior8high=46.310000, depth_time=2026-11-10T09:45:22+00:00, book20_bid_proxy_usdt=549381, book20_ask_proxy_usdt=596530, funding_indicative=0.000023, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.00%, turnover=10664023. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T09:45:02+00:00, last15m_closed_end=2026-11-10T09:45+00:00, prior8high=0.862700, depth_time=2026-11-10T09:45:21+00:00, book20_bid_proxy_usdt=481640, book20_ask_proxy_usdt=691529, funding_indicative=0.000001, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.32%, turnover=8299221. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-10T09:45:02+00:00, last15m_closed_end=2026-11-10T09:45+00:00, prior8high=8.177000, depth_time=2026-11-10T09:45:29+00:00, book20_bid_proxy_usdt=314414, book20_ask_proxy_usdt=246509, funding_indicative=0.000241, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.73%, turnover=16362976. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T09:45:02+00:00, last15m_closed_end=2026-11-10T09:45+00:00, prior8high=0.006657, depth_time=2026-11-10T09:45:10+00:00, book20_bid_proxy_usdt=19534, book20_ask_proxy_usdt=42108, funding_indicative=0.000158, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-44.55%, turnover=25479764. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T09:45:02+00:00, last15m_closed_end=2026-11-10T09:45+00:00, prior8high=0.003593, depth_time=2026-11-10T09:45:20+00:00, book20_bid_proxy_usdt=2705381, book20_ask_proxy_usdt=2899147, funding_indicative=0.000019, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.77%, turnover=7533973. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T09:45:02+00:00, last15m_closed_end=2026-11-10T09:45+00:00, prior8high=192.140000, depth_time=2026-11-10T09:45:18+00:00, book20_bid_proxy_usdt=73052, book20_ask_proxy_usdt=60885, funding_indicative=-0.000167, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.55%, turnover=33408203. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T09:45:02+00:00, last15m_closed_end=2026-11-10T09:45+00:00, prior8high=86.490000, depth_time=2026-11-10T09:45:29+00:00, book20_bid_proxy_usdt=17444176, book20_ask_proxy_usdt=19869756, funding_indicative=0.000096, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.76%, turnover=639616952. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T09:45:02+00:00, last15m_closed_end=2026-11-10T09:45+00:00, prior8high=1159.070000, depth_time=2026-11-10T09:45:14+00:00, book20_bid_proxy_usdt=212171, book20_ask_proxy_usdt=164457, funding_indicative=0.000060, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.75%, turnover=2329104084. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
