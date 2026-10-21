# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T09:30:24Z**
- feed_generated_utc: 2026-10-21T09:30:26+00:00
- source_sha256: `2b5258f32e9c151fe3198b8b9b66cb78943ec6242916d68cba5dfb588f6e8b18`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T09:30+00:00, close=83567.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T09:00+00:00, close=83217, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T08:00+00:00, close=83117.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.049955|-22.70|208.80|-23.89|6840079|5.23|
|BAT_USDT|0.183600|-14.90|3.50|-16.09|10998481|0.55|
|BR_USDT|0.582900|-10.41|34.61|-11.60|26629452|2.23|
|Q_USDT|0.121673|-0.88|195.84|-2.07|5850250|0.25|
|SILVER_USDT|57.470000|-0.82|-3.23|-2.01|214584818|1.74|
|XAU_USDT|4130.630000|-0.21|-0.83|-1.40|387402420|0.02|
|XAUT_USDT|4124.000000|-0.09|-0.78|-1.28|161565072|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.049955|0.041474|0.049658|1.79|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.183600|0.183360|0.183600|1.44|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.582900|0.575440|0.582900|2.30|N|Y/Y|N/N|N|N|
|Q_USDT|0.121673|0.120575|0.121666|0.48|N|Y/N|N/N|N|N|
|SILVER_USDT|57.470000|57.280000|57.470000|0.48|N|Y/Y|N/N|N|N|
|XAUT_USDT|4124.000000|4113.810000|4124.000000|1.76|N|Y/Y|Y/Y|N|N|
|XAU_USDT|4130.630000|4121.340000|4131.020000|1.22|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T09:30:00+00:00, last15m_closed_end=2026-10-21T09:30+00:00, prior8high=0.046764, depth_time=2026-10-21T09:30:09+00:00, book20_bid_proxy_usdt=7423, book20_ask_proxy_usdt=5822, funding_indicative=0.000047, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-22.70%, turnover=6840079. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T09:30:00+00:00, last15m_closed_end=2026-10-21T09:30+00:00, prior8high=0.190510, depth_time=2026-10-21T09:30:11+00:00, book20_bid_proxy_usdt=26166, book20_ask_proxy_usdt=18937, funding_indicative=-0.000131, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-14.90%, turnover=10998481. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T09:30:00+00:00, last15m_closed_end=2026-10-21T09:30+00:00, prior8high=0.627970, depth_time=2026-10-21T09:30:13+00:00, book20_bid_proxy_usdt=2145, book20_ask_proxy_usdt=5116, funding_indicative=-0.000015, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.41%, turnover=26629452. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T09:30:00+00:00, last15m_closed_end=2026-10-21T09:30+00:00, prior8high=0.146637, depth_time=2026-10-21T09:30:13+00:00, book20_bid_proxy_usdt=14366, book20_ask_proxy_usdt=15766, funding_indicative=0.000050, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.88%, turnover=5850250. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T09:30:00+00:00, last15m_closed_end=2026-10-21T09:30+00:00, prior8high=57.550000, depth_time=2026-10-21T09:30:18+00:00, book20_bid_proxy_usdt=39159787, book20_ask_proxy_usdt=34309311, funding_indicative=0.000042, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.82%, turnover=214584818. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-21T09:30:00+00:00, last15m_closed_end=2026-10-21T09:30+00:00, prior8high=4125.440000, depth_time=2026-10-21T09:30:18+00:00, book20_bid_proxy_usdt=111679, book20_ask_proxy_usdt=127607, funding_indicative=0.000017, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.09%, turnover=161565072. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-21T09:30:00+00:00, last15m_closed_end=2026-10-21T09:30+00:00, prior8high=4132.430000, depth_time=2026-10-21T09:30:20+00:00, book20_bid_proxy_usdt=1282590, book20_ask_proxy_usdt=536277, funding_indicative=0.000060, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.21%, turnover=387402420. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
