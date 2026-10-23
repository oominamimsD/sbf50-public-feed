# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T10:45:30Z**
- feed_generated_utc: 2026-10-23T10:45:32+00:00
- source_sha256: `dc8d15f82ea03fd23e34397bb5f0f5290231a7e6eb8d8a95b01fca211821cd7b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T10:45+00:00, close=81656.3, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T10:00+00:00, close=81630.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T08:00+00:00, close=81544.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004111|-10.78|107.10|-10.78|7826251|7.29|
|LIT_USDT|3.380400|-6.46|9.34|-6.46|9316920|0.30|
|STRK_USDT|0.051360|-5.51|-46.69|-5.51|12009910|1.95|
|QNT_USDT|182.930000|-4.07|-12.01|-4.07|52309383|0.55|
|TIA_USDT|0.549700|-3.28|-8.76|-3.28|25469936|1.82|
|PUMPFUN_USDT|0.004561|-2.52|0.77|-2.52|35916536|2.19|
|SILVER_USDT|54.010000|-2.26|-5.47|-2.26|335341404|1.85|
|ZEC_USDT|1210.480000|-1.92|2.60|-1.92|1925622511|0.08|
|ARB_USDT|0.180250|-1.84|-5.10|-1.84|25439219|2.22|
|OP_USDT|0.118040|-1.51|-14.99|-1.51|6298890|0.85|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.180250|0.179350|0.180220|0.77|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.004111|0.004054|0.004113|1.30|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.380400|3.369300|3.380400|0.98|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.118040|0.117700|0.118040|1.23|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004561|0.004556|0.004560|0.47|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|182.930000|181.200000|182.930000|2.41|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|54.010000|53.870000|54.010000|1.49|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.051360|0.051360|0.051360|0.47|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.549700|0.548100|0.549700|0.50|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1210.480000|1213.940000|1211.180000|1.48|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-23T10:45:01+00:00, last15m_closed_end=2026-10-23T10:45+00:00, prior8high=0.182330, depth_time=2026-10-23T10:45:24+00:00, book20_bid_proxy_usdt=59614, book20_ask_proxy_usdt=105724, funding_indicative=-0.000021, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=25439219. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-23T10:45:01+00:00, last15m_closed_end=2026-10-23T10:45+00:00, prior8high=0.004266, depth_time=2026-10-23T10:45:06+00:00, book20_bid_proxy_usdt=42505, book20_ask_proxy_usdt=56159, funding_indicative=0.000064, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.78%, turnover=7826251. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T10:45:01+00:00, last15m_closed_end=2026-10-23T10:45+00:00, prior8high=3.438600, depth_time=2026-10-23T10:45:07+00:00, book20_bid_proxy_usdt=24732, book20_ask_proxy_usdt=23822, funding_indicative=0.000050, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.46%, turnover=9316920. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T10:45:01+00:00, last15m_closed_end=2026-10-23T10:45+00:00, prior8high=0.119730, depth_time=2026-10-23T10:45:29+00:00, book20_bid_proxy_usdt=124858, book20_ask_proxy_usdt=159282, funding_indicative=0.000019, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=6298890. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T10:45:01+00:00, last15m_closed_end=2026-10-23T10:45+00:00, prior8high=0.004660, depth_time=2026-10-23T10:45:19+00:00, book20_bid_proxy_usdt=2113445, book20_ask_proxy_usdt=1916358, funding_indicative=0.000010, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.52%, turnover=35916536. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T10:45:01+00:00, last15m_closed_end=2026-10-23T10:45+00:00, prior8high=188.130000, depth_time=2026-10-23T10:45:14+00:00, book20_bid_proxy_usdt=93702, book20_ask_proxy_usdt=103853, funding_indicative=-0.000141, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.07%, turnover=52309383. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T10:45:01+00:00, last15m_closed_end=2026-10-23T10:45+00:00, prior8high=54.210000, depth_time=2026-10-23T10:45:21+00:00, book20_bid_proxy_usdt=36750201, book20_ask_proxy_usdt=41248740, funding_indicative=0.000041, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.26%, turnover=335341404. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T10:45:01+00:00, last15m_closed_end=2026-10-23T10:45+00:00, prior8high=0.052870, depth_time=2026-10-23T10:45:12+00:00, book20_bid_proxy_usdt=539285, book20_ask_proxy_usdt=615409, funding_indicative=0.000041, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.51%, turnover=12009910. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T10:45:01+00:00, last15m_closed_end=2026-10-23T10:45+00:00, prior8high=0.555200, depth_time=2026-10-23T10:45:16+00:00, book20_bid_proxy_usdt=327601, book20_ask_proxy_usdt=269250, funding_indicative=0.000009, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.28%, turnover=25469936. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-23T10:45:01+00:00, last15m_closed_end=2026-10-23T10:45+00:00, prior8high=1237.640000, depth_time=2026-10-23T10:45:24+00:00, book20_bid_proxy_usdt=162484, book20_ask_proxy_usdt=536293, funding_indicative=0.000026, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.92%, turnover=1925622511. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
