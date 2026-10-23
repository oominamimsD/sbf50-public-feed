# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T16:00:24Z**
- feed_generated_utc: 2026-10-23T16:00:27+00:00
- source_sha256: `0317d8ef95b5a667be90aae19085a9009f3af3dbe74eac4a1e21c56f84d93f08`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T16:00+00:00, close=81651.2, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T16:00+00:00, close=81651.2, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-23T16:00+00:00, close=81651.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|QNT_USDT|182.360000|-4.37|-12.28|-4.37|60794191|0.55|
|TIA_USDT|0.548000|-3.58|-9.04|-3.58|26006678|5.47|
|PUMPFUN_USDT|0.004563|-2.47|0.81|-2.47|35975318|2.19|
|NEAR_USDT|4.859000|-1.71|-5.07|-1.71|123950728|4.12|
|HBAR_USDT|0.079040|-1.33|-5.39|-1.33|20262617|1.26|
|XAU_USDT|4011.920000|-1.17|-3.46|-1.17|650096257|0.03|
|XAUT_USDT|4007.570000|-1.14|-3.31|-1.14|234690111|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|HBAR_USDT|0.079040|0.078580|0.079040|2.02|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.859000|4.788000|4.859000|0.98|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004563|0.004485|0.004563|2.10|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|182.360000|177.480000|182.360000|0.88|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.548000|0.535200|0.547900|1.76|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4007.570000|3978.250000|4007.570000|0.75|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4011.920000|3985.020000|4011.920000|0.97|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- HBAR_USDT: quote_utc=2026-10-23T15:59:59+00:00, last15m_closed_end=2026-10-23T16:00+00:00, prior8high=0.080450, depth_time=2026-10-23T16:00:16+00:00, book20_bid_proxy_usdt=967551, book20_ask_proxy_usdt=687944, funding_indicative=0.000045, next_funding_utc=2026-10-24T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.33%, turnover=20262617. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-23T15:59:59+00:00, last15m_closed_end=2026-10-23T16:00+00:00, prior8high=4.980000, depth_time=2026-10-23T16:00:16+00:00, book20_bid_proxy_usdt=2985367, book20_ask_proxy_usdt=1445665, funding_indicative=0.000029, next_funding_utc=2026-10-24T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=123950728. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T15:59:59+00:00, last15m_closed_end=2026-10-23T16:00+00:00, prior8high=0.004677, depth_time=2026-10-23T16:00:13+00:00, book20_bid_proxy_usdt=1605087, book20_ask_proxy_usdt=897210, funding_indicative=0.000024, next_funding_utc=2026-10-23T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.47%, turnover=35975318. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T15:59:59+00:00, last15m_closed_end=2026-10-23T16:00+00:00, prior8high=183.630000, depth_time=2026-10-23T16:00:08+00:00, book20_bid_proxy_usdt=62555, book20_ask_proxy_usdt=59026, funding_indicative=-0.000175, next_funding_utc=2026-10-24T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.37%, turnover=60794191. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T15:59:59+00:00, last15m_closed_end=2026-10-23T16:00+00:00, prior8high=0.550800, depth_time=2026-10-23T16:00:11+00:00, book20_bid_proxy_usdt=335550, book20_ask_proxy_usdt=173434, funding_indicative=0.000002, next_funding_utc=2026-10-23T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.58%, turnover=26006678. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T15:59:59+00:00, last15m_closed_end=2026-10-23T16:00+00:00, prior8high=4028.530000, depth_time=2026-10-23T16:00:23+00:00, book20_bid_proxy_usdt=167430, book20_ask_proxy_usdt=146023, funding_indicative=0.000050, next_funding_utc=2026-10-23T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.14%, turnover=234690111. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T15:59:59+00:00, last15m_closed_end=2026-10-23T16:00+00:00, prior8high=4035.070000, depth_time=2026-10-23T16:00:21+00:00, book20_bid_proxy_usdt=1080517, book20_ask_proxy_usdt=2027998, funding_indicative=0.000176, next_funding_utc=2026-10-23T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.17%, turnover=650096257. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
