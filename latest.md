# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T22:30:10Z**
- feed_generated_utc: 2026-11-07T22:30:11+00:00
- source_sha256: `1945aa9d8ea57f6fa3dc16960bfd0f61cde0bbadc9be589dfbdf40cee2a0e517`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T22:30+00:00, close=75690.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T22:00+00:00, close=75715.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T20:00+00:00, close=75772.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.121400|-2.41|-60.92|-2.37|9552311|8.24|
|QNT_USDT|195.950000|-1.45|-2.53|-1.41|41851423|0.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|QNT_USDT|195.950000|195.390000|196.220000|1.38|N|Y/N|N/N|Y|N|
|UAI_USDT|0.121400|0.119900|0.121400|0.32|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- QNT_USDT: quote_utc=2026-11-07T22:30:01+00:00, last15m_closed_end=2026-11-07T22:30+00:00, prior8high=198.370000, depth_time=2026-11-07T22:30:08+00:00, book20_bid_proxy_usdt=49736, book20_ask_proxy_usdt=58074, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.45%, turnover=41851423. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T22:30:01+00:00, last15m_closed_end=2026-11-07T22:30+00:00, prior8high=0.124500, depth_time=2026-11-07T22:30:06+00:00, book20_bid_proxy_usdt=218533, book20_ask_proxy_usdt=131089, funding_indicative=0.000050, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.41%, turnover=9552311. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
