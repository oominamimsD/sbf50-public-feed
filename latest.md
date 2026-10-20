# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T07:00:32Z**
- feed_generated_utc: 2026-10-20T07:00:34+00:00
- source_sha256: `379e280527b376eddc884dee9bf9fe439433792489f3c0ff2affa61e690de3fc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T07:00+00:00, close=81779.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T07:00+00:00, close=81779.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T04:00+00:00, close=82099.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.078022|-10.36|368.26|-10.20|10997670|1.03|
|CT_USDT|0.308340|-7.51|-9.87|-7.35|5466413|6.17|
|SAND_USDT|0.057110|-4.11|-8.02|-3.95|7593417|1.75|
|Q_USDT|0.120838|-4.08|292.44|-3.92|7671769|2.07|
|NEAR_USDT|4.782000|-2.96|-13.82|-2.80|167998217|2.09|
|BTW_USDT|1.715400|-2.08|-2.30|-1.92|29889584|0.58|
|UNI_USDT|7.188000|-2.07|-3.10|-1.91|10034224|1.39|
|TAO_USDT|265.640000|-1.63|-7.21|-1.47|53586217|1.13|
|PUMPFUN_USDT|0.004414|-1.51|-16.85|-1.35|29749467|2.27|
|STRK_USDT|0.056560|-1.17|-37.61|-1.01|19759055|1.77|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.078022|0.082057|0.078198|3.01|Y|Y/Y|N/N|Y|N|
|BTW_USDT|1.715400|1.675200|1.720000|2.38|N|Y/Y|Y/Y|Y|N|
|CT_USDT|0.308340|0.301550|0.308340|0.38|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.782000|4.749000|4.782000|0.44|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004414|0.004365|0.004414|2.48|N|Y/Y|N/N|Y|N|
|Q_USDT|0.120838|0.110142|0.120692|0.96|N|Y/Y|N/N|Y|N|
|SAND_USDT|0.057110|0.056650|0.057110|0.48|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.056560|0.055750|0.056560|0.32|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|265.640000|263.780000|265.640000|1.10|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.188000|7.119000|7.188000|1.04|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T07:00:02+00:00, last15m_closed_end=2026-10-20T07:00+00:00, prior8high=0.090417, depth_time=2026-10-20T07:00:08+00:00, book20_bid_proxy_usdt=4652, book20_ask_proxy_usdt=9302, funding_indicative=0.000380, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.36%, turnover=10997670. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T07:00:03+00:00, last15m_closed_end=2026-10-20T07:00+00:00, prior8high=1.834800, depth_time=2026-10-20T07:00:21+00:00, book20_bid_proxy_usdt=14175, book20_ask_proxy_usdt=5816, funding_indicative=-0.003983, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.08%, turnover=29889584. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CT_USDT: quote_utc=2026-10-20T07:00:03+00:00, last15m_closed_end=2026-10-20T07:00+00:00, prior8high=0.312450, depth_time=2026-10-20T07:00:10+00:00, book20_bid_proxy_usdt=12704, book20_ask_proxy_usdt=11957, funding_indicative=-0.002499, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.51%, turnover=5466413. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T07:00:02+00:00, last15m_closed_end=2026-10-20T07:00+00:00, prior8high=4.830000, depth_time=2026-10-20T07:00:18+00:00, book20_bid_proxy_usdt=4534387, book20_ask_proxy_usdt=2837844, funding_indicative=-0.000007, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.96%, turnover=167998217. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-20T07:00:03+00:00, last15m_closed_end=2026-10-20T07:00+00:00, prior8high=0.004449, depth_time=2026-10-20T07:00:29+00:00, book20_bid_proxy_usdt=1169527, book20_ask_proxy_usdt=1338317, funding_indicative=0.000050, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.51%, turnover=29749467. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T07:00:02+00:00, last15m_closed_end=2026-10-20T07:00+00:00, prior8high=0.133766, depth_time=2026-10-20T07:00:15+00:00, book20_bid_proxy_usdt=14364, book20_ask_proxy_usdt=14662, funding_indicative=-0.000142, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.08%, turnover=7671769. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T07:00:03+00:00, last15m_closed_end=2026-10-20T07:00+00:00, prior8high=0.057530, depth_time=2026-10-20T07:00:09+00:00, book20_bid_proxy_usdt=775502, book20_ask_proxy_usdt=1170614, funding_indicative=-0.001578, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.11%, turnover=7593417. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-20T07:00:03+00:00, last15m_closed_end=2026-10-20T07:00+00:00, prior8high=0.057090, depth_time=2026-10-20T07:00:31+00:00, book20_bid_proxy_usdt=618594, book20_ask_proxy_usdt=752675, funding_indicative=0.000033, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.17%, turnover=19759055. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T07:00:03+00:00, last15m_closed_end=2026-10-20T07:00+00:00, prior8high=267.940000, depth_time=2026-10-20T07:00:26+00:00, book20_bid_proxy_usdt=124722, book20_ask_proxy_usdt=65500, funding_indicative=0.000042, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.63%, turnover=53586217. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T07:00:03+00:00, last15m_closed_end=2026-10-20T07:00+00:00, prior8high=7.305000, depth_time=2026-10-20T07:00:24+00:00, book20_bid_proxy_usdt=1997204, book20_ask_proxy_usdt=2408665, funding_indicative=0.000022, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.07%, turnover=10034224. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
