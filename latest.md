# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T18:45:29Z**
- feed_generated_utc: 2026-10-26T18:45:32+00:00
- source_sha256: `f84ee3bf639c460430920972146449126b93764899c941517e28ff3a280eba82`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T18:45+00:00, close=80156.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T18:00+00:00, close=80301.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-26T16:00+00:00, close=80399.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.026490|-3.95|115.71|-3.65|9903195|3.77|
|NEAR_USDT|4.465000|-2.36|-8.95|-2.06|122731940|4.48|
|WLD_USDT|0.435900|-2.04|-13.90|-1.74|72920029|2.29|
|LIT_USDT|3.060500|-1.85|0.94|-1.55|5066105|0.33|
|ARB_USDT|0.167260|-1.60|-14.50|-1.30|20642591|0.60|
|FILECOIN_USDT|0.906000|-1.59|-10.47|-1.29|6152308|1.10|
|DOT_USDT|1.006400|-1.58|-12.24|-1.28|9880740|0.99|
|APT_USDT|0.691400|-1.50|-9.37|-1.20|5477321|1.45|
|PEPE_USDT|0.000004|-1.45|4.61|-1.15|84687797|0.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.691400|0.689500|0.691400|0.81|N|N/Y|Y/Y|Y|N|
|ARB_USDT|0.167260|0.166950|0.167260|0.48|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.006400|1.003500|1.006300|0.81|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.906000|0.903400|0.905900|0.05|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.026490|0.026060|0.026490|0.43|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.060500|3.067700|3.060500|1.55|Y|N/Y|Y/Y|Y|N|
|NEAR_USDT|4.465000|4.474000|4.465000|0.74|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|1.77|Y|Y/N|Y/Y|Y|N|
|WLD_USDT|0.435900|0.435100|0.435900|0.74|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-26T18:45:00+00:00, last15m_closed_end=2026-10-26T18:45+00:00, prior8high=0.703900, depth_time=2026-10-26T18:45:25+00:00, book20_bid_proxy_usdt=173761, book20_ask_proxy_usdt=158072, funding_indicative=-0.000031, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.50%, turnover=5477321. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-26T18:45:00+00:00, last15m_closed_end=2026-10-26T18:45+00:00, prior8high=0.169580, depth_time=2026-10-26T18:45:18+00:00, book20_bid_proxy_usdt=140782, book20_ask_proxy_usdt=92361, funding_indicative=-0.000030, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=20642591. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T18:45:00+00:00, last15m_closed_end=2026-10-26T18:45+00:00, prior8high=1.020300, depth_time=2026-10-26T18:45:22+00:00, book20_bid_proxy_usdt=305523, book20_ask_proxy_usdt=274966, funding_indicative=-0.000035, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=9880740. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-26T18:45:01+00:00, last15m_closed_end=2026-10-26T18:45+00:00, prior8high=0.922000, depth_time=2026-10-26T18:45:19+00:00, book20_bid_proxy_usdt=993774, book20_ask_proxy_usdt=1436074, funding_indicative=0.000074, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=6152308. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T18:45:00+00:00, last15m_closed_end=2026-10-26T18:45+00:00, prior8high=0.027470, depth_time=2026-10-26T18:45:06+00:00, book20_bid_proxy_usdt=98422, book20_ask_proxy_usdt=114895, funding_indicative=-0.000815, next_funding_utc=2026-10-26T19:00:00+00:00, funding_cycle_h=1, 24h_change=-3.95%, turnover=9903195. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T18:45:00+00:00, last15m_closed_end=2026-10-26T18:45+00:00, prior8high=3.150400, depth_time=2026-10-26T18:45:14+00:00, book20_bid_proxy_usdt=23086, book20_ask_proxy_usdt=23407, funding_indicative=0.000050, next_funding_utc=2026-10-26T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.85%, turnover=5066105. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T18:45:00+00:00, last15m_closed_end=2026-10-26T18:45+00:00, prior8high=4.569000, depth_time=2026-10-26T18:45:10+00:00, book20_bid_proxy_usdt=5085070, book20_ask_proxy_usdt=724028, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.36%, turnover=122731940. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T18:45:00+00:00, last15m_closed_end=2026-10-26T18:45+00:00, prior8high=0.000004, depth_time=2026-10-26T18:45:28+00:00, book20_bid_proxy_usdt=40584, book20_ask_proxy_usdt=104738, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.45%, turnover=84687797. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T18:45:00+00:00, last15m_closed_end=2026-10-26T18:45+00:00, prior8high=0.445400, depth_time=2026-10-26T18:45:13+00:00, book20_bid_proxy_usdt=3205581, book20_ask_proxy_usdt=2762209, funding_indicative=-0.000133, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=72920029. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
