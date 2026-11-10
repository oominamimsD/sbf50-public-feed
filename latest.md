# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T06:15:29Z**
- feed_generated_utc: 2026-11-10T06:15:31+00:00
- source_sha256: `ea77c439d472a69387bbc92f4b31cc993e475ffa5315b3aecca95387632db4d5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T06:15+00:00, close=74609.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T06:00+00:00, close=74787.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T04:00+00:00, close=74537.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002486|-49.23|-54.81|-48.05|15273947|4.01|
|JCT_USDT|0.006892|-31.97|59.64|-30.79|25816507|8.71|
|ARB_USDT|0.171440|-6.84|7.60|-5.66|33908249|1.17|
|ZEC_USDT|1147.870000|-6.35|-8.47|-5.17|2400308499|0.09|
|AAVE_USDT|125.300000|-6.03|-4.02|-4.85|13098158|0.80|
|QNT_USDT|190.290000|-4.87|-6.00|-3.69|35168343|2.10|
|DOT_USDT|0.855200|-4.00|-8.44|-2.82|10412083|1.17|
|DASH_USDT|45.720000|-3.98|-3.13|-2.80|13754562|2.19|
|PUMPFUN_USDT|0.003561|-3.28|-13.23|-2.10|7538498|2.81|
|SOL_USDT|85.910000|-2.25|-8.12|-1.07|646256288|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|125.300000|126.070000|125.300000|4.27|Y|Y/Y|Y/N|Y|N|
|AKE_USDT|0.002486|0.002443|0.002486|0.13|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.171440|0.170290|0.171440|0.42|N|Y/Y|N/N|Y|N|
|DASH_USDT|45.720000|45.750000|45.710000|1.20|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.855200|0.846900|0.855300|0.26|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.006892|0.006725|0.006880|1.22|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003561|0.003562|0.003561|0.30|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|190.290000|190.450000|190.360000|0.95|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|85.910000|85.710000|85.910000|1.47|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1147.870000|1146.050000|1148.070000|1.07|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T06:15:02+00:00, last15m_closed_end=2026-11-10T06:15+00:00, prior8high=128.690000, depth_time=2026-11-10T06:15:17+00:00, book20_bid_proxy_usdt=578446, book20_ask_proxy_usdt=960693, funding_indicative=0.000023, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.03%, turnover=13098158. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T06:15:02+00:00, last15m_closed_end=2026-11-10T06:15+00:00, prior8high=0.002790, depth_time=2026-11-10T06:15:07+00:00, book20_bid_proxy_usdt=95742, book20_ask_proxy_usdt=47107, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-49.23%, turnover=15273947. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T06:15:02+00:00, last15m_closed_end=2026-11-10T06:15+00:00, prior8high=0.173110, depth_time=2026-11-10T06:15:11+00:00, book20_bid_proxy_usdt=166654, book20_ask_proxy_usdt=63734, funding_indicative=-0.000022, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.84%, turnover=33908249. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T06:15:02+00:00, last15m_closed_end=2026-11-10T06:15+00:00, prior8high=46.350000, depth_time=2026-11-10T06:15:23+00:00, book20_bid_proxy_usdt=909152, book20_ask_proxy_usdt=666793, funding_indicative=0.000032, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.98%, turnover=13754562. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T06:15:02+00:00, last15m_closed_end=2026-11-10T06:15+00:00, prior8high=0.858800, depth_time=2026-11-10T06:15:21+00:00, book20_bid_proxy_usdt=676240, book20_ask_proxy_usdt=589459, funding_indicative=0.000040, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.00%, turnover=10412083. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T06:15:02+00:00, last15m_closed_end=2026-11-10T06:15+00:00, prior8high=0.008970, depth_time=2026-11-10T06:15:10+00:00, book20_bid_proxy_usdt=20169, book20_ask_proxy_usdt=19262, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-31.97%, turnover=25816507. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T06:15:02+00:00, last15m_closed_end=2026-11-10T06:15+00:00, prior8high=0.003603, depth_time=2026-11-10T06:15:24+00:00, book20_bid_proxy_usdt=2736430, book20_ask_proxy_usdt=2958357, funding_indicative=0.000000, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.28%, turnover=7538498. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T06:15:02+00:00, last15m_closed_end=2026-11-10T06:15+00:00, prior8high=192.760000, depth_time=2026-11-10T06:15:18+00:00, book20_bid_proxy_usdt=81128, book20_ask_proxy_usdt=75329, funding_indicative=-0.000138, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.87%, turnover=35168343. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T06:15:02+00:00, last15m_closed_end=2026-11-10T06:15+00:00, prior8high=86.580000, depth_time=2026-11-10T06:15:29+00:00, book20_bid_proxy_usdt=17750252, book20_ask_proxy_usdt=17889552, funding_indicative=0.000030, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.25%, turnover=646256288. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T06:15:02+00:00, last15m_closed_end=2026-11-10T06:15+00:00, prior8high=1165.460000, depth_time=2026-11-10T06:15:14+00:00, book20_bid_proxy_usdt=291091, book20_ask_proxy_usdt=411766, funding_indicative=0.000076, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.35%, turnover=2400308499. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
