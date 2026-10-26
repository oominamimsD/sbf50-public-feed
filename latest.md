# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T16:00:11Z**
- feed_generated_utc: 2026-10-26T16:00:14+00:00
- source_sha256: `a1c4d6fcfac2bc28b9badd947ff157e49f2cd46b2ccedbf17aad65aac17c9b2a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1186; contracts: 1178; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T16:00+00:00, close=80399.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T16:00+00:00, close=80399.8, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T16:00+00:00, close=80399.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.174000|-1.81|-32.99|-1.81|15267316|5.13|
|NIL_USDT|0.088670|-1.29|1.36|-1.29|5055236|1.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.174000|1.032300|1.195700|2.56|N|Y/Y|Y/Y|Y|N|
|NIL_USDT|0.088670|0.086200|0.088670|0.19|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-26T16:00:03+00:00, last15m_closed_end=2026-10-26T16:00+00:00, prior8high=1.634800, depth_time=2026-10-26T16:00:08+00:00, book20_bid_proxy_usdt=17607, book20_ask_proxy_usdt=14250, funding_indicative=-0.017418, next_funding_utc=2026-10-26T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.81%, turnover=15267316. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-26T16:00:03+00:00, last15m_closed_end=2026-10-26T16:00+00:00, prior8high=0.090640, depth_time=2026-10-26T16:00:08+00:00, book20_bid_proxy_usdt=16228, book20_ask_proxy_usdt=30209, funding_indicative=-0.000079, next_funding_utc=2026-10-26T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.29%, turnover=5055236. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
