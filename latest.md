# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T19:45:13Z**
- feed_generated_utc: 2026-11-08T19:45:14+00:00
- source_sha256: `ca13e65193b6c6f4231de5335d11e5e48028f0fcc75a8e25edadc60f59fd420c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T19:45+00:00, close=75869.9, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T19:00+00:00, close=75913.5, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T16:00+00:00, close=76037.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001778|-9.20|52.65|-8.99|16356314|0.56|
|AKE_USDT|0.005226|-2.44|-42.94|-2.23|18380116|1.91|
|ARB_USDT|0.166930|-1.74|0.45|-1.53|19237081|0.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005226|0.005112|0.005226|0.32|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.166930|0.166560|0.166930|1.45|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001778|0.001766|0.001778|0.36|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-08T19:45:03+00:00, last15m_closed_end=2026-11-08T19:45+00:00, prior8high=0.005317, depth_time=2026-11-08T19:45:09+00:00, book20_bid_proxy_usdt=58276, book20_ask_proxy_usdt=45748, funding_indicative=0.000050, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.44%, turnover=18380116. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-08T19:45:03+00:00, last15m_closed_end=2026-11-08T19:45+00:00, prior8high=0.169110, depth_time=2026-11-08T19:45:11+00:00, book20_bid_proxy_usdt=60255, book20_ask_proxy_usdt=84864, funding_indicative=-0.000035, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=19237081. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T19:45:03+00:00, last15m_closed_end=2026-11-08T19:45+00:00, prior8high=0.001846, depth_time=2026-11-08T19:45:07+00:00, book20_bid_proxy_usdt=13177, book20_ask_proxy_usdt=14935, funding_indicative=-0.000532, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.20%, turnover=16356314. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
