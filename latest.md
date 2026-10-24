# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T22:45:22Z**
- feed_generated_utc: 2026-10-24T22:45:25+00:00
- source_sha256: `683a4d0088e1e9f425d14fd852956e10d64a5f9101701d1b4b2efae6edb62aae`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T22:45+00:00, close=80547.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T22:00+00:00, close=80383.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T20:00+00:00, close=80455.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.057030|-15.38|84.26|-16.36|12786928|1.75|
|BIRB_USDT|0.086110|-11.82|77.47|-12.80|11703429|1.16|
|IRYS_USDT|0.043270|-6.03|239.10|-7.01|36245405|2.31|
|BTW_USDT|1.674600|-3.83|-26.20|-4.81|11710929|1.79|
|STRK_USDT|0.046260|-1.00|-30.06|-1.98|9043841|2.16|
|DOT_USDT|1.036400|-0.25|-7.24|-1.23|12539540|0.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.086110|0.083640|0.086110|0.63|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.674600|1.684600|1.674600|2.38|Y|N/N|Y/Y|Y|N|
|DOT_USDT|1.036400|1.033000|1.036400|1.38|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.043270|0.042610|0.043270|0.66|N|Y/Y|Y/N|Y|N|
|ORDER_USDT|0.057030|0.053680|0.057030|0.36|N|Y/N|N/N|Y|N|
|STRK_USDT|0.046260|0.046190|0.046260|1.94|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-24T22:45:00+00:00, last15m_closed_end=2026-10-24T22:45+00:00, prior8high=0.094010, depth_time=2026-10-24T22:45:08+00:00, book20_bid_proxy_usdt=16183, book20_ask_proxy_usdt=22884, funding_indicative=-0.008727, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.82%, turnover=11703429. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-24T22:45:00+00:00, last15m_closed_end=2026-10-24T22:45+00:00, prior8high=1.761200, depth_time=2026-10-24T22:45:15+00:00, book20_bid_proxy_usdt=17052, book20_ask_proxy_usdt=10210, funding_indicative=-0.006120, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.83%, turnover=11710929. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-24T22:45:00+00:00, last15m_closed_end=2026-10-24T22:45+00:00, prior8high=1.040800, depth_time=2026-10-24T22:45:21+00:00, book20_bid_proxy_usdt=391224, book20_ask_proxy_usdt=407080, funding_indicative=-0.000082, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.25%, turnover=12539540. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-24T22:45:00+00:00, last15m_closed_end=2026-10-24T22:45+00:00, prior8high=0.045590, depth_time=2026-10-24T22:45:13+00:00, book20_bid_proxy_usdt=63192, book20_ask_proxy_usdt=68337, funding_indicative=0.000012, next_funding_utc=2026-10-24T23:00:00+00:00, funding_cycle_h=1, 24h_change=-6.03%, turnover=36245405. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-24T22:45:00+00:00, last15m_closed_end=2026-10-24T22:45+00:00, prior8high=0.063900, depth_time=2026-10-24T22:45:09+00:00, book20_bid_proxy_usdt=92054, book20_ask_proxy_usdt=58949, funding_indicative=-0.001016, next_funding_utc=2026-10-24T23:00:00+00:00, funding_cycle_h=1, 24h_change=-15.38%, turnover=12786928. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-24T22:45:00+00:00, last15m_closed_end=2026-10-24T22:45+00:00, prior8high=0.047050, depth_time=2026-10-24T22:45:18+00:00, book20_bid_proxy_usdt=1134036, book20_ask_proxy_usdt=746062, funding_indicative=0.000035, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.00%, turnover=9043841. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
