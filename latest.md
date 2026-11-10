# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T08:15:33Z**
- feed_generated_utc: 2026-11-10T08:15:34+00:00
- source_sha256: `473f1fe3952c934ed83b930fdb4198c26951afd06d389ff4e09a7cc16e5a46ab`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T08:15+00:00, close=74760, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T08:00+00:00, close=74805.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T08:00+00:00, close=74805.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002466|-49.64|-55.17|-48.66|15275281|4.06|
|JCT_USDT|0.006100|-39.78|41.30|-38.80|24593088|1.64|
|ARB_USDT|0.166760|-9.38|4.66|-8.40|36595829|0.60|
|ZEC_USDT|1147.470000|-6.38|-8.50|-5.40|2319493182|0.09|
|AAVE_USDT|126.340000|-5.25|-3.23|-4.27|12688901|0.79|
|QNT_USDT|190.680000|-4.67|-5.81|-3.69|33101864|0.53|
|DASH_USDT|45.580000|-4.28|-3.43|-3.30|10822464|2.19|
|DOT_USDT|0.857000|-3.80|-8.25|-2.82|8413384|1.17|
|PUMPFUN_USDT|0.003568|-3.09|-13.06|-2.11|6902383|2.80|
|SOL_USDT|85.950000|-2.20|-8.08|-1.22|633067564|1.16|
|XRP_USDT|1.089500|-2.19|-12.72|-1.21|266714502|0.92|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|126.340000|125.050000|126.340000|4.23|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002466|0.002463|0.002467|0.60|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.166760|0.167240|0.166760|2.17|Y|Y/Y|Y/N|Y|N|
|DASH_USDT|45.580000|45.580000|45.580000|0.36|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.857000|0.853600|0.857000|1.00|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.006100|0.005560|0.006080|2.62|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003568|0.003555|0.003568|1.98|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|190.680000|189.670000|190.680000|1.22|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|85.950000|85.770000|85.950000|2.55|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.089500|1.094300|1.090000|1.97|Y|Y/Y|Y/Y|Y|Y|
|ZEC_USDT|1147.470000|1144.770000|1147.660000|0.80|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T08:15:03+00:00, last15m_closed_end=2026-11-10T08:15+00:00, prior8high=127.890000, depth_time=2026-11-10T08:15:17+00:00, book20_bid_proxy_usdt=454047, book20_ask_proxy_usdt=408664, funding_indicative=0.000065, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.25%, turnover=12688901. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T08:15:03+00:00, last15m_closed_end=2026-11-10T08:15+00:00, prior8high=0.002556, depth_time=2026-11-10T08:15:07+00:00, book20_bid_proxy_usdt=69002, book20_ask_proxy_usdt=67594, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-49.64%, turnover=15275281. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T08:15:03+00:00, last15m_closed_end=2026-11-10T08:15+00:00, prior8high=0.172460, depth_time=2026-11-10T08:15:09+00:00, book20_bid_proxy_usdt=53377, book20_ask_proxy_usdt=68435, funding_indicative=-0.000094, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.38%, turnover=36595829. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T08:15:03+00:00, last15m_closed_end=2026-11-10T08:15+00:00, prior8high=45.950000, depth_time=2026-11-10T08:15:21+00:00, book20_bid_proxy_usdt=841321, book20_ask_proxy_usdt=540049, funding_indicative=0.000033, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.28%, turnover=10822464. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T08:15:03+00:00, last15m_closed_end=2026-11-10T08:15+00:00, prior8high=0.862700, depth_time=2026-11-10T08:15:23+00:00, book20_bid_proxy_usdt=733938, book20_ask_proxy_usdt=532894, funding_indicative=-0.000042, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.80%, turnover=8413384. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T08:15:03+00:00, last15m_closed_end=2026-11-10T08:15+00:00, prior8high=0.007158, depth_time=2026-11-10T08:15:10+00:00, book20_bid_proxy_usdt=52596, book20_ask_proxy_usdt=28940, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-39.78%, turnover=24593088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T08:15:03+00:00, last15m_closed_end=2026-11-10T08:15+00:00, prior8high=0.003602, depth_time=2026-11-10T08:15:23+00:00, book20_bid_proxy_usdt=2903457, book20_ask_proxy_usdt=2910216, funding_indicative=0.000045, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.09%, turnover=6902383. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T08:15:03+00:00, last15m_closed_end=2026-11-10T08:15+00:00, prior8high=192.140000, depth_time=2026-11-10T08:15:19+00:00, book20_bid_proxy_usdt=98200, book20_ask_proxy_usdt=81445, funding_indicative=-0.000141, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.67%, turnover=33101864. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T08:15:03+00:00, last15m_closed_end=2026-11-10T08:15+00:00, prior8high=86.490000, depth_time=2026-11-10T08:15:29+00:00, book20_bid_proxy_usdt=17013748, book20_ask_proxy_usdt=18446811, funding_indicative=0.000087, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=633067564. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-10T08:15:03+00:00, last15m_closed_end=2026-11-10T08:15+00:00, prior8high=1.106100, depth_time=2026-11-10T08:15:31+00:00, book20_bid_proxy_usdt=4194616, book20_ask_proxy_usdt=5035372, funding_indicative=0.000090, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.19%, turnover=266714502. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T08:15:03+00:00, last15m_closed_end=2026-11-10T08:15+00:00, prior8high=1159.070000, depth_time=2026-11-10T08:15:14+00:00, book20_bid_proxy_usdt=226602, book20_ask_proxy_usdt=340348, funding_indicative=0.000048, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.38%, turnover=2319493182. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
