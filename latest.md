# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T11:45:18Z**
- feed_generated_utc: 2026-10-14T11:45:20+00:00
- source_sha256: `f2a32c9bdda400d8c2808b1ced279a9ca2173582353834f100f1d0c7ef1450b6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T11:45+00:00, close=83411.5, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T11:00+00:00, close=83430.4, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T08:00+00:00, close=83540.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.077640|-10.68|48.76|-10.70|28174603|1.29|
|W_USDT|0.015822|-5.83|9.02|-5.85|6472090|1.90|
|TIA_USDT|0.553500|-4.12|16.20|-4.14|36000900|1.81|
|UNI_USDT|7.352000|-2.90|-15.15|-2.92|18258803|1.36|
|SILVER_USDT|58.590000|-1.34|-4.52|-1.36|265943506|1.71|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|SILVER_USDT|58.590000|58.480000|58.590000|0.77|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.077640|0.077640|0.077640|1.17|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.553500|0.540100|0.553500|1.50|N|Y/Y|Y/N|N|N|
|UNI_USDT|7.352000|7.313000|7.352000|0.09|N|Y/Y|Y/Y|N|N|
|W_USDT|0.015822|0.015659|0.015822|1.04|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- SILVER_USDT: quote_utc=2026-10-14T11:45:01+00:00, last15m_closed_end=2026-10-14T11:45+00:00, prior8high=58.790000, depth_time=2026-10-14T11:45:17+00:00, book20_bid_proxy_usdt=45827770, book20_ask_proxy_usdt=48239736, funding_indicative=0.000108, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.34%, turnover=265943506. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T11:45:01+00:00, last15m_closed_end=2026-10-14T11:45+00:00, prior8high=0.079950, depth_time=2026-10-14T11:45:07+00:00, book20_bid_proxy_usdt=558017, book20_ask_proxy_usdt=251442, funding_indicative=0.000050, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.68%, turnover=28174603. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T11:45:01+00:00, last15m_closed_end=2026-10-14T11:45+00:00, prior8high=0.550900, depth_time=2026-10-14T11:45:12+00:00, book20_bid_proxy_usdt=169978, book20_ask_proxy_usdt=225354, funding_indicative=-0.000042, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.12%, turnover=36000900. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T11:45:01+00:00, last15m_closed_end=2026-10-14T11:45+00:00, prior8high=7.381000, depth_time=2026-10-14T11:45:15+00:00, book20_bid_proxy_usdt=1609356, book20_ask_proxy_usdt=1446343, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.90%, turnover=18258803. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T11:45:01+00:00, last15m_closed_end=2026-10-14T11:45+00:00, prior8high=0.016220, depth_time=2026-10-14T11:45:10+00:00, book20_bid_proxy_usdt=35765, book20_ask_proxy_usdt=29618, funding_indicative=-0.000255, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.83%, turnover=6472090. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
