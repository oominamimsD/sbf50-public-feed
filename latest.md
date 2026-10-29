# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T12:52:31Z**
- feed_generated_utc: 2026-10-29T12:52:33+00:00
- source_sha256: `6e3b95c377718822b78d555a7fd8563b6946658929bddca347bd3c178ec7987c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T12:45+00:00, close=80097.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-29T12:00+00:00, close=80133.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-29T12:00+00:00, close=80133.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.040710|-34.62|-64.95|-34.03|33928395|9.82|
|EVAA_USDT|1.218900|-17.91|116.27|-17.32|21278652|7.38|
|DASH_USDT|50.080000|-5.58|-5.98|-4.99|13925448|2.00|
|BCH_USDT|278.750000|-4.84|-3.77|-4.25|5303694|3.59|
|NEAR_USDT|4.437000|-4.14|-17.60|-3.55|110044140|2.25|
|WLD_USDT|0.420700|-2.79|-26.65|-2.20|85755331|2.38|
|HBAR_USDT|0.074030|-2.47|-13.85|-1.88|16445014|1.35|
|SILVER_USDT|52.560000|-2.06|-8.84|-1.47|507838721|1.90|
|XRP_USDT|1.290300|-1.59|-6.52|-1.00|295707053|0.78|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|278.750000|278.530000|279.000000|2.86|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|50.080000|49.950000|50.300000|4.77|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.218900|1.086500|1.226900|0.92|N|N/Y|N/N|Y|N|
|HBAR_USDT|0.074030|0.073220|0.074110|3.95|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.437000|4.356000|4.443000|2.07|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.040710|0.039240|0.041250|0.32|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|52.560000|52.450000|52.630000|7.32|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.420700|0.416800|0.420500|1.29|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.290300|1.286900|1.291400|1.77|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-10-29T12:52:00+00:00, last15m_closed_end=2026-10-29T12:45+00:00, prior8high=282.150000, depth_time=2026-10-29T12:52:16+00:00, book20_bid_proxy_usdt=96628, book20_ask_proxy_usdt=44867, funding_indicative=0.000074, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.84%, turnover=5303694. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-29T12:52:00+00:00, last15m_closed_end=2026-10-29T12:45+00:00, prior8high=50.850000, depth_time=2026-10-29T12:52:13+00:00, book20_bid_proxy_usdt=588652, book20_ask_proxy_usdt=682291, funding_indicative=0.000035, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.58%, turnover=13925448. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-29T12:51:59+00:00, last15m_closed_end=2026-10-29T12:45+00:00, prior8high=1.285900, depth_time=2026-10-29T12:52:11+00:00, book20_bid_proxy_usdt=16046, book20_ask_proxy_usdt=17747, funding_indicative=0.000193, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-17.91%, turnover=21278652. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-29T12:52:00+00:00, last15m_closed_end=2026-10-29T12:45+00:00, prior8high=0.074100, depth_time=2026-10-29T12:52:25+00:00, book20_bid_proxy_usdt=1109915, book20_ask_proxy_usdt=1185015, funding_indicative=0.000100, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.47%, turnover=16445014. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-29T12:51:59+00:00, last15m_closed_end=2026-10-29T12:45+00:00, prior8high=4.438000, depth_time=2026-10-29T12:52:19+00:00, book20_bid_proxy_usdt=3895753, book20_ask_proxy_usdt=3502333, funding_indicative=0.000060, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.14%, turnover=110044140. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-29T12:51:59+00:00, last15m_closed_end=2026-10-29T12:45+00:00, prior8high=0.045970, depth_time=2026-10-29T12:52:08+00:00, book20_bid_proxy_usdt=53075, book20_ask_proxy_usdt=40529, funding_indicative=0.000179, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-34.62%, turnover=33928395. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-29T12:51:59+00:00, last15m_closed_end=2026-10-29T12:45+00:00, prior8high=53.180000, depth_time=2026-10-29T12:52:28+00:00, book20_bid_proxy_usdt=49826445, book20_ask_proxy_usdt=47253430, funding_indicative=0.000094, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.06%, turnover=507838721. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-29T12:52:00+00:00, last15m_closed_end=2026-10-29T12:45+00:00, prior8high=0.426400, depth_time=2026-10-29T12:52:23+00:00, book20_bid_proxy_usdt=4074526, book20_ask_proxy_usdt=4594979, funding_indicative=0.000080, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.79%, turnover=85755331. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-10-29T12:51:59+00:00, last15m_closed_end=2026-10-29T12:45+00:00, prior8high=1.296500, depth_time=2026-10-29T12:52:30+00:00, book20_bid_proxy_usdt=3970530, book20_ask_proxy_usdt=3791359, funding_indicative=0.000096, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=295707053. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
