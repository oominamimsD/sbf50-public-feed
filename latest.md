# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T05:45:28Z**
- feed_generated_utc: 2026-11-10T05:45:29+00:00
- source_sha256: `e949a208dac1b899e1d29389849a8062e5f07baf93ef446d6a9722f75b5011bf`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T05:45+00:00, close=74876.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T05:00+00:00, close=74754.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T04:00+00:00, close=74537.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002490|-49.15|-54.74|-48.33|15495126|4.02|
|JCT_USDT|0.007087|-30.04|64.16|-29.22|27336270|5.65|
|ARB_USDT|0.172070|-6.50|7.99|-5.68|33976575|0.58|
|ZEC_USDT|1160.240000|-5.34|-7.48|-4.52|2448976413|0.09|
|AAVE_USDT|127.270000|-4.55|-2.51|-3.73|13588938|0.79|
|QNT_USDT|191.290000|-4.37|-5.51|-3.55|36764300|0.52|
|DOT_USDT|0.854700|-4.06|-8.50|-3.24|10747811|1.17|
|DASH_USDT|46.040000|-3.31|-2.45|-2.49|14157572|2.17|
|PUMPFUN_USDT|0.003575|-2.90|-12.88|-2.08|7687304|2.80|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|127.270000|126.070000|127.270000|1.38|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.002490|0.002472|0.002484|0.43|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.172070|0.170290|0.172070|0.93|N|Y/Y|N/N|Y|N|
|DASH_USDT|46.040000|45.750000|46.040000|0.13|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.854700|0.846300|0.854700|0.75|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.007087|0.006725|0.007117|1.82|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003575|0.003556|0.003574|1.21|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|191.290000|190.450000|191.290000|0.37|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1160.240000|1142.950000|1160.360000|0.90|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T05:45:01+00:00, last15m_closed_end=2026-11-10T05:45+00:00, prior8high=129.250000, depth_time=2026-11-10T05:45:14+00:00, book20_bid_proxy_usdt=386922, book20_ask_proxy_usdt=367520, funding_indicative=0.000020, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.55%, turnover=13588938. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T05:45:01+00:00, last15m_closed_end=2026-11-10T05:45+00:00, prior8high=0.002790, depth_time=2026-11-10T05:45:07+00:00, book20_bid_proxy_usdt=59173, book20_ask_proxy_usdt=77627, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-49.15%, turnover=15495126. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T05:45:01+00:00, last15m_closed_end=2026-11-10T05:45+00:00, prior8high=0.172370, depth_time=2026-11-10T05:45:12+00:00, book20_bid_proxy_usdt=121247, book20_ask_proxy_usdt=110849, funding_indicative=-0.000007, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.50%, turnover=33976575. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T05:45:01+00:00, last15m_closed_end=2026-11-10T05:45+00:00, prior8high=46.350000, depth_time=2026-11-10T05:45:20+00:00, book20_bid_proxy_usdt=466706, book20_ask_proxy_usdt=809848, funding_indicative=0.000027, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.31%, turnover=14157572. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T05:45:01+00:00, last15m_closed_end=2026-11-10T05:45+00:00, prior8high=0.854900, depth_time=2026-11-10T05:45:20+00:00, book20_bid_proxy_usdt=367304, book20_ask_proxy_usdt=747901, funding_indicative=0.000027, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.06%, turnover=10747811. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T05:45:01+00:00, last15m_closed_end=2026-11-10T05:45+00:00, prior8high=0.008970, depth_time=2026-11-10T05:45:10+00:00, book20_bid_proxy_usdt=34694, book20_ask_proxy_usdt=23126, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-30.04%, turnover=27336270. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T05:45:01+00:00, last15m_closed_end=2026-11-10T05:45+00:00, prior8high=0.003602, depth_time=2026-11-10T05:45:27+00:00, book20_bid_proxy_usdt=2286372, book20_ask_proxy_usdt=3459966, funding_indicative=0.000006, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.90%, turnover=7687304. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T05:45:01+00:00, last15m_closed_end=2026-11-10T05:45+00:00, prior8high=193.230000, depth_time=2026-11-10T05:45:17+00:00, book20_bid_proxy_usdt=100625, book20_ask_proxy_usdt=75152, funding_indicative=-0.000125, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.37%, turnover=36764300. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T05:45:01+00:00, last15m_closed_end=2026-11-10T05:45+00:00, prior8high=1159.000000, depth_time=2026-11-10T05:45:14+00:00, book20_bid_proxy_usdt=586657, book20_ask_proxy_usdt=267080, funding_indicative=0.000077, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.34%, turnover=2448976413. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
