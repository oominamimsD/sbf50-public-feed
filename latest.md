# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T14:00:31Z**
- feed_generated_utc: 2026-11-06T14:00:32+00:00
- source_sha256: `2e93bb7b641fdc32395427a3b80f0ad53f8de2d627abb05a7b3a6201cb1b2e5f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T14:00+00:00, close=75866.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T14:00+00:00, close=75866.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T12:00+00:00, close=76114.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BCH_USDT|266.130000|-6.55|-7.68|-6.37|6806996|1.13|
|ANTHROPIC_USDT|1416.310000|-5.46|-21.32|-5.28|5931856|2.26|
|QNT_USDT|189.200000|-5.22|-4.80|-5.04|36805209|2.11|
|XRP_USDT|1.186500|-4.66|-9.39|-4.48|474253987|0.84|
|NEAR_USDT|3.717000|-3.90|-20.04|-3.72|70710756|2.69|
|ONDO_USDT|0.373900|-3.88|-13.00|-3.70|25844353|2.67|
|XLM_USDT|0.154430|-3.61|-10.59|-3.43|36211093|0.65|
|SOL_USDT|90.340000|-2.81|-11.98|-2.63|814963159|1.11|
|DOGE_USDT|0.072440|-2.43|-10.15|-2.25|143758228|1.38|
|XAUT_USDT|4027.330000|-1.62|0.14|-1.44|191225618|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1416.310000|1397.580000|1416.610000|20.75|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|266.130000|265.100000|266.130000|0.69|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.072440|0.071920|0.072440|0.62|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.717000|3.685000|3.717000|2.15|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.373900|0.370900|0.373900|0.89|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|189.200000|188.210000|189.200000|2.93|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|90.340000|89.710000|90.340000|0.74|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4027.330000|4001.340000|4027.330000|2.73|N|Y/Y|N/N|Y|N|
|XLM_USDT|0.154430|0.152810|0.154430|1.04|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.186500|1.177800|1.186400|0.44|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-06T14:00:02+00:00, last15m_closed_end=2026-11-06T14:00+00:00, prior8high=1510.080000, depth_time=2026-11-06T14:00:10+00:00, book20_bid_proxy_usdt=7232, book20_ask_proxy_usdt=6697, funding_indicative=0.000050, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.46%, turnover=5931856. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-06T14:00:02+00:00, last15m_closed_end=2026-11-06T14:00+00:00, prior8high=271.890000, depth_time=2026-11-06T14:00:07+00:00, book20_bid_proxy_usdt=39086, book20_ask_proxy_usdt=51879, funding_indicative=-0.000038, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.55%, turnover=6806996. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-06T14:00:02+00:00, last15m_closed_end=2026-11-06T14:00+00:00, prior8high=0.072960, depth_time=2026-11-06T14:00:28+00:00, book20_bid_proxy_usdt=5445058, book20_ask_proxy_usdt=6659802, funding_indicative=0.000068, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.43%, turnover=143758228. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-06T14:00:02+00:00, last15m_closed_end=2026-11-06T14:00+00:00, prior8high=3.795000, depth_time=2026-11-06T14:00:17+00:00, book20_bid_proxy_usdt=2610918, book20_ask_proxy_usdt=4069254, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.90%, turnover=70710756. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-06T14:00:02+00:00, last15m_closed_end=2026-11-06T14:00+00:00, prior8high=0.379400, depth_time=2026-11-06T14:00:20+00:00, book20_bid_proxy_usdt=1691858, book20_ask_proxy_usdt=1317890, funding_indicative=0.000050, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.88%, turnover=25844353. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T14:00:02+00:00, last15m_closed_end=2026-11-06T14:00+00:00, prior8high=192.700000, depth_time=2026-11-06T14:00:12+00:00, book20_bid_proxy_usdt=46326, book20_ask_proxy_usdt=97348, funding_indicative=-0.000007, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.22%, turnover=36805209. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-06T14:00:02+00:00, last15m_closed_end=2026-11-06T14:00+00:00, prior8high=90.860000, depth_time=2026-11-06T14:00:25+00:00, book20_bid_proxy_usdt=10766203, book20_ask_proxy_usdt=14065504, funding_indicative=0.000040, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.81%, turnover=814963159. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-11-06T14:00:02+00:00, last15m_closed_end=2026-11-06T14:00+00:00, prior8high=4057.200000, depth_time=2026-11-06T14:00:30+00:00, book20_bid_proxy_usdt=209904, book20_ask_proxy_usdt=155909, funding_indicative=0.000080, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.62%, turnover=191225618. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-06T14:00:02+00:00, last15m_closed_end=2026-11-06T14:00+00:00, prior8high=0.155540, depth_time=2026-11-06T14:00:22+00:00, book20_bid_proxy_usdt=125275, book20_ask_proxy_usdt=176015, funding_indicative=-0.000139, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.61%, turnover=36211093. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T14:00:02+00:00, last15m_closed_end=2026-11-06T14:00+00:00, prior8high=1.202300, depth_time=2026-11-06T14:00:15+00:00, book20_bid_proxy_usdt=2455238, book20_ask_proxy_usdt=3418384, funding_indicative=0.000096, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.66%, turnover=474253987. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
