# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T17:00:15Z**
- feed_generated_utc: 2026-10-29T17:00:16+00:00
- source_sha256: `71725c5d1960a6769ab689360cbd03455698184fb92979a4d98bb6ee5bca88ec`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T17:00+00:00, close=81232.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-29T17:00+00:00, close=81232.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-29T16:00+00:00, close=81732.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.523000|-10.13|-14.91|-9.52|9532977|3.29|
|Q_USDT|0.038640|-3.95|-70.00|-3.34|31094549|2.59|
|AKE_USDT|0.020575|-3.25|-33.25|-2.64|5644803|8.75|
|EVAA_USDT|1.152000|-2.83|121.53|-2.22|13252478|7.82|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.020575|0.020487|0.020575|0.57|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.523000|1.565900|1.522900|2.00|Y|Y/Y|Y/N|N|N|
|EVAA_USDT|1.152000|1.084300|1.151900|1.69|N|Y/Y|N/N|N|N|
|Q_USDT|0.038640|0.037740|0.038640|1.13|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-29T17:00:01+00:00, last15m_closed_end=2026-10-29T17:00+00:00, prior8high=0.021549, depth_time=2026-10-29T17:00:11+00:00, book20_bid_proxy_usdt=6959, book20_ask_proxy_usdt=3863, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.25%, turnover=5644803. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-29T17:00:01+00:00, last15m_closed_end=2026-10-29T17:00+00:00, prior8high=1.711300, depth_time=2026-10-29T17:00:07+00:00, book20_bid_proxy_usdt=19110, book20_ask_proxy_usdt=11542, funding_indicative=-0.000058, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-10.13%, turnover=9532977. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-29T17:00:00+00:00, last15m_closed_end=2026-10-29T17:00+00:00, prior8high=1.206300, depth_time=2026-10-29T17:00:14+00:00, book20_bid_proxy_usdt=15659, book20_ask_proxy_usdt=5183, funding_indicative=0.000131, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.83%, turnover=13252478. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-29T17:00:00+00:00, last15m_closed_end=2026-10-29T17:00+00:00, prior8high=0.040970, depth_time=2026-10-29T17:00:10+00:00, book20_bid_proxy_usdt=42786, book20_ask_proxy_usdt=47972, funding_indicative=0.000044, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.95%, turnover=31094549. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
