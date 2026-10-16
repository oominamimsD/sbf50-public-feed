# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T04:00:15Z**
- feed_generated_utc: 2026-10-16T04:00:16+00:00
- source_sha256: `a1a9d1d23208b2e3b63a8e898c264d14ded8735058247cfd94cf12a43587e350`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T04:00+00:00, close=82094.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T04:00+00:00, close=82094.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T04:00+00:00, close=82094.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WAL_USDT|0.045430|-16.56|36.46|-16.22|5040814|2.20|
|ZEREBRO_USDT|0.040876|-13.09|48.87|-12.75|6982440|6.86|
|NIL_USDT|0.085510|-4.00|-1.24|-3.66|10071663|2.34|
|ZKSYNC_USDT|0.016695|-2.88|50.12|-2.54|7793690|1.80|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NIL_USDT|0.085510|0.083590|0.085510|1.32|N|Y/Y|N/N|Y|N|
|WAL_USDT|0.045430|0.044820|0.045430|0.34|N|Y/Y|Y/N|Y|N|
|ZEREBRO_USDT|0.040876|0.043879|0.040876|5.45|Y|Y/N|N/N|Y|N|
|ZKSYNC_USDT|0.016695|0.016384|0.016695|0.71|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- NIL_USDT: quote_utc=2026-10-16T04:00:00+00:00, last15m_closed_end=2026-10-16T04:00+00:00, prior8high=0.088420, depth_time=2026-10-16T04:00:12+00:00, book20_bid_proxy_usdt=16953, book20_ask_proxy_usdt=21413, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.00%, turnover=10071663. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-16T04:00:00+00:00, last15m_closed_end=2026-10-16T04:00+00:00, prior8high=0.047130, depth_time=2026-10-16T04:00:07+00:00, book20_bid_proxy_usdt=124056, book20_ask_proxy_usdt=170025, funding_indicative=-0.000553, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.56%, turnover=5040814. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEREBRO_USDT: quote_utc=2026-10-16T04:00:00+00:00, last15m_closed_end=2026-10-16T04:00+00:00, prior8high=0.059435, depth_time=2026-10-16T04:00:10+00:00, book20_bid_proxy_usdt=5734, book20_ask_proxy_usdt=20576, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-13.09%, turnover=6982440. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZKSYNC_USDT: quote_utc=2026-10-16T04:00:00+00:00, last15m_closed_end=2026-10-16T04:00+00:00, prior8high=0.016741, depth_time=2026-10-16T04:00:14+00:00, book20_bid_proxy_usdt=10391, book20_ask_proxy_usdt=6165, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.88%, turnover=7793690. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
