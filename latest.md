# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T21:30:10Z**
- feed_generated_utc: 2026-10-15T21:30:12+00:00
- source_sha256: `d577331b6d6d2f63363c4b2e2b3446df71379dee0490b77dadd16717eaf7c937`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T21:30+00:00, close=82269.9, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-15T21:00+00:00, close=82081.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-15T20:00+00:00, close=82350.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|NIL_USDT|0.082860|-4.62|-4.30|-4.50|15873461|2.41|
|WAL_USDT|0.051650|-3.09|55.15|-2.97|9236274|1.94|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NIL_USDT|0.082860|0.081300|0.082860|0.82|N|Y/Y|N/N|Y|N|
|WAL_USDT|0.051650|0.050590|0.051650|0.29|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- NIL_USDT: quote_utc=2026-10-15T21:29:59+00:00, last15m_closed_end=2026-10-15T21:30+00:00, prior8high=0.090190, depth_time=2026-10-15T21:30:06+00:00, book20_bid_proxy_usdt=20441, book20_ask_proxy_usdt=20114, funding_indicative=0.000050, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.62%, turnover=15873461. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-15T21:29:59+00:00, last15m_closed_end=2026-10-15T21:30+00:00, prior8high=0.052350, depth_time=2026-10-15T21:30:09+00:00, book20_bid_proxy_usdt=186305, book20_ask_proxy_usdt=150048, funding_indicative=-0.000221, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.09%, turnover=9236274. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
