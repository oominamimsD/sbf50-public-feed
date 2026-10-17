# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T18:45:16Z**
- feed_generated_utc: 2026-10-17T18:45:18+00:00
- source_sha256: `34694ebe97d21e29e6e65b0e2a027739f8ee3a9ab45df07a8a8f4625a2392698`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T18:45+00:00, close=81509.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T18:00+00:00, close=81340.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T16:00+00:00, close=81315.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DNA_USDT|0.255600|-6.06|UNKNOWN|-6.29|7329715|3.91|
|EIGEN_USDT|0.253200|-1.20|7.47|-1.43|9467056|3.95|
|FILECOIN_USDT|1.075100|-1.13|-4.67|-1.36|24829111|0.93|
|ARB_USDT|0.182440|-0.80|-2.26|-1.03|26866215|0.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.182440|0.180230|0.182450|0.53|N|Y/Y|Y/Y|Y|N|
|DNA_USDT|0.255600|0.254500|0.255600|0.59|N|Y/Y|?|Y|N|
|EIGEN_USDT|0.253200|0.247500|0.253200|0.49|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|1.075100|1.059300|1.075500|1.07|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-17T18:45:01+00:00, last15m_closed_end=2026-10-17T18:45+00:00, prior8high=0.183420, depth_time=2026-10-17T18:45:15+00:00, book20_bid_proxy_usdt=84106, book20_ask_proxy_usdt=75463, funding_indicative=-0.000016, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.80%, turnover=26866215. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-17T18:45:01+00:00, last15m_closed_end=2026-10-17T18:45+00:00, prior8high=0.272400, depth_time=2026-10-17T18:45:07+00:00, book20_bid_proxy_usdt=96678, book20_ask_proxy_usdt=70377, funding_indicative=-0.001455, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.06%, turnover=7329715. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-17T18:45:01+00:00, last15m_closed_end=2026-10-17T18:45+00:00, prior8high=0.256400, depth_time=2026-10-17T18:45:07+00:00, book20_bid_proxy_usdt=555785, book20_ask_proxy_usdt=553303, funding_indicative=0.000050, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.20%, turnover=9467056. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T18:45:01+00:00, last15m_closed_end=2026-10-17T18:45+00:00, prior8high=1.092700, depth_time=2026-10-17T18:45:13+00:00, book20_bid_proxy_usdt=492138, book20_ask_proxy_usdt=855479, funding_indicative=-0.000103, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=24829111. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
