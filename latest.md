# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T13:30:14Z**
- feed_generated_utc: 2026-11-06T13:30:15+00:00
- source_sha256: `d54cadb0e5c14b1e2325c9276e6f8cd60da358a4b18a0ad7605d486f537b5e6c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T13:30+00:00, close=76003.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T13:00+00:00, close=76005.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T12:00+00:00, close=76114.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|XRP_USDT|1.188200|-4.53|-9.26|-4.52|477809939|0.84|
|BCH_USDT|267.140000|-4.29|-7.33|-4.28|6979897|6.37|
|XPL_USDT|0.057790|-1.34|-26.78|-1.33|11681448|3.46|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|267.140000|265.710000|267.140000|0.39|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057790|0.057410|0.057790|2.04|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.188200|1.183800|1.188200|0.74|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T13:30:00+00:00, last15m_closed_end=2026-11-06T13:30+00:00, prior8high=271.890000, depth_time=2026-11-06T13:30:11+00:00, book20_bid_proxy_usdt=29697, book20_ask_proxy_usdt=34718, funding_indicative=-0.000033, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.29%, turnover=6979897. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T13:30:00+00:00, last15m_closed_end=2026-11-06T13:30+00:00, prior8high=0.058510, depth_time=2026-11-06T13:30:13+00:00, book20_bid_proxy_usdt=207530, book20_ask_proxy_usdt=266751, funding_indicative=0.000050, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.34%, turnover=11681448. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T13:29:59+00:00, last15m_closed_end=2026-11-06T13:30+00:00, prior8high=1.202300, depth_time=2026-11-06T13:30:08+00:00, book20_bid_proxy_usdt=521757, book20_ask_proxy_usdt=839210, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.53%, turnover=477809939. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
