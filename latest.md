# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T20:00:32Z**
- feed_generated_utc: 2026-10-26T20:00:35+00:00
- source_sha256: `1bc78fa20c10f21346cb432033d38be86eb2ceaed36462e4fee1cbb9846ee01f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T20:00+00:00, close=79988.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T20:00+00:00, close=79988.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T20:00+00:00, close=79988.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.128900|-5.58|-35.56|-5.09|20220105|0.89|
|IRYS_USDT|0.026140|-5.22|112.86|-4.73|9415398|3.83|
|NEAR_USDT|4.479000|-3.78|-8.66|-3.29|116531009|2.23|
|LIT_USDT|3.044300|-3.34|0.40|-2.85|5052409|0.33|
|PUMPFUN_USDT|0.004225|-3.02|-5.18|-2.53|22103673|2.37|
|ARB_USDT|0.168290|-2.10|-13.97|-1.61|20439827|0.59|
|FILECOIN_USDT|0.907000|-2.10|-10.37|-1.61|5936774|1.10|
|AAVE_USDT|135.080000|-2.03|-8.24|-1.54|27800072|0.74|
|APT_USDT|0.693900|-1.85|-9.04|-1.36|5294641|1.44|
|SOL_USDT|100.410000|-1.64|-3.53|-1.15|652087846|0.99|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|135.080000|134.390000|135.080000|0.34|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.693900|0.689500|0.693900|0.29|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.168290|0.166530|0.168290|0.44|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.128900|1.103200|1.124500|0.19|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.907000|0.904500|0.907000|0.09|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.026140|0.026060|0.026120|1.01|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.044300|3.043100|3.044300|0.76|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.479000|4.442000|4.479000|0.40|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004225|0.004209|0.004225|0.34|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|100.410000|100.220000|100.410000|0.48|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-26T20:00:02+00:00, last15m_closed_end=2026-10-26T20:00+00:00, prior8high=136.550000, depth_time=2026-10-26T20:00:24+00:00, book20_bid_proxy_usdt=386344, book20_ask_proxy_usdt=448845, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.03%, turnover=27800072. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-26T20:00:02+00:00, last15m_closed_end=2026-10-26T20:00+00:00, prior8high=0.702300, depth_time=2026-10-26T20:00:28+00:00, book20_bid_proxy_usdt=179622, book20_ask_proxy_usdt=177057, funding_indicative=-0.000018, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=5294641. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-26T20:00:02+00:00, last15m_closed_end=2026-10-26T20:00+00:00, prior8high=0.169070, depth_time=2026-10-26T20:00:21+00:00, book20_bid_proxy_usdt=87733, book20_ask_proxy_usdt=86566, funding_indicative=-0.000030, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=20439827. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T20:00:02+00:00, last15m_closed_end=2026-10-26T20:00+00:00, prior8high=1.304000, depth_time=2026-10-26T20:00:08+00:00, book20_bid_proxy_usdt=13747, book20_ask_proxy_usdt=18512, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.58%, turnover=20220105. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-26T20:00:02+00:00, last15m_closed_end=2026-10-26T20:00+00:00, prior8high=0.916900, depth_time=2026-10-26T20:00:22+00:00, book20_bid_proxy_usdt=1006207, book20_ask_proxy_usdt=1304449, funding_indicative=0.000063, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=5936774. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T20:00:02+00:00, last15m_closed_end=2026-10-26T20:00+00:00, prior8high=0.027280, depth_time=2026-10-26T20:00:10+00:00, book20_bid_proxy_usdt=143561, book20_ask_proxy_usdt=100842, funding_indicative=-0.000773, next_funding_utc=2026-10-26T21:00:00+00:00, funding_cycle_h=1, 24h_change=-5.22%, turnover=9415398. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T20:00:02+00:00, last15m_closed_end=2026-10-26T20:00+00:00, prior8high=3.132600, depth_time=2026-10-26T20:00:14+00:00, book20_bid_proxy_usdt=20340, book20_ask_proxy_usdt=23357, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.34%, turnover=5052409. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T20:00:02+00:00, last15m_closed_end=2026-10-26T20:00+00:00, prior8high=4.530000, depth_time=2026-10-26T20:00:13+00:00, book20_bid_proxy_usdt=5309026, book20_ask_proxy_usdt=3547647, funding_indicative=0.000085, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.78%, turnover=116531009. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T20:00:02+00:00, last15m_closed_end=2026-10-26T20:00+00:00, prior8high=0.004291, depth_time=2026-10-26T20:00:18+00:00, book20_bid_proxy_usdt=2202586, book20_ask_proxy_usdt=1652184, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.02%, turnover=22103673. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-26T20:00:02+00:00, last15m_closed_end=2026-10-26T20:00+00:00, prior8high=101.510000, depth_time=2026-10-26T20:00:30+00:00, book20_bid_proxy_usdt=20589192, book20_ask_proxy_usdt=19267450, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=652087846. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
