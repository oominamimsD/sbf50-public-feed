# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T04:00:33Z**
- feed_generated_utc: 2026-10-31T04:00:35+00:00
- source_sha256: `91849ecfe9991b3482193c488df3d878792370113a7336f7ee8a7bcfd0fb18ab`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T04:00+00:00, close=77131.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T04:00+00:00, close=77131.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T04:00+00:00, close=77131.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011434|-40.52|-67.32|-39.95|6388223|5.25|
|Q_USDT|0.029990|-36.83|-74.65|-36.26|21049049|3.33|
|BLESS_USDT|0.010544|-21.92|29.19|-21.35|12733630|6.67|
|BEAT_USDT|0.099830|-5.58|37.52|-5.01|8634656|4.02|
|LIT_USDT|2.748400|-4.03|-17.31|-3.46|5524885|0.36|
|HYPE_USDT|89.389000|-3.19|14.01|-2.62|111052757|0.11|
|PEPE_USDT|0.000005|-3.11|0.86|-2.54|137493845|2.04|
|TRX_USDT|0.326980|-2.80|-0.71|-2.23|7199430|1.22|
|BTW_USDT|1.189400|-2.29|-30.13|-1.72|9586244|1.68|
|DASH_USDT|48.380000|-1.60|-10.15|-1.03|16013813|2.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011434|0.011264|0.011434|0.33|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.099830|0.096210|0.099830|0.55|N|Y/Y|N/N|Y|N|
|BLESS_USDT|0.010544|0.009190|0.010545|1.61|N|N/Y|Y/Y|Y|N|
|BTW_USDT|1.189400|1.114700|1.189400|1.09|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.380000|48.370000|48.380000|0.34|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|89.389000|89.256000|89.371000|0.84|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.748400|2.749000|2.748400|0.45|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.53|N|Y/Y|N/N|Y|N|
|Q_USDT|0.029990|0.026260|0.030760|3.37|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.326980|0.322860|0.326980|0.86|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T04:00:01+00:00, last15m_closed_end=2026-10-31T04:00+00:00, prior8high=0.012906, depth_time=2026-10-31T04:00:09+00:00, book20_bid_proxy_usdt=6135, book20_ask_proxy_usdt=23956, funding_indicative=-0.000095, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-40.52%, turnover=6388223. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T04:00:01+00:00, last15m_closed_end=2026-10-31T04:00+00:00, prior8high=0.101470, depth_time=2026-10-31T04:00:16+00:00, book20_bid_proxy_usdt=13223, book20_ask_proxy_usdt=10673, funding_indicative=0.000148, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.58%, turnover=8634656. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T04:00:00+00:00, last15m_closed_end=2026-10-31T04:00+00:00, prior8high=0.010336, depth_time=2026-10-31T04:00:14+00:00, book20_bid_proxy_usdt=12139, book20_ask_proxy_usdt=9671, funding_indicative=0.000073, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-21.92%, turnover=12733630. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T04:00:01+00:00, last15m_closed_end=2026-10-31T04:00+00:00, prior8high=1.291900, depth_time=2026-10-31T04:00:29+00:00, book20_bid_proxy_usdt=11604, book20_ask_proxy_usdt=9488, funding_indicative=-0.000251, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.29%, turnover=9586244. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T04:00:01+00:00, last15m_closed_end=2026-10-31T04:00+00:00, prior8high=49.030000, depth_time=2026-10-31T04:00:31+00:00, book20_bid_proxy_usdt=617007, book20_ask_proxy_usdt=655396, funding_indicative=0.000070, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=16013813. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T04:00:00+00:00, last15m_closed_end=2026-10-31T04:00+00:00, prior8high=90.160000, depth_time=2026-10-31T04:00:21+00:00, book20_bid_proxy_usdt=95710, book20_ask_proxy_usdt=72422, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.19%, turnover=111052757. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-31T04:00:01+00:00, last15m_closed_end=2026-10-31T04:00+00:00, prior8high=2.792700, depth_time=2026-10-31T04:00:15+00:00, book20_bid_proxy_usdt=25256, book20_ask_proxy_usdt=39329, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.03%, turnover=5524885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T04:00:00+00:00, last15m_closed_end=2026-10-31T04:00+00:00, prior8high=0.000005, depth_time=2026-10-31T04:00:23+00:00, book20_bid_proxy_usdt=22191, book20_ask_proxy_usdt=26868, funding_indicative=-0.000206, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.11%, turnover=137493845. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T04:00:00+00:00, last15m_closed_end=2026-10-31T04:00+00:00, prior8high=0.037200, depth_time=2026-10-31T04:00:11+00:00, book20_bid_proxy_usdt=25889, book20_ask_proxy_usdt=90561, funding_indicative=-0.020000, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-36.83%, turnover=21049049. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T04:00:00+00:00, last15m_closed_end=2026-10-31T04:00+00:00, prior8high=0.327950, depth_time=2026-10-31T04:00:26+00:00, book20_bid_proxy_usdt=39451, book20_ask_proxy_usdt=30764, funding_indicative=-0.001603, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.80%, turnover=7199430. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
