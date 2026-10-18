# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T17:15:15Z**
- feed_generated_utc: 2026-10-18T17:15:17+00:00
- source_sha256: `9bbab54de967f69c63c93f820905e1e3f2f5a5d07ece27fd45b33982cc013cd0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T17:15+00:00, close=81135, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T17:00+00:00, close=81040.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T16:00+00:00, close=81137.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.229900|-3.27|32.55|-3.27|27267774|1.79|
|BAT_USDT|0.171880|-1.99|3.14|-1.99|9994028|0.58|
|STRK_USDT|0.060350|-1.96|-49.40|-1.96|14640299|3.32|
|PUMPFUN_USDT|0.004131|-1.52|-28.46|-1.52|29195091|2.42|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.171880|0.171970|0.171880|0.70|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|2.229900|2.184900|2.229900|1.67|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004131|0.004108|0.004131|0.31|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.060350|0.060160|0.060350|1.58|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-18T17:15:00+00:00, last15m_closed_end=2026-10-18T17:15+00:00, prior8high=0.180190, depth_time=2026-10-18T17:15:09+00:00, book20_bid_proxy_usdt=19746, book20_ask_proxy_usdt=23920, funding_indicative=-0.000016, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.99%, turnover=9994028. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-18T17:15:00+00:00, last15m_closed_end=2026-10-18T17:15+00:00, prior8high=2.405100, depth_time=2026-10-18T17:15:06+00:00, book20_bid_proxy_usdt=8931, book20_ask_proxy_usdt=13410, funding_indicative=-0.000445, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.27%, turnover=27267774. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T17:15:00+00:00, last15m_closed_end=2026-10-18T17:15+00:00, prior8high=0.004252, depth_time=2026-10-18T17:15:15+00:00, book20_bid_proxy_usdt=1956590, book20_ask_proxy_usdt=2102044, funding_indicative=0.000050, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.52%, turnover=29195091. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T17:15:00+00:00, last15m_closed_end=2026-10-18T17:15+00:00, prior8high=0.062250, depth_time=2026-10-18T17:15:12+00:00, book20_bid_proxy_usdt=334558, book20_ask_proxy_usdt=311518, funding_indicative=0.000050, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.96%, turnover=14640299. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
