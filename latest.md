# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-02T22:00:30Z**
- feed_generated_utc: 2026-11-02T22:00:32+00:00
- source_sha256: `47712c62af744dc8b2a342f3eb36c70549686ce88492262bc3661cc066aaeaf9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-02T22:00+00:00, close=76830.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-02T22:00+00:00, close=76830.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-02T20:00+00:00, close=77068.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1157.620000|-7.69|-7.22|-6.86|1845905740|0.09|
|XPL_USDT|0.067000|-3.70|-9.81|-2.87|10105897|1.49|
|ZRO_USDT|1.723900|-3.21|0.98|-2.38|5942681|1.74|
|PUMPFUN_USDT|0.003988|-2.82|-7.85|-1.99|9377515|2.51|
|QNT_USDT|196.950000|-2.71|-6.33|-1.88|48555361|0.51|
|NEAR_USDT|3.912000|-2.44|-14.45|-1.61|81636693|2.56|
|XLM_USDT|0.163700|-2.32|-3.47|-1.49|33044309|1.22|
|AAVE_USDT|127.980000|-1.97|-6.39|-1.14|23219391|0.78|
|TAO_USDT|225.050000|-1.88|-11.22|-1.05|39127367|1.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|127.980000|126.360000|128.010000|1.64|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.912000|3.847000|3.913000|0.31|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003988|0.003877|0.003990|0.40|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|196.950000|192.300000|196.910000|1.33|N|Y/Y|Y/N|Y|N|
|TAO_USDT|225.050000|220.940000|225.050000|0.41|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.163700|0.163080|0.163680|0.75|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.067000|0.066130|0.067030|2.11|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1157.620000|1131.680000|1157.650000|0.56|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.723900|1.692200|1.723900|0.45|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-02T22:00:06+00:00, last15m_closed_end=2026-11-02T22:00+00:00, prior8high=127.880000, depth_time=2026-11-02T22:00:25+00:00, book20_bid_proxy_usdt=511832, book20_ask_proxy_usdt=277932, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=23219391. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-02T22:00:06+00:00, last15m_closed_end=2026-11-02T22:00+00:00, prior8high=3.936000, depth_time=2026-11-02T22:00:21+00:00, book20_bid_proxy_usdt=3002765, book20_ask_proxy_usdt=3857217, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.44%, turnover=81636693. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-02T22:00:06+00:00, last15m_closed_end=2026-11-02T22:00+00:00, prior8high=0.003989, depth_time=2026-11-02T22:00:17+00:00, book20_bid_proxy_usdt=2763384, book20_ask_proxy_usdt=2576968, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.82%, turnover=9377515. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-02T22:00:06+00:00, last15m_closed_end=2026-11-02T22:00+00:00, prior8high=196.550000, depth_time=2026-11-02T22:00:19+00:00, book20_bid_proxy_usdt=80098, book20_ask_proxy_usdt=54579, funding_indicative=0.000091, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.71%, turnover=48555361. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-02T22:00:06+00:00, last15m_closed_end=2026-11-02T22:00+00:00, prior8high=224.770000, depth_time=2026-11-02T22:00:29+00:00, book20_bid_proxy_usdt=224972, book20_ask_proxy_usdt=233243, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.88%, turnover=39127367. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-02T22:00:06+00:00, last15m_closed_end=2026-11-02T22:00+00:00, prior8high=0.165410, depth_time=2026-11-02T22:00:19+00:00, book20_bid_proxy_usdt=160390, book20_ask_proxy_usdt=182022, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.32%, turnover=33044309. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-02T22:00:06+00:00, last15m_closed_end=2026-11-02T22:00+00:00, prior8high=0.067700, depth_time=2026-11-02T22:00:13+00:00, book20_bid_proxy_usdt=407460, book20_ask_proxy_usdt=393660, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.70%, turnover=10105897. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-02T22:00:06+00:00, last15m_closed_end=2026-11-02T22:00+00:00, prior8high=1164.850000, depth_time=2026-11-02T22:00:11+00:00, book20_bid_proxy_usdt=412482, book20_ask_proxy_usdt=651363, funding_indicative=0.000057, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-7.69%, turnover=1845905740. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-02T22:00:06+00:00, last15m_closed_end=2026-11-02T22:00+00:00, prior8high=1.724500, depth_time=2026-11-02T22:00:15+00:00, book20_bid_proxy_usdt=48165, book20_ask_proxy_usdt=28309, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.21%, turnover=5942681. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
