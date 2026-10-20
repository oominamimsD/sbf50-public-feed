# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T02:30:14Z**
- feed_generated_utc: 2026-10-20T02:30:16+00:00
- source_sha256: `6741a5786e099ca5703d219e13e6f52491bed811e61869132f5df0ae7fbcc6bc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T02:30+00:00, close=81680.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T02:00+00:00, close=81765.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T00:00+00:00, close=81903.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.861600|-2.12|-17.66|-1.84|7670907|1.07|
|SAND_USDT|0.058050|-1.84|-6.50|-1.56|9156734|3.45|
|NEAR_USDT|4.823000|-1.65|-13.08|-1.37|170018820|2.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NEAR_USDT|4.823000|4.785000|4.823000|1.51|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.058050|0.057130|0.058050|1.96|N|Y/Y|N/Y|Y|N|
|ZRO_USDT|1.861600|1.833600|1.861600|1.99|N|Y/N|N/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- NEAR_USDT: quote_utc=2026-10-20T02:30:01+00:00, last15m_closed_end=2026-10-20T02:30+00:00, prior8high=4.885000, depth_time=2026-10-20T02:30:13+00:00, book20_bid_proxy_usdt=343772, book20_ask_proxy_usdt=1584813, funding_indicative=0.000062, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=170018820. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T02:30:01+00:00, last15m_closed_end=2026-10-20T02:30+00:00, prior8high=0.059090, depth_time=2026-10-20T02:30:11+00:00, book20_bid_proxy_usdt=521613, book20_ask_proxy_usdt=770788, funding_indicative=-0.002272, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=9156734. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T02:30:01+00:00, last15m_closed_end=2026-10-20T02:30+00:00, prior8high=1.904600, depth_time=2026-10-20T02:30:08+00:00, book20_bid_proxy_usdt=43952, book20_ask_proxy_usdt=48670, funding_indicative=0.000050, next_funding_utc=2026-10-20T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.12%, turnover=7670907. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
