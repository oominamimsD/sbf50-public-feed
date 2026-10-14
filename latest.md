# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T19:00:28Z**
- feed_generated_utc: 2026-10-14T19:00:29+00:00
- source_sha256: `9777dc9d2968c92ceb6581d56234e7a1f0247e3871ea6e195f9c102300ac9f21`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T19:00+00:00, close=81679.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T19:00+00:00, close=81679.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T16:00+00:00, close=81600.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.164700|-11.13|75.09|-11.22|58855425|3.23|
|S_USDT|0.052560|-5.36|31.92|-5.45|6833038|1.90|
|FET_USDT|0.200800|-3.50|-11.34|-3.59|9224185|4.98|
|PUMPFUN_USDT|0.004721|-2.61|-24.71|-2.70|21393083|4.24|
|BAT_USDT|0.170490|-2.25|71.93|-2.34|35379370|1.76|
|LDO_USDT|0.402200|-1.90|-5.89|-1.99|5002698|2.49|
|STRK_USDT|0.075990|-1.54|53.63|-1.63|23741276|3.95|
|AAVE_USDT|154.520000|-1.42|-10.03|-1.51|23445128|0.65|
|ENA_USDT|0.195900|-1.39|-14.13|-1.48|36477796|0.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.520000|153.970000|154.520000|0.67|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.170490|0.169480|0.170490|0.45|N|Y/Y|N/N|Y|N|
|BTW_USDT|2.164700|2.064400|2.165600|0.59|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.195900|0.195010|0.195900|0.45|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.200800|0.200100|0.200700|0.78|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.402200|0.400600|0.402200|0.69|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004721|0.004673|0.004721|0.31|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.075990|0.075170|0.076030|0.32|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.052560|0.052320|0.052560|0.50|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-14T19:00:02+00:00, last15m_closed_end=2026-10-14T19:00+00:00, prior8high=158.400000, depth_time=2026-10-14T19:00:24+00:00, book20_bid_proxy_usdt=188061, book20_ask_proxy_usdt=307709, funding_indicative=0.000028, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.42%, turnover=23445128. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-14T19:00:02+00:00, last15m_closed_end=2026-10-14T19:00+00:00, prior8high=0.174590, depth_time=2026-10-14T19:00:17+00:00, book20_bid_proxy_usdt=21150, book20_ask_proxy_usdt=30568, funding_indicative=0.000046, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.25%, turnover=35379370. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-14T19:00:02+00:00, last15m_closed_end=2026-10-14T19:00+00:00, prior8high=2.353800, depth_time=2026-10-14T19:00:08+00:00, book20_bid_proxy_usdt=7342, book20_ask_proxy_usdt=10591, funding_indicative=-0.000012, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-11.13%, turnover=58855425. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-14T19:00:02+00:00, last15m_closed_end=2026-10-14T19:00+00:00, prior8high=0.200340, depth_time=2026-10-14T19:00:27+00:00, book20_bid_proxy_usdt=139873, book20_ask_proxy_usdt=298727, funding_indicative=0.000036, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.39%, turnover=36477796. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T19:00:02+00:00, last15m_closed_end=2026-10-14T19:00+00:00, prior8high=0.208600, depth_time=2026-10-14T19:00:12+00:00, book20_bid_proxy_usdt=1447522, book20_ask_proxy_usdt=1367771, funding_indicative=-0.000005, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.50%, turnover=9224185. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-14T19:00:02+00:00, last15m_closed_end=2026-10-14T19:00+00:00, prior8high=0.412700, depth_time=2026-10-14T19:00:19+00:00, book20_bid_proxy_usdt=521028, book20_ask_proxy_usdt=620415, funding_indicative=-0.000085, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=5002698. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-14T19:00:02+00:00, last15m_closed_end=2026-10-14T19:00+00:00, prior8high=0.004810, depth_time=2026-10-14T19:00:15+00:00, book20_bid_proxy_usdt=2221231, book20_ask_proxy_usdt=1235068, funding_indicative=0.000050, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.61%, turnover=21393083. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T19:00:02+00:00, last15m_closed_end=2026-10-14T19:00+00:00, prior8high=0.077570, depth_time=2026-10-14T19:00:21+00:00, book20_bid_proxy_usdt=198033, book20_ask_proxy_usdt=220562, funding_indicative=0.000049, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.54%, turnover=23741276. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T19:00:02+00:00, last15m_closed_end=2026-10-14T19:00+00:00, prior8high=0.053970, depth_time=2026-10-14T19:00:09+00:00, book20_bid_proxy_usdt=153348, book20_ask_proxy_usdt=163664, funding_indicative=-0.000070, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.36%, turnover=6833038. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
