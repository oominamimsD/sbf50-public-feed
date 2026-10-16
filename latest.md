# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T06:45:13Z**
- feed_generated_utc: 2026-10-16T06:45:14+00:00
- source_sha256: `ec248ea47d962b747607a1be52210fd7ad70e79090a38e08258b2aac7a188c45`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T06:45+00:00, close=82114.7, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T06:00+00:00, close=82131.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T04:00+00:00, close=82094.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEREBRO_USDT|0.044236|-13.76|61.11|-13.45|6875673|6.99|
|RLC_USDT|0.875500|-4.41|19.42|-4.10|5013495|2.29|
|AKE_USDT|0.030523|-3.42|5.16|-3.11|20945643|1.31|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.030523|0.030578|0.030523|1.67|Y|Y/Y|N/N|Y|N|
|RLC_USDT|0.875500|0.873100|0.875500|1.56|N|N/N|Y/Y|Y|N|
|ZEREBRO_USDT|0.044236|0.038700|0.044236|1.32|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T06:45:00+00:00, last15m_closed_end=2026-10-16T06:45+00:00, prior8high=0.033159, depth_time=2026-10-16T06:45:12+00:00, book20_bid_proxy_usdt=13936, book20_ask_proxy_usdt=10115, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.42%, turnover=20945643. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-16T06:45:00+00:00, last15m_closed_end=2026-10-16T06:45+00:00, prior8high=0.888900, depth_time=2026-10-16T06:45:09+00:00, book20_bid_proxy_usdt=88432, book20_ask_proxy_usdt=46317, funding_indicative=-0.000520, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.41%, turnover=5013495. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEREBRO_USDT: quote_utc=2026-10-16T06:45:00+00:00, last15m_closed_end=2026-10-16T06:45+00:00, prior8high=0.043015, depth_time=2026-10-16T06:45:07+00:00, book20_bid_proxy_usdt=7622, book20_ask_proxy_usdt=16115, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-13.76%, turnover=6875673. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
