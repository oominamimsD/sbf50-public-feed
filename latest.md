# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T00:30:20Z**
- feed_generated_utc: 2026-10-26T00:30:23+00:00
- source_sha256: `451719a2fdf2db08da88c6081de3218fda46484daa02f326c9b00927e9fe06a3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T00:30+00:00, close=80240, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T00:00+00:00, close=80114.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T00:00+00:00, close=80114.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.006115|-12.29|231.79|-11.85|10056305|3.27|
|T_USDT|0.005024|-6.66|6.84|-6.22|8675151|1.99|
|IRYS_USDT|0.036550|-4.91|199.59|-4.47|19960540|5.46|
|BTW_USDT|1.615600|-2.61|-29.92|-2.17|12575943|1.24|
|PEPE_USDT|0.000004|-2.18|11.54|-1.74|75318827|0.23|
|XMR_USDT|594.310000|-2.13|2.02|-1.69|6638427|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.615600|1.617800|1.615600|1.04|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.036550|0.035210|0.036570|0.92|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.006115|0.006069|0.006115|0.90|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.27|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.005024|0.004978|0.005024|1.03|N|Y/Y|N/N|Y|N|
|XMR_USDT|594.310000|589.580000|594.310000|0.61|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-26T00:30:00+00:00, last15m_closed_end=2026-10-26T00:30+00:00, prior8high=1.655700, depth_time=2026-10-26T00:30:14+00:00, book20_bid_proxy_usdt=17440, book20_ask_proxy_usdt=19242, funding_indicative=-0.007138, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.61%, turnover=12575943. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T00:30:00+00:00, last15m_closed_end=2026-10-26T00:30+00:00, prior8high=0.039720, depth_time=2026-10-26T00:30:12+00:00, book20_bid_proxy_usdt=29399, book20_ask_proxy_usdt=40846, funding_indicative=-0.000421, next_funding_utc=2026-10-26T01:00:00+00:00, funding_cycle_h=1, 24h_change=-4.91%, turnover=19960540. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-26T00:30:00+00:00, last15m_closed_end=2026-10-26T00:30+00:00, prior8high=0.006858, depth_time=2026-10-26T00:30:07+00:00, book20_bid_proxy_usdt=43591, book20_ask_proxy_usdt=32673, funding_indicative=0.000050, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.29%, turnover=10056305. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T00:30:00+00:00, last15m_closed_end=2026-10-26T00:30+00:00, prior8high=0.000004, depth_time=2026-10-26T00:30:17+00:00, book20_bid_proxy_usdt=41037, book20_ask_proxy_usdt=30354, funding_indicative=0.000074, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=75318827. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T00:30:00+00:00, last15m_closed_end=2026-10-26T00:30+00:00, prior8high=0.005411, depth_time=2026-10-26T00:30:09+00:00, book20_bid_proxy_usdt=70607, book20_ask_proxy_usdt=111714, funding_indicative=-0.004777, next_funding_utc=2026-10-26T01:00:00+00:00, funding_cycle_h=1, 24h_change=-6.66%, turnover=8675151. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T00:30:00+00:00, last15m_closed_end=2026-10-26T00:30+00:00, prior8high=597.350000, depth_time=2026-10-26T00:30:19+00:00, book20_bid_proxy_usdt=38956, book20_ask_proxy_usdt=19611, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=6638427. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
