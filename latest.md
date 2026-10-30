# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T20:45:19Z**
- feed_generated_utc: 2026-10-30T20:45:21+00:00
- source_sha256: `549d5af104a0f0cf1fcae75e5bd8f79b4af7cf942c2b2e5aca340ea84b91977b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T20:45+00:00, close=77019.8, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T20:00+00:00, close=76903, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T20:00+00:00, close=76903, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EVAA_USDT|1.109500|-13.46|111.37|-12.73|6756844|4.51|
|BLESS_USDT|0.009276|-5.83|13.66|-5.10|14407883|6.46|
|Q_USDT|0.045350|-4.48|-61.67|-3.75|23810488|2.21|
|LIT_USDT|2.718800|-3.73|-18.20|-3.00|12149915|0.37|
|HYPE_USDT|90.031000|-2.50|14.82|-1.77|202920349|0.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009276|0.008786|0.009276|0.53|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.109500|1.072200|1.109500|0.55|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|90.031000|89.105000|90.031000|0.41|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.718800|2.683300|2.718800|1.24|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.045350|0.044090|0.045350|1.16|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-30T20:45:00+00:00, last15m_closed_end=2026-10-30T20:45+00:00, prior8high=0.009387, depth_time=2026-10-30T20:45:11+00:00, book20_bid_proxy_usdt=11589, book20_ask_proxy_usdt=16565, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.83%, turnover=14407883. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T20:45:00+00:00, last15m_closed_end=2026-10-30T20:45+00:00, prior8high=1.246600, depth_time=2026-10-30T20:45:07+00:00, book20_bid_proxy_usdt=8149, book20_ask_proxy_usdt=13258, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-13.46%, turnover=6756844. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-30T20:45:00+00:00, last15m_closed_end=2026-10-30T20:45+00:00, prior8high=90.924000, depth_time=2026-10-30T20:45:18+00:00, book20_bid_proxy_usdt=152645, book20_ask_proxy_usdt=56492, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.50%, turnover=202920349. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T20:45:00+00:00, last15m_closed_end=2026-10-30T20:45+00:00, prior8high=2.780500, depth_time=2026-10-30T20:45:15+00:00, book20_bid_proxy_usdt=20831, book20_ask_proxy_usdt=23291, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.73%, turnover=12149915. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-30T20:45:00+00:00, last15m_closed_end=2026-10-30T20:45+00:00, prior8high=0.045840, depth_time=2026-10-30T20:45:13+00:00, book20_bid_proxy_usdt=27423, book20_ask_proxy_usdt=29110, funding_indicative=0.000054, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.48%, turnover=23810488. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
