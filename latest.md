# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T19:45:18Z**
- feed_generated_utc: 2026-11-06T19:45:19+00:00
- source_sha256: `2e4dd2441714a2d205ea2e56143f4e3af8ab1df1f979bce14fcf84da18d3fbdb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T19:45+00:00, close=75770.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T19:00+00:00, close=75764.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T16:00+00:00, close=75832.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.124700|-34.36|-53.04|-34.28|29763785|8.02|
|ANTHROPIC_USDT|1321.520000|-7.66|-21.17|-7.58|5715823|1.81|
|AKE_USDT|0.003543|-5.89|-81.27|-5.81|53676817|5.65|
|LIT_USDT|3.283000|-3.22|16.24|-3.14|12136133|0.30|
|PUMPFUN_USDT|0.003953|-2.27|-3.74|-2.19|10800676|2.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003543|0.003497|0.003540|0.50|N|Y/Y|Y/N|Y|N|
|ANTHROPIC_USDT|1321.520000|1323.010000|1321.520000|2.12|Y|Y/Y|Y/Y|Y|Y|
|LIT_USDT|3.283000|3.280800|3.283000|0.71|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003953|0.003965|0.003953|1.08|N|Y/N|Y/Y|Y|N|
|UAI_USDT|0.124700|0.105200|0.125100|0.85|N|Y/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-06T19:45:01+00:00, last15m_closed_end=2026-11-06T19:45+00:00, prior8high=0.004389, depth_time=2026-11-06T19:45:12+00:00, book20_bid_proxy_usdt=22383, book20_ask_proxy_usdt=23286, funding_indicative=-0.000903, next_funding_utc=2026-11-06T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.89%, turnover=53676817. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-06T19:45:02+00:00, last15m_closed_end=2026-11-06T19:45+00:00, prior8high=1385.470000, depth_time=2026-11-06T19:45:10+00:00, book20_bid_proxy_usdt=23565, book20_ask_proxy_usdt=23178, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-7.66%, turnover=5715823. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-06T19:45:02+00:00, last15m_closed_end=2026-11-06T19:45+00:00, prior8high=3.428700, depth_time=2026-11-06T19:45:14+00:00, book20_bid_proxy_usdt=31646, book20_ask_proxy_usdt=27179, funding_indicative=0.000050, next_funding_utc=2026-11-06T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.22%, turnover=12136133. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-06T19:45:02+00:00, last15m_closed_end=2026-11-06T19:45+00:00, prior8high=0.004070, depth_time=2026-11-06T19:45:16+00:00, book20_bid_proxy_usdt=1889656, book20_ask_proxy_usdt=2115533, funding_indicative=0.000041, next_funding_utc=2026-11-06T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.27%, turnover=10800676. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-06T19:45:01+00:00, last15m_closed_end=2026-11-06T19:45+00:00, prior8high=0.249200, depth_time=2026-11-06T19:45:06+00:00, book20_bid_proxy_usdt=167275, book20_ask_proxy_usdt=187998, funding_indicative=0.000050, next_funding_utc=2026-11-06T20:00:00+00:00, funding_cycle_h=4, 24h_change=-34.36%, turnover=29763785. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
