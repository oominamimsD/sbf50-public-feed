# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T18:00:34Z**
- feed_generated_utc: 2026-10-28T18:00:39+00:00
- source_sha256: `b71eb94e1639eead3de6bad956055fe3eb95e212563668a771ae9d01d75f5b18`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.08 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T18:00+00:00, close=80827.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T18:00+00:00, close=80827.7, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-28T16:00+00:00, close=80528, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TIA_USDT|0.523800|-3.01|-17.18|-3.58|14415399|7.64|
|STRK_USDT|0.045630|-2.50|-26.36|-3.07|5090772|2.19|
|WLD_USDT|0.425100|-1.77|-25.88|-2.34|62552429|7.04|
|OP_USDT|0.109710|-1.23|-16.82|-1.80|6364281|3.64|
|HBAR_USDT|0.075000|-1.19|-12.72|-1.76|11501251|5.32|
|ONDO_USDT|0.414400|-1.14|-11.18|-1.71|16395749|4.83|
|DOT_USDT|0.994200|-0.93|-15.73|-1.50|12145039|1.00|
|ARB_USDT|0.166300|-0.84|-15.41|-1.41|18890052|1.20|
|NEAR_USDT|4.593000|-0.77|-14.70|-1.34|90881405|2.18|
|AAVE_USDT|132.000000|-0.53|-16.72|-1.10|15344660|0.76|
|XMR_USDT|601.000000|-0.51|0.80|-1.08|5422486|3.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|132.000000|130.940000|131.810000|1.54|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.166300|0.164410|0.166160|2.36|N|Y/Y|Y/Y|N|N|
|DOT_USDT|0.994200|0.987000|0.991300|1.10|N|Y/Y|Y/Y|N|N|
|HBAR_USDT|0.075000|0.074660|0.074960|1.41|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|4.593000|4.557000|4.593000|0.77|N|Y/Y|N/N|N|N|
|ONDO_USDT|0.414400|0.412000|0.413700|0.75|N|Y/Y|N/N|N|N|
|OP_USDT|0.109710|0.109270|0.109680|1.08|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.045630|0.045520|0.045640|0.51|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.523800|0.523300|0.523600|0.73|N|Y/Y|N/Y|N|N|
|WLD_USDT|0.425100|0.416900|0.424700|0.50|N|Y/Y|Y/Y|N|N|
|XMR_USDT|601.000000|598.000000|600.480000|1.82|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-28T18:00:04+00:00, last15m_closed_end=2026-10-28T18:00+00:00, prior8high=132.900000, depth_time=2026-10-28T18:00:31+00:00, book20_bid_proxy_usdt=212942, book20_ask_proxy_usdt=197251, funding_indicative=0.000095, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.53%, turnover=15344660. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-28T18:00:04+00:00, last15m_closed_end=2026-10-28T18:00+00:00, prior8high=0.167890, depth_time=2026-10-28T18:00:26+00:00, book20_bid_proxy_usdt=31582, book20_ask_proxy_usdt=51097, funding_indicative=-0.000035, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.84%, turnover=18890052. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-28T18:00:04+00:00, last15m_closed_end=2026-10-28T18:00+00:00, prior8high=1.006600, depth_time=2026-10-28T18:00:24+00:00, book20_bid_proxy_usdt=114730, book20_ask_proxy_usdt=89670, funding_indicative=0.000049, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.93%, turnover=12145039. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T18:00:04+00:00, last15m_closed_end=2026-10-28T18:00+00:00, prior8high=0.075940, depth_time=2026-10-28T18:00:19+00:00, book20_bid_proxy_usdt=261768, book20_ask_proxy_usdt=400391, funding_indicative=0.000024, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.19%, turnover=11501251. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-28T18:00:04+00:00, last15m_closed_end=2026-10-28T18:00+00:00, prior8high=4.641000, depth_time=2026-10-28T18:00:28+00:00, book20_bid_proxy_usdt=1407864, book20_ask_proxy_usdt=3175494, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.77%, turnover=90881405. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-28T18:00:04+00:00, last15m_closed_end=2026-10-28T18:00+00:00, prior8high=0.419600, depth_time=2026-10-28T18:00:21+00:00, book20_bid_proxy_usdt=786052, book20_ask_proxy_usdt=841121, funding_indicative=0.000050, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.14%, turnover=16395749. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-28T18:00:05+00:00, last15m_closed_end=2026-10-28T18:00+00:00, prior8high=0.111150, depth_time=2026-10-28T18:00:17+00:00, book20_bid_proxy_usdt=62256, book20_ask_proxy_usdt=48769, funding_indicative=-0.000078, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.23%, turnover=6364281. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-28T18:00:04+00:00, last15m_closed_end=2026-10-28T18:00+00:00, prior8high=0.047080, depth_time=2026-10-28T18:00:12+00:00, book20_bid_proxy_usdt=640715, book20_ask_proxy_usdt=547761, funding_indicative=-0.000011, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.50%, turnover=5090772. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-28T18:00:04+00:00, last15m_closed_end=2026-10-28T18:00+00:00, prior8high=0.541600, depth_time=2026-10-28T18:00:09+00:00, book20_bid_proxy_usdt=82246, book20_ask_proxy_usdt=137823, funding_indicative=0.000029, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=14415399. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-28T18:00:04+00:00, last15m_closed_end=2026-10-28T18:00+00:00, prior8high=0.433500, depth_time=2026-10-28T18:00:14+00:00, book20_bid_proxy_usdt=2007762, book20_ask_proxy_usdt=1574803, funding_indicative=0.000010, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=62552429. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-28T18:00:05+00:00, last15m_closed_end=2026-10-28T18:00+00:00, prior8high=608.380000, depth_time=2026-10-28T18:00:33+00:00, book20_bid_proxy_usdt=10510, book20_ask_proxy_usdt=15969, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.51%, turnover=5422486. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
