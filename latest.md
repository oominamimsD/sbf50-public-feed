# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T19:45:15Z**
- feed_generated_utc: 2026-10-13T19:45:18+00:00
- source_sha256: `c3e900cb9eec00bf55f9c5959331b073d3f1277dad280dd2a204c1d006926963`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T19:45+00:00, close=83137.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-13T19:00+00:00, close=83113.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-13T16:00+00:00, close=83393, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CT_USDT|0.351780|-5.37|-5.33|-5.07|5856108|5.41|
|RLC_USDT|0.893600|-3.20|9.00|-2.90|5780845|1.12|
|DOS_USDT|0.210800|-2.09|-2.18|-1.79|9519853|4.75|
|W_USDT|0.016489|-1.86|13.62|-1.56|10499607|9.72|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.351780|0.356760|0.351780|0.53|N|Y/N|N/N|Y|N|
|DOS_USDT|0.210800|0.206400|0.210800|0.92|N|Y/Y|Y/Y|Y|N|
|RLC_USDT|0.893600|0.874600|0.893600|0.19|N|Y/Y|Y/Y|Y|N|
|W_USDT|0.016489|0.015938|0.016489|0.82|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-13T19:45:02+00:00, last15m_closed_end=2026-10-13T19:45+00:00, prior8high=0.372510, depth_time=2026-10-13T19:45:06+00:00, book20_bid_proxy_usdt=8099, book20_ask_proxy_usdt=10671, funding_indicative=0.000050, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.37%, turnover=5856108. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOS_USDT: quote_utc=2026-10-13T19:45:02+00:00, last15m_closed_end=2026-10-13T19:45+00:00, prior8high=0.213600, depth_time=2026-10-13T19:45:12+00:00, book20_bid_proxy_usdt=120118, book20_ask_proxy_usdt=83896, funding_indicative=-0.000083, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.09%, turnover=9519853. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T19:45:02+00:00, last15m_closed_end=2026-10-13T19:45+00:00, prior8high=0.908000, depth_time=2026-10-13T19:45:09+00:00, book20_bid_proxy_usdt=51206, book20_ask_proxy_usdt=67223, funding_indicative=-0.000575, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.20%, turnover=5780845. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T19:45:02+00:00, last15m_closed_end=2026-10-13T19:45+00:00, prior8high=0.016566, depth_time=2026-10-13T19:45:14+00:00, book20_bid_proxy_usdt=29967, book20_ask_proxy_usdt=45227, funding_indicative=-0.000304, next_funding_utc=2026-10-13T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.86%, turnover=10499607. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
