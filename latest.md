# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T16:00:24Z**
- feed_generated_utc: 2026-10-29T16:00:26+00:00
- source_sha256: `6bda9cfe43de3eb4b2bad5394ee5914791f517a0ea292d844623804a72c2f6cc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T16:00+00:00, close=81732.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-29T16:00+00:00, close=81732.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-29T16:00+00:00, close=81732.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.038410|-38.31|-66.93|-39.79|35132566|5.21|
|EVAA_USDT|1.120900|-24.51|98.88|-25.99|17183762|6.25|
|BTW_USDT|1.638100|-5.74|11.45|-7.22|9673076|0.61|
|DASH_USDT|51.490000|-2.92|-3.34|-4.40|16551300|1.94|
|SILVER_USDT|52.640000|-1.91|-8.70|-3.39|553861333|1.90|
|XAU_USDT|4030.500000|-0.47|-2.63|-1.95|631470174|0.03|
|XAUT_USDT|4021.100000|-0.39|-2.63|-1.87|271025237|0.03|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.638100|1.583900|1.638100|0.99|N|Y/Y|Y/N|N|N|
|DASH_USDT|51.490000|50.140000|51.490000|0.42|N|Y/Y|Y/Y|N|N|
|EVAA_USDT|1.120900|1.140900|1.120900|0.91|N|Y/Y|N/N|N|N|
|Q_USDT|0.038410|0.038230|0.038410|1.10|N|Y/Y|Y/Y|N|N|
|SILVER_USDT|52.640000|52.110000|52.640000|0.33|N|Y/Y|Y/Y|N|N|
|XAUT_USDT|4021.100000|4015.260000|4021.500000|0.37|N|Y/Y|Y/Y|N|N|
|XAU_USDT|4030.500000|4025.280000|4030.500000|1.19|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-29T15:59:59+00:00, last15m_closed_end=2026-10-29T16:00+00:00, prior8high=1.785400, depth_time=2026-10-29T16:00:12+00:00, book20_bid_proxy_usdt=18479, book20_ask_proxy_usdt=13916, funding_indicative=0.000023, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.74%, turnover=9673076. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-29T15:59:59+00:00, last15m_closed_end=2026-10-29T16:00+00:00, prior8high=51.560000, depth_time=2026-10-29T16:00:16+00:00, book20_bid_proxy_usdt=703109, book20_ask_proxy_usdt=530700, funding_indicative=-0.000013, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.92%, turnover=16551300. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-29T15:59:59+00:00, last15m_closed_end=2026-10-29T16:00+00:00, prior8high=1.249100, depth_time=2026-10-29T16:00:11+00:00, book20_bid_proxy_usdt=10105, book20_ask_proxy_usdt=8703, funding_indicative=0.000154, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-24.51%, turnover=17183762. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-29T15:59:59+00:00, last15m_closed_end=2026-10-29T16:00+00:00, prior8high=0.042760, depth_time=2026-10-29T16:00:08+00:00, book20_bid_proxy_usdt=76001, book20_ask_proxy_usdt=59520, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-38.31%, turnover=35132566. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-29T15:59:59+00:00, last15m_closed_end=2026-10-29T16:00+00:00, prior8high=52.890000, depth_time=2026-10-29T16:00:19+00:00, book20_bid_proxy_usdt=50234721, book20_ask_proxy_usdt=52302700, funding_indicative=0.000070, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.91%, turnover=553861333. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-29T15:59:59+00:00, last15m_closed_end=2026-10-29T16:00+00:00, prior8high=4032.730000, depth_time=2026-10-29T16:00:23+00:00, book20_bid_proxy_usdt=106670, book20_ask_proxy_usdt=267015, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.39%, turnover=271025237. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-29T15:59:59+00:00, last15m_closed_end=2026-10-29T16:00+00:00, prior8high=4044.530000, depth_time=2026-10-29T16:00:20+00:00, book20_bid_proxy_usdt=2533027, book20_ask_proxy_usdt=2255206, funding_indicative=0.000065, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.47%, turnover=631470174. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
