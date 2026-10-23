# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T13:45:33Z**
- feed_generated_utc: 2026-10-23T13:45:36+00:00
- source_sha256: `3f43cef920f9a301c539357a7caf8b64535ce91de8c8984881db511a375678b3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T13:45+00:00, close=81972.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T13:00+00:00, close=81711.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T12:00+00:00, close=81696.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|MAGMA_USDT|0.429350|-14.47|81.58|-14.83|6348271|8.15|
|LIT_USDT|3.370500|-6.74|9.02|-7.10|8695185|0.30|
|QNT_USDT|183.170000|-3.95|-11.89|-4.31|57373968|2.18|
|TIA_USDT|0.549700|-3.28|-8.76|-3.64|24847214|1.82|
|STRK_USDT|0.052740|-2.98|-45.26|-3.34|12136451|1.90|
|SILVER_USDT|54.110000|-2.08|-5.30|-2.44|337056303|3.70|
|OP_USDT|0.118420|-1.19|-14.72|-1.55|6320455|1.69|
|PUMPFUN_USDT|0.004639|-0.85|2.49|-1.21|39722425|2.16|
|XAU_USDT|4031.120000|-0.70|-3.00|-1.06|590900785|0.03|
|XAUT_USDT|4026.690000|-0.67|-2.85|-1.03|230167885|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|LIT_USDT|3.370500|3.317600|3.370500|1.20|N|Y/Y|Y/Y|Y|N|
|MAGMA_USDT|0.429350|0.419990|0.429370|0.79|N|Y/Y|N/N|Y|N|
|OP_USDT|0.118420|0.117320|0.118410|3.81|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004639|0.004564|0.004639|0.67|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|183.170000|180.210000|183.170000|1.01|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|54.110000|53.830000|54.110000|9.69|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052740|0.051600|0.052740|0.92|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.549700|0.543400|0.549700|0.94|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4026.690000|4024.150000|4026.690000|0.84|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4031.120000|4030.620000|4032.740000|1.73|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- LIT_USDT: quote_utc=2026-10-23T13:44:59+00:00, last15m_closed_end=2026-10-23T13:45+00:00, prior8high=3.406000, depth_time=2026-10-23T13:45:10+00:00, book20_bid_proxy_usdt=26022, book20_ask_proxy_usdt=23608, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.74%, turnover=8695185. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGMA_USDT: quote_utc=2026-10-23T13:44:59+00:00, last15m_closed_end=2026-10-23T13:45+00:00, prior8high=0.462420, depth_time=2026-10-23T13:45:09+00:00, book20_bid_proxy_usdt=2359, book20_ask_proxy_usdt=3271, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.47%, turnover=6348271. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T13:44:59+00:00, last15m_closed_end=2026-10-23T13:45+00:00, prior8high=0.118580, depth_time=2026-10-23T13:45:24+00:00, book20_bid_proxy_usdt=53606, book20_ask_proxy_usdt=59409, funding_indicative=0.000000, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.19%, turnover=6320455. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T13:44:59+00:00, last15m_closed_end=2026-10-23T13:45+00:00, prior8high=0.004674, depth_time=2026-10-23T13:45:26+00:00, book20_bid_proxy_usdt=869896, book20_ask_proxy_usdt=1567596, funding_indicative=0.000017, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.85%, turnover=39722425. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T13:44:59+00:00, last15m_closed_end=2026-10-23T13:45+00:00, prior8high=183.550000, depth_time=2026-10-23T13:45:13+00:00, book20_bid_proxy_usdt=46972, book20_ask_proxy_usdt=53263, funding_indicative=-0.000186, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.95%, turnover=57373968. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T13:44:59+00:00, last15m_closed_end=2026-10-23T13:45+00:00, prior8high=54.150000, depth_time=2026-10-23T13:45:21+00:00, book20_bid_proxy_usdt=25566924, book20_ask_proxy_usdt=26544550, funding_indicative=0.000074, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.08%, turnover=337056303. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T13:44:59+00:00, last15m_closed_end=2026-10-23T13:45+00:00, prior8high=0.053770, depth_time=2026-10-23T13:45:18+00:00, book20_bid_proxy_usdt=507734, book20_ask_proxy_usdt=556590, funding_indicative=-0.000022, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.98%, turnover=12136451. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T13:44:59+00:00, last15m_closed_end=2026-10-23T13:45+00:00, prior8high=0.552300, depth_time=2026-10-23T13:45:16+00:00, book20_bid_proxy_usdt=286189, book20_ask_proxy_usdt=276823, funding_indicative=0.000000, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.28%, turnover=24847214. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T13:44:59+00:00, last15m_closed_end=2026-10-23T13:45+00:00, prior8high=4035.760000, depth_time=2026-10-23T13:45:32+00:00, book20_bid_proxy_usdt=95559, book20_ask_proxy_usdt=121642, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.67%, turnover=230167885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T13:45:02+00:00, last15m_closed_end=2026-10-23T13:45+00:00, prior8high=4042.750000, depth_time=2026-10-23T13:45:30+00:00, book20_bid_proxy_usdt=750266, book20_ask_proxy_usdt=1358781, funding_indicative=0.000172, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.70%, turnover=590900785. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
