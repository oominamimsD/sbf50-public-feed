# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T10:00:33Z**
- feed_generated_utc: 2026-11-10T10:00:35+00:00
- source_sha256: `b79ace36413b86bbc1d2a1037117d07e69a26b6abfedc2c1652dfca1b6a9a376`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T10:00+00:00, close=74485, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T10:00+00:00, close=74485, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T08:00+00:00, close=74805.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.005589|-49.07|29.46|-47.73|24025820|1.80|
|AKE_USDT|0.002470|-48.01|-55.10|-46.67|14341721|4.05|
|ON_USDT|0.128700|-35.32|-24.07|-33.98|5648017|7.74|
|XMR_USDT|550.730000|-8.36|-9.01|-7.02|5010430|0.18|
|ARB_USDT|0.167450|-7.12|5.09|-5.78|36709548|0.60|
|ZEC_USDT|1143.450000|-6.71|-8.82|-5.37|2272587457|0.09|
|QNT_USDT|189.340000|-5.29|-6.47|-3.95|32349163|0.53|
|AAVE_USDT|125.570000|-5.24|-3.82|-3.90|11903759|0.80|
|DOT_USDT|0.852200|-3.79|-8.76|-2.45|7893365|1.17|
|PUMPFUN_USDT|0.003550|-3.45|-13.49|-2.11|7273276|2.82|
|INJ_USDT|7.953000|-2.73|13.46|-1.39|15367559|1.26|
|DASH_USDT|46.200000|-2.34|-2.11|-1.00|10112108|2.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|125.570000|124.500000|125.570000|0.83|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002470|0.002406|0.002470|1.22|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.167450|0.166250|0.167450|0.39|N|Y/Y|Y/N|Y|N|
|DASH_USDT|46.200000|45.390000|46.200000|0.79|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.852200|0.846200|0.852200|2.08|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.953000|7.862000|7.955000|0.47|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005589|0.005560|0.005589|1.35|N|Y/Y|Y/N|Y|N|
|ON_USDT|0.128700|0.149200|0.128700|2.73|Y|Y/Y|N/Y|Y|N|
|PUMPFUN_USDT|0.003550|0.003516|0.003550|1.76|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|189.340000|187.970000|189.340000|0.97|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|550.730000|551.210000|550.650000|12.54|Y|Y/Y|Y/Y|Y|Y|
|ZEC_USDT|1143.450000|1134.630000|1143.460000|0.81|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T10:00:01+00:00, last15m_closed_end=2026-11-10T10:00+00:00, prior8high=127.340000, depth_time=2026-11-10T10:00:21+00:00, book20_bid_proxy_usdt=375670, book20_ask_proxy_usdt=337223, funding_indicative=0.000045, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.24%, turnover=11903759. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T10:00:00+00:00, last15m_closed_end=2026-11-10T10:00+00:00, prior8high=0.002518, depth_time=2026-11-10T10:00:09+00:00, book20_bid_proxy_usdt=59441, book20_ask_proxy_usdt=69171, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-48.01%, turnover=14341721. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T10:00:00+00:00, last15m_closed_end=2026-11-10T10:00+00:00, prior8high=0.169380, depth_time=2026-11-10T10:00:15+00:00, book20_bid_proxy_usdt=49392, book20_ask_proxy_usdt=65617, funding_indicative=-0.000159, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.12%, turnover=36709548. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T10:00:01+00:00, last15m_closed_end=2026-11-10T10:00+00:00, prior8high=46.310000, depth_time=2026-11-10T10:00:30+00:00, book20_bid_proxy_usdt=759113, book20_ask_proxy_usdt=573722, funding_indicative=0.000015, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=10112108. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T10:00:01+00:00, last15m_closed_end=2026-11-10T10:00+00:00, prior8high=0.859200, depth_time=2026-11-10T10:00:24+00:00, book20_bid_proxy_usdt=351130, book20_ask_proxy_usdt=660486, funding_indicative=-0.000006, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.79%, turnover=7893365. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-10T10:00:00+00:00, last15m_closed_end=2026-11-10T10:00+00:00, prior8high=8.134000, depth_time=2026-11-10T10:00:28+00:00, book20_bid_proxy_usdt=178587, book20_ask_proxy_usdt=322224, funding_indicative=-0.000041, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.73%, turnover=15367559. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T10:00:00+00:00, last15m_closed_end=2026-11-10T10:00+00:00, prior8high=0.006657, depth_time=2026-11-10T10:00:07+00:00, book20_bid_proxy_usdt=27208, book20_ask_proxy_usdt=36185, funding_indicative=0.000184, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-49.07%, turnover=24025820. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ON_USDT: quote_utc=2026-11-10T10:00:00+00:00, last15m_closed_end=2026-11-10T10:00+00:00, prior8high=0.200900, depth_time=2026-11-10T10:00:11+00:00, book20_bid_proxy_usdt=56316, book20_ask_proxy_usdt=52261, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-35.32%, turnover=5648017. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T10:00:01+00:00, last15m_closed_end=2026-11-10T10:00+00:00, prior8high=0.003588, depth_time=2026-11-10T10:00:27+00:00, book20_bid_proxy_usdt=2566917, book20_ask_proxy_usdt=2728111, funding_indicative=0.000016, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.45%, turnover=7273276. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T10:00:01+00:00, last15m_closed_end=2026-11-10T10:00+00:00, prior8high=191.930000, depth_time=2026-11-10T10:00:20+00:00, book20_bid_proxy_usdt=78458, book20_ask_proxy_usdt=65846, funding_indicative=-0.000166, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.29%, turnover=32349163. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-10T10:00:01+00:00, last15m_closed_end=2026-11-10T10:00+00:00, prior8high=565.400000, depth_time=2026-11-10T10:00:14+00:00, book20_bid_proxy_usdt=13177, book20_ask_proxy_usdt=17198, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.36%, turnover=5010430. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T10:00:00+00:00, last15m_closed_end=2026-11-10T10:00+00:00, prior8high=1159.070000, depth_time=2026-11-10T10:00:18+00:00, book20_bid_proxy_usdt=333747, book20_ask_proxy_usdt=92217, funding_indicative=0.000066, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.71%, turnover=2272587457. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
