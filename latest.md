# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T04:00:23Z**
- feed_generated_utc: 2026-11-11T04:00:25+00:00
- source_sha256: `6e114ad46344cde5652e184b96c345c30791100d9206dd1dfc0bcbd2439d6978`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T04:00+00:00, close=73740.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T04:00+00:00, close=73740.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T04:00+00:00, close=73740.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1028.220000|-5.95|-14.58|-6.71|2226158450|0.10|
|UNI_USDT|6.699000|-5.18|-8.89|-5.94|35744360|2.99|
|VVV_USDT|19.281000|-2.70|-13.77|-3.46|5264419|1.56|
|HYPE_USDT|71.916000|-2.30|-17.66|-3.06|39320496|0.14|
|SOL_USDT|83.310000|-1.18|-11.10|-1.94|623495950|1.20|
|QNT_USDT|181.000000|-1.14|-7.37|-1.90|46374866|0.55|
|AKE_USDT|0.002690|-0.81|-35.27|-1.57|9671680|3.72|
|XRP_USDT|1.058100|-0.66|-17.38|-1.42|320437282|0.94|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002690|0.002606|0.002690|1.78|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|71.916000|71.323000|71.916000|0.02|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|181.000000|179.740000|181.000000|0.55|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|83.310000|82.840000|83.310000|0.34|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.699000|6.626000|6.699000|4.53|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.281000|19.007000|19.281000|0.78|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.058100|1.046700|1.058100|0.76|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1028.220000|1007.730000|1028.220000|0.84|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T04:00:00+00:00, last15m_closed_end=2026-11-11T04:00+00:00, prior8high=0.003032, depth_time=2026-11-11T04:00:20+00:00, book20_bid_proxy_usdt=52870, book20_ask_proxy_usdt=70057, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.81%, turnover=9671680. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-11T04:00:00+00:00, last15m_closed_end=2026-11-11T04:00+00:00, prior8high=72.421000, depth_time=2026-11-11T04:00:13+00:00, book20_bid_proxy_usdt=117090, book20_ask_proxy_usdt=78644, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.30%, turnover=39320496. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T04:00:00+00:00, last15m_closed_end=2026-11-11T04:00+00:00, prior8high=183.190000, depth_time=2026-11-11T04:00:16+00:00, book20_bid_proxy_usdt=86150, book20_ask_proxy_usdt=95642, funding_indicative=-0.000162, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.14%, turnover=46374866. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-11T04:00:00+00:00, last15m_closed_end=2026-11-11T04:00+00:00, prior8high=83.750000, depth_time=2026-11-11T04:00:15+00:00, book20_bid_proxy_usdt=17388935, book20_ask_proxy_usdt=13498696, funding_indicative=0.000071, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.18%, turnover=623495950. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T04:00:00+00:00, last15m_closed_end=2026-11-11T04:00+00:00, prior8high=6.809000, depth_time=2026-11-11T04:00:08+00:00, book20_bid_proxy_usdt=2474084, book20_ask_proxy_usdt=3347462, funding_indicative=0.000049, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.18%, turnover=35744360. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T04:00:00+00:00, last15m_closed_end=2026-11-11T04:00+00:00, prior8high=19.540000, depth_time=2026-11-11T04:00:11+00:00, book20_bid_proxy_usdt=38779, book20_ask_proxy_usdt=23854, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.70%, turnover=5264419. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-11T04:00:00+00:00, last15m_closed_end=2026-11-11T04:00+00:00, prior8high=1.065200, depth_time=2026-11-11T04:00:22+00:00, book20_bid_proxy_usdt=4151164, book20_ask_proxy_usdt=3390325, funding_indicative=0.000100, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.66%, turnover=320437282. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T03:59:59+00:00, last15m_closed_end=2026-11-11T04:00+00:00, prior8high=1038.490000, depth_time=2026-11-11T04:00:06+00:00, book20_bid_proxy_usdt=715325, book20_ask_proxy_usdt=270715, funding_indicative=0.000099, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.95%, turnover=2226158450. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
