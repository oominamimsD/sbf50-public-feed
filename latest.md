# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T00:15:14Z**
- feed_generated_utc: 2026-10-14T00:15:16+00:00
- source_sha256: `cbf4db97580fae4d49f918048a0facbb9e7c48454c7ec2f158e34ef5fe530502`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T00:15+00:00, close=83349.9, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T00:00+00:00, close=83125.7, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T00:00+00:00, close=83125.7, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|1000RATS_USDT|0.016470|-10.92|-58.99|-10.89|5226714|6.07|
|RLC_USDT|0.888100|-3.80|8.33|-3.77|5024038|2.25|
|STRK_USDT|0.084780|-2.47|62.44|-2.44|35806675|1.18|
|CT_USDT|0.363190|-2.30|-2.26|-2.27|5374988|0.28|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|1000RATS_USDT|0.016470|0.015990|0.016440|0.69|N|Y/Y|Y/Y|N|N|
|CT_USDT|0.363190|0.356040|0.363190|1.27|N|Y/Y|N/N|N|N|
|RLC_USDT|0.888100|0.887000|0.888100|0.72|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.084780|0.082530|0.084830|0.94|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- 1000RATS_USDT: quote_utc=2026-10-14T00:15:02+00:00, last15m_closed_end=2026-10-14T00:15+00:00, prior8high=0.017190, depth_time=2026-10-14T00:15:07+00:00, book20_bid_proxy_usdt=48989, book20_ask_proxy_usdt=118322, funding_indicative=0.000050, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.92%, turnover=5226714. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CT_USDT: quote_utc=2026-10-14T00:15:02+00:00, last15m_closed_end=2026-10-14T00:15+00:00, prior8high=0.366370, depth_time=2026-10-14T00:15:13+00:00, book20_bid_proxy_usdt=10935, book20_ask_proxy_usdt=6519, funding_indicative=0.000050, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.30%, turnover=5374988. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-14T00:15:02+00:00, last15m_closed_end=2026-10-14T00:15+00:00, prior8high=0.903000, depth_time=2026-10-14T00:15:09+00:00, book20_bid_proxy_usdt=90048, book20_ask_proxy_usdt=67726, funding_indicative=-0.000443, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.80%, turnover=5024038. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T00:15:02+00:00, last15m_closed_end=2026-10-14T00:15+00:00, prior8high=0.085960, depth_time=2026-10-14T00:15:11+00:00, book20_bid_proxy_usdt=358415, book20_ask_proxy_usdt=196101, funding_indicative=-0.000015, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.47%, turnover=35806675. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
