# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T20:45:16Z**
- feed_generated_utc: 2026-10-25T20:45:19+00:00
- source_sha256: `ca6df3cf67837d70a0e92ef7141cbc80a4e08bc9d7da241f3c50cfff5a4c6d71`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T20:45+00:00, close=80445.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T20:00+00:00, close=80530.1, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T20:00+00:00, close=80530.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.035830|-6.78|193.68|-6.59|20638381|2.79|
|USELESS_USDT|0.169510|-1.77|19.84|-1.58|5243948|0.59|
|T_USDT|0.005295|-1.63|12.61|-1.44|8524427|1.89|
|DASH_USDT|51.750000|-1.25|8.08|-1.06|14416181|1.93|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|51.750000|51.940000|51.740000|3.93|Y|N/N|N/N|Y|N|
|IRYS_USDT|0.035830|0.035650|0.035830|0.53|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.005295|0.005285|0.005295|1.85|N|Y/Y|N/N|Y|N|
|USELESS_USDT|0.169510|0.166550|0.169510|0.42|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-10-25T20:45:01+00:00, last15m_closed_end=2026-10-25T20:45+00:00, prior8high=52.450000, depth_time=2026-10-25T20:45:15+00:00, book20_bid_proxy_usdt=603657, book20_ask_proxy_usdt=723338, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=14416181. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T20:45:01+00:00, last15m_closed_end=2026-10-25T20:45+00:00, prior8high=0.036760, depth_time=2026-10-25T20:45:08+00:00, book20_bid_proxy_usdt=60195, book20_ask_proxy_usdt=60283, funding_indicative=-0.000043, next_funding_utc=2026-10-25T21:00:00+00:00, funding_cycle_h=1, 24h_change=-6.78%, turnover=20638381. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-25T20:45:01+00:00, last15m_closed_end=2026-10-25T20:45+00:00, prior8high=0.005476, depth_time=2026-10-25T20:45:11+00:00, book20_bid_proxy_usdt=98203, book20_ask_proxy_usdt=125791, funding_indicative=-0.003029, next_funding_utc=2026-10-25T21:00:00+00:00, funding_cycle_h=1, 24h_change=-1.63%, turnover=8524427. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-25T20:45:01+00:00, last15m_closed_end=2026-10-25T20:45+00:00, prior8high=0.170640, depth_time=2026-10-25T20:45:10+00:00, book20_bid_proxy_usdt=34681, book20_ask_proxy_usdt=23801, funding_indicative=0.000151, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.77%, turnover=5243948. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
