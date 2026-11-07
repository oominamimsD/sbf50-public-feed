# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T00:45:33Z**
- feed_generated_utc: 2026-11-07T00:45:35+00:00
- source_sha256: `f76454ce2bfb103705603740342f5c9b3abda861d3c65c87d0ef15986d41c81e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T00:45+00:00, close=75884, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-07T00:00+00:00, close=75811.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T00:00+00:00, close=75811.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CYBER_USDT|0.326600|-7.74|19.54|-7.80|6923065|3.05|
|ANTHROPIC_USDT|1336.000000|-6.65|-20.30|-6.71|7489582|3.89|
|TRUMPOFFICIAL_USDT|1.201000|-3.30|-23.60|-3.36|12698582|8.33|
|PUMPFUN_USDT|0.003923|-3.01|-4.48|-3.07|12739127|2.55|
|DOT_USDT|0.910000|-2.89|-6.10|-2.95|7383293|1.10|
|ENA_USDT|0.163790|-2.22|-13.74|-2.28|33206386|1.22|
|ADA_USDT|0.184100|-2.12|-4.41|-2.18|28492037|5.43|
|LIT_USDT|3.342900|-1.45|18.36|-1.51|9423514|0.30|
|HBAR_USDT|0.067590|-1.18|-5.92|-1.24|5201075|1.48|
|XLM_USDT|0.153500|-1.01|-10.88|-1.07|23565198|0.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.184100|0.183700|0.184100|0.59|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1336.000000|1322.000000|1336.000000|0.06|N|Y/Y|Y/Y|Y|N|
|CYBER_USDT|0.326600|0.327000|0.326600|1.12|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.910000|0.909000|0.910000|0.29|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.163790|0.163290|0.163790|0.95|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.067590|0.067340|0.067590|0.46|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.342900|3.292600|3.342200|0.87|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003923|0.003882|0.003923|0.18|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.201000|1.196000|1.201000|0.55|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.153500|0.153080|0.153510|0.45|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-07T00:45:02+00:00, last15m_closed_end=2026-11-07T00:45+00:00, prior8high=0.185900, depth_time=2026-11-07T00:45:24+00:00, book20_bid_proxy_usdt=10300087, book20_ask_proxy_usdt=10320540, funding_indicative=0.000100, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=28492037. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-07T00:45:02+00:00, last15m_closed_end=2026-11-07T00:45+00:00, prior8high=1351.160000, depth_time=2026-11-07T00:45:11+00:00, book20_bid_proxy_usdt=24131, book20_ask_proxy_usdt=17767, funding_indicative=0.000050, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.65%, turnover=7489582. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CYBER_USDT: quote_utc=2026-11-07T00:45:02+00:00, last15m_closed_end=2026-11-07T00:45+00:00, prior8high=0.348400, depth_time=2026-11-07T00:45:08+00:00, book20_bid_proxy_usdt=233244, book20_ask_proxy_usdt=92492, funding_indicative=-0.002279, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.74%, turnover=6923065. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T00:45:02+00:00, last15m_closed_end=2026-11-07T00:45+00:00, prior8high=0.920800, depth_time=2026-11-07T00:45:18+00:00, book20_bid_proxy_usdt=514138, book20_ask_proxy_usdt=434424, funding_indicative=0.000100, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.89%, turnover=7383293. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T00:45:02+00:00, last15m_closed_end=2026-11-07T00:45+00:00, prior8high=0.164890, depth_time=2026-11-07T00:45:18+00:00, book20_bid_proxy_usdt=228944, book20_ask_proxy_usdt=220586, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.22%, turnover=33206386. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-07T00:45:02+00:00, last15m_closed_end=2026-11-07T00:45+00:00, prior8high=0.067750, depth_time=2026-11-07T00:45:30+00:00, book20_bid_proxy_usdt=852426, book20_ask_proxy_usdt=594952, funding_indicative=-0.000024, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.18%, turnover=5201075. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-07T00:45:02+00:00, last15m_closed_end=2026-11-07T00:45+00:00, prior8high=3.352300, depth_time=2026-11-07T00:45:25+00:00, book20_bid_proxy_usdt=23334, book20_ask_proxy_usdt=24346, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.45%, turnover=9423514. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T00:45:02+00:00, last15m_closed_end=2026-11-07T00:45+00:00, prior8high=0.003974, depth_time=2026-11-07T00:45:16+00:00, book20_bid_proxy_usdt=2050424, book20_ask_proxy_usdt=2434380, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=12739127. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T00:45:02+00:00, last15m_closed_end=2026-11-07T00:45+00:00, prior8high=1.223000, depth_time=2026-11-07T00:45:07+00:00, book20_bid_proxy_usdt=1537747, book20_ask_proxy_usdt=1443126, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.30%, turnover=12698582. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-07T00:45:02+00:00, last15m_closed_end=2026-11-07T00:45+00:00, prior8high=0.154720, depth_time=2026-11-07T00:45:28+00:00, book20_bid_proxy_usdt=244282, book20_ask_proxy_usdt=231141, funding_indicative=0.000009, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.01%, turnover=23565198. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
