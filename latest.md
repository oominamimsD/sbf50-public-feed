# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T14:30:43Z**
- feed_generated_utc: 2026-10-23T14:30:45+00:00
- source_sha256: `c677b62ac152d23bef5d55e4113566b138874810edcaa491fd5760587a371fb0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T14:30+00:00, close=81423, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T14:00+00:00, close=81969.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-23T12:00+00:00, close=81696.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|MAGMA_USDT|0.406660|-18.99|71.98|-18.72|5419710|2.21|
|LIT_USDT|3.338100|-7.63|7.98|-7.36|8508419|0.30|
|QNT_USDT|181.440000|-4.86|-12.73|-4.59|59312727|0.55|
|TIA_USDT|0.542500|-4.55|-9.95|-4.28|24972326|3.69|
|SILVER_USDT|53.280000|-3.58|-6.75|-3.31|343876400|1.88|
|STRK_USDT|0.052430|-3.55|-45.58|-3.28|11890770|1.91|
|ARB_USDT|0.178680|-2.70|-5.92|-2.43|26036311|0.56|
|APT_USDT|0.751900|-2.62|-9.04|-2.35|7746378|1.33|
|PUMPFUN_USDT|0.004558|-2.58|0.70|-2.31|38095322|2.19|
|OP_USDT|0.117240|-2.17|-15.57|-1.90|6705002|0.85|
|XAU_USDT|3987.290000|-1.78|-4.06|-1.51|613576144|0.03|
|XAUT_USDT|3984.420000|-1.72|-3.87|-1.45|233372198|0.07|
|NEAR_USDT|4.862000|-1.65|-5.02|-1.38|122341243|2.06|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.751900|0.756400|0.752000|6.21|Y|Y/Y|Y/Y|Y|Y|
|ARB_USDT|0.178680|0.178680|0.178680|6.55|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.338100|3.286200|3.338100|1.63|N|Y/Y|Y/Y|Y|N|
|MAGMA_USDT|0.406660|0.413320|0.406660|1.10|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.862000|4.886000|4.862000|3.80|Y|N/Y|Y/Y|Y|N|
|OP_USDT|0.117240|0.117120|0.117240|10.17|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004558|0.004564|0.004558|4.42|Y|N/Y|Y/Y|Y|N|
|QNT_USDT|181.440000|180.210000|181.440000|2.87|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|53.280000|53.830000|53.280000|11.97|Y|Y/Y|Y/Y|Y|Y|
|STRK_USDT|0.052430|0.052180|0.052430|0.95|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.542500|0.542700|0.542500|3.44|Y|Y/Y|Y/Y|Y|Y|
|XAUT_USDT|3984.420000|4009.610000|3984.420000|13.59|Y|Y/Y|Y/Y|Y|Y|
|XAU_USDT|3987.290000|4015.820000|3987.290000|7.71|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-23T14:29:59+00:00, last15m_closed_end=2026-10-23T14:30+00:00, prior8high=0.770000, depth_time=2026-10-23T14:30:28+00:00, book20_bid_proxy_usdt=87279, book20_ask_proxy_usdt=127442, funding_indicative=0.000042, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.62%, turnover=7746378. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-23T14:29:59+00:00, last15m_closed_end=2026-10-23T14:30+00:00, prior8high=0.182320, depth_time=2026-10-23T14:30:24+00:00, book20_bid_proxy_usdt=72795, book20_ask_proxy_usdt=97785, funding_indicative=-0.000019, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.70%, turnover=26036311. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T14:30:00+00:00, last15m_closed_end=2026-10-23T14:30+00:00, prior8high=3.406000, depth_time=2026-10-23T14:30:11+00:00, book20_bid_proxy_usdt=27650, book20_ask_proxy_usdt=19792, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.63%, turnover=8508419. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGMA_USDT: quote_utc=2026-10-23T14:29:59+00:00, last15m_closed_end=2026-10-23T14:30+00:00, prior8high=0.462420, depth_time=2026-10-23T14:30:09+00:00, book20_bid_proxy_usdt=2704, book20_ask_proxy_usdt=4156, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-18.99%, turnover=5419710. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-23T14:29:59+00:00, last15m_closed_end=2026-10-23T14:30+00:00, prior8high=4.980000, depth_time=2026-10-23T14:30:42+00:00, book20_bid_proxy_usdt=418054, book20_ask_proxy_usdt=592403, funding_indicative=0.000035, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=122341243. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T14:30:00+00:00, last15m_closed_end=2026-10-23T14:30+00:00, prior8high=0.118860, depth_time=2026-10-23T14:30:33+00:00, book20_bid_proxy_usdt=82566, book20_ask_proxy_usdt=53303, funding_indicative=-0.000024, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=6705002. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T14:29:59+00:00, last15m_closed_end=2026-10-23T14:30+00:00, prior8high=0.004677, depth_time=2026-10-23T14:30:30+00:00, book20_bid_proxy_usdt=1550333, book20_ask_proxy_usdt=1086344, funding_indicative=0.000016, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.58%, turnover=38095322. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T14:29:59+00:00, last15m_closed_end=2026-10-23T14:30+00:00, prior8high=183.630000, depth_time=2026-10-23T14:30:14+00:00, book20_bid_proxy_usdt=59190, book20_ask_proxy_usdt=60142, funding_indicative=-0.000180, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.86%, turnover=59312727. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T14:29:59+00:00, last15m_closed_end=2026-10-23T14:30+00:00, prior8high=54.240000, depth_time=2026-10-23T14:30:19+00:00, book20_bid_proxy_usdt=27376491, book20_ask_proxy_usdt=25600514, funding_indicative=0.000068, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.58%, turnover=343876400. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T14:29:59+00:00, last15m_closed_end=2026-10-23T14:30+00:00, prior8high=0.053770, depth_time=2026-10-23T14:30:22+00:00, book20_bid_proxy_usdt=619930, book20_ask_proxy_usdt=562048, funding_indicative=-0.000023, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.55%, turnover=11890770. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T14:29:59+00:00, last15m_closed_end=2026-10-23T14:30+00:00, prior8high=0.552300, depth_time=2026-10-23T14:30:16+00:00, book20_bid_proxy_usdt=228225, book20_ask_proxy_usdt=404621, funding_indicative=-0.000005, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.55%, turnover=24972326. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T14:29:59+00:00, last15m_closed_end=2026-10-23T14:30+00:00, prior8high=4035.760000, depth_time=2026-10-23T14:30:39+00:00, book20_bid_proxy_usdt=127921, book20_ask_proxy_usdt=193651, funding_indicative=0.000050, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.72%, turnover=233372198. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T14:29:59+00:00, last15m_closed_end=2026-10-23T14:30+00:00, prior8high=4042.750000, depth_time=2026-10-23T14:30:36+00:00, book20_bid_proxy_usdt=1851155, book20_ask_proxy_usdt=1080804, funding_indicative=0.000170, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.78%, turnover=613576144. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
