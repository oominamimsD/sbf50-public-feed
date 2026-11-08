# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T20:30:17Z**
- feed_generated_utc: 2026-11-08T20:30:18+00:00
- source_sha256: `ef4b418d615124406266b11cf7702529991927a9bd5f88e3add5afe45881dfb8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T20:30+00:00, close=75863.1, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T20:00+00:00, close=75894.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T20:00+00:00, close=75894.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001738|-11.21|49.28|-10.99|15264892|0.57|
|NEAR_USDT|3.635000|-1.78|-16.07|-1.56|32255080|2.75|
|ARB_USDT|0.167060|-1.67|0.52|-1.45|18682358|0.60|
|TRUMPOFFICIAL_USDT|1.171000|-1.51|-31.75|-1.29|5040500|8.54|
|WLD_USDT|0.321900|-1.22|-18.65|-1.00|24565571|3.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.167060|0.166560|0.167070|0.05|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.635000|3.608000|3.635000|2.25|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001738|0.001721|0.001739|0.62|N|Y/Y|N/N|Y|N|
|TRUMPOFFICIAL_USDT|1.171000|1.168000|1.171000|0.08|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.321900|0.320800|0.321900|0.73|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-11-08T20:30:02+00:00, last15m_closed_end=2026-11-08T20:30+00:00, prior8high=0.168590, depth_time=2026-11-08T20:30:11+00:00, book20_bid_proxy_usdt=100923, book20_ask_proxy_usdt=106933, funding_indicative=-0.000028, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.67%, turnover=18682358. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-08T20:30:02+00:00, last15m_closed_end=2026-11-08T20:30+00:00, prior8high=3.666000, depth_time=2026-11-08T20:30:06+00:00, book20_bid_proxy_usdt=3736559, book20_ask_proxy_usdt=3293996, funding_indicative=0.000100, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=32255080. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T20:30:02+00:00, last15m_closed_end=2026-11-08T20:30+00:00, prior8high=0.001846, depth_time=2026-11-08T20:30:07+00:00, book20_bid_proxy_usdt=10885, book20_ask_proxy_usdt=5547, funding_indicative=-0.000260, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.21%, turnover=15264892. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-08T20:30:02+00:00, last15m_closed_end=2026-11-08T20:30+00:00, prior8high=1.179000, depth_time=2026-11-08T20:30:12+00:00, book20_bid_proxy_usdt=2585424, book20_ask_proxy_usdt=2098525, funding_indicative=-0.000097, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.51%, turnover=5040500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T20:30:02+00:00, last15m_closed_end=2026-11-08T20:30+00:00, prior8high=0.327200, depth_time=2026-11-08T20:30:16+00:00, book20_bid_proxy_usdt=3800624, book20_ask_proxy_usdt=3814957, funding_indicative=-0.000029, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.22%, turnover=24565571. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
