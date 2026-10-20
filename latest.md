# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T20:15:16Z**
- feed_generated_utc: 2026-10-20T20:15:18+00:00
- source_sha256: `54885a62d6c54849ceef46f47de6f3934334b1f4cb8ac6def58a7a7942d9eed7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T20:15+00:00, close=82602.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T20:00+00:00, close=82561, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T20:00+00:00, close=82561, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.198810|-7.86|12.08|-7.88|11210566|0.50|
|AGT_USDT|0.059742|-7.56|269.30|-7.58|7370793|2.18|
|BTW_USDT|1.718400|-7.09|-11.98|-7.11|28546369|0.58|
|SEI_USDT|0.060880|-1.21|-2.38|-1.23|6042898|1.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.059742|0.057751|0.059749|1.76|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.198810|0.198710|0.198810|0.57|N|Y/N|N/N|N|N|
|BTW_USDT|1.718400|1.657000|1.723000|1.70|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.060880|0.060550|0.060880|0.10|N|N/N|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T20:15:02+00:00, last15m_closed_end=2026-10-20T20:15+00:00, prior8high=0.063088, depth_time=2026-10-20T20:15:08+00:00, book20_bid_proxy_usdt=2358, book20_ask_proxy_usdt=4484, funding_indicative=0.000047, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.56%, turnover=7370793. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-20T20:15:02+00:00, last15m_closed_end=2026-10-20T20:15+00:00, prior8high=0.206160, depth_time=2026-10-20T20:15:08+00:00, book20_bid_proxy_usdt=24503, book20_ask_proxy_usdt=16903, funding_indicative=0.000085, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-7.86%, turnover=11210566. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T20:15:02+00:00, last15m_closed_end=2026-10-20T20:15+00:00, prior8high=1.754000, depth_time=2026-10-20T20:15:13+00:00, book20_bid_proxy_usdt=12549, book20_ask_proxy_usdt=14974, funding_indicative=-0.002739, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.09%, turnover=28546369. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-20T20:15:02+00:00, last15m_closed_end=2026-10-20T20:15+00:00, prior8high=0.061750, depth_time=2026-10-20T20:15:14+00:00, book20_bid_proxy_usdt=222093, book20_ask_proxy_usdt=202574, funding_indicative=0.000018, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.21%, turnover=6042898. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
