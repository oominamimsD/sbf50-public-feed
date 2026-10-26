# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T22:45:34Z**
- feed_generated_utc: 2026-10-26T22:45:38+00:00
- source_sha256: `6c49316d775ec52289fe20123036c83f76321c26c6cd3e034c7191f8dcb09e90`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T22:45+00:00, close=79976.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T22:00+00:00, close=80070.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T20:00+00:00, close=79988.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.624600|-4.83|-14.58|-4.31|5474052|0.61|
|LIT_USDT|3.001000|-3.76|-1.01|-3.24|5230945|0.33|
|BR_USDT|0.483500|-3.20|-21.50|-2.68|12134855|2.07|
|NEAR_USDT|4.468000|-2.29|-8.89|-1.77|119043800|2.24|
|PEPE_USDT|0.000004|-2.11|3.91|-1.59|80943953|1.40|
|FILECOIN_USDT|0.903000|-1.92|-10.77|-1.40|6443627|1.11|
|LINK_USDT|11.329000|-1.72|-5.14|-1.20|100262164|1.76|
|ARB_USDT|0.167070|-1.71|-14.59|-1.19|20756405|1.20|
|DOT_USDT|1.005200|-1.70|-12.34|-1.18|10624439|1.99|
|WLD_USDT|0.438200|-1.52|-13.45|-1.00|72985557|2.28|
|TAO_USDT|249.640000|-1.52|-6.95|-1.00|47866235|1.20|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.167070|0.166370|0.167070|0.80|N|Y/Y|Y/Y|Y|N|
|BR_USDT|0.483500|0.472600|0.483500|0.94|N|Y/Y|Y/N|Y|N|
|DOT_USDT|1.005200|0.999300|1.005200|1.15|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.903000|0.895300|0.903000|0.72|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.329000|11.304000|11.329000|0.76|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.001000|2.972000|3.001000|0.19|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.468000|4.437000|4.468000|1.44|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|1.56|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|249.640000|248.640000|249.640000|5.93|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.438200|0.432200|0.438200|0.42|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.624600|1.608700|1.624600|2.08|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-26T22:45:00+00:00, last15m_closed_end=2026-10-26T22:45+00:00, prior8high=0.168330, depth_time=2026-10-26T22:45:26+00:00, book20_bid_proxy_usdt=77958, book20_ask_proxy_usdt=57255, funding_indicative=-0.000025, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=20756405. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-26T22:45:00+00:00, last15m_closed_end=2026-10-26T22:45+00:00, prior8high=0.487600, depth_time=2026-10-26T22:45:13+00:00, book20_bid_proxy_usdt=41152, book20_ask_proxy_usdt=39616, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.20%, turnover=12134855. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T22:45:00+00:00, last15m_closed_end=2026-10-26T22:45+00:00, prior8high=1.011200, depth_time=2026-10-26T22:45:28+00:00, book20_bid_proxy_usdt=520940, book20_ask_proxy_usdt=369635, funding_indicative=-0.000044, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=10624439. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-26T22:45:00+00:00, last15m_closed_end=2026-10-26T22:45+00:00, prior8high=0.909400, depth_time=2026-10-26T22:45:19+00:00, book20_bid_proxy_usdt=1185538, book20_ask_proxy_usdt=1221917, funding_indicative=0.000075, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.92%, turnover=6443627. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-26T22:45:00+00:00, last15m_closed_end=2026-10-26T22:45+00:00, prior8high=11.397000, depth_time=2026-10-26T22:45:22+00:00, book20_bid_proxy_usdt=641450, book20_ask_proxy_usdt=468039, funding_indicative=0.000098, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=100262164. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T22:45:00+00:00, last15m_closed_end=2026-10-26T22:45+00:00, prior8high=3.033200, depth_time=2026-10-26T22:45:10+00:00, book20_bid_proxy_usdt=22339, book20_ask_proxy_usdt=26335, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.76%, turnover=5230945. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T22:45:00+00:00, last15m_closed_end=2026-10-26T22:45+00:00, prior8high=4.492000, depth_time=2026-10-26T22:45:11+00:00, book20_bid_proxy_usdt=5333080, book20_ask_proxy_usdt=3621530, funding_indicative=0.000062, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.29%, turnover=119043800. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T22:45:00+00:00, last15m_closed_end=2026-10-26T22:45+00:00, prior8high=0.000004, depth_time=2026-10-26T22:45:17+00:00, book20_bid_proxy_usdt=47278, book20_ask_proxy_usdt=71850, funding_indicative=0.000080, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.11%, turnover=80943953. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-26T22:45:00+00:00, last15m_closed_end=2026-10-26T22:45+00:00, prior8high=250.800000, depth_time=2026-10-26T22:45:33+00:00, book20_bid_proxy_usdt=112347, book20_ask_proxy_usdt=65264, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.52%, turnover=47866235. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T22:45:00+00:00, last15m_closed_end=2026-10-26T22:45+00:00, prior8high=0.438800, depth_time=2026-10-26T22:45:30+00:00, book20_bid_proxy_usdt=2876124, book20_ask_proxy_usdt=2827867, funding_indicative=-0.000133, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.52%, turnover=72985557. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-26T22:45:00+00:00, last15m_closed_end=2026-10-26T22:45+00:00, prior8high=1.643300, depth_time=2026-10-26T22:45:08+00:00, book20_bid_proxy_usdt=22960, book20_ask_proxy_usdt=45654, funding_indicative=-0.000030, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.83%, turnover=5474052. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
