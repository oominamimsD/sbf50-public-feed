# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T20:30:16Z**
- feed_generated_utc: 2026-10-20T20:30:19+00:00
- source_sha256: `6a1cac7c8a207a00736022d96a92fef4060916e820caad9d0edfb1ab83a6bd11`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T20:30+00:00, close=82615.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T20:00+00:00, close=82561, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T20:00+00:00, close=82561, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.199390|-7.59|12.40|-7.63|11251656|0.50|
|BTW_USDT|1.710400|-7.52|-12.39|-7.56|28737191|1.75|
|AGT_USDT|0.059850|-7.39|269.96|-7.43|7393738|2.17|
|SEI_USDT|0.060900|-1.18|-2.35|-1.22|6091037|3.28|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.059850|0.057751|0.059850|0.44|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.199390|0.198710|0.199390|0.31|N|Y/N|N/N|N|N|
|BTW_USDT|1.710400|1.657000|1.710400|1.05|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.060900|0.060550|0.060910|0.87|N|N/N|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T20:29:59+00:00, last15m_closed_end=2026-10-20T20:30+00:00, prior8high=0.063088, depth_time=2026-10-20T20:30:12+00:00, book20_bid_proxy_usdt=4549, book20_ask_proxy_usdt=5805, funding_indicative=0.000047, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.39%, turnover=7393738. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-20T20:30:00+00:00, last15m_closed_end=2026-10-20T20:30+00:00, prior8high=0.204960, depth_time=2026-10-20T20:30:07+00:00, book20_bid_proxy_usdt=22917, book20_ask_proxy_usdt=17050, funding_indicative=0.000066, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-7.59%, turnover=11251656. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T20:29:59+00:00, last15m_closed_end=2026-10-20T20:30+00:00, prior8high=1.754000, depth_time=2026-10-20T20:30:10+00:00, book20_bid_proxy_usdt=11919, book20_ask_proxy_usdt=10914, funding_indicative=-0.002930, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.52%, turnover=28737191. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-20T20:30:00+00:00, last15m_closed_end=2026-10-20T20:30+00:00, prior8high=0.061610, depth_time=2026-10-20T20:30:15+00:00, book20_bid_proxy_usdt=208030, book20_ask_proxy_usdt=262556, funding_indicative=0.000010, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.18%, turnover=6091037. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
