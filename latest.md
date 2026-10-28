# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T23:15:16Z**
- feed_generated_utc: 2026-10-28T23:15:20+00:00
- source_sha256: `7f437bde493687f0ba71d00252b6f7feef0a6d90ff2ffb65f2fe84b71e83ee05`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T23:15+00:00, close=81287.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T23:00+00:00, close=81236, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T20:00+00:00, close=81544.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.721400|-0.95|17.11|-1.89|11411738|4.07|
|HBAR_USDT|0.075210|-0.92|-12.48|-1.86|12303560|1.33|
|XMR_USDT|599.660000|-0.73|0.57|-1.67|5425244|2.83|
|BCH_USDT|290.880000|-0.70|0.41|-1.64|5883539|4.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|290.880000|288.270000|290.880000|0.30|N|Y/Y|N/N|N|N|
|BTW_USDT|1.721400|1.719100|1.721400|1.37|N|N/N|N/N|N|N|
|HBAR_USDT|0.075210|0.075040|0.075210|2.47|N|Y/Y|Y/Y|N|N|
|XMR_USDT|599.660000|597.350000|599.660000|0.67|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-10-28T23:15:01+00:00, last15m_closed_end=2026-10-28T23:15+00:00, prior8high=291.470000, depth_time=2026-10-28T23:15:14+00:00, book20_bid_proxy_usdt=50556, book20_ask_proxy_usdt=87491, funding_indicative=0.000000, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.70%, turnover=5883539. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-28T23:15:01+00:00, last15m_closed_end=2026-10-28T23:15+00:00, prior8high=1.751000, depth_time=2026-10-28T23:15:08+00:00, book20_bid_proxy_usdt=23232, book20_ask_proxy_usdt=26532, funding_indicative=0.000050, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.95%, turnover=11411738. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T23:15:01+00:00, last15m_closed_end=2026-10-28T23:15+00:00, prior8high=0.076200, depth_time=2026-10-28T23:15:10+00:00, book20_bid_proxy_usdt=931501, book20_ask_proxy_usdt=1241764, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.92%, turnover=12303560. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-28T23:15:02+00:00, last15m_closed_end=2026-10-28T23:15+00:00, prior8high=609.340000, depth_time=2026-10-28T23:15:11+00:00, book20_bid_proxy_usdt=13190, book20_ask_proxy_usdt=8452, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.73%, turnover=5425244. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
