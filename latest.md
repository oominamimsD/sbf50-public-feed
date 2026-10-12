# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-12T16:30:19Z**
- feed_generated_utc: 2026-10-12T16:30:22+00:00
- source_sha256: `03017e75f4b8a8922a3cdafb01590148cb965eb8bc969de778e2b0dbe391c26c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-12T16:30+00:00, close=82787.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-12T16:00+00:00, close=82680.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-12T16:00+00:00, close=82680.3, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CKB_USDT|0.001620|-2.10|22.24|-2.22|5702636|0.62|
|S_USDT|0.056490|-1.56|31.52|-1.68|31237694|3.55|
|PONS_USDT|0.290200|-1.52|-24.32|-1.64|6350445|6.89|
|MAGIC_USDT|0.120440|-1.24|94.28|-1.36|12697429|0.83|
|RLC_USDT|0.979100|-0.96|78.66|-1.08|11291180|1.02|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CKB_USDT|0.001620|0.001600|0.001620|0.51|N|Y/Y|N/N|Y|N|
|MAGIC_USDT|0.120440|0.116500|0.120580|0.44|N|Y/Y|N/N|Y|N|
|PONS_USDT|0.290200|0.285300|0.290600|0.80|N|Y/Y|Y/Y|Y|N|
|RLC_USDT|0.979100|0.953600|0.979100|0.93|N|Y/Y|N/N|Y|N|
|S_USDT|0.056490|0.056430|0.056650|0.24|N|Y/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- CKB_USDT: quote_utc=2026-10-12T16:30:02+00:00, last15m_closed_end=2026-10-12T16:30+00:00, prior8high=0.001674, depth_time=2026-10-12T16:30:07+00:00, book20_bid_proxy_usdt=20149, book20_ask_proxy_usdt=16903, funding_indicative=-0.000774, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=5702636. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGIC_USDT: quote_utc=2026-10-12T16:30:02+00:00, last15m_closed_end=2026-10-12T16:30+00:00, prior8high=0.123510, depth_time=2026-10-12T16:30:16+00:00, book20_bid_proxy_usdt=171289, book20_ask_proxy_usdt=175319, funding_indicative=-0.000223, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.24%, turnover=12697429. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-12T16:30:03+00:00, last15m_closed_end=2026-10-12T16:30+00:00, prior8high=0.306000, depth_time=2026-10-12T16:30:14+00:00, book20_bid_proxy_usdt=207773, book20_ask_proxy_usdt=187435, funding_indicative=0.000050, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.52%, turnover=6350445. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-12T16:30:02+00:00, last15m_closed_end=2026-10-12T16:30+00:00, prior8high=1.051400, depth_time=2026-10-12T16:30:18+00:00, book20_bid_proxy_usdt=57676, book20_ask_proxy_usdt=37423, funding_indicative=-0.001057, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.96%, turnover=11291180. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-12T16:30:02+00:00, last15m_closed_end=2026-10-12T16:30+00:00, prior8high=0.060540, depth_time=2026-10-12T16:30:10+00:00, book20_bid_proxy_usdt=181396, book20_ask_proxy_usdt=120776, funding_indicative=0.000042, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.56%, turnover=31237694. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
