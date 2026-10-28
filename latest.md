# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T19:45:15Z**
- feed_generated_utc: 2026-10-28T19:45:19+00:00
- source_sha256: `39c9dffdd37736596217f6b440b38ff6594d51a6f1490eb19657be4d0bd53ee4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T19:45+00:00, close=81291.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T19:00+00:00, close=80980.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-28T16:00+00:00, close=80528, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AIN_USDT|0.140600|-6.64|251.06|-7.59|7593959|1.42|
|BCH_USDT|288.410000|-1.54|-0.43|-2.49|5493656|2.43|
|XMR_USDT|599.030000|-0.84|0.46|-1.79|5512532|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AIN_USDT|0.140600|0.140770|0.140360|0.37|N|Y/Y|N/N|N|N|
|BCH_USDT|288.410000|282.710000|288.430000|1.23|N|Y/Y|N/N|N|N|
|XMR_USDT|599.030000|598.000000|598.930000|0.23|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AIN_USDT: quote_utc=2026-10-28T19:45:02+00:00, last15m_closed_end=2026-10-28T19:45+00:00, prior8high=0.147870, depth_time=2026-10-28T19:45:09+00:00, book20_bid_proxy_usdt=16618, book20_ask_proxy_usdt=8093, funding_indicative=0.000818, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.64%, turnover=7593959. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-10-28T19:45:03+00:00, last15m_closed_end=2026-10-28T19:45+00:00, prior8high=287.650000, depth_time=2026-10-28T19:45:11+00:00, book20_bid_proxy_usdt=53706, book20_ask_proxy_usdt=192434, funding_indicative=0.000030, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=5493656. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-28T19:45:03+00:00, last15m_closed_end=2026-10-28T19:45+00:00, prior8high=605.630000, depth_time=2026-10-28T19:45:14+00:00, book20_bid_proxy_usdt=15399, book20_ask_proxy_usdt=18885, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.84%, turnover=5512532. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
