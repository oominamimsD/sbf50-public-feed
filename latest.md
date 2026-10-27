# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T22:45:20Z**
- feed_generated_utc: 2026-10-27T22:45:25+00:00
- source_sha256: `bc22c7083f934ab1d1bba925c5d9b7fd087bf897951d2cc7a6eed68974699eac`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.09 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T22:45+00:00, close=80855.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T22:00+00:00, close=80874.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T20:00+00:00, close=80778.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.053694|-15.55|-56.25|-15.95|49510216|1.86|
|INJ_USDT|7.925000|-3.25|-7.84|-3.65|23666480|1.26|
|ARB_USDT|0.166480|-1.19|-11.89|-1.59|14932915|0.60|
|SYN_USDT|0.179400|-1.10|-2.28|-1.50|5890846|5.57|
|NIL_USDT|0.091970|-0.77|3.49|-1.17|5591529|7.61|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.166480|0.165630|0.166480|2.10|N|Y/Y|Y/Y|N|N|
|INJ_USDT|7.925000|7.965000|7.925000|2.46|Y|N/N|N/N|N|N|
|NIL_USDT|0.091970|0.091840|0.091970|1.77|N|Y/N|N/N|N|N|
|Q_USDT|0.053694|0.052810|0.053811|0.77|N|Y/Y|Y/Y|N|N|
|SYN_USDT|0.179400|0.178600|0.179400|0.56|N|N/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-27T22:45:04+00:00, last15m_closed_end=2026-10-27T22:45+00:00, prior8high=0.169030, depth_time=2026-10-27T22:45:14+00:00, book20_bid_proxy_usdt=62378, book20_ask_proxy_usdt=77195, funding_indicative=-0.000014, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.19%, turnover=14932915. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-27T22:45:04+00:00, last15m_closed_end=2026-10-27T22:45+00:00, prior8high=8.171000, depth_time=2026-10-27T22:45:10+00:00, book20_bid_proxy_usdt=195107, book20_ask_proxy_usdt=546375, funding_indicative=0.000241, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.25%, turnover=23666480. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-27T22:45:04+00:00, last15m_closed_end=2026-10-27T22:45+00:00, prior8high=0.095420, depth_time=2026-10-27T22:45:19+00:00, book20_bid_proxy_usdt=3111, book20_ask_proxy_usdt=10721, funding_indicative=-0.000523, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.77%, turnover=5591529. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-27T22:45:04+00:00, last15m_closed_end=2026-10-27T22:45+00:00, prior8high=0.055980, depth_time=2026-10-27T22:45:09+00:00, book20_bid_proxy_usdt=2905, book20_ask_proxy_usdt=3886, funding_indicative=-0.000034, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-15.55%, turnover=49510216. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SYN_USDT: quote_utc=2026-10-27T22:45:04+00:00, last15m_closed_end=2026-10-27T22:45+00:00, prior8high=0.183400, depth_time=2026-10-27T22:45:15+00:00, book20_bid_proxy_usdt=100385, book20_ask_proxy_usdt=100808, funding_indicative=0.000050, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.10%, turnover=5890846. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
