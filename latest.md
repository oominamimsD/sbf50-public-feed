# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T22:00:19Z**
- feed_generated_utc: 2026-10-30T22:00:20+00:00
- source_sha256: `1bb3850df4c2a5af0874b39091a47eece34abcc8ff922b50f2e4230036ed33f4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T22:00+00:00, close=76670.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T22:00+00:00, close=76670.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T20:00+00:00, close=76903, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BLESS_USDT|0.009696|-28.20|18.80|-27.06|12699543|5.15|
|EVAA_USDT|1.105900|-13.74|110.68|-12.60|6657631|4.51|
|LIT_USDT|2.697300|-5.82|-18.85|-4.68|9407203|0.37|
|BTW_USDT|1.151800|-3.97|-32.34|-2.83|10225709|0.87|
|HYPE_USDT|89.156000|-3.45|13.71|-2.31|153578626|0.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009696|0.009000|0.009696|0.28|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.151800|1.156600|1.153100|0.65|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.105900|1.082800|1.105400|1.06|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|89.156000|89.442000|89.105000|1.00|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.697300|2.703000|2.697300|0.85|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-30T22:00:03+00:00, last15m_closed_end=2026-10-30T22:00+00:00, prior8high=0.009655, depth_time=2026-10-30T22:00:09+00:00, book20_bid_proxy_usdt=12758, book20_ask_proxy_usdt=13624, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-28.20%, turnover=12699543. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T22:00:03+00:00, last15m_closed_end=2026-10-30T22:00+00:00, prior8high=1.292700, depth_time=2026-10-30T22:00:15+00:00, book20_bid_proxy_usdt=15647, book20_ask_proxy_usdt=9107, funding_indicative=-0.000277, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.97%, turnover=10225709. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T22:00:03+00:00, last15m_closed_end=2026-10-30T22:00+00:00, prior8high=1.143000, depth_time=2026-10-30T22:00:09+00:00, book20_bid_proxy_usdt=4272, book20_ask_proxy_usdt=3188, funding_indicative=0.000128, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-13.74%, turnover=6657631. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-30T22:00:03+00:00, last15m_closed_end=2026-10-30T22:00+00:00, prior8high=90.924000, depth_time=2026-10-30T22:00:18+00:00, book20_bid_proxy_usdt=44842, book20_ask_proxy_usdt=222485, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.45%, turnover=153578626. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T22:00:03+00:00, last15m_closed_end=2026-10-30T22:00+00:00, prior8high=2.780500, depth_time=2026-10-30T22:00:13+00:00, book20_bid_proxy_usdt=22448, book20_ask_proxy_usdt=29874, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.82%, turnover=9407203. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
