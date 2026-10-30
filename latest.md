# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T20:30:18Z**
- feed_generated_utc: 2026-10-30T20:30:20+00:00
- source_sha256: `2ad59a1a5e36db51773ac3f6279b3ce95c1bddcb730edd0b7c90782c4a5608be`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T20:30+00:00, close=76960, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T20:00+00:00, close=76903, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T20:00+00:00, close=76903, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EVAA_USDT|1.123000|-12.40|113.94|-11.61|6737912|3.56|
|BLESS_USDT|0.009199|-6.61|12.71|-5.82|14314944|5.45|
|Q_USDT|0.044820|-5.60|-62.12|-4.81|23737764|2.24|
|LIT_USDT|2.732400|-3.25|-17.79|-2.46|12074049|0.37|
|HYPE_USDT|90.258000|-2.25|15.11|-1.46|202424867|0.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009199|0.008786|0.009199|0.74|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.123000|1.072200|1.123000|0.61|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|90.258000|89.105000|90.260000|0.51|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.732400|2.683300|2.732100|0.80|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.044820|0.044090|0.044830|0.81|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-30T20:30:03+00:00, last15m_closed_end=2026-10-30T20:30+00:00, prior8high=0.009789, depth_time=2026-10-30T20:30:10+00:00, book20_bid_proxy_usdt=16430, book20_ask_proxy_usdt=15703, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.61%, turnover=14314944. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T20:30:03+00:00, last15m_closed_end=2026-10-30T20:30+00:00, prior8high=1.254200, depth_time=2026-10-30T20:30:08+00:00, book20_bid_proxy_usdt=7221, book20_ask_proxy_usdt=13849, funding_indicative=0.000080, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-12.40%, turnover=6737912. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-30T20:30:03+00:00, last15m_closed_end=2026-10-30T20:30+00:00, prior8high=90.924000, depth_time=2026-10-30T20:30:17+00:00, book20_bid_proxy_usdt=99828, book20_ask_proxy_usdt=127095, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.25%, turnover=202424867. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T20:30:03+00:00, last15m_closed_end=2026-10-30T20:30+00:00, prior8high=2.780500, depth_time=2026-10-30T20:30:14+00:00, book20_bid_proxy_usdt=18443, book20_ask_proxy_usdt=22688, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.25%, turnover=12074049. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-30T20:30:03+00:00, last15m_closed_end=2026-10-30T20:30+00:00, prior8high=0.046070, depth_time=2026-10-30T20:30:12+00:00, book20_bid_proxy_usdt=21824, book20_ask_proxy_usdt=24622, funding_indicative=0.000060, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.60%, turnover=23737764. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
