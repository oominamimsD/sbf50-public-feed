# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T12:15:17Z**
- feed_generated_utc: 2026-11-04T12:15:19+00:00
- source_sha256: `d77d972e7f03a047527042529f75da8ce0bf0117d16ccec1bf59d8c9a348e2d6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T12:15+00:00, close=78051.5, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T12:00+00:00, close=78453.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T12:00+00:00, close=78453.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.032300|-39.97|-32.02|-40.46|10501609|3.10|
|AKE_USDT|0.002827|-31.97|-86.61|-32.46|13342243|3.54|
|TRUMPOFFICIAL_USDT|1.448000|-9.95|-14.21|-10.44|11202897|6.91|
|HOT_USDT|0.000487|-9.45|41.14|-9.94|7300334|2.05|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.032300|0.032450|0.032300|0.64|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.002827|0.002804|0.002827|1.20|N|Y/Y|Y/Y|N|N|
|HOT_USDT|0.000487|0.000492|0.000487|1.07|N|Y/N|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.448000|1.449000|1.448000|4.40|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T12:14:59+00:00, last15m_closed_end=2026-11-04T12:15+00:00, prior8high=0.034540, depth_time=2026-11-04T12:15:09+00:00, book20_bid_proxy_usdt=26468, book20_ask_proxy_usdt=33192, funding_indicative=0.000053, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-39.97%, turnover=10501609. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T12:14:59+00:00, last15m_closed_end=2026-11-04T12:15+00:00, prior8high=0.003000, depth_time=2026-11-04T12:15:11+00:00, book20_bid_proxy_usdt=115554, book20_ask_proxy_usdt=84496, funding_indicative=0.000050, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-31.97%, turnover=13342243. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-04T12:14:59+00:00, last15m_closed_end=2026-11-04T12:15+00:00, prior8high=0.000534, depth_time=2026-11-04T12:15:16+00:00, book20_bid_proxy_usdt=75645, book20_ask_proxy_usdt=80331, funding_indicative=-0.000060, next_funding_utc=2026-11-04T13:00:00+00:00, funding_cycle_h=1, 24h_change=-9.45%, turnover=7300334. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T12:14:59+00:00, last15m_closed_end=2026-11-04T12:15+00:00, prior8high=1.497000, depth_time=2026-11-04T12:15:13+00:00, book20_bid_proxy_usdt=2016430, book20_ask_proxy_usdt=2206873, funding_indicative=-0.000285, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.95%, turnover=11202897. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
