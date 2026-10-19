# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T01:00:18Z**
- feed_generated_utc: 2026-10-19T01:00:19+00:00
- source_sha256: `ba3ee9c77b4e9c8fadd94460620735b79132947b9237ff74a86caeeb348376fd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T01:00+00:00, close=82269.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T01:00+00:00, close=82269.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T00:00+00:00, close=82076.8, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.109441|-10.27|286.41|-11.66|9999612|0.09|
|AGT_USDT|0.062042|-8.12|250.81|-9.51|10148607|0.32|
|BTW_USDT|2.258000|-2.05|34.22|-3.44|23790079|0.89|
|HBAR_USDT|0.084360|-1.65|-10.04|-3.04|50684328|1.19|
|STRK_USDT|0.060610|-1.54|-49.18|-2.93|16871045|1.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.062042|0.060544|0.062046|0.68|N|Y/Y|N/N|N|N|
|BTW_USDT|2.258000|2.309900|2.258400|1.49|Y|Y/Y|N/N|N|N|
|HBAR_USDT|0.084360|0.084400|0.084360|0.80|N|Y/Y|N/Y|N|N|
|Q_USDT|0.109441|0.109090|0.109441|0.65|N|Y/Y|N/N|N|N|
|STRK_USDT|0.060610|0.059540|0.060630|1.66|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-19T00:59:59+00:00, last15m_closed_end=2026-10-19T01:00+00:00, prior8high=0.068584, depth_time=2026-10-19T01:00:09+00:00, book20_bid_proxy_usdt=3388, book20_ask_proxy_usdt=2923, funding_indicative=0.000171, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.12%, turnover=10148607. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-19T00:59:59+00:00, last15m_closed_end=2026-10-19T01:00+00:00, prior8high=2.489400, depth_time=2026-10-19T01:00:11+00:00, book20_bid_proxy_usdt=13074, book20_ask_proxy_usdt=7897, funding_indicative=-0.000458, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.05%, turnover=23790079. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T00:59:59+00:00, last15m_closed_end=2026-10-19T01:00+00:00, prior8high=0.085750, depth_time=2026-10-19T01:00:14+00:00, book20_bid_proxy_usdt=590422, book20_ask_proxy_usdt=810922, funding_indicative=-0.000032, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=50684328. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-19T00:59:59+00:00, last15m_closed_end=2026-10-19T01:00+00:00, prior8high=0.121020, depth_time=2026-10-19T01:00:07+00:00, book20_bid_proxy_usdt=10850, book20_ask_proxy_usdt=7373, funding_indicative=0.000110, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.27%, turnover=9999612. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T00:59:59+00:00, last15m_closed_end=2026-10-19T01:00+00:00, prior8high=0.060690, depth_time=2026-10-19T01:00:17+00:00, book20_bid_proxy_usdt=323883, book20_ask_proxy_usdt=353601, funding_indicative=0.000046, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.54%, turnover=16871045. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
