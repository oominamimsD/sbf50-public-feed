# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T22:45:24Z**
- feed_generated_utc: 2026-11-10T22:45:25+00:00
- source_sha256: `99f25aa7c4af9ecff6ee2d2ce876f264265d535e87b2eb8a0c8c58a0b1683ba1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T22:45+00:00, close=73719.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T22:00+00:00, close=73819.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T20:00+00:00, close=73437.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.189140|-24.62|40.64|-25.35|51037537|4.76|
|PIEVERSE_USDT|1.840000|-9.18|56.54|-9.91|5754406|4.35|
|DASH_USDT|42.880000|-5.00|-7.06|-5.73|14213325|2.33|
|ZEC_USDT|1055.220000|-3.48|-12.34|-4.21|2257602846|0.10|
|UNI_USDT|6.681000|-2.18|-9.13|-2.91|31375174|2.99|
|JUP_USDT|0.250000|-1.26|0.36|-1.99|5510388|4.00|
|ARB_USDT|0.160380|-0.61|0.31|-1.34|34160511|1.87|
|JCT_USDT|0.005260|-0.28|25.89|-1.01|19763110|3.80|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.160380|0.158140|0.160380|1.14|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|42.880000|42.550000|42.880000|0.50|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.189140|0.191620|0.189150|1.01|N|Y/N|N/N|Y|N|
|JCT_USDT|0.005260|0.005119|0.005260|0.57|N|Y/Y|Y/Y|Y|N|
|JUP_USDT|0.250000|0.249400|0.250000|0.20|N|Y/N|N/N|Y|N|
|PIEVERSE_USDT|1.840000|1.782100|1.840000|0.28|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.681000|6.670000|6.681000|0.70|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1055.220000|1034.100000|1055.220000|0.85|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-11-10T22:45:01+00:00, last15m_closed_end=2026-11-10T22:45+00:00, prior8high=0.161100, depth_time=2026-11-10T22:45:20+00:00, book20_bid_proxy_usdt=38430, book20_ask_proxy_usdt=67142, funding_indicative=-0.000225, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.61%, turnover=34160511. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T22:45:01+00:00, last15m_closed_end=2026-11-10T22:45+00:00, prior8high=43.460000, depth_time=2026-11-10T22:45:10+00:00, book20_bid_proxy_usdt=728480, book20_ask_proxy_usdt=732274, funding_indicative=-0.000188, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.00%, turnover=14213325. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-10T22:45:00+00:00, last15m_closed_end=2026-11-10T22:45+00:00, prior8high=0.245520, depth_time=2026-11-10T22:45:06+00:00, book20_bid_proxy_usdt=12457, book20_ask_proxy_usdt=11451, funding_indicative=-0.017912, next_funding_utc=2026-11-10T23:00:00+00:00, funding_cycle_h=1, 24h_change=-24.62%, turnover=51037537. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T22:45:00+00:00, last15m_closed_end=2026-11-10T22:45+00:00, prior8high=0.005437, depth_time=2026-11-10T22:45:22+00:00, book20_bid_proxy_usdt=49286, book20_ask_proxy_usdt=34408, funding_indicative=0.000574, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.28%, turnover=19763110. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-11-10T22:45:01+00:00, last15m_closed_end=2026-11-10T22:45+00:00, prior8high=0.257600, depth_time=2026-11-10T22:45:11+00:00, book20_bid_proxy_usdt=456173, book20_ask_proxy_usdt=402442, funding_indicative=-0.000016, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.26%, turnover=5510388. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T22:45:00+00:00, last15m_closed_end=2026-11-10T22:45+00:00, prior8high=1.858500, depth_time=2026-11-10T22:45:09+00:00, book20_bid_proxy_usdt=27823, book20_ask_proxy_usdt=17641, funding_indicative=0.000078, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.18%, turnover=5754406. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T22:45:01+00:00, last15m_closed_end=2026-11-10T22:45+00:00, prior8high=6.769000, depth_time=2026-11-10T22:45:15+00:00, book20_bid_proxy_usdt=2093895, book20_ask_proxy_usdt=2473469, funding_indicative=-0.000018, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=31375174. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T22:45:00+00:00, last15m_closed_end=2026-11-10T22:45+00:00, prior8high=1069.190000, depth_time=2026-11-10T22:45:13+00:00, book20_bid_proxy_usdt=330725, book20_ask_proxy_usdt=193036, funding_indicative=0.000011, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.48%, turnover=2257602846. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
