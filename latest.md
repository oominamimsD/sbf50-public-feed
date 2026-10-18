# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T04:30:33Z**
- feed_generated_utc: 2026-10-18T04:30:35+00:00
- source_sha256: `912c62d00a3fa38c88fd66e6fd6176e75952b4c51c9cf2d9d27f146bb5556d9c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T04:30+00:00, close=81882.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T04:00+00:00, close=81919.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T04:00+00:00, close=81919.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.063290|-4.32|-32.25|-5.01|14189969|1.58|
|TIA_USDT|0.631300|-4.05|23.06|-4.74|69948143|3.17|
|QNT_USDT|195.540000|-2.43|-20.23|-3.12|70007954|1.53|
|EIGEN_USDT|0.250300|-2.34|6.23|-3.03|9640962|4.00|
|FILECOIN_USDT|1.062800|-2.26|-5.76|-2.95|20875516|0.94|
|PUMPFUN_USDT|0.004354|-1.31|-23.94|-2.00|23307229|2.30|
|DOT_USDT|1.109100|-0.74|-11.75|-1.43|16559106|1.80|
|ICNT_USDT|0.184000|-0.64|85.67|-1.33|14388575|5.44|
|APT_USDT|0.792900|-0.57|-4.10|-1.26|10038248|1.26|
|OP_USDT|0.128290|-0.55|-7.40|-1.24|9458396|0.78|
|WLD_USDT|0.493600|-0.40|-11.69|-1.09|63542067|2.03|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.792900|0.788100|0.792500|0.34|N|Y/Y|Y/Y|N|N|
|DOT_USDT|1.109100|1.104700|1.109100|0.63|N|Y/Y|Y/Y|N|N|
|EIGEN_USDT|0.250300|0.247900|0.250300|1.50|N|Y/Y|N/Y|N|N|
|FILECOIN_USDT|1.062800|1.056600|1.062100|1.10|N|Y/Y|Y/Y|N|N|
|ICNT_USDT|0.184000|0.152200|0.184000|1.10|N|Y/Y|N/N|N|N|
|OP_USDT|0.128290|0.127270|0.128260|0.37|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004354|0.004301|0.004354|0.53|N|Y/Y|Y/Y|N|N|
|QNT_USDT|195.540000|194.620000|195.540000|0.16|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.063290|0.063200|0.063290|0.77|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.631300|0.628300|0.631300|0.93|N|Y/Y|Y/N|N|N|
|WLD_USDT|0.493600|0.489400|0.493600|0.33|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-18T04:29:59+00:00, last15m_closed_end=2026-10-18T04:30+00:00, prior8high=0.800600, depth_time=2026-10-18T04:30:26+00:00, book20_bid_proxy_usdt=165184, book20_ask_proxy_usdt=122319, funding_indicative=-0.000084, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.57%, turnover=10038248. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T04:29:59+00:00, last15m_closed_end=2026-10-18T04:30+00:00, prior8high=1.120700, depth_time=2026-10-18T04:30:22+00:00, book20_bid_proxy_usdt=374234, book20_ask_proxy_usdt=280278, funding_indicative=-0.000007, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.74%, turnover=16559106. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T04:29:59+00:00, last15m_closed_end=2026-10-18T04:30+00:00, prior8high=0.253900, depth_time=2026-10-18T04:30:14+00:00, book20_bid_proxy_usdt=543616, book20_ask_proxy_usdt=331460, funding_indicative=0.000013, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.34%, turnover=9640962. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T04:29:59+00:00, last15m_closed_end=2026-10-18T04:30+00:00, prior8high=1.074100, depth_time=2026-10-18T04:30:18+00:00, book20_bid_proxy_usdt=773278, book20_ask_proxy_usdt=647244, funding_indicative=-0.000095, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=20875516. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-18T04:29:59+00:00, last15m_closed_end=2026-10-18T04:30+00:00, prior8high=0.179900, depth_time=2026-10-18T04:30:26+00:00, book20_bid_proxy_usdt=403259, book20_ask_proxy_usdt=157503, funding_indicative=0.000042, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.64%, turnover=14388575. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T04:29:59+00:00, last15m_closed_end=2026-10-18T04:30+00:00, prior8high=0.129950, depth_time=2026-10-18T04:30:30+00:00, book20_bid_proxy_usdt=113676, book20_ask_proxy_usdt=80903, funding_indicative=-0.000173, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.55%, turnover=9458396. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T04:29:59+00:00, last15m_closed_end=2026-10-18T04:30+00:00, prior8high=0.004401, depth_time=2026-10-18T04:30:20+00:00, book20_bid_proxy_usdt=2315166, book20_ask_proxy_usdt=1299547, funding_indicative=0.000025, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=23307229. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T04:29:59+00:00, last15m_closed_end=2026-10-18T04:30+00:00, prior8high=197.180000, depth_time=2026-10-18T04:30:13+00:00, book20_bid_proxy_usdt=78205, book20_ask_proxy_usdt=67544, funding_indicative=-0.000119, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.43%, turnover=70007954. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T04:29:59+00:00, last15m_closed_end=2026-10-18T04:30+00:00, prior8high=0.064400, depth_time=2026-10-18T04:30:08+00:00, book20_bid_proxy_usdt=315433, book20_ask_proxy_usdt=353362, funding_indicative=0.000050, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.32%, turnover=14189969. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T04:29:59+00:00, last15m_closed_end=2026-10-18T04:30+00:00, prior8high=0.638400, depth_time=2026-10-18T04:30:10+00:00, book20_bid_proxy_usdt=275642, book20_ask_proxy_usdt=196241, funding_indicative=-0.000006, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.05%, turnover=69948143. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T04:29:59+00:00, last15m_closed_end=2026-10-18T04:30+00:00, prior8high=0.498500, depth_time=2026-10-18T04:30:32+00:00, book20_bid_proxy_usdt=2280805, book20_ask_proxy_usdt=2057385, funding_indicative=-0.000156, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.40%, turnover=63542067. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
