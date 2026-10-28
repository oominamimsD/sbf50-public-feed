# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T02:15:12Z**
- feed_generated_utc: 2026-10-28T02:15:15+00:00
- source_sha256: `f857f177e4ff549d770ae4a0aa4ef8f6460c05ef3384d9b818f1a98a8cdc1d68`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T02:15+00:00, close=81009.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T02:00+00:00, close=80912.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T00:00+00:00, close=80868.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.054491|-14.30|-55.60|-14.89|38308477|0.18|
|NIL_USDT|0.085800|-7.43|-3.44|-8.02|5815167|2.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NIL_USDT|0.085800|0.085040|0.085800|0.70|N|Y/Y|N/N|N|N|
|Q_USDT|0.054491|0.052383|0.054478|0.42|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- NIL_USDT: quote_utc=2026-10-28T02:15:01+00:00, last15m_closed_end=2026-10-28T02:15+00:00, prior8high=0.091910, depth_time=2026-10-28T02:15:11+00:00, book20_bid_proxy_usdt=2030, book20_ask_proxy_usdt=3492, funding_indicative=-0.000232, next_funding_utc=2026-10-28T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.43%, turnover=5815167. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T02:15:01+00:00, last15m_closed_end=2026-10-28T02:15+00:00, prior8high=0.055141, depth_time=2026-10-28T02:15:09+00:00, book20_bid_proxy_usdt=26400, book20_ask_proxy_usdt=29176, funding_indicative=-0.000123, next_funding_utc=2026-10-28T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.30%, turnover=38308477. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
