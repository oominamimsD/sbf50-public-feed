# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T21:15:18Z**
- feed_generated_utc: 2026-10-30T21:15:20+00:00
- source_sha256: `796cd2efa3e9f48f4b12c1f5a652c598e3240ba1fdc7d8db8389d7c2db6e19e7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T21:15+00:00, close=76660, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T21:00+00:00, close=76891.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T20:00+00:00, close=76903, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EVAA_USDT|1.090600|-14.93|107.77|-13.75|6698771|3.67|
|BLESS_USDT|0.009459|-3.97|15.90|-2.79|13236199|2.12|
|LIT_USDT|2.713100|-3.93|-18.37|-2.75|10395933|0.37|
|Q_USDT|0.045630|-3.89|-61.44|-2.71|22565639|6.57|
|HYPE_USDT|89.921000|-2.62|14.68|-1.44|168440355|0.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009459|0.008805|0.009472|0.92|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.090600|1.107000|1.094300|1.35|Y|Y/Y|Y/N|Y|N|
|HYPE_USDT|89.921000|89.655000|89.940000|1.21|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.713100|2.714300|2.713100|1.22|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.045630|0.044150|0.045630|1.10|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-30T21:15:02+00:00, last15m_closed_end=2026-10-30T21:15+00:00, prior8high=0.009584, depth_time=2026-10-30T21:15:10+00:00, book20_bid_proxy_usdt=12339, book20_ask_proxy_usdt=15872, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.97%, turnover=13236199. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T21:15:02+00:00, last15m_closed_end=2026-10-30T21:15+00:00, prior8high=1.163600, depth_time=2026-10-30T21:15:08+00:00, book20_bid_proxy_usdt=5320, book20_ask_proxy_usdt=7954, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-14.93%, turnover=6698771. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-30T21:15:02+00:00, last15m_closed_end=2026-10-30T21:15+00:00, prior8high=90.924000, depth_time=2026-10-30T21:15:17+00:00, book20_bid_proxy_usdt=161694, book20_ask_proxy_usdt=30258, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.62%, turnover=168440355. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T21:15:03+00:00, last15m_closed_end=2026-10-30T21:15+00:00, prior8high=2.780500, depth_time=2026-10-30T21:15:12+00:00, book20_bid_proxy_usdt=32621, book20_ask_proxy_usdt=31384, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.93%, turnover=10395933. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-30T21:15:02+00:00, last15m_closed_end=2026-10-30T21:15+00:00, prior8high=0.046010, depth_time=2026-10-30T21:15:13+00:00, book20_bid_proxy_usdt=21163, book20_ask_proxy_usdt=35745, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.89%, turnover=22565639. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
