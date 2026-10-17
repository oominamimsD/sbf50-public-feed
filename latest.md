# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T18:30:17Z**
- feed_generated_utc: 2026-10-17T18:30:18+00:00
- source_sha256: `f52809225f96b9c476755be4c4b79624444bc1ccecbf37246a6b72eaf906823d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T18:30+00:00, close=81518.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T18:00+00:00, close=81340.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T16:00+00:00, close=81315.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DNA_USDT|0.262900|-3.38|UNKNOWN|-3.63|7303090|3.80|
|FILECOIN_USDT|1.072000|-1.41|-4.94|-1.66|24504385|0.93|
|EIGEN_USDT|0.253500|-1.09|7.59|-1.34|9409369|3.95|
|ARB_USDT|0.182530|-0.75|-2.21|-1.00|26736517|0.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.182530|0.180230|0.182530|0.56|N|Y/Y|Y/Y|Y|N|
|DNA_USDT|0.262900|0.254400|0.262900|0.51|N|Y/Y|?|Y|N|
|EIGEN_USDT|0.253500|0.247500|0.253400|1.07|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|1.072000|1.059300|1.072000|0.68|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-17T18:30:00+00:00, last15m_closed_end=2026-10-17T18:30+00:00, prior8high=0.183980, depth_time=2026-10-17T18:30:15+00:00, book20_bid_proxy_usdt=81182, book20_ask_proxy_usdt=93097, funding_indicative=-0.000024, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.75%, turnover=26736517. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-17T18:30:00+00:00, last15m_closed_end=2026-10-17T18:30+00:00, prior8high=0.272400, depth_time=2026-10-17T18:30:07+00:00, book20_bid_proxy_usdt=100741, book20_ask_proxy_usdt=81990, funding_indicative=-0.001497, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.38%, turnover=7303090. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-17T18:30:00+00:00, last15m_closed_end=2026-10-17T18:30+00:00, prior8high=0.257700, depth_time=2026-10-17T18:30:13+00:00, book20_bid_proxy_usdt=634067, book20_ask_proxy_usdt=420940, funding_indicative=0.000050, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.09%, turnover=9409369. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T18:30:00+00:00, last15m_closed_end=2026-10-17T18:30+00:00, prior8high=1.095600, depth_time=2026-10-17T18:30:11+00:00, book20_bid_proxy_usdt=526943, book20_ask_proxy_usdt=709036, funding_indicative=-0.000097, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=24504385. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
