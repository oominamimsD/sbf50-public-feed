# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T07:30:34Z**
- feed_generated_utc: 2026-11-11T07:30:35+00:00
- source_sha256: `c6b7f9c910f7332c517eebfc34510b703367efefff72ac207a14c8958ffb0474`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T07:30+00:00, close=73892.3, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-11T07:00+00:00, close=73586.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T04:00+00:00, close=73740.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.213190|-15.04|58.52|-16.01|67456643|1.41|
|ZEC_USDT|984.710000|-9.93|-18.20|-10.90|2192373656|0.10|
|ONE_USDT|0.001631|-9.09|46.06|-10.06|12369632|0.61|
|AKE_USDT|0.002652|-8.99|-36.18|-9.96|9206346|3.77|
|UNI_USDT|6.481000|-5.10|-11.85|-6.07|39623053|1.54|
|DASH_USDT|44.060000|-2.39|-4.50|-3.36|15676548|2.27|
|ARB_USDT|0.158470|-1.80|-0.88|-2.77|31514885|0.63|
|DOT_USDT|0.832100|-1.14|-11.72|-2.11|8490555|1.20|
|QNT_USDT|178.950000|-0.96|-8.42|-1.93|46163583|0.56|
|VVV_USDT|19.102000|-0.71|-14.57|-1.68|5440124|0.52|
|HBAR_USDT|0.065420|-0.54|-6.58|-1.51|6092635|1.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002652|0.002607|0.002652|0.23|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.158470|0.157280|0.158470|0.90|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|44.060000|43.260000|44.060000|3.28|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.832100|0.824500|0.832100|0.63|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.065420|0.064970|0.065420|1.43|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.213190|0.199690|0.213200|0.66|N|Y/N|N/N|Y|N|
|ONE_USDT|0.001631|0.001651|0.001631|1.13|N|Y/Y|N/N|Y|N|
|QNT_USDT|178.950000|177.180000|178.950000|1.18|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.481000|6.373000|6.481000|3.04|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.102000|18.851000|19.102000|0.94|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|984.710000|965.410000|984.600000|1.10|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T07:30:00+00:00, last15m_closed_end=2026-11-11T07:30+00:00, prior8high=0.002864, depth_time=2026-11-11T07:30:15+00:00, book20_bid_proxy_usdt=46744, book20_ask_proxy_usdt=122014, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.99%, turnover=9206346. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T07:30:00+00:00, last15m_closed_end=2026-11-11T07:30+00:00, prior8high=0.163800, depth_time=2026-11-11T07:30:23+00:00, book20_bid_proxy_usdt=586913, book20_ask_proxy_usdt=51402, funding_indicative=0.000011, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.80%, turnover=31514885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T07:30:00+00:00, last15m_closed_end=2026-11-11T07:30+00:00, prior8high=45.400000, depth_time=2026-11-11T07:30:20+00:00, book20_bid_proxy_usdt=789081, book20_ask_proxy_usdt=393292, funding_indicative=-0.000135, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.39%, turnover=15676548. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-11T07:30:00+00:00, last15m_closed_end=2026-11-11T07:30+00:00, prior8high=0.845900, depth_time=2026-11-11T07:30:19+00:00, book20_bid_proxy_usdt=619126, book20_ask_proxy_usdt=454157, funding_indicative=0.000051, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.14%, turnover=8490555. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T07:30:00+00:00, last15m_closed_end=2026-11-11T07:30+00:00, prior8high=0.065870, depth_time=2026-11-11T07:30:28+00:00, book20_bid_proxy_usdt=697494, book20_ask_proxy_usdt=668524, funding_indicative=-0.000009, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.54%, turnover=6092635. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T07:30:00+00:00, last15m_closed_end=2026-11-11T07:30+00:00, prior8high=0.298110, depth_time=2026-11-11T07:30:08+00:00, book20_bid_proxy_usdt=15033, book20_ask_proxy_usdt=3677, funding_indicative=-0.012701, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=1, 24h_change=-15.04%, turnover=67456643. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T07:30:00+00:00, last15m_closed_end=2026-11-11T07:30+00:00, prior8high=0.001832, depth_time=2026-11-11T07:30:13+00:00, book20_bid_proxy_usdt=24753, book20_ask_proxy_usdt=31802, funding_indicative=-0.003774, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.09%, turnover=12369632. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T07:30:00+00:00, last15m_closed_end=2026-11-11T07:30+00:00, prior8high=181.050000, depth_time=2026-11-11T07:30:28+00:00, book20_bid_proxy_usdt=99039, book20_ask_proxy_usdt=67607, funding_indicative=-0.000091, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.96%, turnover=46163583. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T07:30:00+00:00, last15m_closed_end=2026-11-11T07:30+00:00, prior8high=6.687000, depth_time=2026-11-11T07:30:18+00:00, book20_bid_proxy_usdt=2279669, book20_ask_proxy_usdt=1500723, funding_indicative=0.000007, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.10%, turnover=39623053. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T07:30:00+00:00, last15m_closed_end=2026-11-11T07:30+00:00, prior8high=19.229000, depth_time=2026-11-11T07:30:27+00:00, book20_bid_proxy_usdt=12973, book20_ask_proxy_usdt=20093, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.71%, turnover=5440124. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T07:30:00+00:00, last15m_closed_end=2026-11-11T07:30+00:00, prior8high=1023.190000, depth_time=2026-11-11T07:30:10+00:00, book20_bid_proxy_usdt=188871, book20_ask_proxy_usdt=361407, funding_indicative=0.000072, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-9.93%, turnover=2192373656. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
