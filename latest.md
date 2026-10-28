# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T00:30:15Z**
- feed_generated_utc: 2026-10-28T00:30:17+00:00
- source_sha256: `6626db89da814651c3f5a7231d4d3faaf6cc380c468b5dfb3c0ed5ce6b1870f5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T00:30+00:00, close=80742.7, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T00:00+00:00, close=80868.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T00:00+00:00, close=80868.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.053524|-15.82|-56.39|-16.08|42572385|0.37|
|SYN_USDT|0.178100|-1.81|-2.99|-2.07|5656997|5.62|
|IRYS_USDT|0.024620|-1.16|89.09|-1.42|5640491|4.06|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|IRYS_USDT|0.024620|0.023220|0.024620|2.20|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.053524|0.051075|0.053527|0.69|N|Y/Y|Y/Y|N|N|
|SYN_USDT|0.178100|0.177400|0.178100|0.59|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- IRYS_USDT: quote_utc=2026-10-28T00:30:00+00:00, last15m_closed_end=2026-10-28T00:30+00:00, prior8high=0.026530, depth_time=2026-10-28T00:30:14+00:00, book20_bid_proxy_usdt=98039, book20_ask_proxy_usdt=68545, funding_indicative=-0.001770, next_funding_utc=2026-10-28T01:00:00+00:00, funding_cycle_h=1, 24h_change=-1.16%, turnover=5640491. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T00:30:00+00:00, last15m_closed_end=2026-10-28T00:30+00:00, prior8high=0.055000, depth_time=2026-10-28T00:30:08+00:00, book20_bid_proxy_usdt=25819, book20_ask_proxy_usdt=28243, funding_indicative=-0.000182, next_funding_utc=2026-10-28T04:00:00+00:00, funding_cycle_h=4, 24h_change=-15.82%, turnover=42572385. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SYN_USDT: quote_utc=2026-10-28T00:30:00+00:00, last15m_closed_end=2026-10-28T00:30+00:00, prior8high=0.180300, depth_time=2026-10-28T00:30:09+00:00, book20_bid_proxy_usdt=106946, book20_ask_proxy_usdt=101019, funding_indicative=0.000050, next_funding_utc=2026-10-28T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.81%, turnover=5656997. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
