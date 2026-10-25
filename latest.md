# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T22:15:19Z**
- feed_generated_utc: 2026-10-25T22:15:22+00:00
- source_sha256: `2e7049995ed5c801acafce28d4064c3a3f8d45efc1770670711c6b7455e71eae`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T22:15+00:00, close=80383, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T22:00+00:00, close=80235.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T20:00+00:00, close=80530.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.037320|-2.91|205.90|-2.66|20034569|2.68|
|XMR_USDT|595.050000|-2.01|2.15|-1.76|6602613|0.17|
|USELESS_USDT|0.169490|-1.78|19.83|-1.53|5091992|0.59|
|DASH_USDT|51.590000|-1.56|7.74|-1.31|14033235|1.94|
|TIA_USDT|0.529700|-1.37|-14.27|-1.12|18405135|1.89|
|PEPE_USDT|0.000004|-1.36|12.47|-1.11|73890221|0.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|51.590000|51.310000|51.590000|2.37|N|Y/Y|N/N|Y|N|
|IRYS_USDT|0.037320|0.035580|0.037320|0.93|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|2.93|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.529700|0.525200|0.529700|2.35|N|Y/Y|Y/Y|Y|N|
|USELESS_USDT|0.169490|0.167580|0.169520|4.83|N|Y/Y|N/N|Y|N|
|XMR_USDT|595.050000|595.900000|594.760000|4.95|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-10-25T22:15:01+00:00, last15m_closed_end=2026-10-25T22:15+00:00, prior8high=52.280000, depth_time=2026-10-25T22:15:14+00:00, book20_bid_proxy_usdt=690277, book20_ask_proxy_usdt=523676, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.56%, turnover=14033235. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T22:15:01+00:00, last15m_closed_end=2026-10-25T22:15+00:00, prior8high=0.036740, depth_time=2026-10-25T22:15:07+00:00, book20_bid_proxy_usdt=72091, book20_ask_proxy_usdt=69287, funding_indicative=-0.000103, next_funding_utc=2026-10-25T23:00:00+00:00, funding_cycle_h=1, 24h_change=-2.91%, turnover=20034569. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-25T22:15:01+00:00, last15m_closed_end=2026-10-25T22:15+00:00, prior8high=0.000004, depth_time=2026-10-25T22:15:19+00:00, book20_bid_proxy_usdt=34312, book20_ask_proxy_usdt=45858, funding_indicative=0.000054, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=73890221. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-25T22:15:01+00:00, last15m_closed_end=2026-10-25T22:15+00:00, prior8high=0.536000, depth_time=2026-10-25T22:15:16+00:00, book20_bid_proxy_usdt=234642, book20_ask_proxy_usdt=245443, funding_indicative=0.000040, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.37%, turnover=18405135. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-25T22:15:01+00:00, last15m_closed_end=2026-10-25T22:15+00:00, prior8high=0.170810, depth_time=2026-10-25T22:15:12+00:00, book20_bid_proxy_usdt=14686, book20_ask_proxy_usdt=13110, funding_indicative=0.000086, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.78%, turnover=5091992. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-25T22:15:01+00:00, last15m_closed_end=2026-10-25T22:15+00:00, prior8high=605.460000, depth_time=2026-10-25T22:15:09+00:00, book20_bid_proxy_usdt=32494, book20_ask_proxy_usdt=29213, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.01%, turnover=6602613. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
