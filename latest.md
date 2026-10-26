# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T05:15:30Z**
- feed_generated_utc: 2026-10-26T05:15:33+00:00
- source_sha256: `14186b662282043ce661cdad64104b538a1acb9b41c6b526812c9de4bd915490`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T05:15+00:00, close=80116.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T05:00+00:00, close=80102.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T04:00+00:00, close=79565.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|APR_USDT|0.034330|-16.89|26.02|-16.29|11494526|2.90|
|T_USDT|0.004845|-9.99|3.04|-9.39|5949511|2.06|
|IRYS_USDT|0.034630|-9.91|183.85|-9.31|13999692|8.66|
|LIT_USDT|3.089200|-2.80|5.41|-2.20|6144340|0.32|
|XMR_USDT|591.400000|-2.61|1.52|-2.01|6791513|0.17|
|WLD_USDT|0.445800|-2.36|-6.40|-1.76|73253910|2.24|
|DASH_USDT|51.290000|-2.13|7.12|-1.53|13472341|1.95|
|DOT_USDT|1.019800|-1.86|-4.63|-1.26|11125264|0.98|
|BTW_USDT|1.630000|-1.74|-29.29|-1.14|12463473|0.61|
|PUMPFUN_USDT|0.004212|-1.70|0.40|-1.10|17422908|2.37|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.034330|0.032730|0.034330|0.47|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.630000|1.620600|1.630000|0.46|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|51.290000|50.050000|51.290000|0.22|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.019800|1.011600|1.019800|0.46|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.034630|0.034640|0.034610|0.81|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.089200|3.000300|3.089200|1.57|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004212|0.004111|0.004212|0.42|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004845|0.004840|0.004845|0.63|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.445800|0.434800|0.445800|1.56|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|591.400000|588.910000|591.400000|0.42|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T05:15:00+00:00, last15m_closed_end=2026-10-26T05:15+00:00, prior8high=0.036370, depth_time=2026-10-26T05:15:07+00:00, book20_bid_proxy_usdt=92697, book20_ask_proxy_usdt=84800, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.89%, turnover=11494526. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T05:15:00+00:00, last15m_closed_end=2026-10-26T05:15+00:00, prior8high=1.683000, depth_time=2026-10-26T05:15:26+00:00, book20_bid_proxy_usdt=12210, book20_ask_proxy_usdt=16627, funding_indicative=-0.003744, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.74%, turnover=12463473. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T05:15:01+00:00, last15m_closed_end=2026-10-26T05:15+00:00, prior8high=51.310000, depth_time=2026-10-26T05:15:21+00:00, book20_bid_proxy_usdt=1089565, book20_ask_proxy_usdt=597828, funding_indicative=0.000068, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=13472341. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T05:15:00+00:00, last15m_closed_end=2026-10-26T05:15+00:00, prior8high=1.026700, depth_time=2026-10-26T05:15:24+00:00, book20_bid_proxy_usdt=315715, book20_ask_proxy_usdt=306015, funding_indicative=-0.000010, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.86%, turnover=11125264. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T05:15:00+00:00, last15m_closed_end=2026-10-26T05:15+00:00, prior8high=0.039970, depth_time=2026-10-26T05:15:12+00:00, book20_bid_proxy_usdt=76522, book20_ask_proxy_usdt=85912, funding_indicative=-0.000774, next_funding_utc=2026-10-26T06:00:00+00:00, funding_cycle_h=1, 24h_change=-9.91%, turnover=13999692. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T05:15:00+00:00, last15m_closed_end=2026-10-26T05:15+00:00, prior8high=3.136000, depth_time=2026-10-26T05:15:14+00:00, book20_bid_proxy_usdt=22304, book20_ask_proxy_usdt=21592, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.80%, turnover=6144340. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T05:15:00+00:00, last15m_closed_end=2026-10-26T05:15+00:00, prior8high=0.004203, depth_time=2026-10-26T05:15:29+00:00, book20_bid_proxy_usdt=2178277, book20_ask_proxy_usdt=2228178, funding_indicative=0.000040, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.70%, turnover=17422908. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T05:15:00+00:00, last15m_closed_end=2026-10-26T05:15+00:00, prior8high=0.004998, depth_time=2026-10-26T05:15:09+00:00, book20_bid_proxy_usdt=67253, book20_ask_proxy_usdt=97609, funding_indicative=-0.001099, next_funding_utc=2026-10-26T06:00:00+00:00, funding_cycle_h=1, 24h_change=-9.99%, turnover=5949511. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T05:15:00+00:00, last15m_closed_end=2026-10-26T05:15+00:00, prior8high=0.447400, depth_time=2026-10-26T05:15:19+00:00, book20_bid_proxy_usdt=2636490, book20_ask_proxy_usdt=2314503, funding_indicative=0.000038, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.36%, turnover=73253910. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T05:15:00+00:00, last15m_closed_end=2026-10-26T05:15+00:00, prior8high=598.030000, depth_time=2026-10-26T05:15:16+00:00, book20_bid_proxy_usdt=14255, book20_ask_proxy_usdt=14935, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=6791513. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
