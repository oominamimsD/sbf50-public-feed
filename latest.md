# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T04:00:16Z**
- feed_generated_utc: 2026-10-28T04:00:19+00:00
- source_sha256: `0a415041d1c24c5db2e78e8b722e97a1fa3a74f75ac155943e40101aeb928ca1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T04:00+00:00, close=81110.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T04:00+00:00, close=81110.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T04:00+00:00, close=81110.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.022443|-24.08|-27.81|-24.80|5514319|3.57|
|Q_USDT|0.052727|-17.07|-57.04|-17.79|34289163|1.90|
|NIL_USDT|0.083470|-8.24|-6.06|-8.96|5877457|5.99|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.022443|0.022193|0.022443|1.12|N|Y/Y|Y/Y|N|N|
|NIL_USDT|0.083470|0.083490|0.083470|0.44|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.052727|0.052439|0.052918|0.62|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T04:00:05+00:00, last15m_closed_end=2026-10-28T04:00+00:00, prior8high=0.023284, depth_time=2026-10-28T04:00:10+00:00, book20_bid_proxy_usdt=3651, book20_ask_proxy_usdt=3386, funding_indicative=0.000050, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-24.08%, turnover=5514319. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-28T04:00:05+00:00, last15m_closed_end=2026-10-28T04:00+00:00, prior8high=0.086200, depth_time=2026-10-28T04:00:15+00:00, book20_bid_proxy_usdt=11900, book20_ask_proxy_usdt=6091, funding_indicative=-0.000078, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.24%, turnover=5877457. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T04:00:04+00:00, last15m_closed_end=2026-10-28T04:00+00:00, prior8high=0.055511, depth_time=2026-10-28T04:00:13+00:00, book20_bid_proxy_usdt=27031, book20_ask_proxy_usdt=26460, funding_indicative=0.000004, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-17.07%, turnover=34289163. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
