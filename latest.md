# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T03:15:21Z**
- feed_generated_utc: 2026-10-26T03:15:24+00:00
- source_sha256: `290ab6c75fbe415a78bbf3cc0fcf417f0c752992a00dea3c395d2a1741088ca4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T03:15+00:00, close=79666.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T03:00+00:00, close=79535.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T00:00+00:00, close=80114.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|APR_USDT|0.033970|-17.76|24.70|-16.60|12067210|2.94|
|T_USDT|0.004967|-7.72|5.63|-6.56|6929052|4.03|
|DASH_USDT|50.510000|-3.62|5.49|-2.46|13749839|1.98|
|PEPE_USDT|0.000004|-2.86|10.76|-1.70|70348753|1.41|
|WLD_USDT|0.443600|-2.84|-6.86|-1.68|72460146|2.26|
|PUMPFUN_USDT|0.004172|-2.63|-0.54|-1.47|17184662|2.40|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.033970|0.032120|0.033970|1.16|N|Y/Y|N/N|Y|N|
|DASH_USDT|50.510000|50.270000|50.510000|1.09|N|Y/Y|Y/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|1.21|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004172|0.004152|0.004172|0.24|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004967|0.004873|0.004967|1.07|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.443600|0.441300|0.443600|0.81|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T03:15:01+00:00, last15m_closed_end=2026-10-26T03:15+00:00, prior8high=0.039040, depth_time=2026-10-26T03:15:08+00:00, book20_bid_proxy_usdt=78320, book20_ask_proxy_usdt=58657, funding_indicative=0.000050, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-17.76%, turnover=12067210. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T03:15:01+00:00, last15m_closed_end=2026-10-26T03:15+00:00, prior8high=51.660000, depth_time=2026-10-26T03:15:10+00:00, book20_bid_proxy_usdt=757900, book20_ask_proxy_usdt=622317, funding_indicative=0.000069, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.62%, turnover=13749839. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T03:15:01+00:00, last15m_closed_end=2026-10-26T03:15+00:00, prior8high=0.000004, depth_time=2026-10-26T03:15:15+00:00, book20_bid_proxy_usdt=78378, book20_ask_proxy_usdt=38999, funding_indicative=0.000011, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.86%, turnover=70348753. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T03:15:01+00:00, last15m_closed_end=2026-10-26T03:15+00:00, prior8high=0.004265, depth_time=2026-10-26T03:15:20+00:00, book20_bid_proxy_usdt=2114809, book20_ask_proxy_usdt=2012178, funding_indicative=0.000044, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.63%, turnover=17184662. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T03:15:01+00:00, last15m_closed_end=2026-10-26T03:15+00:00, prior8high=0.004964, depth_time=2026-10-26T03:15:10+00:00, book20_bid_proxy_usdt=70505, book20_ask_proxy_usdt=74004, funding_indicative=-0.001936, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=1, 24h_change=-7.72%, turnover=6929052. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T03:15:01+00:00, last15m_closed_end=2026-10-26T03:15+00:00, prior8high=0.449200, depth_time=2026-10-26T03:15:18+00:00, book20_bid_proxy_usdt=2625340, book20_ask_proxy_usdt=2532074, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.84%, turnover=72460146. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
