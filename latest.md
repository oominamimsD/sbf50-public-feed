# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T20:00:13Z**
- feed_generated_utc: 2026-11-07T20:00:14+00:00
- source_sha256: `82649dac20c0e29645aa50eb3936d6afd1a0893ed74f2efc0a04cec196c3b9c6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T20:00+00:00, close=75772.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T20:00+00:00, close=75772.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T20:00+00:00, close=75772.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ENA_USDT|0.157180|-1.91|-18.98|-1.97|26739678|0.64|
|UAI_USDT|0.122300|-1.68|-60.63|-1.74|12441244|8.15|
|NEAR_USDT|3.646000|-1.53|-18.54|-1.59|23107275|5.49|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ENA_USDT|0.157180|0.156940|0.157180|0.28|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.646000|3.646000|3.646000|0.75|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.122300|0.121100|0.122400|0.44|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ENA_USDT: quote_utc=2026-11-07T20:00:02+00:00, last15m_closed_end=2026-11-07T20:00+00:00, prior8high=0.158990, depth_time=2026-11-07T20:00:07+00:00, book20_bid_proxy_usdt=341376, book20_ask_proxy_usdt=312915, funding_indicative=0.000050, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.91%, turnover=26739678. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-07T20:00:02+00:00, last15m_closed_end=2026-11-07T20:00+00:00, prior8high=3.684000, depth_time=2026-11-07T20:00:12+00:00, book20_bid_proxy_usdt=3809306, book20_ask_proxy_usdt=4068097, funding_indicative=0.000043, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=23107275. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T20:00:02+00:00, last15m_closed_end=2026-11-07T20:00+00:00, prior8high=0.126600, depth_time=2026-11-07T20:00:10+00:00, book20_bid_proxy_usdt=234998, book20_ask_proxy_usdt=192278, funding_indicative=0.000050, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=12441244. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
