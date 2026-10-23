# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T09:30:28Z**
- feed_generated_utc: 2026-10-23T09:30:30+00:00
- source_sha256: `6e50087e3ba06ee3c067ae477c20b5615f387d720dfc8622e75d22e5f6a0ee52`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T09:30+00:00, close=81610, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T09:00+00:00, close=81725, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T08:00+00:00, close=81544.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.377600|-6.54|9.25|-6.50|9528186|0.30|
|STRK_USDT|0.051820|-4.67|-46.22|-4.63|12216910|3.86|
|TIA_USDT|0.550000|-3.23|-8.71|-3.19|25311432|1.82|
|QNT_USDT|185.660000|-2.64|-10.70|-2.60|48222554|1.08|
|PUMPFUN_USDT|0.004573|-2.26|1.03|-2.22|36200622|2.19|
|SILVER_USDT|54.060000|-2.17|-5.39|-2.13|335425358|1.85|
|ARB_USDT|0.180090|-1.93|-5.18|-1.89|25468624|0.56|
|OP_USDT|0.118070|-1.48|-14.97|-1.44|6221069|0.85|
|HBAR_USDT|0.079240|-1.08|-5.15|-1.04|19666713|1.26|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.180090|0.181050|0.180090|3.31|Y|Y/Y|Y/Y|Y|Y|
|HBAR_USDT|0.079240|0.079720|0.079240|2.69|Y|Y/Y|Y/Y|Y|Y|
|LIT_USDT|3.377600|3.398400|3.377600|1.31|Y|Y/Y|Y/Y|Y|Y|
|OP_USDT|0.118070|0.118470|0.118070|1.23|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004573|0.004580|0.004573|4.43|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|185.660000|186.530000|185.660000|3.55|Y|Y/Y|Y/Y|Y|Y|
|SILVER_USDT|54.060000|53.870000|54.060000|0.61|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.051820|0.051860|0.051820|3.53|Y|Y/Y|Y/Y|Y|Y|
|TIA_USDT|0.550000|0.551300|0.550000|3.08|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-23T09:30:01+00:00, last15m_closed_end=2026-10-23T09:30+00:00, prior8high=0.182660, depth_time=2026-10-23T09:30:23+00:00, book20_bid_proxy_usdt=85445, book20_ask_proxy_usdt=61478, funding_indicative=-0.000025, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=25468624. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-23T09:30:01+00:00, last15m_closed_end=2026-10-23T09:30+00:00, prior8high=0.080640, depth_time=2026-10-23T09:30:28+00:00, book20_bid_proxy_usdt=681809, book20_ask_proxy_usdt=677916, funding_indicative=0.000030, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.08%, turnover=19666713. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T09:30:01+00:00, last15m_closed_end=2026-10-23T09:30+00:00, prior8high=3.450000, depth_time=2026-10-23T09:30:07+00:00, book20_bid_proxy_usdt=23877, book20_ask_proxy_usdt=29232, funding_indicative=0.000050, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.54%, turnover=9528186. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T09:30:01+00:00, last15m_closed_end=2026-10-23T09:30+00:00, prior8high=0.120130, depth_time=2026-10-23T09:30:25+00:00, book20_bid_proxy_usdt=176470, book20_ask_proxy_usdt=117130, funding_indicative=-0.000024, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=6221069. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T09:30:01+00:00, last15m_closed_end=2026-10-23T09:30+00:00, prior8high=0.004660, depth_time=2026-10-23T09:30:17+00:00, book20_bid_proxy_usdt=2133640, book20_ask_proxy_usdt=2330615, funding_indicative=0.000005, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.26%, turnover=36200622. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T09:30:01+00:00, last15m_closed_end=2026-10-23T09:30+00:00, prior8high=189.550000, depth_time=2026-10-23T09:30:14+00:00, book20_bid_proxy_usdt=69875, book20_ask_proxy_usdt=83958, funding_indicative=-0.000164, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.64%, turnover=48222554. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T09:30:01+00:00, last15m_closed_end=2026-10-23T09:30+00:00, prior8high=54.210000, depth_time=2026-10-23T09:30:20+00:00, book20_bid_proxy_usdt=31808414, book20_ask_proxy_usdt=29690107, funding_indicative=0.000120, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.17%, turnover=335425358. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T09:30:01+00:00, last15m_closed_end=2026-10-23T09:30+00:00, prior8high=0.053480, depth_time=2026-10-23T09:30:10+00:00, book20_bid_proxy_usdt=505719, book20_ask_proxy_usdt=621152, funding_indicative=-0.000002, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.67%, turnover=12216910. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T09:30:01+00:00, last15m_closed_end=2026-10-23T09:30+00:00, prior8high=0.560600, depth_time=2026-10-23T09:30:12+00:00, book20_bid_proxy_usdt=406713, book20_ask_proxy_usdt=354582, funding_indicative=-0.000014, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.23%, turnover=25311432. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
