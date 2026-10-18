# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T16:30:15Z**
- feed_generated_utc: 2026-10-18T16:30:16+00:00
- source_sha256: `dbde461407f23dc2802bf69ae1336a6dc091c6ea39a98e3c7316fb4c5d99b809`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T16:30+00:00, close=81093.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T16:00+00:00, close=81137.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T16:00+00:00, close=81137.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.227100|-3.39|32.39|-3.34|28435513|0.45|
|PUMPFUN_USDT|0.004125|-1.66|-28.57|-1.61|30616031|2.42|
|ICNT_USDT|0.177100|-1.28|67.07|-1.23|12484253|5.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.227100|2.237700|2.227100|1.55|Y|Y/Y|N/N|Y|N|
|ICNT_USDT|0.177100|0.174200|0.176800|0.38|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004125|0.004114|0.004125|3.35|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-18T16:30:00+00:00, last15m_closed_end=2026-10-18T16:30+00:00, prior8high=2.412700, depth_time=2026-10-18T16:30:09+00:00, book20_bid_proxy_usdt=15985, book20_ask_proxy_usdt=9335, funding_indicative=-0.000315, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.39%, turnover=28435513. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-18T16:30:00+00:00, last15m_closed_end=2026-10-18T16:30+00:00, prior8high=0.189500, depth_time=2026-10-18T16:30:14+00:00, book20_bid_proxy_usdt=143434, book20_ask_proxy_usdt=141299, funding_indicative=-0.000147, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.28%, turnover=12484253. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T16:30:00+00:00, last15m_closed_end=2026-10-18T16:30+00:00, prior8high=0.004275, depth_time=2026-10-18T16:30:11+00:00, book20_bid_proxy_usdt=2757256, book20_ask_proxy_usdt=2043805, funding_indicative=0.000020, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.66%, turnover=30616031. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
