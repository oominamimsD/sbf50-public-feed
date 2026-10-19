# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T00:15:17Z**
- feed_generated_utc: 2026-10-19T00:15:18+00:00
- source_sha256: `acbdfcffd6135fc2a143cc4897d868c57e6dc56c87b7f2ce852dcdb3dcad10e6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T00:15+00:00, close=82100.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T00:00+00:00, close=82076.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T00:00+00:00, close=82076.8, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.110548|-9.36|290.32|-10.55|9926227|0.09|
|STRK_USDT|0.060220|-2.17|-49.50|-3.36|16222682|1.66|
|AGT_USDT|0.066218|-1.94|274.43|-3.13|10041058|8.76|
|SAND_USDT|0.058560|-0.34|-11.86|-1.53|33913589|1.71|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.066218|0.060544|0.066290|0.91|N|Y/Y|N/N|N|N|
|Q_USDT|0.110548|0.111595|0.110547|0.86|N|Y/Y|N/N|N|N|
|SAND_USDT|0.058560|0.056800|0.058560|1.99|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.060220|0.059380|0.060220|1.67|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-19T00:15:01+00:00, last15m_closed_end=2026-10-19T00:15+00:00, prior8high=0.068584, depth_time=2026-10-19T00:15:11+00:00, book20_bid_proxy_usdt=6161, book20_ask_proxy_usdt=4663, funding_indicative=0.000206, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.94%, turnover=10041058. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-19T00:15:01+00:00, last15m_closed_end=2026-10-19T00:15+00:00, prior8high=0.121020, depth_time=2026-10-19T00:15:07+00:00, book20_bid_proxy_usdt=9058, book20_ask_proxy_usdt=8504, funding_indicative=0.000124, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.36%, turnover=9926227. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-19T00:15:01+00:00, last15m_closed_end=2026-10-19T00:15+00:00, prior8high=0.058900, depth_time=2026-10-19T00:15:15+00:00, book20_bid_proxy_usdt=622959, book20_ask_proxy_usdt=635613, funding_indicative=-0.002972, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.34%, turnover=33913589. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T00:15:01+00:00, last15m_closed_end=2026-10-19T00:15+00:00, prior8high=0.061020, depth_time=2026-10-19T00:15:10+00:00, book20_bid_proxy_usdt=410264, book20_ask_proxy_usdt=371920, funding_indicative=0.000050, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.17%, turnover=16222682. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
