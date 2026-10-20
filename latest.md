# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T04:00:15Z**
- feed_generated_utc: 2026-10-20T04:00:17+00:00
- source_sha256: `f1f1bfea5ec3902cdca13ccd4ff3bfafb427618590a59d78e611d43fedc6be1b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T04:00+00:00, close=82099.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T04:00+00:00, close=82099.2, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T04:00+00:00, close=82099.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.120892|-4.04|292.62|-4.26|13432308|0.74|
|SAND_USDT|0.058090|-2.46|-6.44|-2.68|8825883|1.72|
|ZRO_USDT|1.862800|-2.06|-17.61|-2.28|7651300|1.07|
|NEAR_USDT|4.863000|-1.31|-12.36|-1.53|164967687|2.06|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NEAR_USDT|4.863000|4.788000|4.863000|0.70|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.120892|0.121860|0.120842|1.27|N|Y/Y|N/N|N|N|
|SAND_USDT|0.058090|0.057590|0.058090|0.15|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.862800|1.847300|1.863500|2.43|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- NEAR_USDT: quote_utc=2026-10-20T04:00:02+00:00, last15m_closed_end=2026-10-20T04:00+00:00, prior8high=4.885000, depth_time=2026-10-20T04:00:14+00:00, book20_bid_proxy_usdt=3041451, book20_ask_proxy_usdt=2377770, funding_indicative=0.000049, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=164967687. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T04:00:02+00:00, last15m_closed_end=2026-10-20T04:00+00:00, prior8high=0.128625, depth_time=2026-10-20T04:00:07+00:00, book20_bid_proxy_usdt=19126, book20_ask_proxy_usdt=17674, funding_indicative=-0.000192, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.04%, turnover=13432308. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T04:00:02+00:00, last15m_closed_end=2026-10-20T04:00+00:00, prior8high=0.058600, depth_time=2026-10-20T04:00:09+00:00, book20_bid_proxy_usdt=740645, book20_ask_proxy_usdt=781472, funding_indicative=-0.002054, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.46%, turnover=8825883. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T04:00:02+00:00, last15m_closed_end=2026-10-20T04:00+00:00, prior8high=1.883500, depth_time=2026-10-20T04:00:11+00:00, book20_bid_proxy_usdt=52933, book20_ask_proxy_usdt=33542, funding_indicative=0.000050, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.06%, turnover=7651300. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
