# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T00:15:11Z**
- feed_generated_utc: 2026-10-27T00:15:14+00:00
- source_sha256: `0014c72bb4696b558f71d858d0cd3c39dc56036c7a72db6d0c733be6f0ce3e6f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T00:15+00:00, close=80196.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T00:00+00:00, close=80115.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T00:00+00:00, close=80115.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.642700|-3.77|-13.63|-3.52|5295841|1.22|
|BR_USDT|0.492700|-1.36|-20.01|-1.11|9338152|2.03|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BR_USDT|0.492700|0.473800|0.492500|1.93|N|N/Y|N/N|Y|N|
|ZRO_USDT|1.642700|1.610100|1.642700|0.87|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BR_USDT: quote_utc=2026-10-27T00:15:00+00:00, last15m_closed_end=2026-10-27T00:15+00:00, prior8high=0.491500, depth_time=2026-10-27T00:15:10+00:00, book20_bid_proxy_usdt=41613, book20_ask_proxy_usdt=42117, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.36%, turnover=9338152. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T00:15:01+00:00, last15m_closed_end=2026-10-27T00:15+00:00, prior8high=1.643300, depth_time=2026-10-27T00:15:08+00:00, book20_bid_proxy_usdt=25004, book20_ask_proxy_usdt=28350, funding_indicative=-0.000092, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.77%, turnover=5295841. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
