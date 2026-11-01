# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T04:00:26Z**
- feed_generated_utc: 2026-11-01T04:00:27+00:00
- source_sha256: `8b582b4ae47581f91ef9cef74e2f09823a71e18bd48ce32859c1b12e82722799`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T04:00+00:00, close=77753.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T04:00+00:00, close=77753.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T04:00+00:00, close=77753.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.230100|-23.12|37.02|-23.36|29865773|1.30|
|AKE_USDT|0.009077|-18.50|-68.94|-18.74|11516813|3.31|
|BLESS_USDT|0.009370|-12.11|15.49|-12.35|6786552|4.27|
|ZEC_USDT|1243.540000|-2.64|8.58|-2.88|955119166|0.08|
|TRX_USDT|0.307570|-2.44|-6.49|-2.68|10790728|0.33|
|ENA_USDT|0.187810|-2.00|0.54|-2.24|41670313|0.53|
|TAO_USDT|235.560000|-0.83|-4.08|-1.07|22167329|1.27|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.009077|0.008372|0.009100|1.91|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009370|0.009219|0.009370|0.87|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.187810|0.186020|0.187810|0.90|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.230100|0.226590|0.230100|0.39|N|Y/Y|N/N|Y|N|
|TAO_USDT|235.560000|235.710000|235.550000|1.77|Y|Y/Y|Y/Y|Y|Y|
|TRX_USDT|0.307570|0.307900|0.307570|0.12|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1243.540000|1238.980000|1243.540000|0.44|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T04:00:00+00:00, last15m_closed_end=2026-11-01T04:00+00:00, prior8high=0.011493, depth_time=2026-11-01T04:00:12+00:00, book20_bid_proxy_usdt=8078, book20_ask_proxy_usdt=7969, funding_indicative=-0.003337, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-18.50%, turnover=11516813. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T04:00:00+00:00, last15m_closed_end=2026-11-01T04:00+00:00, prior8high=0.009543, depth_time=2026-11-01T04:00:14+00:00, book20_bid_proxy_usdt=16213, book20_ask_proxy_usdt=13652, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-12.11%, turnover=6786552. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T04:00:00+00:00, last15m_closed_end=2026-11-01T04:00+00:00, prior8high=0.189350, depth_time=2026-11-01T04:00:22+00:00, book20_bid_proxy_usdt=141118, book20_ask_proxy_usdt=145056, funding_indicative=0.000022, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.00%, turnover=41670313. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T04:00:00+00:00, last15m_closed_end=2026-11-01T04:00+00:00, prior8high=0.239040, depth_time=2026-11-01T04:00:08+00:00, book20_bid_proxy_usdt=4885, book20_ask_proxy_usdt=5891, funding_indicative=-0.000640, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-23.12%, turnover=29865773. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-01T04:00:00+00:00, last15m_closed_end=2026-11-01T04:00+00:00, prior8high=237.740000, depth_time=2026-11-01T04:00:25+00:00, book20_bid_proxy_usdt=79043, book20_ask_proxy_usdt=172370, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.83%, turnover=22167329. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T04:00:00+00:00, last15m_closed_end=2026-11-01T04:00+00:00, prior8high=0.309960, depth_time=2026-11-01T04:00:20+00:00, book20_bid_proxy_usdt=106548, book20_ask_proxy_usdt=94616, funding_indicative=-0.001250, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.44%, turnover=10790728. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T04:00:00+00:00, last15m_closed_end=2026-11-01T04:00+00:00, prior8high=1260.940000, depth_time=2026-11-01T04:00:16+00:00, book20_bid_proxy_usdt=560995, book20_ask_proxy_usdt=1243225, funding_indicative=-0.000109, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.64%, turnover=955119166. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
