# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T09:45:28Z**
- feed_generated_utc: 2026-10-23T09:45:30+00:00
- source_sha256: `0ce37bc0d53326a76fe85140401bd1a7215ed09cdc3d85c859a902251e4413ac`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T09:45+00:00, close=81643.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T09:00+00:00, close=81725, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T08:00+00:00, close=81544.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004114|-10.72|107.25|-10.72|7916737|7.29|
|LIT_USDT|3.385100|-6.33|9.50|-6.33|9597514|0.29|
|STRK_USDT|0.051980|-4.37|-46.05|-4.37|12350576|1.92|
|TIA_USDT|0.550700|-3.11|-8.59|-3.11|25698288|1.82|
|QNT_USDT|184.970000|-3.00|-11.03|-3.00|49367949|2.16|
|SILVER_USDT|53.930000|-2.40|-5.61|-2.40|338567819|1.85|
|PUMPFUN_USDT|0.004586|-1.98|1.32|-1.98|36367594|2.18|
|ARB_USDT|0.180440|-1.74|-5.00|-1.74|25913368|0.55|
|OP_USDT|0.118120|-1.44|-14.94|-1.44|6309824|0.85|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.180440|0.180040|0.180470|2.61|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.004114|0.004112|0.004114|1.54|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.385100|3.373700|3.385600|1.00|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.118120|0.118050|0.118120|2.24|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004586|0.004561|0.004586|2.22|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|184.970000|185.080000|184.970000|3.98|Y|Y/Y|Y/Y|Y|Y|
|SILVER_USDT|53.930000|53.870000|53.930000|1.68|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.051980|0.051740|0.051980|1.52|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.550700|0.548600|0.550700|1.56|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-23T09:45:02+00:00, last15m_closed_end=2026-10-23T09:45+00:00, prior8high=0.182660, depth_time=2026-10-23T09:45:25+00:00, book20_bid_proxy_usdt=60335, book20_ask_proxy_usdt=81047, funding_indicative=-0.000019, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=25913368. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-23T09:45:01+00:00, last15m_closed_end=2026-10-23T09:45+00:00, prior8high=0.004279, depth_time=2026-10-23T09:45:07+00:00, book20_bid_proxy_usdt=74001, book20_ask_proxy_usdt=45826, funding_indicative=0.000097, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.72%, turnover=7916737. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T09:45:02+00:00, last15m_closed_end=2026-10-23T09:45+00:00, prior8high=3.450000, depth_time=2026-10-23T09:45:09+00:00, book20_bid_proxy_usdt=19358, book20_ask_proxy_usdt=21576, funding_indicative=0.000050, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.33%, turnover=9597514. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T09:45:02+00:00, last15m_closed_end=2026-10-23T09:45+00:00, prior8high=0.120130, depth_time=2026-10-23T09:45:27+00:00, book20_bid_proxy_usdt=140731, book20_ask_proxy_usdt=125694, funding_indicative=-0.000011, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=6309824. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T09:45:02+00:00, last15m_closed_end=2026-10-23T09:45+00:00, prior8high=0.004660, depth_time=2026-10-23T09:45:22+00:00, book20_bid_proxy_usdt=1572655, book20_ask_proxy_usdt=2338371, funding_indicative=0.000004, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.98%, turnover=36367594. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T09:45:02+00:00, last15m_closed_end=2026-10-23T09:45+00:00, prior8high=189.550000, depth_time=2026-10-23T09:45:17+00:00, book20_bid_proxy_usdt=86192, book20_ask_proxy_usdt=95399, funding_indicative=-0.000168, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.00%, turnover=49367949. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T09:45:01+00:00, last15m_closed_end=2026-10-23T09:45+00:00, prior8high=54.210000, depth_time=2026-10-23T09:45:19+00:00, book20_bid_proxy_usdt=31976816, book20_ask_proxy_usdt=40023056, funding_indicative=0.000102, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.40%, turnover=338567819. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T09:45:02+00:00, last15m_closed_end=2026-10-23T09:45+00:00, prior8high=0.053480, depth_time=2026-10-23T09:45:11+00:00, book20_bid_proxy_usdt=729658, book20_ask_proxy_usdt=599625, funding_indicative=0.000006, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.37%, turnover=12350576. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T09:45:02+00:00, last15m_closed_end=2026-10-23T09:45+00:00, prior8high=0.560400, depth_time=2026-10-23T09:45:14+00:00, book20_bid_proxy_usdt=391626, book20_ask_proxy_usdt=421830, funding_indicative=-0.000002, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.11%, turnover=25698288. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
