# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T22:45:18Z**
- feed_generated_utc: 2026-10-14T22:45:20+00:00
- source_sha256: `ce97beb42d803cf38ec56df95451ced91665d77e70b4c09d2721f24c80eecfc0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T22:45+00:00, close=81449.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T22:00+00:00, close=81736.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T20:00+00:00, close=81798.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|FET_USDT|0.196800|-3.48|-13.11|-3.30|10804319|5.08|
|BAT_USDT|0.168930|-3.14|70.36|-2.96|27194021|0.59|
|S_USDT|0.053100|-3.08|33.28|-2.90|5500953|1.88|
|AAVE_USDT|153.280000|-1.67|-10.75|-1.49|26590632|0.65|
|LDO_USDT|0.400600|-1.28|-6.27|-1.10|5159484|2.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|153.280000|153.170000|153.280000|1.23|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.168930|0.167700|0.168930|0.18|N|Y/Y|Y/N|Y|N|
|FET_USDT|0.196800|0.194800|0.196800|0.34|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.400600|0.394500|0.400600|0.50|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.053100|0.052410|0.053100|1.14|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-14T22:44:59+00:00, last15m_closed_end=2026-10-14T22:45+00:00, prior8high=155.100000, depth_time=2026-10-14T22:45:15+00:00, book20_bid_proxy_usdt=195723, book20_ask_proxy_usdt=219147, funding_indicative=0.000081, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.67%, turnover=26590632. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-14T22:45:03+00:00, last15m_closed_end=2026-10-14T22:45+00:00, prior8high=0.171100, depth_time=2026-10-14T22:45:10+00:00, book20_bid_proxy_usdt=43215, book20_ask_proxy_usdt=23907, funding_indicative=0.000028, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.14%, turnover=27194021. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T22:44:59+00:00, last15m_closed_end=2026-10-14T22:45+00:00, prior8high=0.198600, depth_time=2026-10-14T22:45:08+00:00, book20_bid_proxy_usdt=1001001, book20_ask_proxy_usdt=952061, funding_indicative=-0.000006, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.48%, turnover=10804319. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-14T22:44:59+00:00, last15m_closed_end=2026-10-14T22:45+00:00, prior8high=0.402500, depth_time=2026-10-14T22:45:16+00:00, book20_bid_proxy_usdt=656641, book20_ask_proxy_usdt=586274, funding_indicative=-0.000068, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=5159484. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T22:44:59+00:00, last15m_closed_end=2026-10-14T22:45+00:00, prior8high=0.053610, depth_time=2026-10-14T22:45:10+00:00, book20_bid_proxy_usdt=86913, book20_ask_proxy_usdt=107302, funding_indicative=-0.000076, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.08%, turnover=5500953. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
