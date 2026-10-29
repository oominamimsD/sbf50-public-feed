# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T15:45:25Z**
- feed_generated_utc: 2026-10-29T15:45:27+00:00
- source_sha256: `91da855dd56085bf0089f94070f5c77f3d3c34cbe3beee238607e185d72ca589`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T15:45+00:00, close=81713.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-29T15:00+00:00, close=81149.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-29T12:00+00:00, close=80133.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.039280|-36.91|-66.18|-38.37|34927988|7.63|
|EVAA_USDT|1.143100|-23.02|102.82|-24.48|17104446|6.12|
|BTW_USDT|1.635500|-5.89|11.27|-7.35|9603221|0.61|
|DASH_USDT|51.430000|-3.03|-3.45|-4.49|16469314|1.94|
|SILVER_USDT|52.600000|-1.99|-8.77|-3.45|551999479|1.90|
|XAU_USDT|4031.260000|-0.45|-2.61|-1.91|625090395|0.03|
|XAUT_USDT|4020.660000|-0.40|-2.64|-1.86|269417647|0.05|
|XRP_USDT|1.307200|-0.30|-5.29|-1.76|309610075|0.77|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.635500|1.583900|1.635500|2.15|N|Y/Y|N/N|Y|N|
|DASH_USDT|51.430000|50.140000|51.440000|0.64|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.143100|1.156800|1.143100|0.44|N|Y/Y|N/N|Y|N|
|Q_USDT|0.039280|0.038230|0.039280|1.19|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|52.600000|52.110000|52.600000|0.96|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4020.660000|4015.260000|4020.660000|0.23|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4031.260000|4025.280000|4031.260000|0.65|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.307200|1.285100|1.307200|2.02|N|N/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-29T15:45:00+00:00, last15m_closed_end=2026-10-29T15:45+00:00, prior8high=1.785400, depth_time=2026-10-29T15:45:12+00:00, book20_bid_proxy_usdt=10124, book20_ask_proxy_usdt=16838, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.89%, turnover=9603221. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-29T15:45:00+00:00, last15m_closed_end=2026-10-29T15:45+00:00, prior8high=51.530000, depth_time=2026-10-29T15:45:14+00:00, book20_bid_proxy_usdt=573391, book20_ask_proxy_usdt=1126958, funding_indicative=-0.000006, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.03%, turnover=16469314. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-29T15:44:59+00:00, last15m_closed_end=2026-10-29T15:45+00:00, prior8high=1.249100, depth_time=2026-10-29T15:45:09+00:00, book20_bid_proxy_usdt=11103, book20_ask_proxy_usdt=17325, funding_indicative=0.000152, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-23.02%, turnover=17104446. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-29T15:44:59+00:00, last15m_closed_end=2026-10-29T15:45+00:00, prior8high=0.042760, depth_time=2026-10-29T15:45:08+00:00, book20_bid_proxy_usdt=50994, book20_ask_proxy_usdt=42459, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-36.91%, turnover=34927988. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-29T15:44:59+00:00, last15m_closed_end=2026-10-29T15:45+00:00, prior8high=52.890000, depth_time=2026-10-29T15:45:17+00:00, book20_bid_proxy_usdt=49711106, book20_ask_proxy_usdt=47933796, funding_indicative=0.000074, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.99%, turnover=551999479. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-29T15:44:59+00:00, last15m_closed_end=2026-10-29T15:45+00:00, prior8high=4033.370000, depth_time=2026-10-29T15:45:21+00:00, book20_bid_proxy_usdt=124723, book20_ask_proxy_usdt=153347, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.40%, turnover=269417647. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-29T15:44:59+00:00, last15m_closed_end=2026-10-29T15:45+00:00, prior8high=4044.990000, depth_time=2026-10-29T15:45:19+00:00, book20_bid_proxy_usdt=3632231, book20_ask_proxy_usdt=1676174, funding_indicative=0.000061, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.45%, turnover=625090395. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-10-29T15:44:59+00:00, last15m_closed_end=2026-10-29T15:45+00:00, prior8high=1.312300, depth_time=2026-10-29T15:45:24+00:00, book20_bid_proxy_usdt=3678101, book20_ask_proxy_usdt=2819653, funding_indicative=0.000100, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.30%, turnover=309610075. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
