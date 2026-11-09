# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T03:30:17Z**
- feed_generated_utc: 2026-11-09T03:30:18+00:00
- source_sha256: `0e58fb4cb730c5946dded6595444f7be1e9d703f607fa3bc8ab42e1bbc348995`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T03:30+00:00, close=75043.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T03:00+00:00, close=75248.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T00:00+00:00, close=74823.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001676|-14.41|43.89|-13.11|10895436|0.60|
|AKE_USDT|0.004903|-8.47|-46.47|-7.17|12187769|4.08|
|JCT_USDT|0.009137|-7.08|83.51|-5.78|65561469|4.38|
|XRP_USDT|1.109100|-4.04|-11.26|-2.74|229577537|0.90|
|HYPE_USDT|74.759000|-3.45|-14.74|-2.15|40517538|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004903|0.004921|0.004908|1.60|Y|Y/Y|N/N|Y|N|
|HYPE_USDT|74.759000|74.059000|74.759000|0.50|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.009137|0.008360|0.009137|0.87|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001676|0.001675|0.001676|0.48|N|Y/Y|Y/N|Y|N|
|XRP_USDT|1.109100|1.105700|1.109100|1.37|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T03:30:00+00:00, last15m_closed_end=2026-11-09T03:30+00:00, prior8high=0.005168, depth_time=2026-11-09T03:30:09+00:00, book20_bid_proxy_usdt=39200, book20_ask_proxy_usdt=36806, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.47%, turnover=12187769. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T03:30:00+00:00, last15m_closed_end=2026-11-09T03:30+00:00, prior8high=75.262000, depth_time=2026-11-09T03:30:16+00:00, book20_bid_proxy_usdt=53786, book20_ask_proxy_usdt=58693, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.45%, turnover=40517538. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T03:30:00+00:00, last15m_closed_end=2026-11-09T03:30+00:00, prior8high=0.012446, depth_time=2026-11-09T03:30:12+00:00, book20_bid_proxy_usdt=19912, book20_ask_proxy_usdt=20340, funding_indicative=0.001262, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.08%, turnover=65561469. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T03:30:00+00:00, last15m_closed_end=2026-11-09T03:30+00:00, prior8high=0.001731, depth_time=2026-11-09T03:30:06+00:00, book20_bid_proxy_usdt=10844, book20_ask_proxy_usdt=10682, funding_indicative=-0.000646, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.41%, turnover=10895436. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T03:30:00+00:00, last15m_closed_end=2026-11-09T03:30+00:00, prior8high=1.123100, depth_time=2026-11-09T03:30:13+00:00, book20_bid_proxy_usdt=4431130, book20_ask_proxy_usdt=4858116, funding_indicative=-0.000008, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.04%, turnover=229577537. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
