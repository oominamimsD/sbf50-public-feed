# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T20:15:19Z**
- feed_generated_utc: 2026-10-30T20:15:20+00:00
- source_sha256: `da27735f0d569c01acd1fed05b5ea6c47bb480a2b960bc9f3e492c680c37e0ee`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T20:15+00:00, close=76932.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T20:00+00:00, close=76903, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T20:00+00:00, close=76903, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EVAA_USDT|1.111400|-13.31|111.73|-12.49|6716790|4.50|
|BLESS_USDT|0.009193|-6.67|12.64|-5.85|14182320|4.33|
|Q_USDT|0.044900|-5.43|-62.05|-4.61|23685532|4.46|
|LIT_USDT|2.750500|-2.60|-17.25|-1.78|12021376|0.36|
|HYPE_USDT|90.200000|-2.32|15.04|-1.50|201730151|0.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009193|0.008786|0.009193|0.43|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.111400|1.072200|1.111400|0.90|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|90.200000|89.105000|90.210000|0.29|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.750500|2.683300|2.750700|1.63|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.044900|0.044090|0.044900|0.46|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-30T20:15:03+00:00, last15m_closed_end=2026-10-30T20:15+00:00, prior8high=0.009789, depth_time=2026-10-30T20:15:10+00:00, book20_bid_proxy_usdt=12596, book20_ask_proxy_usdt=12249, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.67%, turnover=14182320. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T20:15:03+00:00, last15m_closed_end=2026-10-30T20:15+00:00, prior8high=1.254200, depth_time=2026-10-30T20:15:06+00:00, book20_bid_proxy_usdt=5895, book20_ask_proxy_usdt=4994, funding_indicative=0.000098, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-13.31%, turnover=6716790. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-30T20:15:03+00:00, last15m_closed_end=2026-10-30T20:15+00:00, prior8high=91.050000, depth_time=2026-10-30T20:15:18+00:00, book20_bid_proxy_usdt=168727, book20_ask_proxy_usdt=56782, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.32%, turnover=201730151. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T20:15:03+00:00, last15m_closed_end=2026-10-30T20:15+00:00, prior8high=2.762300, depth_time=2026-10-30T20:15:13+00:00, book20_bid_proxy_usdt=24988, book20_ask_proxy_usdt=21149, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.60%, turnover=12021376. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-30T20:15:03+00:00, last15m_closed_end=2026-10-30T20:15+00:00, prior8high=0.046410, depth_time=2026-10-30T20:15:11+00:00, book20_bid_proxy_usdt=30334, book20_ask_proxy_usdt=23674, funding_indicative=0.000076, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.43%, turnover=23685532. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
