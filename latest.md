# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T22:00:13Z**
- feed_generated_utc: 2026-10-20T22:00:15+00:00
- source_sha256: `c67c92994ce0d7a0215a343f5bafd4595c8729814821c0382c187858d5e97cda`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T22:00+00:00, close=82932.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T22:00+00:00, close=82932.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T20:00+00:00, close=82561, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.196100|-10.21|10.55|-10.62|9787991|0.51|
|AGT_USDT|0.057764|-9.28|257.07|-9.69|7052144|0.52|
|ARB_USDT|0.189140|-3.77|2.43|-4.18|91230607|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.057764|0.057916|0.057764|0.70|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.189140|0.188000|0.189140|1.23|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.196100|0.194560|0.196100|0.51|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T22:00:02+00:00, last15m_closed_end=2026-10-20T22:00+00:00, prior8high=0.062837, depth_time=2026-10-20T22:00:08+00:00, book20_bid_proxy_usdt=12807, book20_ask_proxy_usdt=12968, funding_indicative=0.000047, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.28%, turnover=7052144. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T22:00:02+00:00, last15m_closed_end=2026-10-20T22:00+00:00, prior8high=0.191850, depth_time=2026-10-20T22:00:13+00:00, book20_bid_proxy_usdt=86742, book20_ask_proxy_usdt=30856, funding_indicative=-0.000040, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.77%, turnover=91230607. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-20T22:00:02+00:00, last15m_closed_end=2026-10-20T22:00+00:00, prior8high=0.201830, depth_time=2026-10-20T22:00:07+00:00, book20_bid_proxy_usdt=15353, book20_ask_proxy_usdt=16143, funding_indicative=0.000016, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-10.21%, turnover=9787991. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
