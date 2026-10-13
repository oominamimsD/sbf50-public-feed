# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T23:15:14Z**
- feed_generated_utc: 2026-10-13T23:15:16+00:00
- source_sha256: `f0974ee8be421944be396f5494578508664c71fd2e2c0976a633b83893385743`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T23:15+00:00, close=83239.4, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T23:00+00:00, close=83483.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T20:00+00:00, close=83253, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|1000RATS_USDT|0.016610|-10.16|-58.65|-9.98|5078282|6.01|
|RLC_USDT|0.892200|-3.35|8.83|-3.17|5105048|2.24|
|CT_USDT|0.360440|-3.04|-3.00|-2.86|5437121|1.11|
|STRK_USDT|0.084630|-2.64|62.15|-2.46|37569179|1.18|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|1000RATS_USDT|0.016610|0.016630|0.016610|2.88|Y|Y/Y|Y/Y|N|Y|
|CT_USDT|0.360440|0.357960|0.360630|0.20|N|N/Y|N/N|N|N|
|RLC_USDT|0.892200|0.887100|0.892200|0.95|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.084630|0.082530|0.084610|0.35|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- 1000RATS_USDT: quote_utc=2026-10-13T23:15:03+00:00, last15m_closed_end=2026-10-13T23:15+00:00, prior8high=0.017820, depth_time=2026-10-13T23:15:07+00:00, book20_bid_proxy_usdt=140636, book20_ask_proxy_usdt=33420, funding_indicative=0.000009, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.16%, turnover=5078282. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CT_USDT: quote_utc=2026-10-13T23:15:03+00:00, last15m_closed_end=2026-10-13T23:15+00:00, prior8high=0.367810, depth_time=2026-10-13T23:15:11+00:00, book20_bid_proxy_usdt=12217, book20_ask_proxy_usdt=21071, funding_indicative=0.000050, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.04%, turnover=5437121. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T23:15:03+00:00, last15m_closed_end=2026-10-13T23:15+00:00, prior8high=0.903000, depth_time=2026-10-13T23:15:09+00:00, book20_bid_proxy_usdt=95196, book20_ask_proxy_usdt=121060, funding_indicative=-0.000421, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.35%, turnover=5105048. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T23:15:03+00:00, last15m_closed_end=2026-10-13T23:15+00:00, prior8high=0.085530, depth_time=2026-10-13T23:15:13+00:00, book20_bid_proxy_usdt=137341, book20_ask_proxy_usdt=218058, funding_indicative=-0.000004, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.64%, turnover=37569179. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
