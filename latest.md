# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T09:45:15Z**
- feed_generated_utc: 2026-11-04T09:45:17+00:00
- source_sha256: `94ea10966a4c9a5cdadedc1bbeeeafb3f998cdffd355b3eee8ec0a757b9413db`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T09:45+00:00, close=78410, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T09:00+00:00, close=78473.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T08:00+00:00, close=78117.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.032300|-39.97|-32.02|-40.93|10763646|9.29|
|AKE_USDT|0.002988|-28.10|-85.85|-29.06|12469295|3.35|
|TRUMPOFFICIAL_USDT|1.475000|-8.27|-12.61|-9.23|10531437|6.78|
|Q_USDT|0.028060|-0.39|-55.86|-1.35|7340540|7.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.032300|0.033030|0.032300|2.78|Y|Y/Y|Y/N|N|N|
|AKE_USDT|0.002988|0.002863|0.002987|1.28|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.028060|0.027670|0.028060|0.91|N|Y/Y|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.475000|1.463000|1.475000|0.78|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T09:45:03+00:00, last15m_closed_end=2026-11-04T09:45+00:00, prior8high=0.038080, depth_time=2026-11-04T09:45:07+00:00, book20_bid_proxy_usdt=47751, book20_ask_proxy_usdt=46821, funding_indicative=0.000053, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-39.97%, turnover=10763646. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T09:45:03+00:00, last15m_closed_end=2026-11-04T09:45+00:00, prior8high=0.003115, depth_time=2026-11-04T09:45:10+00:00, book20_bid_proxy_usdt=58696, book20_ask_proxy_usdt=86013, funding_indicative=0.000050, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-28.10%, turnover=12469295. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T09:45:03+00:00, last15m_closed_end=2026-11-04T09:45+00:00, prior8high=0.028430, depth_time=2026-11-04T09:45:14+00:00, book20_bid_proxy_usdt=37855, book20_ask_proxy_usdt=56596, funding_indicative=-0.000464, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.39%, turnover=7340540. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T09:45:03+00:00, last15m_closed_end=2026-11-04T09:45+00:00, prior8high=1.526000, depth_time=2026-11-04T09:45:09+00:00, book20_bid_proxy_usdt=2272589, book20_ask_proxy_usdt=2306994, funding_indicative=-0.000071, next_funding_utc=2026-11-04T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.27%, turnover=10531437. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
