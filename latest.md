# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T22:15:11Z**
- feed_generated_utc: 2026-10-20T22:15:13+00:00
- source_sha256: `0d4847c30182449bf1d09ee420904f4a8ed9b7420640fd6593499ce185b41f6c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T22:15+00:00, close=83050, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T22:00+00:00, close=82932.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T20:00+00:00, close=82561, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.057394|-11.19|254.78|-11.76|7091454|0.35|
|BAT_USDT|0.195450|-9.41|10.18|-9.98|9904709|1.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.057394|0.057611|0.057394|1.06|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.195450|0.194560|0.195450|1.53|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T22:15:00+00:00, last15m_closed_end=2026-10-20T22:15+00:00, prior8high=0.062837, depth_time=2026-10-20T22:15:06+00:00, book20_bid_proxy_usdt=23274, book20_ask_proxy_usdt=16397, funding_indicative=0.000047, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.19%, turnover=7091454. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-20T22:15:01+00:00, last15m_closed_end=2026-10-20T22:15+00:00, prior8high=0.200820, depth_time=2026-10-20T22:15:10+00:00, book20_bid_proxy_usdt=17489, book20_ask_proxy_usdt=18567, funding_indicative=0.000004, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-9.41%, turnover=9904709. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
