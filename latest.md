# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T22:15:20Z**
- feed_generated_utc: 2026-11-07T22:15:21+00:00
- source_sha256: `27a50efa7f490c7916788ff95d5f2dbce166c6acc73fa8a9365bde37a82a9fcf`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T22:15+00:00, close=75705.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T22:00+00:00, close=75715.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T20:00+00:00, close=75772.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.121200|-2.57|-60.99|-2.55|9535129|8.25|
|AAVE_USDT|130.000000|-1.68|-4.06|-1.66|8721632|0.77|
|QNT_USDT|195.690000|-1.58|-2.66|-1.56|41104437|1.53|
|PEPE_USDT|0.000005|-1.38|-3.06|-1.36|41773016|0.21|
|TIA_USDT|0.435500|-1.38|-11.14|-1.36|6849505|2.30|
|WLD_USDT|0.331300|-1.28|-18.07|-1.26|25633622|3.02|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.000000|129.130000|130.000000|0.48|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|2.55|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.690000|195.990000|195.690000|0.96|N|Y/N|N/N|Y|N|
|TIA_USDT|0.435500|0.432500|0.435500|1.21|N|Y/Y|N/N|Y|N|
|UAI_USDT|0.121200|0.120300|0.121200|1.66|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.331300|0.327700|0.331300|1.03|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-07T22:15:01+00:00, last15m_closed_end=2026-11-07T22:15+00:00, prior8high=131.230000, depth_time=2026-11-07T22:15:06+00:00, book20_bid_proxy_usdt=409449, book20_ask_proxy_usdt=353168, funding_indicative=0.000037, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.68%, turnover=8721632. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-07T22:15:01+00:00, last15m_closed_end=2026-11-07T22:15+00:00, prior8high=0.000005, depth_time=2026-11-07T22:15:12+00:00, book20_bid_proxy_usdt=17330, book20_ask_proxy_usdt=23503, funding_indicative=0.000036, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.38%, turnover=41773016. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-07T22:15:01+00:00, last15m_closed_end=2026-11-07T22:15+00:00, prior8high=198.600000, depth_time=2026-11-07T22:15:11+00:00, book20_bid_proxy_usdt=31078, book20_ask_proxy_usdt=84918, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=41104437. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-07T22:15:01+00:00, last15m_closed_end=2026-11-07T22:15+00:00, prior8high=0.442100, depth_time=2026-11-07T22:15:17+00:00, book20_bid_proxy_usdt=263962, book20_ask_proxy_usdt=322999, funding_indicative=0.000031, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.38%, turnover=6849505. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T22:15:01+00:00, last15m_closed_end=2026-11-07T22:15+00:00, prior8high=0.124500, depth_time=2026-11-07T22:15:01+00:00, book20_bid_proxy_usdt=211683, book20_ask_proxy_usdt=146794, funding_indicative=0.000050, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.57%, turnover=9535129. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-07T22:15:01+00:00, last15m_closed_end=2026-11-07T22:15+00:00, prior8high=0.334300, depth_time=2026-11-07T22:15:16+00:00, book20_bid_proxy_usdt=3098289, book20_ask_proxy_usdt=4325676, funding_indicative=-0.000117, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=25633622. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
