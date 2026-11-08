# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T08:45:24Z**
- feed_generated_utc: 2026-11-08T08:45:25+00:00
- source_sha256: `ce77557a63b5a13cd14edb892ed3aa13130f04a954c821f2e9728f3bb2f024bb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T08:45+00:00, close=75895.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T08:00+00:00, close=75939, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T08:00+00:00, close=75939, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TIA_USDT|0.428200|-3.03|-12.63|-3.25|7561525|2.33|
|ENA_USDT|0.154620|-2.25|-20.30|-2.47|29476158|0.65|
|WLD_USDT|0.328500|-2.11|-18.76|-2.33|24097714|3.04|
|QNT_USDT|195.860000|-1.50|-2.58|-1.72|43972382|1.53|
|AAVE_USDT|130.570000|-1.25|-3.64|-1.47|10883067|0.77|
|LINK_USDT|10.735000|-1.00|-7.22|-1.22|66567356|0.93|
|ONDO_USDT|0.360000|-0.85|-12.70|-1.07|8513734|2.78|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.570000|129.910000|130.570000|0.98|N|Y/Y|Y/N|Y|N|
|ENA_USDT|0.154620|0.153450|0.154620|1.67|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.735000|10.708000|10.734000|0.89|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.360000|0.357600|0.360200|0.57|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.860000|194.160000|195.860000|0.75|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.428200|0.428500|0.428200|3.43|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.328500|0.328600|0.328500|3.21|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T08:45:02+00:00, last15m_closed_end=2026-11-08T08:45+00:00, prior8high=130.800000, depth_time=2026-11-08T08:45:18+00:00, book20_bid_proxy_usdt=790846, book20_ask_proxy_usdt=424864, funding_indicative=0.000020, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=10883067. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T08:45:02+00:00, last15m_closed_end=2026-11-08T08:45+00:00, prior8high=0.154850, depth_time=2026-11-08T08:45:06+00:00, book20_bid_proxy_usdt=202818, book20_ask_proxy_usdt=267163, funding_indicative=0.000028, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.25%, turnover=29476158. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T08:45:02+00:00, last15m_closed_end=2026-11-08T08:45+00:00, prior8high=10.753000, depth_time=2026-11-08T08:45:18+00:00, book20_bid_proxy_usdt=524618, book20_ask_proxy_usdt=608862, funding_indicative=0.000062, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=66567356. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T08:45:02+00:00, last15m_closed_end=2026-11-08T08:45+00:00, prior8high=0.360600, depth_time=2026-11-08T08:45:21+00:00, book20_bid_proxy_usdt=1247434, book20_ask_proxy_usdt=1791292, funding_indicative=0.000000, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.85%, turnover=8513734. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T08:45:02+00:00, last15m_closed_end=2026-11-08T08:45+00:00, prior8high=196.140000, depth_time=2026-11-08T08:45:15+00:00, book20_bid_proxy_usdt=72928, book20_ask_proxy_usdt=80165, funding_indicative=0.000100, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.50%, turnover=43972382. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T08:45:02+00:00, last15m_closed_end=2026-11-08T08:45+00:00, prior8high=0.433300, depth_time=2026-11-08T08:45:07+00:00, book20_bid_proxy_usdt=298649, book20_ask_proxy_usdt=348511, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.03%, turnover=7561525. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T08:45:02+00:00, last15m_closed_end=2026-11-08T08:45+00:00, prior8high=0.331200, depth_time=2026-11-08T08:45:12+00:00, book20_bid_proxy_usdt=3635096, book20_ask_proxy_usdt=3720251, funding_indicative=-0.000173, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.11%, turnover=24097714. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
