# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T03:45:18Z**
- feed_generated_utc: 2026-11-11T03:45:19+00:00
- source_sha256: `0958d6ba8b15d9adffedd9aa24c4d85466aa392ff5881a311c1fdea6a457b652`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T03:45+00:00, close=73724.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T03:00+00:00, close=73615.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T00:00+00:00, close=73762.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.757900|-13.23|49.55|-13.97|5089770|1.14|
|AKE_USDT|0.002683|-7.92|-35.44|-8.66|10547417|3.73|
|ZEC_USDT|1029.690000|-5.82|-14.46|-6.56|2208770218|0.10|
|DASH_USDT|44.310000|-1.83|-3.96|-2.57|14381997|2.26|
|UNI_USDT|6.707000|-1.80|-8.78|-2.54|35294538|1.49|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002683|0.002606|0.002683|3.57|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|44.310000|42.750000|44.310000|0.67|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.757900|1.682600|1.758500|0.96|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.707000|6.626000|6.707000|0.82|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1029.690000|1007.730000|1029.480000|0.99|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T03:45:03+00:00, last15m_closed_end=2026-11-11T03:45+00:00, prior8high=0.003032, depth_time=2026-11-11T03:45:05+00:00, book20_bid_proxy_usdt=45638, book20_ask_proxy_usdt=45862, funding_indicative=0.000050, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.92%, turnover=10547417. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T03:45:03+00:00, last15m_closed_end=2026-11-11T03:45+00:00, prior8high=44.600000, depth_time=2026-11-11T03:45:14+00:00, book20_bid_proxy_usdt=482464, book20_ask_proxy_usdt=702874, funding_indicative=-0.000101, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.83%, turnover=14381997. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-11T03:45:03+00:00, last15m_closed_end=2026-11-11T03:45+00:00, prior8high=1.853200, depth_time=2026-11-11T03:45:05+00:00, book20_bid_proxy_usdt=13025, book20_ask_proxy_usdt=9271, funding_indicative=0.000108, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-13.23%, turnover=5089770. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T03:45:03+00:00, last15m_closed_end=2026-11-11T03:45+00:00, prior8high=6.820000, depth_time=2026-11-11T03:45:16+00:00, book20_bid_proxy_usdt=2709129, book20_ask_proxy_usdt=2529276, funding_indicative=0.000038, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.80%, turnover=35294538. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T03:45:02+00:00, last15m_closed_end=2026-11-11T03:45+00:00, prior8high=1042.760000, depth_time=2026-11-11T03:45:12+00:00, book20_bid_proxy_usdt=162031, book20_ask_proxy_usdt=382715, funding_indicative=0.000100, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.82%, turnover=2208770218. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
