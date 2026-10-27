# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T22:00:14Z**
- feed_generated_utc: 2026-10-27T22:00:17+00:00
- source_sha256: `0c1e85f83b0182808dd55aca3d15727f743d59397f9a9a4a698e88cb18a1f674`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T22:00+00:00, close=80874.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T22:00+00:00, close=80874.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T20:00+00:00, close=80778.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.021687|-26.64|-30.24|-27.12|5257396|0.46|
|Q_USDT|0.054174|-14.79|-55.86|-15.27|49239269|0.74|
|IRYS_USDT|0.024900|-1.61|91.24|-2.09|5617294|4.01|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.021687|0.022038|0.021687|1.17|N|Y/Y|Y/Y|N|N|
|IRYS_USDT|0.024900|0.024330|0.024900|1.81|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.054174|0.051125|0.054110|0.82|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-27T22:00:03+00:00, last15m_closed_end=2026-10-27T22:00+00:00, prior8high=0.022803, depth_time=2026-10-27T22:00:09+00:00, book20_bid_proxy_usdt=9693, book20_ask_proxy_usdt=8362, funding_indicative=0.000050, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-26.64%, turnover=5257396. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T22:00:03+00:00, last15m_closed_end=2026-10-27T22:00+00:00, prior8high=0.025300, depth_time=2026-10-27T22:00:13+00:00, book20_bid_proxy_usdt=115768, book20_ask_proxy_usdt=60734, funding_indicative=-0.001355, next_funding_utc=2026-10-27T23:00:00+00:00, funding_cycle_h=1, 24h_change=-1.61%, turnover=5617294. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-27T22:00:03+00:00, last15m_closed_end=2026-10-27T22:00+00:00, prior8high=0.055980, depth_time=2026-10-27T22:00:11+00:00, book20_bid_proxy_usdt=1826, book20_ask_proxy_usdt=2192, funding_indicative=-0.000003, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-14.79%, turnover=49239269. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
