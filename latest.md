# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T21:00:14Z**
- feed_generated_utc: 2026-10-20T21:00:16+00:00
- source_sha256: `dbb2015303eef3c7e2254a5f542a534a4dddb0f9d89d954343113b172f8d8854`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T21:00+00:00, close=82810, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T21:00+00:00, close=82810, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T20:00+00:00, close=82561, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.058316|-9.76|260.48|-10.03|7453633|3.09|
|BTW_USDT|1.687600|-8.75|-13.56|-9.02|29018557|0.59|
|BAT_USDT|0.199960|-7.32|12.72|-7.59|11313729|2.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.058316|0.057751|0.058316|0.47|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.199960|0.198230|0.199960|0.27|N|Y/N|N/N|N|N|
|BTW_USDT|1.687600|1.657000|1.687000|0.61|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T20:59:59+00:00, last15m_closed_end=2026-10-20T21:00+00:00, prior8high=0.063088, depth_time=2026-10-20T21:00:08+00:00, book20_bid_proxy_usdt=10477, book20_ask_proxy_usdt=4131, funding_indicative=0.000047, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.76%, turnover=7453633. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-20T20:59:59+00:00, last15m_closed_end=2026-10-20T21:00+00:00, prior8high=0.204690, depth_time=2026-10-20T21:00:13+00:00, book20_bid_proxy_usdt=18967, book20_ask_proxy_usdt=22929, funding_indicative=0.000041, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-7.32%, turnover=11313729. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T20:59:59+00:00, last15m_closed_end=2026-10-20T21:00+00:00, prior8high=1.754000, depth_time=2026-10-20T21:00:10+00:00, book20_bid_proxy_usdt=13022, book20_ask_proxy_usdt=12360, funding_indicative=-0.003279, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.75%, turnover=29018557. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
