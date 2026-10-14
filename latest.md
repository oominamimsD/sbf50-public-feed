# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T00:30:18Z**
- feed_generated_utc: 2026-10-14T00:30:20+00:00
- source_sha256: `71ad72099c6ae83322b1cd8873336935d0ebb43a872e190ddc6e78926ce6b8bc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T00:30+00:00, close=83417.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T00:00+00:00, close=83125.7, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T00:00+00:00, close=83125.7, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|1000RATS_USDT|0.016710|-9.62|-58.40|-9.64|5252853|5.99|
|RLC_USDT|0.890300|-3.56|8.59|-3.58|5029064|6.74|
|CT_USDT|0.362590|-2.46|-2.42|-2.48|5377295|3.86|
|STRK_USDT|0.085590|-1.54|63.99|-1.56|35858394|2.34|
|OGN_USDT|0.034850|-0.99|55.51|-1.01|5321059|2.87|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|1000RATS_USDT|0.016710|0.015990|0.016710|1.08|N|Y/Y|Y/Y|N|N|
|CT_USDT|0.362590|0.356040|0.362590|0.25|N|Y/Y|N/N|N|N|
|OGN_USDT|0.034850|0.034530|0.034850|4.46|N|Y/Y|Y/N|N|N|
|RLC_USDT|0.890300|0.886100|0.890300|0.36|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.085590|0.082530|0.085590|0.27|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- 1000RATS_USDT: quote_utc=2026-10-14T00:29:59+00:00, last15m_closed_end=2026-10-14T00:30+00:00, prior8high=0.017190, depth_time=2026-10-14T00:30:07+00:00, book20_bid_proxy_usdt=49176, book20_ask_proxy_usdt=43334, funding_indicative=0.000050, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.62%, turnover=5252853. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CT_USDT: quote_utc=2026-10-14T00:29:59+00:00, last15m_closed_end=2026-10-14T00:30+00:00, prior8high=0.366370, depth_time=2026-10-14T00:30:12+00:00, book20_bid_proxy_usdt=7384, book20_ask_proxy_usdt=6650, funding_indicative=0.000050, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.46%, turnover=5377295. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OGN_USDT: quote_utc=2026-10-14T00:29:59+00:00, last15m_closed_end=2026-10-14T00:30+00:00, prior8high=0.035050, depth_time=2026-10-14T00:30:17+00:00, book20_bid_proxy_usdt=158081, book20_ask_proxy_usdt=147611, funding_indicative=-0.000075, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.99%, turnover=5321059. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-14T00:30:00+00:00, last15m_closed_end=2026-10-14T00:30+00:00, prior8high=0.901200, depth_time=2026-10-14T00:30:06+00:00, book20_bid_proxy_usdt=91205, book20_ask_proxy_usdt=81777, funding_indicative=-0.000423, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.56%, turnover=5029064. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T00:29:59+00:00, last15m_closed_end=2026-10-14T00:30+00:00, prior8high=0.085960, depth_time=2026-10-14T00:30:14+00:00, book20_bid_proxy_usdt=175103, book20_ask_proxy_usdt=220561, funding_indicative=-0.000008, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.54%, turnover=35858394. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
