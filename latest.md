# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T04:45:15Z**
- feed_generated_utc: 2026-11-11T04:45:17+00:00
- source_sha256: `c2f99a5a413f3e48c568032490bef892d1a5ec8a007feabf07796c1c8f0485c9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T04:45+00:00, close=73766.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T04:00+00:00, close=73740.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T04:00+00:00, close=73740.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1023.210000|-6.41|-15.00|-7.19|2195170077|0.10|
|DASH_USDT|44.110000|-2.28|-4.39|-3.06|14705757|2.27|
|UNI_USDT|6.692000|-2.02|-8.98|-2.80|36333469|1.49|
|QNT_USDT|179.990000|-0.39|-7.89|-1.17|47349739|3.89|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|44.110000|42.980000|44.120000|2.20|N|N/Y|Y/Y|Y|N|
|QNT_USDT|179.990000|179.480000|179.990000|1.14|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.692000|6.651000|6.693000|0.64|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1023.210000|1012.300000|1023.670000|1.11|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-11-11T04:45:03+00:00, last15m_closed_end=2026-11-11T04:45+00:00, prior8high=44.810000, depth_time=2026-11-11T04:45:08+00:00, book20_bid_proxy_usdt=779778, book20_ask_proxy_usdt=559383, funding_indicative=-0.000124, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.28%, turnover=14705757. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T04:45:03+00:00, last15m_closed_end=2026-11-11T04:45+00:00, prior8high=181.920000, depth_time=2026-11-11T04:45:14+00:00, book20_bid_proxy_usdt=88428, book20_ask_proxy_usdt=126537, funding_indicative=-0.000137, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.39%, turnover=47349739. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T04:45:03+00:00, last15m_closed_end=2026-11-11T04:45+00:00, prior8high=6.768000, depth_time=2026-11-11T04:45:12+00:00, book20_bid_proxy_usdt=2227715, book20_ask_proxy_usdt=2909317, funding_indicative=0.000061, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.02%, turnover=36333469. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T04:45:03+00:00, last15m_closed_end=2026-11-11T04:45+00:00, prior8high=1038.490000, depth_time=2026-11-11T04:45:08+00:00, book20_bid_proxy_usdt=666837, book20_ask_proxy_usdt=329018, funding_indicative=0.000100, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.41%, turnover=2195170077. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
