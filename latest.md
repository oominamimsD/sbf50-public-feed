# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T19:15:11Z**
- feed_generated_utc: 2026-10-25T19:15:13+00:00
- source_sha256: `60e079294026aa601a4faefbc91bcaaf822c7cd540e37dd1c2120322fd53dc63`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T19:15+00:00, close=80571.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T19:00+00:00, close=80623.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T16:00+00:00, close=80602.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.035830|-6.78|193.68|-6.74|21121860|5.58|
|USELESS_USDT|0.168760|-2.20|19.31|-2.16|5240459|1.19|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|IRYS_USDT|0.035830|0.035970|0.035800|0.78|N|Y/Y|Y/Y|Y|N|
|USELESS_USDT|0.168760|0.166550|0.168760|0.23|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- IRYS_USDT: quote_utc=2026-10-25T19:15:01+00:00, last15m_closed_end=2026-10-25T19:15+00:00, prior8high=0.037780, depth_time=2026-10-25T19:15:08+00:00, book20_bid_proxy_usdt=84394, book20_ask_proxy_usdt=56907, funding_indicative=0.000003, next_funding_utc=2026-10-25T20:00:00+00:00, funding_cycle_h=1, 24h_change=-6.78%, turnover=21121860. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-25T19:15:01+00:00, last15m_closed_end=2026-10-25T19:15+00:00, prior8high=0.171370, depth_time=2026-10-25T19:15:10+00:00, book20_bid_proxy_usdt=20387, book20_ask_proxy_usdt=29948, funding_indicative=0.000127, next_funding_utc=2026-10-25T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.20%, turnover=5240459. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
