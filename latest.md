# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T21:45:31Z**
- feed_generated_utc: 2026-10-26T21:45:34+00:00
- source_sha256: `ea6ac4d502ffa78e12aebe1d15123294e392e83714fbe3d13d1797dc71a71bfa`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T21:45+00:00, close=80099.4, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T21:00+00:00, close=79843, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T20:00+00:00, close=79988.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BR_USDT|0.476300|-4.64|-22.67|-4.27|12765680|2.10|
|IRYS_USDT|0.026300|-4.64|114.16|-4.27|9419563|3.80|
|ZRO_USDT|1.630900|-4.46|-14.25|-4.09|5166242|0.61|
|LIT_USDT|3.004100|-3.66|-0.91|-3.29|5281950|0.33|
|NEAR_USDT|4.475000|-2.14|-8.74|-1.77|119282860|2.23|
|PEPE_USDT|0.000004|-1.99|4.04|-1.62|84634196|0.23|
|WLD_USDT|0.436800|-1.84|-13.72|-1.47|73667321|2.29|
|FILECOIN_USDT|0.905600|-1.64|-10.51|-1.27|6648690|1.10|
|DOT_USDT|1.007700|-1.45|-12.12|-1.08|10796162|0.99|
|ARB_USDT|0.167660|-1.37|-14.29|-1.00|20936635|0.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.167660|0.166370|0.167660|3.16|N|Y/Y|Y/Y|Y|N|
|BR_USDT|0.476300|0.472600|0.476300|0.53|N|Y/Y|Y/N|Y|N|
|DOT_USDT|1.007700|0.999300|1.007700|1.76|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.905600|0.895300|0.905600|1.43|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.026300|0.025640|0.026300|1.05|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.004100|2.972000|3.004100|1.69|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.475000|4.437000|4.475000|1.26|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.88|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.436800|0.432200|0.436700|0.65|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.630900|1.608700|1.630900|2.15|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-26T21:45:02+00:00, last15m_closed_end=2026-10-26T21:45+00:00, prior8high=0.168910, depth_time=2026-10-26T21:45:29+00:00, book20_bid_proxy_usdt=50587, book20_ask_proxy_usdt=68010, funding_indicative=-0.000039, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.37%, turnover=20936635. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-26T21:45:02+00:00, last15m_closed_end=2026-10-26T21:45+00:00, prior8high=0.481300, depth_time=2026-10-26T21:45:07+00:00, book20_bid_proxy_usdt=40321, book20_ask_proxy_usdt=44601, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.64%, turnover=12765680. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T21:45:03+00:00, last15m_closed_end=2026-10-26T21:45+00:00, prior8high=1.010600, depth_time=2026-10-26T21:45:26+00:00, book20_bid_proxy_usdt=433499, book20_ask_proxy_usdt=246116, funding_indicative=-0.000048, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.45%, turnover=10796162. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-26T21:44:59+00:00, last15m_closed_end=2026-10-26T21:45+00:00, prior8high=0.911500, depth_time=2026-10-26T21:45:21+00:00, book20_bid_proxy_usdt=1061245, book20_ask_proxy_usdt=1264954, funding_indicative=0.000084, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=6648690. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T21:45:02+00:00, last15m_closed_end=2026-10-26T21:45+00:00, prior8high=0.026490, depth_time=2026-10-26T21:45:11+00:00, book20_bid_proxy_usdt=131846, book20_ask_proxy_usdt=81329, funding_indicative=-0.000690, next_funding_utc=2026-10-26T22:00:00+00:00, funding_cycle_h=1, 24h_change=-4.64%, turnover=9419563. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T21:44:59+00:00, last15m_closed_end=2026-10-26T21:45+00:00, prior8high=3.069700, depth_time=2026-10-26T21:45:15+00:00, book20_bid_proxy_usdt=79167, book20_ask_proxy_usdt=36899, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.66%, turnover=5281950. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T21:45:02+00:00, last15m_closed_end=2026-10-26T21:45+00:00, prior8high=4.506000, depth_time=2026-10-26T21:45:18+00:00, book20_bid_proxy_usdt=4433493, book20_ask_proxy_usdt=4469574, funding_indicative=0.000066, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.14%, turnover=119282860. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T21:45:02+00:00, last15m_closed_end=2026-10-26T21:45+00:00, prior8high=0.000004, depth_time=2026-10-26T21:45:20+00:00, book20_bid_proxy_usdt=47410, book20_ask_proxy_usdt=204158, funding_indicative=0.000087, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.99%, turnover=84634196. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T21:45:02+00:00, last15m_closed_end=2026-10-26T21:45+00:00, prior8high=0.441300, depth_time=2026-10-26T21:45:22+00:00, book20_bid_proxy_usdt=2838522, book20_ask_proxy_usdt=3082737, funding_indicative=-0.000127, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=73667321. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-26T21:44:59+00:00, last15m_closed_end=2026-10-26T21:45+00:00, prior8high=1.631800, depth_time=2026-10-26T21:45:12+00:00, book20_bid_proxy_usdt=31124, book20_ask_proxy_usdt=55680, funding_indicative=-0.000072, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.46%, turnover=5166242. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
